## API

<h5>Note: Inherited members are not shown</h5>
<br />

**Properties**

<table class="resourceTable">
<tr>
<td class="nameCell">ActionButton</td>
<td>Gets or sets the action button of the InfoBar.
</td>
</tr>
<tr>
<td class="nameCell">ActionButtonProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.InfoBar.ActionButton` property
</td>
</tr>
<tr>
<td class="nameCell">CloseButtonCommand</td>
<td>Gets or sets the command to invoke when the close button is clicked in the InfoBar.
</td>
</tr>
<tr>
<td class="nameCell">CloseButtonCommandParameter</td>
<td>Gets or sets the parameter to pass to the command for the close button in the InfoBar.
</td>
</tr>
<tr>
<td class="nameCell">CloseButtonCommandParameterProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.InfoBar.CloseButtonCommandParameter` property
</td>
</tr>
<tr>
<td class="nameCell">CloseButtonCommandProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.InfoBar.CloseButtonCommand` property
</td>
</tr>
<tr>
<td class="nameCell">IconSource</td>
<td>Gets or sets the graphic content to appear alongside the title and message in the InfoBar.
</td>
</tr>
<tr>
<td class="nameCell">IconSourceProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.InfoBar.IconSource` property
</td>
</tr>
<tr>
<td class="nameCell">IsClosable</td>
<td>Gets or sets a value that indicates whether the user can close the InfoBar.
</td>
</tr>
<tr>
<td class="nameCell">IsClosableProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.InfoBar.IsClosable` property
</td>
</tr>
<tr>
<td class="nameCell">IsIconVisible</td>
<td>Gets or sets a value that indicates whether the icon is visible in the InfoBar.
</td>
</tr>
<tr>
<td class="nameCell">IsIconVisibleProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.InfoBar.IsIconVisible` property
</td>
</tr>
<tr>
<td class="nameCell">IsOpen</td>
<td>Gets or sets a value that indicates whether the InfoBar is open.
</td>
</tr>
<tr>
<td class="nameCell">IsOpenProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.InfoBar.IsOpen` property
</td>
</tr>
<tr>
<td class="nameCell">Message</td>
<td>Gets or sets the message of the InfoBar.
</td>
</tr>
<tr>
<td class="nameCell">MessageProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.InfoBar.Message` property
</td>
</tr>
<tr>
<td class="nameCell">Severity</td>
<td>Gets or sets the type of the InfoBar to apply consistent status color, icon, and assistive technology settings dependent on the criticality of the notification.
</td>
</tr>
<tr>
<td class="nameCell">SeverityProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.InfoBar.Severity` property
</td>
</tr>
<tr>
<td class="nameCell">Title</td>
<td>Gets or sets the title of the InfoBar.
</td>
</tr>
<tr>
<td class="nameCell">TitleProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.InfoBar.Title` property
</td>
</tr>
</table>


<br />

**Events**

<table class="resourceTable">
<tr>
<td class="nameCell">CloseButtonClick</td>
<td>Occurs after the close button is clicked in the InfoBar.
</td>
</tr>
<tr>
<td class="nameCell">Closed</td>
<td>Occurs after the InfoBar is closed.
</td>
</tr>
<tr>
<td class="nameCell">Closing</td>
<td>Occurs just before the InfoBar begins to close.
</td>
</tr>
</table>


<br />

**Methods**

<table class="resourceTable">
</table>


<br />

## Related Enums/Classes

**InfoBarSeverity**
<table class="resourceTable">
<tr>
<td class="nameCell">Informational</td>
<td>Communicates that the InfoBar is displaying general information that requires the user's attention. For assistive technologies, they will follow the behavior set in the Processing_All constant.
</td>
</tr>
<tr>
<td class="nameCell">Success</td>
<td>Communicates that the InfoBar is displaying information regarding a long-running and/or background task that has completed successfully. For assistive technologies, they will follow the behavior set in the Processing_All constant.
</td>
</tr>
<tr>
<td class="nameCell">Warning</td>
<td>Communicates that the InfoBar is displaying information regarding a condition that might cause a problem in the future. For assistive technologies, they will follow the behavior set in the NotificationProcessing_ImportantAll constan
</td>
</tr>
<tr>
<td class="nameCell">Error</td>
<td>Communicates that the InfoBar is displaying information regarding an error or problem that has occurred. For assistive technologies, they will follow the behavior set in the NotificationProcessing_ImportantAll constant.
</td>
</tr>
</table>

<br />

**InfoBarClosingEventArgs**
<table class="resourceTable">
<tr>
<td class="nameCell">Reason</td>
<td>Gets a constant that specifies whether the cause of the Closing event was due to user interaction (Close button click) or programmatic closure.
</td>
</tr>
<tr>
<td class="nameCell">Cancel</td>
<td>Gets or sets a value that indicates whether the Closing event should be canceled in the InfoBar.
</td>
</tr>
</table>

<br />

**InfoBarClosedEventArgs**
<table class="resourceTable">
<tr>
<td class="nameCell">Reason</td>
<td>Gets a constant that specifies whether the cause of the Closed event was due to user interaction (Close button click) or programmatic closure.
</td>
</tr>
</table>

<br />



