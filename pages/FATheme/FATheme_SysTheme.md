---
layout: default
title: Themes
nav_order: 1
permalink: /pages/FATheme/Themes
parent: FluentAvaloniaTheme
---

# Fluent v2 Themes

As in WinUI, both light and dark theme modes are available within FluentAvalonia. The desired theme can be set manually or, where supported, can be automatically resolved from the operating system. The theme can be changed at any time during the lifetime of the app without needing to restart. A HighContrast theme is available as well and will automatically resolve (Windows only) if enabled on the system. The HighContrast theme also respects the color variations in Windows 11.

For convenience, FATheme provides static string references to the theme names:
```csharp
public static readonly string LightModeString = "Light";
public static readonly string DarkModeString = "Dark";
public static readonly string HighContrastModeString = "HighContrast";
```

## Setting the theme - Manual

Use the `RequestedTheme` property to set the desired theme mode of the app. Valid values (case-insensitive) are `Light`, `Dark`, or `HighContrast`. Custom theme names are not supported.
<br/>

## Setting the theme - Automatic

{: .platform }
Windows fully supported. MacOS and linux may work depending on the environment. `PreferSystemTheme` has no effect on WASM or mobile

To have FATheme automatically resolve the system theme and use it, make sure the `PreferSystemTheme` property is set to `true`, which is the default value. If this lookup fails for any reason, or the platform is not configured to support this, the fallback behavior is to use the `RequestedTheme` property. If `RequestedTheme` is unset, Light mode is used.

{: .note }
Upon app startup, `PreferSystemTheme` will always override the `RequestedTheme` and is only used for fallback. After initialization, `RequestedTheme` can be freely changed.
<br/>


## Responding to system theme changes
Even if you've set `PreferSystemTheme` to `true`, FATheme will not automatically switch if the system does. However, if you monitor for this yourself, you can force automatic invalidation of the system resources by calling `InvalidateThemingFromSystemThemeChange()`. This works for both theme and accent color.

{: .note }
If you use `AppWindow` provided in the FluentAvalonia.UI.Windowing package and are on Windows, this is automatically handled by listening for a `WM_SETTINGCHANGE` windows message.