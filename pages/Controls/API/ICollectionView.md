## API

<h5>Note: Inherited members are not shown</h5>
<br />

**Properties**

<table class="resourceTable">
<tr>
<td class="nameCell">CollectionGroups</td>
<td>Returns any collection groups that are associated with the view
</td>
</tr>
<tr>
<td class="nameCell">CurrentItem</td>
<td>Gets the current item in the view
</td>
</tr>
<tr>
<td class="nameCell">CurrentPosition</td>
<td>Gets the ordinal position of the CurrentItem within the View
</td>
</tr>
<tr>
<td class="nameCell">HasMoreItems</td>
<td>Gets a sentinel value that supports incremental loading implementations. See also LoadMoreItemsAsync
</td>
</tr>
<tr>
<td class="nameCell">IsCurrentAfterLast</td>
<td>Gets a value that indicates whether the CurrentItem of the view is beyond the end of the collection
</td>
</tr>
<tr>
<td class="nameCell">IsCurrentBeforeFirst</td>
<td>Gets a value that indicates whether the CurrentItem of the view is beyond the beginning of the collection
</td>
</tr>
</table>


<br />

**Events**

<table class="resourceTable">
<tr>
<td class="nameCell">CurrentChanged</td>
<td>When implementing this interface, fire this event after the current item has been changed
</td>
</tr>
<tr>
<td class="nameCell">CurrentChanging</td>
<td>When implementing this interface, fire this event before changing the current item. The event handler can cancel this event
</td>
</tr>
</table>


<br />

**Methods**

<table class="resourceTable">
<tr>
<td class="nameCell">LoadMoreItemsAsync(UInt32)</td>
<td>Initializes incremental loading from the view
</td>
</tr>
<tr>
<td class="nameCell">MoveCurrentTo(Object)</td>
<td>Sets the specified item to be the CurrentItem in the view
</td>
</tr>
<tr>
<td class="nameCell">MoveCurrentToFirst()</td>
<td>Sets the first item in the view as the CurrentItem
</td>
</tr>
<tr>
<td class="nameCell">MoveCurrentToLast()</td>
<td>Sets the last item in the view as the CurrentItem
</td>
</tr>
<tr>
<td class="nameCell">MoveCurrentToNext()</td>
<td>Sets the item after the CurrentItem in the view as the CurrentItem
</td>
</tr>
<tr>
<td class="nameCell">MoveCurrentToPosition(Int32)</td>
<td>Sets the item at the specified index to be the CurrentItem in the view
</td>
</tr>
<tr>
<td class="nameCell">MoveCurrentToPrevious()</td>
<td>Sets the item before the CurrentItem in the view as the CurrentItem
</td>
</tr>
</table>


<br />

## Related Enums/Classes



