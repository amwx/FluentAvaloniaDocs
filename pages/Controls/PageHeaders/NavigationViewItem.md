# NavigationViewItem
Namespace: `FluentAvalonia.UI.Controls`

Represents the container for an item in a NavigationView control.

<div class="code-example" markdown="1">
C#
</div>
```csharp
public class NavigationViewItem : NavigationViewItemBase
```

<br />
<div class="code-example" markdown="1">
Xaml
</div>
```xml
<ui:NavigationViewItem />
```

<br />
**Required Template Parts**

| Name | Control Type |
|--|--|
| FlyoutContentGrid | Panel |
| NVIPresenter | NavigationViewItemPresenter |
| NVIRootGrid | Grid |
| NVIMenuItemsHost | ItemsRepeater |


<br />

<div class="code-example" markdown="1">
Pseudoclasses
</div>
```xml
:leftnav, :topnav, :topoverflow, :iconleft, :icononly, :contentonly, :selected, :iconcollapsed, :chevronclosed, :chevronopen, :chevronhidden, :infobadge, :pressed, :selected, :disabled, :focus, :focus-visible, :focus-within, :pointerover
```
<br />