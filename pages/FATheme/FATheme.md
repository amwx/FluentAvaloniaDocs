---
layout: default
title: FluentAvaloniaTheme
nav_order: 3
permalink: /pages/FATheme
has_children: true
---

# FluentAvaloniaTheme
FluentAvaloniaTheme (abbr. FATheme) is my custom theme manager for supplying the fluent v2 styles for all Avalonia controls and the custom controls within FluentAvalonia. FATheme supports runtime theme changing and has options to pull theme information from certain operating systems to ensure your app blends in with the user's current system settings (note that not all operating systems are supported)

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
It is not advised to override the SymbolThemeFontFamily resource. Doing so will break `SymbolIcon` and may break some controls that rely on this font via `SymbolIcon` or `FontIcon`