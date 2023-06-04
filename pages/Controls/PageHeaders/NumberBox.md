# NumberBox
Namespace: `FluentAvalonia.UI.Controls`

Represents a control that can be used to display and edit numbers.

<div class="code-example" markdown="1">
C#
</div>
```csharp
public class NumberBox : TemplatedControl
```

<br />
<div class="code-example" markdown="1">
Xaml
</div>
```xml
<ui:NumberBox />
```

<br />
**Required Template Parts**

| Name | Control Type |
|--|--|
| DownSpinButton | RepeatButton |
| PopupDownSpinButton | RepeatButton |
| UpSpinButton | RepeatButton |
| PopupUpSpinButton | RepeatButton |
| InputBox | TextBox |
| UpDownPopup | Popup |


<br />

<div class="code-example" markdown="1">
Pseudoclasses
</div>
```xml
:spinvisible, :spinpopup, :spincollapsed, :updisabled, :downdisabled, :header, :disabled, :focus, :focus-visible, :focus-within, :pointerover
```
<br />