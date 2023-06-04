# TaskDialog
Namespace: `FluentAvalonia.UI.Controls`

Represents and enhanced dialog with enhanced button, command, and progress support

<div class="code-example" markdown="1">
C#
</div>
```csharp
public class TaskDialog : ContentControl
```

<br />
<div class="code-example" markdown="1">
Xaml
</div>
```xml
<ui:TaskDialog />
```

<br />
**Required Template Parts**

| Name | Control Type |
|--|--|
| ButtonsHost | ItemsPresenter |
| CommandsHost | ItemsPresenter |
| MoreDetailsButton | Button |
| ProgressBar | ProgressBar |


<br />

<div class="code-example" markdown="1">
Pseudoclasses
</div>
```xml
:hosted, :hidden, :open, :header, :subheader, :icon, :footer, :footerAuto, :expanded, :progress, :progressError, :progressSuspend, :disabled, :focus, :focus-visible, :focus-within, :pointerover
```
<br />