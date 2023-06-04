## API

<h5>Note: Inherited members are not shown</h5>
<br />

**Properties**

<table class="resourceTable">
<tr>
<td class="nameCell">Data</td>
<td>Gets or sets a Geometry that specifies the shape to be drawn. In XAML. this can also be set using a string that describes Move and draw commands syntax.
</td>
</tr>
<tr>
<td class="nameCell">DataProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAPathIcon.Data` property
</td>
</tr>
<tr>
<td class="nameCell">Stretch</td>
<td>Gets or sets a `FluentAvalonia.UI.Controls.FAPathIcon.Stretch` enumeration value that describes how the shape fills its allocated space.
</td>
</tr>
<tr>
<td class="nameCell">StretchDirection</td>
<td>Gets or sets a value controlling in what direction contents will be stretched.
</td>
</tr>
<tr>
<td class="nameCell">StretchDirectionProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAPathIcon.StretchDirection` property.
</td>
</tr>
<tr>
<td class="nameCell">StretchProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.FAPathIcon.Stretch` property.
</td>
</tr>
</table>


<br />

**Events**

<table class="resourceTable">
</table>


<br />

**Methods**

<table class="resourceTable">
<tr>
<td class="nameCell">IsDataValid(String, Geometry@)</td>
<td>Quick and dirty check if we have a valid PathGeometry. This probably needs to be more robust, but this is better than a bunch of InvalidDataExceptions becase we don't have a Path.TryParse() method. This does still fail sometimes, but its better than nothing. Its really only meant to be called from the StringToIconElementConverter
</td>
</tr>
</table>


<br />

## Related Enums/Classes



