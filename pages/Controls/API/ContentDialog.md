## API

<h5>Note: Inherited members are not shown</h5>
<br />

**Properties**

<table class="resourceTable">
<tr>
<td class="nameCell">CloseButtonCommand</td>
<td>Gets or sets the command to invoke when the close button is tapped.
</td>
</tr>
<tr>
<td class="nameCell">CloseButtonCommandParameter</td>
<td>Gets or sets the parameter to pass to the command for the close button.
</td>
</tr>
<tr>
<td class="nameCell">CloseButtonCommandParameterProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.CloseButtonCommandParameter` property
</td>
</tr>
<tr>
<td class="nameCell">CloseButtonCommandProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.CloseButtonCommand` property
</td>
</tr>
<tr>
<td class="nameCell">CloseButtonText</td>
<td>Gets or sets the text to display on the close button.
</td>
</tr>
<tr>
<td class="nameCell">CloseButtonTextProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.CloseButtonText` property
</td>
</tr>
<tr>
<td class="nameCell">DefaultButton</td>
<td>Gets or sets a value that indicates which button on the dialog is the default action.
</td>
</tr>
<tr>
<td class="nameCell">DefaultButtonProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.DefaultButton` property
</td>
</tr>
<tr>
<td class="nameCell">FullSizeDesired</td>
<td>Gets or sets whether the Dialog should show full screen On WinUI3, at least desktop, this just show the dialog at the maximum size of a contentdialog.
</td>
</tr>
<tr>
<td class="nameCell">FullSizeDesiredProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.FullSizeDesired` property
</td>
</tr>
<tr>
<td class="nameCell">IsPrimaryButtonEnabled</td>
<td>Gets or sets whether the dialog's primary button is enabled.
</td>
</tr>
<tr>
<td class="nameCell">IsPrimaryButtonEnabledProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.IsPrimaryButtonEnabled` property
</td>
</tr>
<tr>
<td class="nameCell">IsSecondaryButtonEnabled</td>
<td>Gets or sets whether the dialog's secondary button is enabled.
</td>
</tr>
<tr>
<td class="nameCell">IsSecondaryButtonEnabledProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.IsSecondaryButtonEnabled` property
</td>
</tr>
<tr>
<td class="nameCell">PrimaryButtonCommand</td>
<td>Gets or sets the command to invoke when the primary button is tapped.
</td>
</tr>
<tr>
<td class="nameCell">PrimaryButtonCommandParameter</td>
<td>Gets or sets the parameter to pass to the command for the primary button.
</td>
</tr>
<tr>
<td class="nameCell">PrimaryButtonCommandParameterProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.PrimaryButtonCommandParameter` property
</td>
</tr>
<tr>
<td class="nameCell">PrimaryButtonCommandProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.PrimaryButtonCommand` property
</td>
</tr>
<tr>
<td class="nameCell">PrimaryButtonText</td>
<td>Gets or sets the text to display on the primary button.
</td>
</tr>
<tr>
<td class="nameCell">PrimaryButtonTextProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.PrimaryButtonText` property
</td>
</tr>
<tr>
<td class="nameCell">SecondaryButtonCommand</td>
<td>Gets or sets the command to invoke when the secondary button is tapped.
</td>
</tr>
<tr>
<td class="nameCell">SecondaryButtonCommandParameter</td>
<td>Gets or sets the parameter to pass to the command for the secondary button.
</td>
</tr>
<tr>
<td class="nameCell">SecondaryButtonCommandParameterProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.SecondaryButtonCommandParameter` property
</td>
</tr>
<tr>
<td class="nameCell">SecondaryButtonCommandProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.SecondaryButtonCommand` property
</td>
</tr>
<tr>
<td class="nameCell">SecondaryButtonText</td>
<td>Gets or sets the text to be displayed on the secondary button.
</td>
</tr>
<tr>
<td class="nameCell">SecondaryButtonTextProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.SecondaryButtonText` property
</td>
</tr>
<tr>
<td class="nameCell">Title</td>
<td>Gets or sets the title of the dialog.
</td>
</tr>
<tr>
<td class="nameCell">TitleProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.Title` property
</td>
</tr>
<tr>
<td class="nameCell">TitleTemplate</td>
<td>Gets or sets the title template.
</td>
</tr>
<tr>
<td class="nameCell">TitleTemplateProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.ContentDialog.TitleTemplate` property
</td>
</tr>
</table>


<br />

**Events**

<table class="resourceTable">
<tr>
<td class="nameCell">CloseButtonClick</td>
<td>Occurs after the close button has been tapped.
</td>
</tr>
<tr>
<td class="nameCell">Closed</td>
<td>Occurs after the dialog is closed.
</td>
</tr>
<tr>
<td class="nameCell">Closing</td>
<td>Occurs after the dialog starts to close, but before it is closed and before the Closed event occurs.
</td>
</tr>
<tr>
<td class="nameCell">Opened</td>
<td>Occurs after the dialog is opened.
</td>
</tr>
<tr>
<td class="nameCell">Opening</td>
<td>Occurs before the dialog is opened
</td>
</tr>
<tr>
<td class="nameCell">PrimaryButtonClick</td>
<td>Occurs after the primary button has been tapped.
</td>
</tr>
<tr>
<td class="nameCell">SecondaryButtonClick</td>
<td>Occurs after the secondary button has been tapped.
</td>
</tr>
</table>


<br />

**Methods**

<table class="resourceTable">
<tr>
<td class="nameCell">ShowAsync()</td>
<td>Begins an asynchronous operation to show the dialog.
</td>
</tr>
<tr>
<td class="nameCell">ShowAsync(Window)</td>
<td>Begins an asynchronous operation to show the dialog using the specified window
</td>
</tr>
<tr>
<td class="nameCell">ShowAsyncCore(Window, ContentDialogPlacement)</td>
<td>Shows the content dialog on the specified window asynchronously.
</td>
</tr>
<tr>
<td class="nameCell">Hide()</td>
<td>Closes the current `FluentAvalonia.UI.Controls.ContentDialog` without a result (`FluentAvalonia.UI.Controls.ContentDialogResult`.`FluentAvalonia.UI.Controls.ContentDialogResult.None`)
</td>
</tr>
<tr>
<td class="nameCell">Hide(ContentDialogResult)</td>
<td>Closes the current `FluentAvalonia.UI.Controls.ContentDialog` with the given `FluentAvalonia.UI.Controls.ContentDialogResult`<para>ddd</para>
</td>
</tr>
<tr>
<td class="nameCell">OnPrimaryButtonClick(ContentDialogButtonClickEventArgs)</td>
<td>Called when the primary button is invoked
</td>
</tr>
<tr>
<td class="nameCell">OnSecondaryButtonClick(ContentDialogButtonClickEventArgs)</td>
<td>Called when the secondary button is invoked
</td>
</tr>
<tr>
<td class="nameCell">OnCloseButtonClick(ContentDialogButtonClickEventArgs)</td>
<td>Called when the close button is invoked
</td>
</tr>
<tr>
<td class="nameCell">OnOpening()</td>
<td>Called when the ContentDialog is requested to be opened
</td>
</tr>
<tr>
<td class="nameCell">OnOpened()</td>
<td>Called after the ContentDialog is initialized but just before its presented on screen
</td>
</tr>
<tr>
<td class="nameCell">OnClosing(ContentDialogClosingEventArgs)</td>
<td>Called when the ContentDialog has been requested to close, but before it actually closes
</td>
</tr>
<tr>
<td class="nameCell">OnClosed(ContentDialogClosedEventArgs)</td>
<td>Called when the ContentDialog has been closed and removed from the tree
</td>
</tr>
</table>


<br />

## Related Enums/Classes

**ContentDialogButton**
<table class="resourceTable">
<tr>
<td class="nameCell">None</td>
<td>No button is specified as the default.
</td>
</tr>
<tr>
<td class="nameCell">Primary</td>
<td>The primary button is the default.
</td>
</tr>
<tr>
<td class="nameCell">Secondary</td>
<td>The secondary button is the default.
</td>
</tr>
<tr>
<td class="nameCell">Close</td>
<td>The close button is the default.
</td>
</tr>
</table>

<br />

**ContentDialogResult**
<table class="resourceTable">
<tr>
<td class="nameCell">None</td>
<td>No button was tapped.
</td>
</tr>
<tr>
<td class="nameCell">Primary</td>
<td>The primary button was tapped by the user.
</td>
</tr>
<tr>
<td class="nameCell">Secondary</td>
<td>The secondary button was tapped by the user.
</td>
</tr>
</table>

<br />

**ContentDialogButtonClickEventArgs**
<table class="resourceTable">
<tr>
<td class="nameCell">Cancel</td>
<td>Gets or sets a value that can cancel the button click. A true value for Cancel cancels the default behavior.
</td>
</tr>
<tr>
<td class="nameCell">GetDeferral</td>
<td>Gets a `FluentAvalonia.Core.Deferral` that the app can use to respond asynchronously to the closing event.
</td>
</tr>
</table>

<br />

**ContentDialogClosedEventArgs**
<table class="resourceTable">
<tr>
<td class="nameCell">Result</td>
<td>Gets the `FluentAvalonia.UI.Controls.ContentDialogResult` of the button click event.
</td>
</tr>
</table>

<br />

**ContentDialogClosingEventArgs**
<table class="resourceTable">
<tr>
<td class="nameCell">Cancel</td>
<td>Gets or sets a value that can cancel the closing of the dialog. A true value for Cancel cancels the default behavior.
</td>
</tr>
<tr>
<td class="nameCell">Result</td>
<td>Gets the `FluentAvalonia.UI.Controls.ContentDialogResult` of the closing event.
</td>
</tr>
<tr>
<td class="nameCell">GetDeferral</td>
<td>Gets a `FluentAvalonia.Core.Deferral` that the app can use to respond asynchronously to the closing event.
</td>
</tr>
</table>

<br />



