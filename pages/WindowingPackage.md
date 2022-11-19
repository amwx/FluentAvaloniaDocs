---
layout: default
title: Windowing Package
nav_order: 2
permalink: FluentAvaloniaDocs/pages/WindowingPackage
parent: Getting Started
---

# FluentAvalonia.UI.Windowing
Contains controls only usable on desktop platforms

[![Nuget](https://img.shields.io/nuget/v/FluentAvalonia.UI.Windowing?color=%236A5ACD&label=FluentAvalonia.UI.Windowing%20%28nuget%29)](https://www.nuget.org/packages/FluentAvalonia.UI.Windowing/)


### Xaml Namespaces
You can, of course, use whatever xmlns definitions you want, but for any sample code these xml namespaces will be used for FluentAvalonia

`xmlns:wnd="using:FluentAvalonia.UI.Windowing"`

### Styles
As this is a separate package, in order to use the controls provided (currently only `AppWindow`), you'll need to include a separate `StyleInclude` to import the necessary styles:

`<StyleInclude Source="avares://FluentAvalonia.UI.Windowing/Styles/FAWindowingStyles.axaml" />`

### TaskDialog
`TaskDialog` has the option to launch as a Window instead of just an overlay (like `ContentDialog`), however, to suppport this functionality one extra step must be taken to allow `TaskDialog` to work with AppWindow. Add `.UseFAWindowing()` to the AppBuilder of your app:

```csharp
public static AppBuilder BuildAvaloniaApp()
        => AppBuilder.Configure<App>()
            .UsePlatformDetect()
            .LogToTrace()
            .UseFAWindowing();
```

{: .caution }
Failure to include `.UseFAWindowing()` will result in an error unless you specifically tell TaskDialog to launch as an overlay by calling `ShowAsync(/*showHosted*/ true);`