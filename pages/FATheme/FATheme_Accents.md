---
layout: default
title: Accent Color
nav_order: 2
permalink: /pages/FATheme/Accents
parent: FluentAvaloniaTheme
---

# Accent Colors

The Fluent theme provides a `SystemAccentColor` resource that is used all throughout the Fluent v2 styles. FATheme provides a mechanism for specifying, overriding, or using the system's user accent color. There are a total of 7 accent color related resources:

- `SystemAccentColor` (main color)
  - Light Variants
    - `SystemAccentColorLight1`
    - `SystemAccentColorLight2`
    - `SystemAccentColorLight3`
  - Dark Variants
    - `SystemAccentColorDark1`
    - `SystemAccentColorDark2`
    - `SystemAccentColorDark3`
<br/>

## Using the System's accent color

{: .platform }
Windows fully supported. Linux is implemented only on KDE, LXQt, and LXDE. MacOS works if `defaults read -g AppleAccentColor` returns successfully. `PreferUserAccentColor` has no effect on WASM or mobile

To use the system's accent color, set `PreferUserAccentColor` to true (default value). If this lookup fails, or is unavailable on the current platform, a custom accent color can be specified, or the default (based on the color SlateBlue) is used.

## Using a custom accent color - `CustomAccentColor` property

One way you can specify a custom accent color is to set the `CustomAccentColor` property on FATheme. The 6 variants of will be automatically generated from the specified color. To return to the system color or the default (SlateBlue), set the property to null.

{: .warning }
FATheme does no accessibility checks for the given accent color. It is your responsibility to check whether the provided accent color and generated variants are suitable for use by accessibility standards.
<br />

## Using a custom accent color - Overriding resources

As with any xaml resource, you can always override the SystemAccentColor resources to provide custom values. This will also give you more control over the 6 variants, if you desire. While resources can be overriden anywhere, its best to do this in the `App.axaml` resource dictionary so it works across the entire app.

```Xaml
<App.Resources>
    <Color x:Key="SystemAccentColor">Blue</Color>
    <Color x:Key="SystemAccentColorLight1">LightBlue</Color>
    <Color x:Key="SystemAccentColorDark1">DarkBlue</Color>
</App.Resources>
```

## Responding to system theme changes
Even if you've set `PreferUserAccentColor` to `true`, FATheme will not automatically switch if the system does. However, if you monitor for this yourself, you can force automatic invalidation of the system resources by calling `InvalidateThemingFromSystemThemeChange()`. This works for both theme and accent color.

{: .note }
If you use `AppWindow` provided in the FluentAvalonia.UI.Windowing package and are on Windows, this is automatically handled by listening for a `WM_SETTINGCHANGE` windows message.

