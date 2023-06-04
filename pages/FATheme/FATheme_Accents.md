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

Use the `PreferUserAccentColor` property to set how FATheme sets the AccentColor upon startup, the default value is `false`. If the property is set to `true`:

- On Windows, `SystemAccentColor` and the 6 variants (3 light, 3 dark) are loaded from the system
- On all other platforms, the primary accent color is loaded from the `IPlatformSettings` and the 6 variants are auto generated

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
Like the system theme (light/dark mode), FATheme will automatically adjust the system accent color if the underlying platform supports this via the `IPlatformSettings.ColorValuesChanged` event.

