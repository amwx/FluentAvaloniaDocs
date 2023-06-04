---
layout: default
title: HighContrastTheme
nav_order: 4
permalink: /pages/FATheme/HighContrastTheme
parent: FluentAvaloniaTheme
---

# HighContrast Theme

FATheme also provides the resources for `HighContrast` themes, in addition to the standard light and dark. HighContrast mode can be enabled automatically, if `PreferSystemTheme` is set to true, or you can directly set the `RequestedThemeVariant` to HighContrast.

To use the HighContrast theme directly, FATheme defines the ThemeVariant as a static field:

```C#
public static readonly ThemeVariant HighContrastTheme = new ThemeVariant("HighContrast", ThemeVariant.Light);
```
<br />
<div class="code-example" markdown="1">
To set the HighContrast theme in Xaml
</div>
```xml
<Application RequestedThemeVariant="{x:Static sty:FluentAvaloniaTheme.HighContrastTheme}" />
```

<div class="code-example" markdown="1">
To define a custom ThemeDictionary
</div>
```xml
<ResourceDictionary x:Key="{x:Static sty:FluentAvaloniaTheme.HighContrastTheme}" />
```

Unlike light and dark themes, the high contrast theme only uses 8 total colors. The defaults for these colors are taken from the default Windows 10 high contrast theme.

```xml
<Color x:Key="SystemColorWindowTextColor">#FFFFFF</Color>
<Color x:Key="SystemColorGrayTextColor">#FF3FF23F</Color>
<Color x:Key="SystemColorButtonFaceColor">#FF000000</Color>
<Color x:Key="SystemColorWindowColor">#FF000000</Color>
<Color x:Key="SystemColorButtonTextColor">#FFFFFF</Color>
<Color x:Key="SystemColorHighlightColor">#FF1AEBFF</Color>
<Color x:Key="SystemColorHighlightTextColor">#FF000000</Color>
<Color x:Key="SystemColorHotlightColor">#FFFE55</Color>
```

On Windows 11, if one of the high contrast variants is enabled, these colors will be updated to align with the system.