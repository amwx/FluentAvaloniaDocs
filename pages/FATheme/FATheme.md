---
layout: default
title: FluentAvaloniaTheme
nav_order: 3
permalink: /pages/FATheme
has_children: true
---

# FluentAvaloniaTheme
FluentAvaloniaTheme (abbr. FATheme) is the theme manager for supplying the Fluent v2 styles for all Avalonia controls and the custom controls within FluentAvalonia. FATheme uses the new ThemeDictionary and ThemeVariant APIs now available in Avalonia 11.0, thus supporting automatic theme detection and fast runtime theme changing.

## Using FATheme

Add `FluentAvaloniaTheme` to your `App.axaml` file (see the Getting Started page). To obtain a reference to the current FATheme, which can be used to adjust some of the configuration options, use the `AvaloniaLocator`:
```C#
var faTheme = AvaloniaLocator.Current.GetService<FluentAvaloniaTheme>();
```
<br/>

## Hidden Resources
Some resources are handled internally by FluentAvaloniaTheme and not exposed in the resource dictionary files. These resources can still be overridden, if desired.

- `ContentControlThemeFontFamily`
- `SystemAccentColor` and the 6 variants
- `SymbolThemeFontFamily`

{: .warning }
It is not advised to override the SymbolThemeFontFamily resource. Doing so may affect the visual appearances of some controls which rely on glyphs from this font.