---
title: "Update Cell Style for Pivot Table"
type: docs
url: /update-cell-style-for-pivot-table/
weight: 70
---

## **Introduction**
This example shows how to update cell style for Pivot Table using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, Objective C, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/pivottables/{pivotTableIndex}/Format|POST|Updates cell style in pivot table|[PostPivotTableCellStyle](https://apireference.aspose.cloud/cells/#/PivotTables/PostPivotTableCellStyle)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.com/v3.0/cells/Sample\_Pivot\_Table\_Example.xls/worksheets/Sheet2/pivottables/0/Format?column=1&row=1&appSID=xxxx&signature=xxxx" \

     -X POST \

     -d '{"Font":{"Name":"Arial", "Size":10}}' \

     -H "Content-Type: application/json" \

     -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="1" tabID="4" tabName1="Go" >}}

{{< tab tabNum="1" >}}

{{< /tab >}}

{{< /tabs >}}




