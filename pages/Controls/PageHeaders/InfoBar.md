# InfoBar
Namespace: `FluentAvalonia.UI.Controls`

An InfoBar is an inline notification for essential app-wide messages. The InfoBar will take up space in a layout and will not cover up other content or float on top of it. It supports rich content (including titles, messages, icons, and buttons) and can be configured to be user-dismissable or persistent.

<div class="code-example" markdown="1">
C#
</div>
```csharp
public class InfoBar : ContentControl
```

<br />
<div class="code-example" markdown="1">
Xaml
</div>
```xml
<ui:InfoBar />
```

<br />
**Required Template Parts**

| Name | Control Type |
|--|--|
| CloseButton | Button |


<br />

<div class="code-example" markdown="1">
Pseudoclasses
</div>
```xml
:hidden, :closehidden, :success, :warning, :error, :informational, :icon, :standardIcon, :foregroundset, :disabled, :focus, :focus-visible, :focus-within, :pointerover
```
<br />