# FAComboBox
Namespace: `FluentAvalonia.UI.Controls`

Represents a selection control that combines a non-editable text box and a drop-down list box that allows users to select an item from a list.

<div class="code-example" markdown="1">
C#
</div>
```csharp
public class FAComboBox : HeaderedSelectingItemsControl
```

<br />
<div class="code-example" markdown="1">
Xaml
</div>
```xml
<ui:FAComboBox />
```

<br />
**Required Template Parts**

| Name | Control Type |
|--|--|
| Popup | Popup |
| EditableText | TextBox |
| DropDownOverlay | ComboBox |


<br />

<div class="code-example" markdown="1">
Pseudoclasses
</div>
```xml
:selected, :focus, :pressed, :editable, :dropdownopen, :popupAbove, :header, :empty, :singleitem, :disabled, :focus, :focus-visible, :focus-within, :pointerover
```
<br />