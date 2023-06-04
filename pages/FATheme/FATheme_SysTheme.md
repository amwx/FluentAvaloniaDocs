---
layout: default
title: Themes
nav_order: 1
permalink: /pages/FATheme/Themes
parent: FluentAvaloniaTheme
---

# Fluent v2 Themes

FluentAvalonia supports Light, Dark, and HighContrast themes in the Fluentv2 style. FATheme uses the new platform color APIs in Avalonia 11.0 to detect the system theme, though retains some custom logic for KDE systems for resolving the system theme that isn't available in Avalonia. 

## Setting the theme - Manual

Use the `RequestedThemeVariant` property on supported Avalonia controls (such as `Application`) to set the desired theme variant for a given scope. 
<br/>

## Setting the theme - Automatic

FluentAvaloniaTheme has retained the `PreferSystemTheme` property, which now has the default value of `false`. However, it has a slightly different behavior now as much of the theme detection is now taken care of by Avalonia. Primarily, this property now affects the following:

- On supported systems where the platform APIs request HighContrast, FATheme will step in and set the HighContrast theme for the app
- On KDE systems, where FATheme has custom logic not offered by Avalonia.

{: .note }
Upon app startup, `PreferSystemTheme = true` will always override the `RequestedThemeVariant` set on the Application with what it determined as the current system theme. Setting `PreferSystemTheme = false` may still resolve the system theme (this is done in Avalonia) if you didn't set a RequestedThemeVariant
<br/>


## Responding to system theme changes
FATheme subscribes to the `IPlatformSettings.ColorValuesChanged` event and will automaitcally handle switching themes based on the system, provided that is supported on the current OS. 