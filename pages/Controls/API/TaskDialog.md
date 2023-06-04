## API

<h5>Note: Inherited members are not shown</h5>
<br />

**Properties**

<table class="resourceTable">
<tr>
<td class="nameCell">Buttons</td>
<td>Gets the list of buttons that display at the bottom of the TaskDialog
</td>
</tr>
<tr>
<td class="nameCell">ButtonsProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.Buttons` property
</td>
</tr>
<tr>
<td class="nameCell">Commands</td>
<td>Gets the list of Commands displayed in the TaskDialog
</td>
</tr>
<tr>
<td class="nameCell">CommandsProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.Commands` property
</td>
</tr>
<tr>
<td class="nameCell">Footer</td>
<td>Gets or sets the footer content
</td>
</tr>
<tr>
<td class="nameCell">FooterProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.Footer` property
</td>
</tr>
<tr>
<td class="nameCell">FooterTemplate</td>
<td>Gets or sets the IDataTemplate for the footer content
</td>
</tr>
<tr>
<td class="nameCell">FooterTemplateProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.FooterTemplate` property
</td>
</tr>
<tr>
<td class="nameCell">FooterVisibility</td>
<td>Gets or sets the visibility of the Footer area
</td>
</tr>
<tr>
<td class="nameCell">FooterVisibilityProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.FooterVisibility` property
</td>
</tr>
<tr>
<td class="nameCell">Header</td>
<td>Gets or sets the dialog header text
</td>
</tr>
<tr>
<td class="nameCell">HeaderBackground</td>
<td>Gets or sets the background of the header region of the task dialog
</td>
</tr>
<tr>
<td class="nameCell">HeaderBackgroundProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.HeaderBackground` property
</td>
</tr>
<tr>
<td class="nameCell">HeaderForeground</td>
<td>Gets or sets the foreground of the header text for the TaskDialog
</td>
</tr>
<tr>
<td class="nameCell">HeaderForegroundProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.HeaderForeground` property
</td>
</tr>
<tr>
<td class="nameCell">HeaderProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.Header` property
</td>
</tr>
<tr>
<td class="nameCell">IconForeground</td>
<td>Gets or sets the foreground of the `FluentAvalonia.UI.Controls.TaskDialog.IconSource` for the TaskDialog
</td>
</tr>
<tr>
<td class="nameCell">IconForegroundProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.IconForeground` property
</td>
</tr>
<tr>
<td class="nameCell">IconSource</td>
<td>Gets or sets the dialog Icon
</td>
</tr>
<tr>
<td class="nameCell">IconSourceProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.IconSource` property
</td>
</tr>
<tr>
<td class="nameCell">IsFooterExpanded</td>
<td>Gets or sets whether the footer is visible
</td>
</tr>
<tr>
<td class="nameCell">IsFooterExpandedProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.IsFooterExpanded` property
</td>
</tr>
<tr>
<td class="nameCell">ShowProgressBar</td>
<td>Gets or sets whether this TaskDialog shows a progress bar
</td>
</tr>
<tr>
<td class="nameCell">ShowProgressBarProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.ShowProgressBar` property
</td>
</tr>
<tr>
<td class="nameCell">SubHeader</td>
<td>Gets or sets the dialog sub header text
</td>
</tr>
<tr>
<td class="nameCell">SubHeaderProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.SubHeader` property
</td>
</tr>
<tr>
<td class="nameCell">Title</td>
<td>Gets or sets the title of the dialog
</td>
</tr>
<tr>
<td class="nameCell">TitleProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialog.Title` property
</td>
</tr>
<tr>
<td class="nameCell">XamlRoot</td>
<td>Gets or sets the root visual that should host this dialog
</td>
</tr>
</table>


<br />

**Events**

<table class="resourceTable">
<tr>
<td class="nameCell">Closed</td>
<td>Raised when the TaskDialog is closed
</td>
</tr>
<tr>
<td class="nameCell">Closing</td>
<td>Raised when the TaskDialog is beginning to close
</td>
</tr>
<tr>
<td class="nameCell">Opened</td>
<td>Raised when the TaskDialog is opened and ready to be shown on screen
</td>
</tr>
<tr>
<td class="nameCell">Opening</td>
<td>Raised when the TaskDialog is beginning to open, but is not yet visible
</td>
</tr>
</table>


<br />

**Methods**

<table class="resourceTable">
<tr>
<td class="nameCell">ShowAsync(Boolean)</td>
<td>Shows the TaskDialog
</td>
</tr>
<tr>
<td class="nameCell">Hide()</td>
<td>Hides the TaskDialog with a `FluentAvalonia.UI.Controls.TaskDialogStandardResult.None` result
</td>
</tr>
<tr>
<td class="nameCell">Hide(Object)</td>
<td>Hides the dialog with the specified dialog result
</td>
</tr>
</table>


<br />

## Related Enums/Classes

**TaskDialogButton**
<table class="resourceTable">
<tr>
<td class="nameCell">IconSource</td>
<td>Gets or sets the icon displayed in the button
</td>
</tr>
<tr>
<td class="nameCell">Command</td>
<td>Gets or sets the command that is invoked when the button is clicked
</td>
</tr>
<tr>
<td class="nameCell">CommandParameter</td>
<td>Gets or sets the command parameter for the `FluentAvalonia.UI.Controls.TaskDialogButton.Command`
</td>
</tr>
<tr>
<td class="nameCell">IconSourceProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialogButton.IconSource` property
</td>
</tr>
<tr>
<td class="nameCell">CommandProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialogButton.Command` property
</td>
</tr>
<tr>
<td class="nameCell">CommandParameterProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialogButton.CommandParameter` property
</td>
</tr>
<tr>
<td class="nameCell">OKButton</td>
<td>Predefined button for 'OK'. Note that predefined buttons cannot have command, icons, or click handlers attached - they are meant for simple purposes
</td>
</tr>
<tr>
<td class="nameCell">CancelButton</td>
<td>Predefined button for 'Cancel'. Note that predefined buttons cannot have command, icons, or click handlers attached - they are meant for simple purposes
</td>
</tr>
<tr>
<td class="nameCell">YesButton</td>
<td>Predefined button for 'Yes'. Note that predefined buttons cannot have command, icons, or click handlers attached - they are meant for simple purposes
</td>
</tr>
<tr>
<td class="nameCell">NoButton</td>
<td>Predefined button for 'No'. Note that predefined buttons cannot have command, icons, or click handlers attached - they are meant for simple purposes
</td>
</tr>
<tr>
<td class="nameCell">RetryButton</td>
<td>Predefined button for 'Retry'. Note that predefined buttons cannot have command, icons, or click handlers attached - they are meant for simple purposes
</td>
</tr>
<tr>
<td class="nameCell">CloseButton</td>
<td>Predefined button for 'Close'. Note that predefined buttons cannot have command, icons, or click handlers attached - they are meant for simple purposes
</td>
</tr>
<tr>
<td class="nameCell">Click</td>
<td>Raised when the button is clicked
</td>
</tr>
</table>

<br />

**TaskDialogCommand**
<table class="resourceTable">
<tr>
<td class="nameCell">ClosesOnInvoked</td>
<td>Gets or sets whether invoking this command should also close the dialog
</td>
</tr>
<tr>
<td class="nameCell">Description</td>
<td>Gets or sets the description of the TaskDialogCommand
</td>
</tr>
<tr>
<td class="nameCell">DescriptionProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialogCommand.Description` property
</td>
</tr>
</table>

<br />

**TaskDialogCheckBox**
<table class="resourceTable">
</table>

<br />

**TaskDialogRadioButton**
<table class="resourceTable">
<tr>
<td class="nameCell">IsChecked</td>
<td>Gets or sets whether this RadioButton is checked
</td>
</tr>
<tr>
<td class="nameCell">IsCheckedProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.TaskDialogRadioButton.IsChecked` property
</td>
</tr>
</table>

<br />

**TaskDialogFooterVisibility**
<table class="resourceTable">
<tr>
<td class="nameCell">Never</td>
<td>The footer is never shown
</td>
</tr>
<tr>
<td class="nameCell">Auto</td>
<td>The footer is hidden by default, but can be expanded open
</td>
</tr>
<tr>
<td class="nameCell">Always</td>
<td>The footer is always visible
</td>
</tr>
</table>

<br />

**TaskDialogClosingEventArgs**
<table class="resourceTable">
<tr>
<td class="nameCell">Cancel</td>
<td>Gets or sets a value that can cancel the closing of the dialog. A true value for Cancel cancels the default behavior.
</td>
</tr>
<tr>
<td class="nameCell">Result</td>
<td>Gets the result of the closing event.
</td>
</tr>
<tr>
<td class="nameCell">GetDeferral</td>
<td>Gets a `FluentAvalonia.Core.Deferral` that the app can use to respond asynchronously to the closing event.
</td>
</tr>
</table>

<br />

**TaskDialogProgressState**
<table class="resourceTable">
<tr>
<td class="nameCell">Normal</td>
<td>Progress bar is in a normal state
</td>
</tr>
<tr>
<td class="nameCell">Error</td>
<td>Progress bar is shown in an error state
</td>
</tr>
<tr>
<td class="nameCell">Suspended</td>
<td>Progress bar is shown in a suspended state
</td>
</tr>
<tr>
<td class="nameCell">Indeterminate</td>
<td>Progress bar is shown as indeterminate
</td>
</tr>
</table>

<br />

**TaskDialogStandardResult**
<table class="resourceTable">
<tr>
<td class="nameCell">None</td>
<td>
</td>
</tr>
<tr>
<td class="nameCell">OK</td>
<td>
</td>
</tr>
<tr>
<td class="nameCell">Cancel</td>
<td>
</td>
</tr>
<tr>
<td class="nameCell">Yes</td>
<td>
</td>
</tr>
<tr>
<td class="nameCell">No</td>
<td>
</td>
</tr>
<tr>
<td class="nameCell">Retry</td>
<td>
</td>
</tr>
<tr>
<td class="nameCell">Close</td>
<td>
</td>
</tr>
</table>

<br />



