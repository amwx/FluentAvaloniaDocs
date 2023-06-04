# CommandBar
Namespace: `FluentAvalonia.UI.Controls`

Represents a specialized command bar that provides layout for CommandBarButton and related command elements.

<div class="code-example" markdown="1">
C#
</div>
```csharp
public class CommandBar : ContentControl
```

<br />
<div class="code-example" markdown="1">
Xaml
</div>
```xml
<ui:CommandBar />
```

<br />
**Required Template Parts**

| Name | Control Type |
|--|--|
| PrimaryItemsControl | ItemsControl |
| ContentControl | ContentControl |
| SecondaryItemsControl | CommandBarOverflowPresenter |
| MoreButton | Button |


<br />

<div class="code-example" markdown="1">
Pseudoclasses
</div>
```xml
:dynamicoverflow, :compact, :minimal, :hidden, :labelbottom, :labelright, :labelcollapsed, :primaryOnly, :secondaryOnly, :open, :disabled, :focus, :focus-visible, :focus-within, :pointerover
```
<br />