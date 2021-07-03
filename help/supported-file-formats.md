---
title: Filformat som stöds
description: Filformat som stöds för de olika användningsområdena för [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: a1dc66213f602bce5b5a2ec0ba99084c7f7b1ee1
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 9%

---


# Filformat stöds i [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] har stöd för ett stort antal filformat och alla funktioner har olika stöd för olika filtyper.

* ![bildfilstyp ](assets/do-not-localize/image-icon.png) ikonBilder: GIF, JPG, PNG och TIFF
* ![dokumentfiltypsikon](assets/do-not-localize/document-icon.png) Dokument: DOCX, PDF, PPTX och XLSX
* ![video file type ](assets/do-not-localize/video-icon.png) iconVideor: MP4

De olika filtyperna har olika stöd för de användningsområden och funktioner som beskrivs nedan. Använd teckenförklaringen för att förstå supportnivån.

| Supportnivå | Beskrivning |
|---------------|-------------------------|
| ✓ | Stöds |
| * | Stöds villkorligt |
| - | Ej relevant |

* Andra tillgångshanteringsåtgärder:

## Lägga till, överföra och visa resurser {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Tillgångstyp | Bläddra | Kopiera | Överför | Skapa | Ta bort | Information | Zooma bilden | Senast visade |
|---------------|----------|------|----------|----------|----------|----------|------------|-----------------|
| Rasterbilder | ✓ |  | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Mappar | ✓ |  | ✓ | ✓ | ✓ | ✓ | - | - |
| Videor | ✓ |  | ✓ | - | ✓ | * | - | ✓ |
| CC Libraries | ✓ |  | ✓ | ✓ | ✓ | ✓ | - | - |
| PDF | ✓ |  | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD | ✓ |  | ✓ | - | ✓ | * | - | ✓ |
| AI | ✓ |  | ✓ | - | ✓ | * | - | ✓ |
| INDD | ✓ |  | ✓ | - | ✓ | * | - | ✓ |

## Söka efter, använda och redigera resurser {#support-to-search-use-edit}

| Tillgångstyp | Hämta | Dra och släpp | Bildredigerare | Sökning | Smarta taggar | Byt namn på | Versioner |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Rasterbilder | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Mappar | ✓ | ✓ | - | ✓ | - | ✓ | - |
| Videor | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| CC Libraries | - | - | - | - | - | ✓ | - |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| PSD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| AI | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |

## Granska resurser och samarbeta {#support-to-review-collaborate}

| Tillgångstyp | Anteckna | Kommentar | Skapa uppgifter och granska |
|---------------|----------|----------|-------------------------|
| Rasterbilder | ✓ | ✓ | ✓ |
| Mappar | - | - | - |
| Videor | - | ✓ | ✓ |
| CC Libraries | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD | - | ✓ | ✓ |
| AI | - | ✓ | ✓ |
| INDD | - | ✓ | ✓ |

## Andra resurshanteringsåtgärder {#support-to-manage-assets}

| Tillgångstyp | Metadata | Återgivningar | Papperskorgen | Kopiera | Flytta | [!DNL Adobe Asset Link] incheckning |
|---------------|----------|------------|----------|----------|----------|----------------------------------|
| Rasterbilder | * | ✓ | ✓ | ✓ | ✓ | ✓ |
| Mappar | * | - | ✓ | ✓ | ✓ | - |
| Videor | * | - | ✓ | ✓ | ✓ | - |
| CC Libraries | * | - | - | - | - | - |
| PDF | * | - | ✓ | ✓ | ✓ | - |
| PSD | * | - | ✓ | ✓ | ✓ | - |
| AI | * | - | ✓ | ✓ | ✓ | - |
| INDD | * | - | ✓ | ✓ | ✓ | - |

<!-- TBD: Saving template table separately.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->
