---
layout: default
title: Misc. Options
nav_order: 3
permalink: /pages/FATheme/Misc
parent: FluentAvaloniaTheme
---

# Miscellaneous options

FATheme has a few other properties that may be of use to you.

## Automatically use Segoe font (Windows only)

Use the `UseSystemFontOnWindows` property to ensure the `Segoe UI` (Windows 10) or `Segoe UI Variable` (Windows 11) are used automatically with the Fluentv2 styles. If true (default), this will set the resource `ContentControlThemeFontFamily` to the appropriate font. As these fonts are Windows only, this property has no effect on other platforms.
<br/>

## Control text vertical alignment

FluentAvalonia is based on Microsoft's Fluent design system which requires the Segoe UI font family. On non-Windows platforms where these fonts aren't available, some mis-alignments may occur as certain controls use margins or alignments specifically designed for these fonts (see [PR #210](https://github.com/amwx/FluentAvalonia/pull/210) for more). The `TextVerticalAlignmentOverrideBehavior` property adds options to help correct this. The `TextVerticalAlignmentOverride` enum has 3 values:

- `Disabled`
  - Don't use any corrections (use the styles as-is)
- `EnabledNonWindows` (default)
  - Only use the corrections if not on Windows
- `AlwaysEnabled`
  - Always use the corrections (even on Windows)

This property is only respected upon startup.
