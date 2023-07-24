---
layout: post
title: Linear gauge print and export in ##Platform_Name## Linear gauge control | Syncfusion
description: Learn here all about Linear gauge print and export in Syncfusion ##Platform_Name## Linear gauge control of Syncfusion Essential JS 2 and more.
platform: ej2-javascript
control: Linear gauge print and export 
publishingplatform: ##Platform_Name##
documentation: ug
domainurl: ##DomainURL##
---

# Linear gauge print and export in ##Platform_Name## Linear gauge control

## Print

The rendered [JavaScript Linear Gauge](https://www.syncfusion.com/javascript-ui-controls/js-linear-gauge) can be printed directly from the browser by calling the [`print`](../api/linear-gauge/#print) method. To use the print functionality, set the [`allowPrint`](../api/linear-gauge/#allowprint) property as **true**.

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/lineargauge-print-cs2/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/lineargauge-print-cs2/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/lineargauge-print-cs2" %}

## Export

### Image Export

To use the image export functionality, set the [`allowImageExport`](../api/linear-gauge/#allowimageexport) property as **true**. The rendered linear gauge can be exported as an image using the [`export`](../api/linear-gauge/#export) method. This method requires two parameters: export type and file name. The Linear Gauge can be exported as an image with the following formats.

* JPEG
* PNG
* SVG

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/lineargauge-export-cs1/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/lineargauge-export-cs1/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/lineargauge-export-cs1" %}

### PDF Export

To use the PDF export functionality, set the [`allowPdfExport`](../api/linear-gauge/#allowpdfexport) property as **true**. The rendered Linear Gauge can be exported as PDF using the [`export`](../api/linear-gauge/#export) method. The [`export`](../api/linear-gauge/#export) method requires three parameters: file type, file name, and orientation of the PDF document. The orientation of the PDF document can be set as **Portrait** or **Landscape**.

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/lineargauge-export-cs2/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/lineargauge-export-cs2/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/lineargauge-export-cs2" %}

### Exporting Linear Gauge as base64 string of the file

The Linear Gauge can be exported as base64 string for the JPEG, PNG and PDF formats. The rendered Linear Gauge can be exported as base64 string of the exported image or PDF document used in the [`export`](../api/linear-gauge/#export) method. The arguments that are required for this method is export type, file name, orientation of the exported PDF document and **allowDownload** boolean value that is set as **false** to return base64 string. The value for the orientation of the exported PDF document is set as **null** for image export and **Portrait** or **Landscape** for the PDF document.

{% tabs %}
{% highlight js tabtitle="index.js" %}
{% include code-snippet/linear-gauge/lineargauge-export-cs3/index.js %}
{% endhighlight %}
{% highlight html tabtitle="index.html" %}
{% include code-snippet/linear-gauge/lineargauge-export-cs3/index.html %}
{% endhighlight %}
{% endtabs %}
        
{% previewsample "page.domainurl/code-snippet/linear-gauge/lineargauge-export-cs3" %}

>The exporting of the Linear Gauge as base64 string is not applicable for the SVG format.