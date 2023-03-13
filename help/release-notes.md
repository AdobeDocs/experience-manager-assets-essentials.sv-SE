---
title: Versionsinformation
description: Versionsinformation och kända problem med [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: f06e3a5db2c91e6778ea196fdc69293d1b2732e5
workflow-type: tm+mt
source-wordcount: '1690'
ht-degree: 0%

---

# Versionsinformation om [!DNL Assets Essentials] {#release-notes}

Den aktuella versionen av Assets Essentials släpps den 27 januari 2023.

Listan med funktioner i versionen innehåller:

**Min arbetsyta med konfigurerbara widgetar**

Resurserna har nu en anpassad arbetsyta som fungerar som en helhetslösning för att ge smidig åtkomst till viktiga delar av Assets-användargränssnittet och den information som är mest relevant för dig. Snabbare åtkomst till dessa alternativ ökar materialets hastighet och effektivitet.

Min arbetsyta innehåller widgetar för kommande nya funktioner, insikter, uppgifter och innehåll. Du kan konfigurera hur dessa widgetar visas på arbetsytan utifrån dina inställningar.

**Dedikerat gränssnitt för uppgiftshantering**

Med Assets Essentials kan du nu hantera listan över uppgifter som för närvarande är tilldelade dig, skapade av dig och redan har slutförts av dig på en central plats med hjälp av den nya **[!UICONTROL Tasks]** i det vänstra navigeringsfönstret. Du kan också vidta lämpliga åtgärder genom att välja en uppgift som ska godkännas eller avvisas, eller öppna uppgiftsinformationen för att godkänna, avvisa, redigera eller ta bort den.

![Uppgifter på arbetsytan](assets/tasks-workspace.png)

**Automatiskt genererade länkar för att dela resurser**

Assets Essentials genererar nu en länk automatiskt så snart du väljer att dela en resurs med Assets Essentials användargränssnitt. Den genererade länken fortsätter att gälla även om du ändrar förfallodatumet.

![Uppgifter på arbetsytan](assets/share-asset.png)


**Förbättringar baserade på kundfeedback**

Förbättringar och felkorrigeringar som bygger på kundfeedback.

## Kända fel {#known-issues}

Listan över kända fel i [!DNL Assets Essentials] Erbjudandet revideras och uppdateras fortlöpande:

<!--

* Assets Essentials does not support creating Private collections.

-->


* Privata samlingar är tillgängliga för den som skapat dem och för användare med administratörsbehörighet. Som administratör kan du inte delegera behörigheterna för åtkomst till samlingen till andra användare.

Om du stöter på några problem eller till och med förbättringsförfrågningar [ge feedback](#provide-feedback) till teamet.

## Tidigare versioner {#past-releases}

### 2022.11.0 {#november-2022}

Novemberversionen av [!DNL Assets Essentials] släpps den 17 november 2022.

Den här versionen innehåller:

**Förhandsgranska dokument med Document Cloud Viewer**

Med Assets Essentials kan du nu överföra dokument i andra format som stöds och förhandsgranska dem med det medföljande visningsprogrammet för Document Cloud. De formattyper som stöds är TXT, RTF, DOC, DOCX, PPT, PPTX, XLS och XLSX.

<!--

**View Smart Tags moderation reports**

Asset reporting now provides administrators with visibility into the Smart Tags promoted or deleted for an asset. You can specify a folder path and the report lists the Smart Tags promoted or deleted for all assets available at the folder path.

-->

<!--
**Read-only access to large number of users**

Assets Essentials allows administrators to provide read-only access to a large number of users for selected assets or folders in the repository. 
You can easily synchronize the user groups available on the external identity management of an organization with Adobe Admin Console and then manage permissions in Admin Console and Assets Essentials to provide the users with read-only access for selected assets or folders.

-->


**Alternativet Spara metadata**

Det nya alternativet Spara metadata finns nu i Assets Essentials användargränssnitt för bättre metadatastyrning.

**Förbättringar baserade på kundfeedback**

Förbättringar och felkorrigeringar som bygger på kundfeedback.

**Adobe Asset Link version 3.3**

[Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html) version 3.3 släpps den 13 december 2022, med följande funktioner:

* Stöd för [Creative Cloud for teams](https://www.adobe.com/creativecloud/business/teams.html) utöver att stödja [Creative Cloud för företag](https://www.adobe.com/creativecloud/business/enterprise.html) före.

* Stöd för de senaste Adobe InDesign-, Photoshop- och Illustrator 2023-programmen.

* Stöd för CEP-plugin för Adobe Asset Link i miljöer med proxyservrar.

### 2022.8.0 {#august-2022}

Augustiversionen av [!DNL Assets Essentials] släpps den 22 augusti 2022.

Den här versionen innehåller:

**Meddelanden för samlingar**

Med Assets Essentials-meddelanden kan du nu övervaka de åtgärder som utförs på de samlingar som finns i databasen. Du måste välja och prenumerera på de samlingar som meddelandena skickas till dig för. Du kan också konfigurera åtgärder som meddelanden skickas för, till exempel borttagning, delning av länk, flytt, namnbyte och uppdatering av samlingar.

**Redigera smarta samlingar**

Nu kan Assets Essentials även redigera sökvillkoren som används när en smart samling skapas.  Spara de nya sökvillkoren för att uppdatera samlingens innehåll dynamiskt.

**Visa Live-statistik för lagringskonto**

Med Assets Essentials kan du nu även visa kontodata i realtid för din Assets Essentials-miljö med kontrollpanelen Live Statistics. Du kan visa händelsemått i realtid de senaste 30 dagarna eller de senaste 12 månaderna.

**Visa överföringsrapporter**

Resursrapporteringen ger nu administratörer insyn i resurser som överförts till Adobe Experience Manager Assets Essentials-distributionen. Administratörer har redan möjlighet att skapa rapporter för de resurser som hämtas från Assets Essentials-distributionen. Dessa data ger användbar information om hur användarna interagerar med innehållet och produkten.

**Förbättringar baserade på kundfeedback**

Förbättringar och felkorrigeringar som bygger på kundfeedback.

### 2022.6.0 {#june-2022}

Juniversionen av [!DNL Assets Essentials] släpps den 14 juli 2022.

Den här versionen innehåller:

**Smarta samlingar**

Spara sökresultaten som en smart samling för att dynamiskt uppdatera samlingens innehåll. Om det finns resurser som har lagts till i Assets Essentials-databasen och som passar sökvillkoren som definieras under [skapa den smarta samlingen](manage-collections.md#create-smart-collection)uppdateras innehållet i den smarta samlingen automatiskt.

**Meddelanden**

Med Assets Essentials-meddelanden kan du [övervaka de åtgärder som utförs på de resurser eller mappar som är tillgängliga i databasen](manage-notifications.md). Du måste välja och prenumerera på det innehåll som meddelandena skickas till dig för. Du kan också konfigurera de kategorier som meddelanden skickas till dig för.

**Rapportering**

Med tillgångsrapportering kan administratörer utvärdera användaraktiviteten i Adobe Experience Manager Assets Essentials. Rapporterna och kontrollpanelen för live-statistik innehåller användbar information om hur användare interagerar med resurser som är tillgängliga i din distribution. [Använd informationen i rapporterna](manage-reports.md) för att ta fram nyckeltal för att mäta användningen av resurser inom företaget och av kunderna.

Visa tillgångshämtningsrapporter och instrumentpanelsmodulen för livstatistik för att se vilka resurser som hämtas och hur ofta hämtningarna görs.

### 2022.5.0 {#may-2022}

I majversionen av [!DNL Assets Essentials] släpps den 16 juni 2022.

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

Den första versionen av [!DNL Assets Essentials], som släpptes den 21 juni 2021, erbjuder lättviktiga funktioner för resurshantering. Det har stöd för följande huvudfunktioner och CRUD-åtgärder (Create, Read, Update och Delete):

* Överför och lägg till resurser, inklusive kapslade mappar. Förhandsgranska resurserna och versionerna.
* Fulltextsökning, nyansrika sökfilter och sparade sökningar för snabb resursidentifiering.
* Grundläggande resurshanteringsåtgärder som att uppdatera, ta bort, hämta och hantera metadata.
* [!DNL Assets Essentials] är tillgänglig för [!DNL Adobe Journey Optimizer] -användare för att hantera resurser när de skapar meddelanden. Mer information finns i [integrering med andra Adobe-lösningar](/help/integration.md).
