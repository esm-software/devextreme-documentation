In the *bar* series type, data is displayed as sets of rectangular bars with lengths proportional to the values that they represent. Often, *bar* series are used to compare values in different discrete categories such as months, countries, age, etc. When there are several bar series, bars for each argument are displayed side-by-side. If you need to show bars for each series stacked on each other, use the *stackedBar* series type (see [Stacked Bar](/concepts/05%20Widgets/Chart/20%20Series%20Types/Stacked%20Bar.md '/Documentation/Guide/Widgets/Chart/Series_Types/#Stacked_Bar')).

![BarSeriesType ChartJS](/images/ChartJS/Bar.png)

To use the *bar* series type, assign *'bar'* to the **type** property of the **series** configuration object.

    <!--JavaScript-->var chartOptions = {
        // ...
        series: {
            type: 'bar'
        }
    };

To learn how to specify data for a series, refer to the [Data Binding](/concepts/05%20Widgets/zz%20Common/10%20Data%20Visualization%20Widgets/85%20Charts%20-%20Data%20Binding/10%20Provide%20Data '/Documentation/Guide/Widgets/Common/Data_Visualization_Widgets/Charts_-_Data_Binding/Provide_Data/') topic.

To change the series default appearance, set the options of the **series** configuration object. For instance, you can change the following.

*   **Bar Color**  
    A color from the chart's [palette](/concepts/05%20Widgets/zz%20Common/10%20Data%20Visualization%20Widgets/70%20Appearance%20Customization/1%20Palettes/10%20Palettes.md '/Documentation/Guide/Widgets/Common/Data_Visualization_Widgets/Appearance_Customization/#Palettes') is used by default. Set a custom color using the series' [color](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/CommonSeries/color.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Configuration/commonSeriesSettings/#color') property.
    
*   **Bar Border Options**  
    Make a border visible by setting the **visible** property of the series' [border](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/CommonSeries/border '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Configuration/commonSeriesSettings/border/') object. When the border is visible, you can change its width, style and color using the **width**, **dashStyle** and **color** properties of the series' **border** object. In addition, you can change the border settings when the series is hovered or selected. To do this, set the properties of the **border** object within the series' [hoverStyle](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/CommonSeries/hoverStyle '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Series_Types/BarSeries/hoverStyle/') or [selectionStyle](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/CommonSeries/selectionStyle '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Series_Types/BarSeries/selectionStyle/') configuration object.
    
*   **Corner Radius**  
    Set a corner radius for bars using the series' **cornerRadius** property. This is helpful if you need rounded corners in bars.
    
*   **Bar Label Options**  
    Make bar labels visible by setting the **visible** property of the series' [label](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/BarSeries/label '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Series_Types/BarSeries/label/') object. For details on other label options, refer to the [Series Point Labels](/concepts/05%20Widgets/Chart/10%20Visual%20Elements/030%20Series%20Point%20Labels.md '/Documentation/Guide/Widgets/Chart/Visual_Elements/#Series_Point_Labels') topic.

These and other options that can be set for series of the *bar* type are explained in the [BarSeries](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/BarSeries '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Series_Types/BarSeries/') Reference section. Set the required series options within the [series](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/1%20Configuration/series '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Configuration/series/') object of the chart's configuration object.

<a href="https://js.devexpress.com/Demos/WidgetsGallery/Demo/Charts/StandardBar/jQuery/Light/" class="button orange small fix-width-155" style="margin-right: 20px;" target="_blank">View Standard Bar Demo</a>
<a href="https://js.devexpress.com/Demos/WidgetsGallery/Demo/Charts/SideBySideBar/jQuery/Light/" class="button orange small fix-width-155" style="margin-right: 20px;" target="_blank">View Side-by-Side Bar Demo</a>