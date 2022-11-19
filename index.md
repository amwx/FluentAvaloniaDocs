---
layout: default
title: Home
nav_order: 1
---

# FluentAvalonia
## Bringing more of Fluent design and WinUI controls into Avalonia.

Multitargets: netstandard2.0, netstandard2.1, net6.0

Supported on Windows 10/11, MacOS, Linux, WASM, and Mobile

MIT License

{: .note }
This site is still under development and docs may be missing or incomplete

### What's Included?
- Fluent v2 styling for all controls (light, dark, and high contrast variants)
- `FluentAvaloniaTheme`: theme manager for FluentAvalonia that supports runtime theme changes, custom accent colors, and adds options for automatically deriving the theme / colors from the operating system (not available on all platforms)
- **Controls ported/adapted from WinUI**
  - `NavigationView`
  - `Frame`
  - `ContentDialog`
  - `FAIconElement`*/`IconSource`
    - `FontIcon`/`FontIconSource`
    - `FAPathIcon`*/`PathIconSource`
    - `BitmapIcon`/`BitmapIconSource`
    - `ImageIcon`/`ImageIconSource`
    - `SymbolIcon`/`SymbolIconSource`
      - Symbols provided using custom font based on [Fluent System Icons](https://github.com/microsoft/fluentui-system-icons/)
  - `NumberBox`
  - `InfoBar`
  - `InfoBadge`
  - `FAMenuFlyout`*
    - `MenuFlyoutItem`
    - `ToggleMenuFlyoutItem`
    - `MenuFlyoutSubItem`
    - `RadioMenuFlyoutItem`
  - `TabView`
- **Custom controls**
  - `FAColorPicker`*/`ColorPickerButton`
  - `TaskDialog`
  - `AppWindow`

\* denotes controls with 'FA' prefix to separate upstream from FluentAvalonia implementations