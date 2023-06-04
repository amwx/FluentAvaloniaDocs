## API

<h5>Note: Inherited members are not shown</h5>
<br />

**Properties**

<table class="resourceTable">
<tr>
<td class="nameCell">BackStack</td>
<td>Gets a collection of `FluentAvalonia.UI.Navigation.PageStackEntry` instances representing the backward navigation history of the Frame.
</td>
</tr>
<tr>
<td class="nameCell">BackStackDepth</td>
<td>Gets the number of entries in the navigation back stack.
</td>
</tr>
<tr>
<td class="nameCell">BackStackDepthProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.Frame.BackStackDepth` property
</td>
</tr>
<tr>
<td class="nameCell">BackStackProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.Frame.BackStack` property
</td>
</tr>
<tr>
<td class="nameCell">CacheSize</td>
<td>Gets or sets the number of pages in the navigation history that can be cached for the frame.
</td>
</tr>
<tr>
<td class="nameCell">CacheSizeProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.Frame.CacheSize` property
</td>
</tr>
<tr>
<td class="nameCell">CanGoBack</td>
<td>Gets a value that indicates whether there is at least one entry in back navigation history.
</td>
</tr>
<tr>
<td class="nameCell">CanGoBackProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.Frame.CanGoBack` property
</td>
</tr>
<tr>
<td class="nameCell">CanGoForward</td>
<td>Gets a value that indicates whether there is at least one entry in forward navigation history.
</td>
</tr>
<tr>
<td class="nameCell">CanGoForwardProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.Frame.CanGoForward` property
</td>
</tr>
<tr>
<td class="nameCell">CurrentSourcePageType</td>
<td>Gets a type reference for the content that is currently displayed.
</td>
</tr>
<tr>
<td class="nameCell">CurrentSourcePageTypeProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.Frame.CurrentSourcePageType` property
</td>
</tr>
<tr>
<td class="nameCell">ForwardStack</td>
<td>Gets a collection of `FluentAvalonia.UI.Navigation.PageStackEntry` instances representing the forward navigation history of the Frame.
</td>
</tr>
<tr>
<td class="nameCell">ForwardStackProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.Frame.ForwardStack` property
</td>
</tr>
<tr>
<td class="nameCell">IsNavigationStackEnabled</td>
<td>Gets or sets a value that indicates whether navigation is recorded in the Frame's `FluentAvalonia.UI.Controls.Frame.ForwardStack` or `FluentAvalonia.UI.Controls.Frame.BackStack`.
</td>
</tr>
<tr>
<td class="nameCell">IsNavigationStackEnabledProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.Frame.IsNavigationStackEnabled` property
</td>
</tr>
<tr>
<td class="nameCell">NavigationPageFactory</td>
<td>Gets or sets the user specified factory that should be use for resolving pages when types are not controls or from object instances directly
</td>
</tr>
<tr>
<td class="nameCell">NavigationPageFactoryProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.Frame.NavigationPageFactory` property
</td>
</tr>
<tr>
<td class="nameCell">SourcePageType</td>
<td>Gets or sets a type reference of the current content, or the content that should be navigated to.
</td>
</tr>
<tr>
<td class="nameCell">SourcePageTypeProperty</td>
<td>Defines the `FluentAvalonia.UI.Controls.Frame.SourcePageType` property
</td>
</tr>
</table>


<br />

**Events**

<table class="resourceTable">
<tr>
<td class="nameCell">Navigated</td>
<td>Occurs when the content that is being navigated to has been found and is available from the Content property, although it may not have completed loading.
</td>
</tr>
<tr>
<td class="nameCell">NavigatedFromEvent</td>
<td>Indiates to a page that it has been navigated away from. Takes the place of Microsoft.UI.Xaml.Controls.Page.OnNavigatedFrom() method
</td>
</tr>
<tr>
<td class="nameCell">NavigatedToEvent</td>
<td>Indiates to a page that it is being navigated to. Takes the place of Microsoft.UI.Xaml.Controls.Page.OnNavigatedTo() method
</td>
</tr>
<tr>
<td class="nameCell">Navigating</td>
<td>Occurs when a new navigation is requested.
</td>
</tr>
<tr>
<td class="nameCell">NavigatingFromEvent</td>
<td>Indicates to a page that it is being navigated away from. Takes the place of Microsoft.UI.Xaml.Controls.Page.OnNavigatingFrom() method
</td>
</tr>
<tr>
<td class="nameCell">NavigationFailed</td>
<td>Occurs when an error is raised while navigating to the requested content.
</td>
</tr>
<tr>
<td class="nameCell">NavigationStopped</td>
<td>Occurs when a new navigation is requested while a current navigation is in progress.
</td>
</tr>
</table>


<br />

**Methods**

<table class="resourceTable">
<tr>
<td class="nameCell">GoBack()</td>
<td>Navigates to the most recent item in back navigation history, if a Frame manages its own navigation history.
</td>
</tr>
<tr>
<td class="nameCell">GoBack(NavigationTransitionInfo)</td>
<td>Navigates to the most recent item in back navigation history, if a Frame manages its own navigation history, and specifies the animated transition to use.
</td>
</tr>
<tr>
<td class="nameCell">GoForward()</td>
<td>Navigates to the most recent item in forward navigation history, if a Frame manages its own navigation history.
</td>
</tr>
<tr>
<td class="nameCell">Navigate(Type)</td>
<td>Causes the Frame to load content represented by the specified Page.
</td>
</tr>
<tr>
<td class="nameCell">Navigate(Type, Object)</td>
<td>Causes the Frame to load content represented by the specified Page, also passing a parameter to be interpreted by the target of the navigation.
</td>
</tr>
<tr>
<td class="nameCell">Navigate(Type, Object, NavigationTransitionInfo)</td>
<td>Causes the Frame to load content represented by the specified Page -derived data type, also passing a parameter to be interpreted by the target of the navigation, and a value indicating the animated transition to use.
</td>
</tr>
<tr>
<td class="nameCell">NavigateToType(Type, Object, FrameNavigationOptions)</td>
<td>Causes the Frame to load content represented by the specified Page, also passing a parameter to be interpreted by the target of the navigation.
</td>
</tr>
<tr>
<td class="nameCell">NavigateFromObject(Object, FrameNavigationOptions)</td>
<td>Causes the frame to load content represented by the specified target property with the specified navigation options
</td>
</tr>
<tr>
<td class="nameCell">GetNavigationState()</td>
<td>Serializes the Frame navigation history into a string
</td>
</tr>
<tr>
<td class="nameCell">SetNavigationState(String)</td>
<td>Reads and restores the navigation history of a Frame from a provided serialization string.
</td>
</tr>
<tr>
<td class="nameCell">SetNavigationState(String, Boolean)</td>
<td>Reads and restores the navigation history of a Frame from a provided serialization string, and optionally supresses navigation to the last page type
</td>
</tr>
</table>


<br />

## Related Enums/Classes

**PageStackEntry**
<table class="resourceTable">
<tr>
<td class="nameCell">SourcePageType</td>
<td>Gets the type of page associated with this navigation entry.
</td>
</tr>
<tr>
<td class="nameCell">NavigationTransitionInfo</td>
<td>Gets a value that indicates the animated transition associated with the navigation entry.
</td>
</tr>
<tr>
<td class="nameCell">Parameter</td>
<td>Gets the navigation parameter associated with this navigation entry.
</td>
</tr>
</table>

<br />

**INavigationPageFactory**
<table class="resourceTable">
<tr>
<td class="nameCell">GetPage(Type)</td>
<td>Returns a user specified page based on the given type passed to <see cref="M:FluentAvalonia.UI.Controls.Frame.Navigate(System.Type)" />
</td>
</tr>
<tr>
<td class="nameCell">GetPageFromObject(Object)</td>
<td>Returns a user specified page based on an instance of an existing object
</td>
</tr>
</table>

<br />

**NavigationEventArgs**
<table class="resourceTable">
<tr>
<td class="nameCell">Content</td>
<td>Gets the root node of the target page's content.
</td>
</tr>
<tr>
<td class="nameCell">NavigationMode</td>
<td>Gets a value that indicates the direction of movement during navigation
</td>
</tr>
<tr>
<td class="nameCell">Parameter</td>
<td>Gets any "Parameter" object passed to the target page for the navigation.
</td>
</tr>
<tr>
<td class="nameCell">SourcePageType</td>
<td>Gets the data type of the source page.
</td>
</tr>
<tr>
<td class="nameCell">NavigationTransitionInfo</td>
<td>Gets a value that indicates the animated transition associated with the navigation.
</td>
</tr>
</table>

<br />

**NavigatingCancelEventArgs**
<table class="resourceTable">
<tr>
<td class="nameCell">Cancel</td>
<td>Specifies whether a pending navigation should be canceled.
</td>
</tr>
<tr>
<td class="nameCell">NavigationMode</td>
<td>Gets the value of the mode parameter from the originating Navigate call.
</td>
</tr>
<tr>
<td class="nameCell">SourcePageType</td>
<td>Gets the value of the SourcePageType parameter from the originating Navigate call.
</td>
</tr>
<tr>
<td class="nameCell">NavigationTransitionInfo</td>
<td>Gets a value that indicates the animated transition associated with the navigation.
</td>
</tr>
<tr>
<td class="nameCell">Parameter</td>
<td>Gets the navigation parameter associated with this navigation.
</td>
</tr>
</table>

<br />

**NavigationFailedEventArgs**
<table class="resourceTable">
<tr>
<td class="nameCell">Handled</td>
<td>Gets or sets a value that indicates whether the failure event has been handled.
</td>
</tr>
<tr>
<td class="nameCell">Exception</td>
<td>Gets the result code for the exception that is associated with the failed navigation.
</td>
</tr>
<tr>
<td class="nameCell">SourcePageType</td>
<td>Gets the data type of the target page.
</td>
</tr>
</table>

<br />



