## API

<h5>Note: Inherited members are not shown</h5>
<br />

**Properties**

<table class="resourceTable">
<tr>
<td class="nameCell">ClosedDisplayMode</td>
<td>Gets or sets a value that indicates whether icon buttons are displayed when the command bar is not completely open.
</td>
</tr>
<tr>
<td class="nameCell">ClosedDisplayModeProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.CommandBar.ClosedDisplayMode` property
</td>
</tr>
<tr>
<td class="nameCell">DefaultLabelPosition</td>
<td>Gets or sets a value that indicates the placement and visibility of the labels on the command bar's buttons.
</td>
</tr>
<tr>
<td class="nameCell">DefaultLabelPositionProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.CommandBar.DefaultLabelPosition` property
</td>
</tr>
<tr>
<td class="nameCell">IsDynamicOverflowEnabled</td>
<td>Gets or sets a value that indicates whether primary commands automatically move to the overflow menu when space is limited.
</td>
</tr>
<tr>
<td class="nameCell">IsDynamicOverflowEnabledProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.CommandBar.IsDynamicOverflowEnabled`
</td>
</tr>
<tr>
<td class="nameCell">IsOpen</td>
<td>Gets or sets a value that indicates whether the CommandBar is open.
</td>
</tr>
<tr>
<td class="nameCell">IsOpenProperty</td>
<td>Define the `FluentAvalonia.UI.Controls.CommandBar.IsOpen` property
</td>
</tr>
<tr>
<td class="nameCell">IsSticky</td>
<td>Gets or sets a value that indicates whether the CommandBar does not close on light dismiss.
</td>
</tr>
<tr>
<td class="nameCell">IsStickyProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.CommandBar.IsSticky` property
</td>
</tr>
<tr>
<td class="nameCell">ItemsAlignment</td>
<td>Gets or sets how the `FluentAvalonia.UI.Controls.CommandBar.PrimaryCommands` align in the CommandBar
</td>
</tr>
<tr>
<td class="nameCell">ItemsAlignmentProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.CommandBar.ItemsAlignment` property
</td>
</tr>
<tr>
<td class="nameCell">OverflowButtonVisibility</td>
<td>Gets or sets a value that indicates when a command bar's overflow button is shown.
</td>
</tr>
<tr>
<td class="nameCell">OverflowButtonVisibilityProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.CommandBar.OverflowButtonVisibility` property
</td>
</tr>
<tr>
<td class="nameCell">PrimaryCommands</td>
<td>Gets the collection of primary command elements for the CommandBar.
</td>
</tr>
<tr>
<td class="nameCell">PrimaryCommandsProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.CommandBar.PrimaryCommands` property
</td>
</tr>
<tr>
<td class="nameCell">SecondaryCommands</td>
<td>Gets the collection of secondary command elements for the CommandBar.
</td>
</tr>
<tr>
<td class="nameCell">SecondaryCommandsProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.CommandBar.SecondaryCommands` property
</td>
</tr>
</table>


<br />

**Events**

<table class="resourceTable">
<tr>
<td class="nameCell">Closed</td>
<td>Occurs when the CommandBar changes from visible to hidden.
</td>
</tr>
<tr>
<td class="nameCell">Closing</td>
<td>Occurs when the CommandBar starts to change from visible to hidden.
</td>
</tr>
<tr>
<td class="nameCell">Opened</td>
<td>Occurs when the CommandBar changes from hidden to visible.
</td>
</tr>
<tr>
<td class="nameCell">Opening</td>
<td>Occurs when the CommandBar starts to change from hidden to visible.
</td>
</tr>
</table>


<br />

**Methods**

<table class="resourceTable">
</table>


<br />

## Related Enums/Classes

**CommandBarClosedDisplayMode**
<table class="resourceTable">
<tr>
<td class="nameCell">Compact</td>
<td>Icon buttons are displayed but labels are not visible.
</td>
</tr>
<tr>
<td class="nameCell">Minimal</td>
<td>Only the ellipsis is displayed. Neither icon buttons nor labels are visible.
</td>
</tr>
<tr>
<td class="nameCell">Hidden</td>
<td>The app bar is not displayed.
</td>
</tr>
</table>

<br />

**CommandBarOverflowButtonVisibility**
<table class="resourceTable">
<tr>
<td class="nameCell">Auto</td>
<td>The overflow button automatically hides when there are no secondary commands and the closed state of the CommandBar is the same as the open state.
</td>
</tr>
<tr>
<td class="nameCell">Visible</td>
<td>The overflow button is always shown.
</td>
</tr>
<tr>
<td class="nameCell">Collapsed</td>
<td>The overflow button is never shown.
</td>
</tr>
</table>

<br />

**CommandBarItemsAlignment**
<table class="resourceTable">
<tr>
<td class="nameCell">Left</td>
<td>The items are left-aligned on the CommandBar
</td>
</tr>
<tr>
<td class="nameCell">Right</td>
<td>The items are right-aligned on the CommandBar
</td>
</tr>
</table>

<br />

**CommandBarDefaultLabelPosition**
<table class="resourceTable">
<tr>
<td class="nameCell">Bottom</td>
<td>App bar button labels are shown below the icon. Labels are visible only when the command bar is open.
</td>
</tr>
<tr>
<td class="nameCell">Right</td>
<td>App bar button labels are shown to the right of the icon. Labels are visible even when the command bar is closed.
</td>
</tr>
<tr>
<td class="nameCell">Collapsed</td>
<td>App bar button labels are always hidden whether the command bar is open or closed.
</td>
</tr>
</table>

<br />

**ICommandBarElement**
<table class="resourceTable">
<tr>
<td class="nameCell">DynamicOverflowOrder</td>
<td>Gets or sets a value that indicates the order in which a primary command in a CommandBar should be moved to the overflow menu when there is not enough room to display all primary commands.
</td>
</tr>
<tr>
<td class="nameCell">IsCompact</td>
<td>Gets or sets a value that indicates whether the element is shown with no label and reduced padding.
</td>
</tr>
<tr>
<td class="nameCell">IsInOverflow</td>
<td>Gets a value that indicates whether the CommandBar command is currently located in the overflow menu.
</td>
</tr>
</table>

<br />



