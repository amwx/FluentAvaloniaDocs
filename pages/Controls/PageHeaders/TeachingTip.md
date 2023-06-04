# TeachingTip
Namespace: `FluentAvalonia.UI.Controls`

A teaching tip is a notification flyout used to provide contextually relevant information. It supports rich content (including titles, subtitles, icons, images, and text) and can be configured for either explicit or light-dismiss.

<div class="code-example" markdown="1">
C#
</div>
```csharp
public class TeachingTip : ContentControl
```

<br />
<div class="code-example" markdown="1">
Xaml
</div>
```xml
<ui:TeachingTip />
```

<br />
**Required Template Parts**

| Name | Control Type |
|--|--|
| Container | Border |
| TailOcclusionGrid | Grid |
| ContentRootGrid | Grid |
| NonHeroContentRootGrid | Grid |
| HeroContentBorder | Border |
| ActionButton | Button |
| AlternateCloseButton | Button |
| CloseButton | Button |
| TailPolygon | Path |


<br />

<div class="code-example" markdown="1">
Pseudoclasses
</div>
```xml
:lightDismiss, :actionButton, :closeButton, :content, :icon, :footerClose, :heroContentTop, :heroContentBottom, :top, :bottom, :left, :right, :center, :topRight, :topLeft, :bottomLeft, :bottomRight, :leftTop, :leftBottom, :rightTop, :rightBottom, :showTitle, :showSubTitle, :disabled, :focus, :focus-visible, :focus-within, :pointerover
```
<br />