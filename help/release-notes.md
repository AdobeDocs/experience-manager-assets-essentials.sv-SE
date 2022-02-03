---
title: Versionsinformation
description: Versionsinformation och kända problem med [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: a72c3399fabd37c561f3c51e51029810d038ae40
workflow-type: tm+mt
source-wordcount: '420'
ht-degree: 0%

---

# Versionsinformation om [!DNL Assets Essentials] {#release-notes}

Den aktuella versionen av [!DNL Assets Essentials] släpps den 3 februari 2022. I den här versionen:

* [!DNL Assets Essentials] gör att du nu kan skapa en länk och dela resurser med andra som inte har tillgång till [!DNL Assets Essentials] program. Du kan definiera: <!-- CQ-4329575 -->

   * Ett förfallodatum för länken

   * Om mottagarna får ladda ned resursen efter att ha öppnat länken.

   Baserat på de här inställningarna kan mottagaren av länken välja att förhandsgranska resurserna eller hämta dem.

* Prestandaförbättringar för [!UICONTROL Create Folder] operation. <!-- CQ-4338818 -->

## Kända fel {#known-issues}

Listan över kända fel i [!DNL Assets Essentials] Erbjudandet revideras och uppdateras fortlöpande:

* Inget

Om du stöter på några problem eller till och med förbättringsförfrågningar [ge feedback](#provide-feedback) till teamet.

## Tidigare versioner {#past-release}

### 2021.11.0-utgåvan {#november-2021}

[!DNL Assets Essentials] släpps den 16 december 2021, med följande uppdateringar:

* Adobe distribuerar Assets Essentials automatiskt när provisioneringsprocessen är slutförd. Administratörerna behöver inte utföra ytterligare steg för att distribuera Assets Essentials med [!DNL Cloud Manager] användargränssnitt. Den här automatiska distributionen kommer att vara tillgänglig för miljöer som etablerats efter den 6 januari 2022.
* Nya versioner av Creative Cloud-plugin-program som fungerar med Assets Essentials finns på Adobe Exchange - [Adobe Asset Link for Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) och [Adobe Asset Link for Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Olika felkorrigeringar och produktförbättringar, inklusive tidigare kända fel (mapparna visas nu korrekt i det vänstra navigeringsträdet efter överföringen<!-- CQ-4337638 -->kan användaren välja antingen aktuell mapp eller en undermapp när den släpps för överföring genom att dra och släppa<!-- CQ-4327753 -->).

### 2021.8.0-utgåvan {#august2021}

[!DNL Assets Essentials] 2021.8.0 släpps den 30 augusti 2021, med följande uppdateringar:

* Integrering med [!DNL Adobe Workfront] som [!DNL Workfront] användarna hanterar sina digitala resurser när de hanterar arbetet. Mer information finns i [integrering med andra Adobe-lösningar](/help/integration.md).

### 2021.7.0-utgåvan {#july2021}

[!DNL Assets Essentials] 2021.7.0 släpps den 29 juli 2021, med följande uppdateringar:

* Du kan skapa och hantera anpassade metadataformulär som ska användas för att visa metadataegenskaper för användare på resursinformationsskärmen i [!UICONTROL Metadata Forms] option under [!DNL Settings]. Se [metadataformulär](metadata.md#metadata-forms).
* Olika felkorrigeringar och produktförbättringar, inklusive bättre prestanda vid överföring av en kapslad mapp med många undermappar.

### 2021.6.0-utgåvan {#june2021}

Den första versionen av [!DNL Assets Essentials], som släpptes den 21 juni 2021, erbjuder lättviktiga funktioner för resurshantering. Det har stöd för följande huvudfunktioner och CRUD-åtgärder (skapa, läsa, uppdatera och ta bort):

* Överför och lägg till resurser, inklusive kapslade mappar. Förhandsgranska resurserna och versionerna.
* Fulltextsökning, nyansrika sökfilter och sparade sökningar för snabb resursidentifiering.
* Grundläggande resurshanteringsåtgärder som att uppdatera, ta bort, hämta och hantera metadata.
* [!DNL Assets Essentials] är tillgänglig för [!DNL Adobe Journey Optimizer] -användare för att hantera resurser när de skapar meddelanden. Mer information finns i [integrering med andra Adobe-lösningar](/help/integration.md).
