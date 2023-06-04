# NavigationView
Namespace: `FluentAvalonia.UI.Controls`

Represents a container that enables navigation of app content. It has a header, a view for the main content, and a menu pane for navigation commands.

<div class="code-example" markdown="1">
C#
</div>
```csharp
public class NavigationView : HeaderedContentControl
```

<br />
<div class="code-example" markdown="1">
Xaml
</div>
```xml
<ui:NavigationView />
```

<br />
**Required Template Parts**

| Name | Control Type |
|--|--|
| TogglePaneButton | Button |
| PaneHeaderContentBorder | ContentControl |
| PaneCustomContentBorder | ContentControl |
| FooterContentBorder | ContentControl |
| PaneHeaderOnTopPane | ContentControl |
| PaneTitleOnTopPane | ContentControl |
| PaneCustomContentOnTopPane | ContentControl |
| PaneFooterOnTopPane | ContentControl |
| RootSplitView | SplitView |
| TopNavGrid | Grid |
| MenuItemsHost | ItemsRepeater |
| TopNavMenuItemsHost | ItemsRepeater |
| TopNavMenuItemsOverflowHost | ItemsRepeater |
| TopNavOverflowButton | Button |
| FooterMenuItemsHost | ItemsRepeater |
| TopFooterMenuItemsHost | ItemsRepeater |
| TopNavContentOverlayAreaGrid | Border |
| PaneAutoSuggestBoxPresenter | ContentControl |
| TopPaneAutoSuggestBoxPresenter | ContentControl |
| PaneContentGrid | Grid |
| ContentLeftPadding | Rectangle |
| PlaceholderGrid | Grid |
| PaneTitleTextBlock | Control |
| PaneTitlePresenter | ContentControl |
| PaneTitleHolder | Control |
| PaneAutoSuggestButton | Button |
| NavigationViewBackButton | Button |
| NavigationViewCloseButton | Button |
| MenuItemsScrollViewer | ScrollViewer |
| FooterItemsScrollViewer | ScrollViewer |
| ItemsContainerGrid | Control |


<br />

<div class="code-example" markdown="1">
Pseudoclasses
</div>
```xml
:separator, :listsizecompact, :closedcompact, :backbuttoncollapsed, :panecollapsed, :headercollapsed, :minimalwithback, :minimal, :topnavminimal, :compact, :expanded, :autosuggestcollapsed, :settingscollapsed, :panetogglecollapsed, :panenotoverlaying, :disabled, :focus, :focus-visible, :focus-within, :pointerover
```
<br />