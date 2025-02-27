﻿---
title: Fil kopieren
second_title: Aspose.Cells Cloud Documen
type: docs
url: /de/file/copy/
keywords: Learn how to copy file with Aspose Cells Cloud REST API
description: Erfahren Sie, wie Sie Dateien mit Aspose Cells Cloud REST API SDK-Unterstützungsarten von Entwicklungssprachen kopieren. Dazu gehören Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby und Swift
weight: 100
---
Dieser REST API zeigt `copy file` an.
 
## RSET API
 
```bash
 
PUT http://api.aspose.cloud/v3.0/cells/storage/file/copy/{srcPath}
 
```
 Die Anforderungsparameter sind:
 
| Parametername| Typ| Pfad/Abfragezeichenfolge/HTTPBody|Beschreibung|
|:- |:- |:- |:- |
| Quellenpfad| Schnur| Weg| Quelldateipfad zB '/folder/file.ext'|
| ZielPfad| Schnur| Anfrage| Zieldateipfad|
| srcStorageName| Schnur| Anfrage| Quellspeichername|
| destStorageName| Schnur| Anfrage| Name des Zielspeichers|
| versionId| Schnur| Anfrage|Zu kopierende Dateiversions-ID|
 
 Der[OpenAPI-Spezifikation](https://apireference.aspose.cloud/cells/#/File/CopyFile) definiert eine öffentlich zugängliche Programmierschnittstelle und lässt Sie REST-Interaktionen direkt von einem Webbrowser ausführen.
 
Sie können das cURL-Befehlszeilentool verwenden, um einfach auf Aspose.Cells-Webdienste zuzugreifen. Das folgende Beispiel zeigt, wie Sie Cloud API mit cURL anrufen.
 
{{< tabs tabTotal="2" tabID="11" tabName11="Request" tabName21="Response" >}}
 
{{< tab tabNum="11" >}}
 
```bash
 
curl -v "http://api.aspose.cloud/v3.0/cells/storage/file/copy/Book1.xlsx?destPath=Book2.xlsx" \
-X PUT \
-H "Content-Type: application/json" \
-H "Accept: application/json" \
-H "Authorization: Bearer <jwt token>"
 
```
 
{{< /tab >}}
 
{{< tab tabNum="12" >}}
 
```bash
{
"Code": 200,
"Status": "OK"
}
 
```
 
{{< /tab >}}
 
{{< /tabs >}}
 
## Cloud SDK-Familie
 
 Die Verwendung eines SDK ist der beste Weg, um die Entwicklung zu beschleunigen. Ein SDK kümmert sich um Details auf niedriger Ebene und lässt Sie sich auf Ihre Projektaufgaben konzentrieren. Bitte überprüfen Sie die[GitHub-Repository](https://github.com/aspose-cells-cloud) für eine vollständige Liste der Aspose.Cells Cloud SDKs.
 
Die folgenden Codebeispiele zeigen, wie Sie mit verschiedenen SDKs Aufrufe an Aspose.Cells-Webdienste tätigen:
 
 