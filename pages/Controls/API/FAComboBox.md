## API

<h5>Note: Inherited members are not shown</h5>
<br />

**Properties**

<table class="resourceTable">
<tr>
<td class="nameCell">HorizontalContentAlignment</td>
<td>Gets or sets the `Avalonia.Layout.HorizontalAlignment` of the content in the ComboBox
</td>
</tr>
<tr>
<td class="nameCell">HorizontalContentAlignmentProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.HorizontalContentAlignment` property
</td>
</tr>
<tr>
<td class="nameCell">IsDropDownOpen</td>
<td>Gets or sets whether this ComboBox's dropdown is open
</td>
</tr>
<tr>
<td class="nameCell">IsDropDownOpenProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.IsDropDownOpen` property
</td>
</tr>
<tr>
<td class="nameCell">IsEditable</td>
<td>Gets or sets whether this ComboBox is editable
</td>
</tr>
<tr>
<td class="nameCell">IsEditableProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.IsEditable` property
</td>
</tr>
<tr>
<td class="nameCell">IsSelectionBoxHighlighted</td>
<td>Gets whether the SelectionBox is hightlighted
</td>
</tr>
<tr>
<td class="nameCell">IsSelectionBoxHighlightedProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.IsSelectionBoxHighlighted` property
</td>
</tr>
<tr>
<td class="nameCell">MaxDropDownHeight</td>
<td>Gets or sets the maximum allowed height of the dropdown
</td>
</tr>
<tr>
<td class="nameCell">MaxDropDownHeightProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.MaxDropDownHeight` property
</td>
</tr>
<tr>
<td class="nameCell">PlaceholderForeground</td>
<td>Gets or sets a brush that describes the color of placeholder text.
</td>
</tr>
<tr>
<td class="nameCell">PlaceholderForegroundProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.PlaceholderForeground` property
</td>
</tr>
<tr>
<td class="nameCell">PlaceholderText</td>
<td>Gets or sets the text that is displayed in the control until the value is changed by a user action or some other operation.
</td>
</tr>
<tr>
<td class="nameCell">PlaceholderTextProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.PlaceholderText` property
</td>
</tr>
<tr>
<td class="nameCell">SelectionBoxItem</td>
<td>Gets the item shown whne the ComboBox is closed
</td>
</tr>
<tr>
<td class="nameCell">SelectionBoxItemProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.SelectionBoxItem` property
</td>
</tr>
<tr>
<td class="nameCell">SelectionBoxItemTemplate</td>
<td>Gets the template applied to the selection box content.
</td>
</tr>
<tr>
<td class="nameCell">SelectionBoxItemTemplateProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.SelectionBoxItemTemplate` property
</td>
</tr>
<tr>
<td class="nameCell">SelectionChangedTrigger</td>
<td>Gets or sets a value that indicates what action causes a SelectionChanged event to occur.
</td>
</tr>
<tr>
<td class="nameCell">SelectionChangedTriggerProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.SelectionChangedTrigger` property
</td>
</tr>
<tr>
<td class="nameCell">Text</td>
<td>Gets or sets the text in the ComboBox.
</td>
</tr>
<tr>
<td class="nameCell">TextBoxTheme</td>
<td>Gets or sets the `Avalonia.Styling.ControlTheme` used for the TextBox part of the ComboBox
</td>
</tr>
<tr>
<td class="nameCell">TextBoxThemeProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.TextBoxTheme` property
</td>
</tr>
<tr>
<td class="nameCell">TextProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.Text` property
</td>
</tr>
<tr>
<td class="nameCell">VerticalContentAlignment</td>
<td>Gets or sets the `Avalonia.Layout.VerticalAlignment` of the content in the ComboBox
</td>
</tr>
<tr>
<td class="nameCell">VerticalContentAlignmentProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAComboBox.VerticalContentAlignment` property
</td>
</tr>
</table>


<br />

**Events**

<table class="resourceTable">
<tr>
<td class="nameCell">DropDownClosed</td>
<td>Occurs when the drop-down portion of the ComboBox closes.
</td>
</tr>
<tr>
<td class="nameCell">DropDownOpened</td>
<td>Occurs when the drop-down portion of the ComboBox opens.
</td>
</tr>
<tr>
<td class="nameCell">TextSubmitted</td>
<td>Occurs when the user submits some text that does not correspond to an item in the ComboBox dropdown list.
</td>
</tr>
</table>


<br />

**Methods**

<table class="resourceTable">
</table>


<br />

## Related Enums/Classes

**FAComboBoxSelectionChangedTrigger**
<table class="resourceTable">
<tr>
<td class="nameCell">Committed</td>
<td>A change event occurs when the user commits a selection in the ComboBox
</td>
</tr>
<tr>
<td class="nameCell">Always</td>
<td>A change event occurs each time the user navigates to a new selection in the ComboBox
</td>
</tr>
</table>

<br />

**FAComboBoxTextSubmittedEventArgs**
<table class="resourceTable">
<tr>
<td class="nameCell">Handled</td>
<td>Gets or sets whether the TextSubmitted event was handled or not. If **true**, the framework will not automatically update the selected item of the ComboBox to the new value.
</td>
</tr>
<tr>
<td class="nameCell">Text</td>
<td>Gets the custom text value entered by the user
</td>
</tr>
</table>

<br />



