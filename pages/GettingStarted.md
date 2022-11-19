---
layout: default
title: Getting Started
nav_order: 2
permalink: /pages/GettingStarted
has_children: true
---

## **Nuget Packages**

### Main Package
Contains all styles for the Fluent v2 theme and controls hosted in FluentAvalonia

[![Nuget](https://img.shields.io/nuget/v/FluentAvaloniaUI?color=%236A5ACD&label=FluentAvaloniaUI%20%28nuget%29)](https://www.nuget.org/packages/FluentAvaloniaUI/)

### Desktop Package
Contains controls only usable on desktop platforms (Mobile and WASM don't need this package)

[![Nuget](https://img.shields.io/nuget/v/FluentAvalonia.UI.Windowing?color=%236A5ACD&label=FluentAvalonia.UI.Windowing%20%28nuget%29)](https://www.nuget.org/packages/FluentAvalonia.UI.Windowing/)


### Xaml Namespaces
You can, of course, use whatever xmlns definitions you want, but for any sample code these xml namespaces will be used for FluentAvalonia

- Styling:
  - `xmlns:sty="using:FluentAvalonia.Styling"`

- Controls:
  - `xmlns:ui="using:FluentAvalonia.UI.Controls"`
  - `xmlns:uip="using:FluentAvalonia.UI.Controls.Primitives"`

- If you're using the Windowing package too:
  - `xmlns:wnd="using:FluentAvalonia.UI.Windowing"`

### Styles
To attach the styles needed for FluentAvalonia, add the following to your `App.axaml` file (don't forget the xmlns definition):

`<sty:FluentAvaloniaTheme />`

{: .warning }
You don't need to include any other themes with FluentAvalonia (FluentTheme or SimpleTheme, for example). Doing so may result in visual artifacts and a degraded experience.
