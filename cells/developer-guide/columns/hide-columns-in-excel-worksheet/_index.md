---
title: "Hide Columns in an Excel Worksheet"
second_title: "Aspose.Cells Cloud Document"
type: docs
url: /columns/hide/
aliases: [/hide-columns-in-excel-worksheet/,/hide-columns-in-an-excel-worksheet/]
keywords: "REST API, hide columns, spreadsheets, excel"
description: "Cells.Cloud API for Excel operate: hide columns from an Excel Worksheet."
weight: 40
---

This REST API hide `columns`  in an Excel Worksheet.


**Query Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
|startColumn|integer | |
|totalColumns|integer | |
|folder|string|Original workbook folder.|
|storageName|string|Storage name.|

## REST API 

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|` `/cells/{name}/worksheets/{sheetName}/cells/columns/hide|` `POST|` `Hide a column in a Excel Worksheet|` `[PostHideWorksheetColumns](https://apireference.aspose.cloud/cells/#/Cells/PostHideWorksheetColumns)|


The [OpenAPI Specification](https://apireference.aspose.cloud/cells/#/Cells/PostHideWorksheetColumns) defines a publicly accessible programming interface and lets you carry out REST interactions directly from a web browser.

You can use **cURL** command-line tool to access Aspose.Cells web services easily. The following example shows how to make calls to Cloud API with cURL.


{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```bash

 curl -X POST "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/cells/columns/hide?startColumn=1&totalColumns=1" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```bash

 {

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}

## Cloud SDK Family

Using an SDK is the best way to speed up the development. An SDK takes care of low-level details and lets you focus on your project tasks. Please check out the [GitHub repository](https://github.com/aspose-cells-cloud) for a complete list of Aspose.Cells Cloud SDKs.

The following code examples demonstrate how to make calls to Aspose.Cells web services using various SDKs:


{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Swift" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNET-CSharp-Columns-HideColumnsInWorksheet-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-Columns-HideColumnsInWorksheet-hide-Columns-in-excel-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "5c1a68c4cea73845b221ff0d3b9ec9df" "Examples-PHP-Columns-PostHideWorksheetColumns-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "3c5c9f9fff9898bb8251aa7ee9191641" "Examples-Ruby-Columns-hide_worksheet_Columns-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "5161752550311c9baf73ffa0a811ea0b" "HideColumnsInExcelWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "04e9dd952c704f334a4eceb3925d479e" "Examples-Node.js-SDK-Columns-HideColumnsInWorksheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-Columns-HideColumnsInWorksheet-hide-Columns-in-excel-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-Columns-HideColumnsInWorksheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "7cef96bfea49039ccfe0deb8beb4d22e" >}}

{{< /tab >}}

{{< /tabs >}}
