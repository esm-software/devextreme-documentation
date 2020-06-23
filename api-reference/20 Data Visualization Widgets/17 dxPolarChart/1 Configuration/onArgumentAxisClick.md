---
EventForAction: ..\4 Events\argumentAxisClick.md
type: function(e) | string
---
---
##### notUsedInTheme

##### shortDescription
A handler for the [argumentAxisClick](/api-reference/20%20Data%20Visualization%20Widgets/17%20dxPolarChart/4%20Events/argumentAxisClick.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxPolarChart/Events/#argumentAxisClick') event.

##### param(e): object
Information about the event.

##### field(e.component): object
The <a href="/Documentation/16_1/ApiReference/Data_Visualization_Widgets/dxPolarChart/Methods/#instance">widget instance</a>.

##### field(e.element): object
The widget's container.

##### field(e.jQueryEvent): jQuery-event object
The jQuery event.

##### field(e.target): object
The argument axis.

##### field(e.argument): Date|Number|string
The value of the clicked label.

---
When implementing a handling function, use the object passed to it as the parameter. You can find the value of the clicked label among fields of this object.

Alternatively, you can navigate to a specific URL when the **argumentAxisClick** event fires. For this purpose, assign this URL to the **onArgumentAxisClick** option.