---
layout: post
title: Axis in ##Platform_Name## Linear gauge control | Syncfusion
description: Learn here all about Axis in Syncfusion ##Platform_Name## Linear gauge control of Syncfusion Essential JS 2 and more.
platform: ej2-javascript
control: Axis 
publishingplatform: ##Platform_Name##
documentation: ug
domainurl: ##DomainURL##
---

# Axis in ##Platform_Name## Linear gauge control

Axis is used to indicate the numeric values in the linear scale. The Linear Gauge component can have any number of axes. The sub-elements of an axis are line, ticks, labels, ranges, and pointers.

## Setting the start value and end value of the axis

The start value and end value for the Linear Gauge can be set using the [`minimum`](../api/linear-gauge/axisModel/#minimum) and [`maximum`](../api/linear-gauge/axisModel/#maximum) properties in the [`axes`](../api/linear-gauge/axisModel/) respectively. By default, the start value of the axis is **0** and the end value of the axis is **100**.

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs1/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs1/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs1" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs1/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs1/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs1" %}
{% endif %}

## Line Customization

The following properties in the [`line`](../api/linear-gauge/lineModel) can be used to customize the axis line in the Linear Gauge.

* [`height`](../api/linear-gauge/lineModel/#height) - To set the length of the axis line.
* [`width`](../api/linear-gauge/lineModel/#width) - To set the thickness of the axis line.
* [`color`](../api/linear-gauge/lineModel/#color) - To set the color of the axis line.
* [`offset`](../api/linear-gauge/lineModel/#offset) - To render the axis line with the specified distance from the Linear Gauge.

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs2/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs2/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs2" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs2/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs2/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs2" %}
{% endif %}

## Ticks Customization

Ticks are used to specify the interval in the axis. Ticks are of two types, major ticks and minor ticks. The following properties in the [`majorTicks`](../api/linear-gauge/axisModel/#majorticks) and [`minorTicks`](../api/linear-gauge/axisModel/#minorticks) can be used to customize the major ticks and minor ticks respectively

* [`height`](../api/linear-gauge/tickModel/#height) - To set the length of the major and minor ticks in pixel values.
* [`color`](../api/linear-gauge/tickModel/#color) - To set the color of the major and minor ticks of the Linear Gauge.
* [`width`](../api/linear-gauge/tickModel/#width) - To set the thickness of the major and minor ticks in pixel values.
* [`interval`](../api/linear-gauge/tickModel/#interval) - To set the interval for the major ticks and minor ticks in the Linear Gauge.


{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs3/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs3/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs3" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs3/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs3/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs3" %}
{% endif %}

### Positioning the ticks

The minor and major ticks can be positioned by using [`offset`](../api/linear-gauge/tickModel/#offset) and [`position`](../api/linear-gauge/tickModel/#position) properties. The [`offset`](../api/linear-gauge/tickModel/#offset) is used to render the ticks with the specified distance from the axis. By default, the offset value is **0**. The possible values of the [`position`](../api/linear-gauge/tickModel/#position) property are **Inside**, **Outside**, **Cross**, and **Auto**. By default, the ticks will be placed inside the axis.

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs4/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs4/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs4" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs4/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs4/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs4" %}
{% endif %}

## Labels Customization

The style of the labels can be customized using the following properties in the [`font`](../api/linear-gauge/labelModel/#font) property in [`labelStyle`](../api/linear-gauge/labelModel).

* [`color`](../api/linear-gauge/font/#color) - To set the color of the axis label.
* [`fontFamily`](../api/linear-gauge/fontModel/#fontfamily) - To set the font family of the axis label.
* [`fontStyle`](../api/linear-gauge/fontModel/#fontstyle) - To set the font style of the axis label.
* [`fontWeight`](../api/linear-gauge/fontModel/#fontweight) - To set the font weight of the axis label.
* [`opacity`](../api/linear-gauge/fontModel/#opacity) - To set the opacity of the axis label.
* [`size`](../api/linear-gauge/fontModel/#size) - To set the size of the axis label.

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs5/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs5/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs5" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs5/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs5/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs5" %}
{% endif %}

### Positioning the axis label

Labels can be positioned by using [`offset`](../api/linear-gauge/labelModel/#offset) and [`position`](../api/linear-gauge/labelModel/#position) properties in the [`labelStyle`](../api/linear-gauge/labelModel). The [`offset`](../api/linear-gauge/labelModel/#offset) defines the distance between the labels and ticks. By default, the offset value is **0**. The possible values of the [`position`](../api/linear-gauge/labelModel/#position) property are **Inside**, **Outside**, **Cross**, and **Auto**. By default, labels will be placed inside the axis.

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs6/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs6/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs6" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs6/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs6/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs6" %}
{% endif %}

### Customizing the display of the last label

If the last label is not in the visible range, it will be hidden by default. The last label can be made visible by setting the [`showLastLabel`](../api/linear-gauge/axis/#showlastlabel) property as **true** in the [`axes`](../api/linear-gauge/axisModel/).

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs7/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs7/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs7" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs7/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs7/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs7" %}
{% endif %}


### Label Format

Axis labels in the Linear Gauge control can be formatted using the [`format`](../api/linear-gauge/labelModel/#format) property in the [`labelStyle`](../api/linear-gauge/axis/#labelstyle). It is used to render the axis labels in a certain format or to add a user-defined unit in the label. It works with the help of placeholder like **{value}°C**, where **value** represents the axis value. For example, 20°C.

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs8/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs8/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs8" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs8/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs8/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs8" %}
{% endif %}

### Displaying numeric format in labels

The numeric formats such as currency, percentage, and so on can be displayed in the labels of the Linear Gauge using the [`format`](../api/linear-gauge/linearGaugeModel/#format) property in the Linear Gauge component. The following table describes the result of applying some commonly used label formats on numeric values.

<table>
<tr>
<td><b>Label Value</b></td>
<td><b>Label Format property value</b></td>
<td><b>Result </b></td>
<td><b>Description </b></td>
</tr>
<tr>
<td>1000</td>
<td>n1</td>
<td>1000.0</td>
<td>The number is rounded to 1 decimal place.</td>
</tr>
<tr>
<td>1000</td>
<td>n2</td>
<td>1000.00</td>
<td>The number is rounded to 2 decimal place.</td>
</tr>
<tr>
<td>1000</td>
<td>n3</td>
<td>1000.000</td>
<td>The Number is rounded to 3 decimal place.</td>
</tr>
<tr>
<td>0.01</td>
<td>p1</td>
<td>1.0%</td>
<td>The number is converted to percentage with 1 decimal place.</td>
</tr>
<tr>
<td>0.01</td>
<td>p2</td>
<td>1.00%</td>
<td>The Number is converted to percentage with 2 decimal place.</td>
</tr>
<tr>
<td>0.01</td>
<td>p3</td>
<td>1.000%</td>
<td>The number is converted to percentage with 3 decimal place.</td>
</tr>
<tr>
<td>1000</td>
<td>c1</td>
<td>$1,000.0</td>
<td>The currency symbol is appended to number and number is rounded to 1 decimal place.</td>
</tr>
<tr>
<td>1000</td>
<td>c2</td>
<td>$1,000.00</td>
<td>The currency symbol is appended to number and number is rounded to 2 decimal place.</td>
</tr>
</table>

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs9/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs9/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs9" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs9/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs9/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs9" %}
{% endif %}

## Orientation

By default, the Linear Gauge is rendered vertically. To change its orientation, the [`orientation`](../api/linear-gauge/linearGaugeModel/#orientation) property must be set to **Horizontal**.

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs10/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs10/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs10" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs10/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs10/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs10" %}
{% endif %}

## Inverted Axis

The axis of the Linear Gauge component can be inversed by setting the [`isInversed`](../api/linear-gauge/axis/#isinversed) property to **true** in the [`axes`](../api/linear-gauge/axisModel/).

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs11/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs11/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs11" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs11/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs11/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs11" %}
{% endif %}

## Opposed Axis

To place an axis opposite from its original position, [`opposedPosition`](../api/linear-gauge/axis/#opposedposition) property in the [`axes`](../api/linear-gauge/axisModel/) must be set as **true**.

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs12/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs12/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs12" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs12/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs12/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs12" %}
{% endif %}

## Multiple Axes

Multiple axes can be added to the Linear Gauge by adding multiple [`axis`](../api/linear-gauge/axisModel/) object in the [`axes`](../api/linear-gauge/linearGaugeModel/#axes) and customization can be done with the [`axis`](../api/linear-gauge/axisModel/). Each axis can be customized separately as shown in the following example.

{% if page.publishingplatform == "typescript" %}

 {% tabs %}
{% highlight ts tabtitle="index.ts" %}
{% include code-snippet/linear-gauge/axis-cs13/index.ts %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs13/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs13" %}

{% elsif page.publishingplatform == "javascript" %}

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/axis-cs13/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/axis-cs13/index.html %}
{% endhighlight %}
{% endtabs %}

{% previewsample "page.domainurl/code-snippet/linear-gauge/axis-cs13" %}
{% endif %}