﻿---
title: 使用 CellsObjectOperate Tas
second_title: Aspose.Cells Cloud Documen
type: docs
url: /zh/tasks/cells-object-operate/
aliases: [/working-with-cellsobjectoperate-task/]
description: Cells.Cloud API for Excel操作：单元格对象操作任务
weight: 20
---
此 REST API 操作单元格对象 `task`。

**操作对象**

|参数名称|类型|描述|
|:- |:- |:- |
|操作对象类型|细绳|工作簿/工作表/PageSetup/Cells/图表/形状/ListObject/数据透视表/WorkbookSettings/PageBreak|
|操作对象位置|目的||

**操作对象位置**

|参数名称|类型|描述|
|:- |:- |:- |
|工作簿|目的||
|工作表名称|细绳||
|图表索引|整数||
|形状索引|整数||
|小区名称|细绳||
|列表对象索引|整数||


**图表操作参数**

|参数名称|类型|描述|
|:- |:- |:- |
|图表索引|整数||
|图表类型|细绳||
|左上行|整数||
|左上栏|整数||
|右下行|整数||
|右下栏|整数||
|区域|细绳||
|是垂直的|细绳|真假|
|类别数据|细绳||
|IsAutoGetSerialName|细绳|真假|
|区域|标题||

**列表对象操作参数** 

|参数名称|类型|描述|
|:- |:- |:- |
|列表对象|目的||

**分页操作参数**

|参数名称|类型|描述|
|:- |:- |:- |
|分页类型|细绳||
|指数|指数||
|排|整数||
|柱子|整数||
|起始索引|整数||
|结束索引|整数||


**页面设置操作参数**

|参数名称|类型|描述|
|:- |:- |:- |
|页面设置|目的||


**数据透视表操作参数**

|参数名称|类型|描述|
|:- |:- |:- |
|目的地小区名称|细绳||
|源数据|细绳||
|表名|细绳||
|使用相同的来源|细绳|真假|
|数据透视表索引|整数||
|数据透视字段行|整数[]||
|数据透视字段列|整数[]||
|数据透视表|整数[]||


**形状操作参数**


|参数名称|类型|描述|
|:- |:- |:- |
|形状|目的||


**工作簿设置操作参数**


|参数名称|类型|描述|
|:- |:- |:- |
|工作簿设置|目的||

**工作表操作参数**


|参数名称|类型|描述|
|:- |:- |:- |
|姓名|细绳||
|图纸类型|细绳||
|新名字|细绳||
|搬家要求|目的||

## 休息 API

|**API**|**类型**|**描述**|**资源链接**|
|:- |:- |:- |:- |
|/细胞/任务/运行任务|邮政|运行任务|[后运行任务](https://apireference.aspose.cloud/cells/#/Task/PostRunTask)|

这[OpenAPI 规范](https://apireference.aspose.cloud/cells/#/Workbook/PostImportData)定义了一个可公开访问的编程接口，并允许您直接从 Web 浏览器执行 REST 交互。

