---
title: "Export Excel Charts"
second_title: "Aspose.Cells Cloud Document"
type: docs
url: /export/excel-chart-to-different-formats/
keywords: "REST API, convert, export，spreadsheets, excel,chart"
description: "Cells.Cloud API for Excel operate: export excel charts to different format file."
weight: 20
---


You can export formats:  [PNG](https://docs.fileformat.com/Image/png/), [GIF]](https://docs.fileformat.com/image/gif/), [JPEG](https://docs.fileformat.com/image/jpeg/),  [BMP](https://docs.fileformat.com/image/bmp/), [SVG](https://docs.fileformat.com/page-description-language/svg/), [TIFF](https://docs.fileformat.com/image/tiff/), [EMF](https://docs.fileformat.com/image/emf/), [WMF](https://docs.fileformat.com/image/Wmf/).

## REST API

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/cells/export|PUT|Export excel objects from request content to some format|[PostExport](https://apireference.aspose.cloud/cells/#/Export/PostExport)|


The [OpenAPI Specification](https://apireference.aspose.cloud/cells/#/Export/PostExport) defines a publicly accessible programming interface and lets you carry out REST interactions directly from a web browser. 

You can use **cURL** command-line tool to access Aspose.Cells web services easily. The following example shows how to make calls to Cloud API with cURL.


{{< tabs tabTotal="1" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```bash

curl -X PUT "https://api.aspose.cloud/v3.0/cells/export?objectType=chart&format=tiff" -H "accept: multipart/form-data" -H "Content-Type: multipart/form-data" -H "x-aspose-client: Containerize.Swagger" -d {"File":{}}
```

{{< /tab >}}
{{< tab tabNum="2" >}}
```bash
{
    "Files": [{
        "Filename": "Book1_xlsx_Sheet4_Charts_0.tif",
        "FileSize": 10040,
        "FileContent": "-----Base64String--------"
    }, {
        "Filename": "Book1_xlsx_Sheet4_Charts_1.tif",
        "FileSize": 12978,
        "FileContent": "-----Base64String--------"
    }, {
        "Filename": "Book1_xlsx_Sheet4_Charts_2.tif",
        "FileSize": 7002,
        "FileContent": "-----Base64String--------"
    }, {
        "Filename": "Book1_xlsx_Sheet4_Charts_3.tif",
        "FileSize": 11532,
        "FileContent": "-----Base64String--------"
    }, {
        "Filename": "Book1_xlsx_Sheet6_Charts_0.tif",
        "FileSize": 8270,
        "FileContent": "-----Base64String--------"
    }, {
        "Filename": "myDocument_xlsx_Sheet3_Charts_0.tif",
        "FileSize": 42570,
        "FileContent": "-----Base64String--------"
    }, {
        "Filename": "myDocument_xlsx_Sheet3_Charts_1.tif",
        "FileSize": 12102,
        "FileContent": "-----Base64String--------"
    }, {
        "Filename": "myDocument_xlsx_Sheet3_Charts_2.tif",
        "FileSize": 8290,
        "FileContent": "-----Base64String--------"
    }]
}
```
{{< /tab >}}
{{< /tabs >}}

## Cloud SDK Family

Using an SDK is the best way to speed up the development. An SDK takes care of low-level details and lets you focus on your project tasks. Please check out the [GitHub repository](https://github.com/aspose-cells-cloud) for a complete list of Aspose.Cells Cloud SDKs.
