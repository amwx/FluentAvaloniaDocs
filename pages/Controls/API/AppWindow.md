## API

<h5>Note: Inherited members are not shown</h5>
<br />

**Properties**



<br />

**Events**



<br />

**Methods**



<br />

## Related Enums/Classes

**IApplicationSplashScreen**
<table class="resourceTable">
<tr>
<td class="nameCell">AppName</td>
<td>Specifies the name of the Application to display during the SplashScreen
</td>
</tr>
<tr>
<td class="nameCell">AppIcon</td>
<td>Specifies the desired image to be shown during the SplashScreen
</td>
</tr>
<tr>
<td class="nameCell">SplashScreenContent</td>
<td>Specifies custom content to be shown during the SplashScreen
</td>
</tr>
<tr>
<td class="nameCell">MinimumShowTime</td>
<td>Specifies the minimum show time (in milliseconds) for the SplashScreen.
</td>
</tr>
<tr>
<td class="nameCell">RunTasks(CancellationToken)</td>
<td>Called by AppWindow to run necessary background tasks during the splashscreen
</td>
</tr>
</table>

<br />

**AppWindowTitleBar**
<table class="resourceTable">
<tr>
<td class="nameCell">BackgroundColor</td>
<td>Gets or sets the background color of the title bar when the window is active
</td>
</tr>
<tr>
<td class="nameCell">ForegroundColor</td>
<td>Gets or sets the foreground color of the title bar when the window is active
</td>
</tr>
<tr>
<td class="nameCell">InactiveBackgroundColor</td>
<td>Gets or sets the background color of the title bar when the window is inactive
</td>
</tr>
<tr>
<td class="nameCell">InactiveForegroundColor</td>
<td>Gets or sets the foreground color of the title bar when the window is inactive
</td>
</tr>
<tr>
<td class="nameCell">ButtonBackgroundColor</td>
<td>Gets or sets the background color of the caption buttons when the window is active
</td>
</tr>
<tr>
<td class="nameCell">ButtonForegroundColor</td>
<td>Gets or sets the foreground color of the caption buttons when the window is active
</td>
</tr>
<tr>
<td class="nameCell">ButtonHoverBackgroundColor</td>
<td>Gets or sets the background color of the caption buttons when the window is active and the pointer is over the minimize or maximize button
</td>
</tr>
<tr>
<td class="nameCell">ButtonHoverForegroundColor</td>
<td>Gets or sets the foreground color of the caption buttons when the window is active and the pointer is over the minimize or maximize button
</td>
</tr>
<tr>
<td class="nameCell">ButtonPressedBackgroundColor</td>
<td>Gets or sets the background color of the caption buttons when the window is active and the pointer is pressed on the minimize or maximize button
</td>
</tr>
<tr>
<td class="nameCell">ButtonPressedForegroundColor</td>
<td>Gets or sets the foreground color of the caption buttons when the window is active and the pointer is pressed on the minimize or maximize button
</td>
</tr>
<tr>
<td class="nameCell">ButtonInactiveBackgroundColor</td>
<td>Gets or sets the background color of the caption buttons when the window is inactive
</td>
</tr>
<tr>
<td class="nameCell">ButtonInactiveForegroundColor</td>
<td>Gets or sets the foreground color of the caption buttons when the window is inactive
</td>
</tr>
<tr>
<td class="nameCell">ExtendsContentIntoTitleBar</td>
<td>Gets or sets whether the window content should display in the title bar area of the window
</td>
</tr>
<tr>
<td class="nameCell">TitleBarHitTestType</td>
<td>Gets or sets how the hit test logic should handle hit testing controls that are placed in the title bar drag rect region
</td>
</tr>
<tr>
<td class="nameCell">Height</td>
<td>Gets or sets the height of the default title bar
</td>
</tr>
<tr>
<td class="nameCell">LeftInset</td>
<td>Gets or sets the system reserved region for caption buttons
</td>
</tr>
<tr>
<td class="nameCell">RightInset</td>
<td>Gets or sets the system reserved region for caption buttons
</td>
</tr>
<tr>
<td class="nameCell">SetDragRectangles(Rect[])</td>
<td>Sets custom specified drag regions for the window. Setting this value overrides the default drag rect. Pass null to restore to the default.
</td>
</tr>
</table>

<br />

**IAppWindowPlatformFeatures**
<table class="resourceTable">
<tr>
<td class="nameCell">SetWindowBorderColor(Color)</td>
<td>Windows11 only, sets the border color of the current window to the specified color
</td>
</tr>
<tr>
<td class="nameCell">SetTaskBarProgressBarState(TaskBarProgressBarState)</td>
<td>Activate the taskbar progressbar indicator with the given state
</td>
</tr>
<tr>
<td class="nameCell">SetTaskBarProgressBarValue(UInt64, UInt64)</td>
<td>Activate the taskbar progressbar indicator with the given values
</td>
</tr>
</table>

<br />

**TaskBarProgressBarState**
<table class="resourceTable">
<tr>
<td class="nameCell">None</td>
<td>No TaskBarProgressBar is displayed
</td>
</tr>
<tr>
<td class="nameCell">Normal</td>
<td>A green indicator is displayed in the taskbar button
</td>
</tr>
<tr>
<td class="nameCell">Paused</td>
<td>A yellow progress indicator is displayed in the taskbar button.
</td>
</tr>
<tr>
<td class="nameCell">Error</td>
<td>A red progress indicator is displayed in the taskbar button.
</td>
</tr>
<tr>
<td class="nameCell">Indeterminate</td>
<td>A pulsing green indicator is displayed in the taskbar button.
</td>
</tr>
</table>

<br />



