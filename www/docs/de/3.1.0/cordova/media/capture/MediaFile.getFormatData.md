---
license: >
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

title: MediaFile.getFormatData
---

# MediaFile.getFormatData

> Ruft formatieren Informationen über die Medien-Capture-Datei.

    mediaFile.getFormatData(
        MediaFileDataSuccessCB successCallback,
        [MediaFileDataErrorCB errorCallback]
    );
    

## Beschreibung

Diese Funktion versucht asynchron, die Formatierungsinformationen für die Mediendatei abzurufen. Wenn erfolgreich, es ruft die `MediaFileDataSuccessCB` Rückruf mit einem `[MediaFileData](MediaFileData.html)` Objekt. Wenn der Versuch fehlschlägt, ruft diese Funktion die `MediaFileDataErrorCB` Rückruf.

## Unterstützte Plattformen

*   Android
*   BlackBerry WebWorks (OS 5.0 und höher)
*   iOS
*   Windows Phone 7 und 8
*   Windows 8

## BlackBerry WebWorks Macken

Bietet eine API keine Informationen zum Media-Dateien, so dass alle `[MediaFileData](MediaFileData.html)` Objekte zurückgeben, mit Standardwerten.

## Android Macken

Die API zum Zugriff [Medien](../media.html) Dateiformat-Information ist begrenzt, so dass nicht alle `[MediaFileData](MediaFileData.html)` Eigenschaften werden unterstützt.

## iOS Macken

Die API zum Zugriff [Medien](../media.html) Dateiformat-Information ist begrenzt, so dass nicht alle `[MediaFileData](MediaFileData.html)` Eigenschaften werden unterstützt.