---
title: "Import Batch Data into Excel Worksheet"
type: docs
url: /import-batch-data-into-worksheet/
aliases: [/import-batch-data-into-excel-worksheet/]
description: "Cells.Cloud API for Excel operate: Import Batch Data into Excel Worksheet."
weight: 10
---


This REST API import batch data into Excel work sheet.

The request is an HTTP request with multipart content (see [RFC 2046](http://tools.ietf.org/html/rfc2046#page-17) or [RFC 1341](http://www.w3.org/Protocols/rfc1341/7_2_Multipart.html)). The first part of the multipart content contains the ImportBatchDataOption data and the second contains a data file.

The important parameters are described in the following table:

**Query Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
|folder|string|Original workbook folder.|
|storageName|string|Storage name.|

**Request Body Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
|ImportBatchDataOption|Object | import batch data option.The first part of the multipart content.|
|datafile|data file |If the file source type of data file is the request body, The data file save into the second part of the multipart content.|



**ImportBatchDataOption**

| Parameter Name|Type|Description|
| :- | :- | :- |
| BatchData | List<CellValue> | batch data | 
| DestinationWorksheet | string | destination work sheet name. |
| IsInsert | string | true/false. |
| ImportDataType | string | IntArray/DoubleArray/StringArray/TwoDimensionIntArray/TwoDimensionDoubleArray/TwoDimensionStringArray/BatchData/CSVData.|
| Source | FileSource | Indicates data file position when the BatchData parameter is null. |
| DestinationWorksheet | string | destination work sheet name. |


**CellValue**

| Parameter Name|Type|Description|
| :- | :- | :- |
| rowIndex | int |  | 
| columnIndex | int |  | 
| type | string | data type |
| value | string |  |
| style | Style(object) |  |



**FileSource**
| Parameter Name|Type|Description|
| :- | :- | :- |
| FileSourceType | string | InMemoryFiles/CloudFileSystem/RequestFiles | 
| FilePath | string | file position |





## REST API


|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/importdata|POST|Imports data into workbook|[PostImportData](https://apireference.aspose.cloud/cells/#/Workbook/PostImportData)|

The [OpenAPI Specification](https://apireference.aspose.cloud/cells/#/Workbook/PostImportData) defines a publicly accessible programming interface and lets you carry out REST interactions directly from a web browser. 

You can use **cURL** command-line tool to access Aspose.Cells web services easily. The following example shows how to make calls to Cloud API with cURL.

{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```bash
# cURL example to import batch data into excel work book
curl -X POST "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/importdata" -d '{"BatchData":null, "DestinationWorksheet":"Sheet1", "IsInsert":false, "ImportDataType":"BatchData", "Source":{"FileSourceType":1, "FilePath":"Batch_data_json.txt"}}' -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"Code":200,"Status":"OK"}

```

{{< /tab >}}

{{< /tabs >}}

## Cloud SDK Family

Using an SDK is the best way to speed up the development. An SDK takes care of low-level details and lets you focus on your project tasks. Please check out the [GitHub repository](https://github.com/aspose-cells-cloud) for a complete list of Aspose.Cells Cloud SDKs.

The following code examples demonstrate how to make calls to Aspose.Cells web services using various SDKs:


{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNet-CSharp-ImportData-PostImportDataCloudFile-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "5c1a68c4cea73845b221ff0d3b9ec9df" "Examples-PHP-Workbook-PostImportDataCloudFile-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Workbook-post_import_data-.rb" >}}

{{< /tab >}}

{{< /tabs >}}
