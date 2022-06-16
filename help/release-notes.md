---
title: Versionsinformation
description: Versionsinformation och kända problem med [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 7c6293bb99d5be8084e6998da966bb89be9c714e
workflow-type: tm+mt
source-wordcount: '885'
ht-degree: 0%

---

# Versionsinformation om [!DNL Assets Essentials] {#release-notes}

Den aktuella versionen av [!DNL Assets Essentials] släpps den 16 juni 2022.

Den här versionen innehåller:

**Förbättringar av resursstatus**

* Assets Essentials ger dig nu möjlighet att [ange ett förfallodatum för en tillgång](manage-organize.md#set-asset-status). Dessutom kan du [filterresurser](search.md#refine-search-results) baserat på `Expired` tillgångsstatus och ett förfallodatumintervall.

* Nu kan du visa statusindikatorn för alla resurser som är tillgängliga i Papperskorgen. Därför kan du välja att återställa en resurs baserat på dess status.

**Förbättrade sökfilter**

* Assets Essentials ger dig nu möjlighet att [filterresurser](search.md#refine-search-results) med `No Status` tillgångsstatus.

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**Förbättrade samlingar**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials har nu stöd för [hämta en samling](manage-collections.md).

* Nu kan du redigera metadatafältet Beskrivning för en samling.

**Förbättrad dokumentation**

* En ny version av [Översiktsdokumentation för Assets Essentials](introduction.md) är nu tillgängligt.

**Förbättringar baserade på kundfeedback**

* Förbättringar och felkorrigeringar som bygger på kundfeedback.


## Kända fel {#known-issues}

Listan över kända fel i [!DNL Assets Essentials] Erbjudandet revideras och uppdateras fortlöpande:

* Assets Essentials stöder inte skapande av privata samlingar.

Om du stöter på några problem eller till och med förbättringsförfrågningar [ge feedback](#provide-feedback) till teamet.

## Tidigare versioner {#past-release}

### 2022.4.0 {#april-2022}

Den aktuella versionen av [!DNL Assets Essentials] släpps den 12 maj 2022. Den här versionen innehåller:

* [!DNL Assets Essentials] nu har stöd för [skapa samlingar](manage-collections.md). En samling är en uppsättning resurser i Experience Manager Assets Essentials. Använd samlingar för att dela resurser mellan användare. Till skillnad från mappar kan en samling innehålla resurser från olika platser.

* Nu kan Assets Essentials även [lägga till egna filter](search.md#custom-filters) till användargränssnittet. Du kan sedan använda dessa anpassade filter utöver standardfiltren för att förfina sökresultaten.

* Nu kan du [ange status](manage-organize.md#set-asset-status) på resurser som är tillgängliga i databasen. Ange en resursstatus som bättre styr och hanterar nedströmsanvändningen av digitala resurser.

* Förbättringar och felkorrigeringar som bygger på kundfeedback.

#### Inkognitoläge i Chrome {#incognito-mode}

I den här versionen optimerar vi prestanda för gränssnittsleverans och specifika funktioner i Assets Essentials - som kommenterar resurser och bildredigering - beroende på att webblagring och tredjepartskcookies är aktiverade. Inkognitoläget i webbläsaren Chrome blockerar cookies från tredje part som standard - användarna har ett antal alternativ för att fortsätta få tillgång till alla funktioner:

* Använd Chrome-profiler i stället för Incognito-läge när användaren behöver separata webbläsarsessioner

* Stäng av `Block third-party cookies` på skärmen Inkognito-läge i Chrome

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] släpps den 9 mars 2022 med följande uppdateringar:

* [!DNL Assets Essentials] nu kan du [skapa en länk och dela resurser med externa intressenter](share-links-for-assets.md), som inte har tillgång till [!DNL Assets Essentials] program. Du kan definiera ett förfallodatum för länken och sedan dela det med andra via den kommunikationsmetod du föredrar, som e-post eller meddelandetjänster. Mottagarna av länken kan förhandsgranska resurser och hämta dem.

* The [!DNL Assets Essentials] nu omfattar [en administratörsproduktprofil](deploy-administer.md#add-users-to-essentials) på Admin Console utöver de befintliga vanliga produktprofilerna och konsumentproduktprofilerna. En administratör kan nu tilldela andra användare till administratörens produktprofil.

* Assets Essentials tillåter nu administratörer att [hantera åtkomstnivåer för mappar som är tillgängliga i databasen](manage-permissions.md). Som administratör kan du skapa användargrupper och tilldela behörigheter till dessa grupper för att hantera åtkomstnivåer. Du kan även delegera behörighetshanteringsprivilegier till användargrupper på mappnivå.

* Förbättringar och felkorrigeringar som bygger på kundfeedback.

Dessutom [!DNL Adobe Asset Link] för Creative Cloud (Photoshop, Illustrator och InDesign) lanserade [ny version 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html), med prestandaförbättringar för panelens starttid och hämtningshastighet.


### 2022.1.0-utgåvan {#january-2022}

[!DNL Assets Essentials] släpps den 3 februari 2022 med följande uppdateringar:

* Prestandaförbättringar för [!UICONTROL Create Folder] operation. <!-- CQ-4338818 -->

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
