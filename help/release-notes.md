---
title: Versionsinformation
description: Versionsinformation och kända fel i [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: eda2ba0d271310d0e87f904dc7622583a80d002e
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---


# Versionsinformation om [!DNL Assets Essentials] {#release-notes}

Den aktuella versionen av [!DNL Assets Essentials] släpps den 30 augusti 2021. Den innehåller integreringar med [!DNL Adobe Workfront] som gör att [!DNL Workfront]-användare kan hantera sina digitala resurser när de hanterar sitt arbete. Se [integreringar med andra Adobe-lösningar](/help/integration.md).

Mer information om lösningen finns i [introduktionen till [!DNL Assets Essentials]](introduction.md). Information om hur du börjar använda funktionerna finns i [komma igång](/help/get-started.md).

## Kända fel {#known-issues}

Listan över kända fel i [!DNL Assets Essentials]-erbjudandet revideras och uppdateras fortlöpande:

* Om du vill överföra en mapp eller resurser placeras överföringen automatiskt i en av undermapparna när du drar objekten till en mapp med undermappar i databasen. Du kan lösa problemet genom att klicka på [!DNL Upload assets] och dra det till dialogrutan. <!-- CQ-4327753 -->
* När du har överfört en mapp kan nya mappar ibland visas felaktigt i den vänstra listen i stället för att visas i trädvyn. Du kan lösa problemet genom att uppdatera webbläsaren. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

Om du stöter på problem eller till och med förbättringsförfrågningar kan du [ge feedback](#provide-feedback) till teamet.

## Tidigare versioner {#past-release}

### 2021.7.0-utgåvan {#july2021}

[!DNL Assets Essentials] 2021.7.0 släpps den 29 juli 2021, med följande uppdateringar:

* Du kan skapa och hantera anpassade metadataformulär som ska användas för att visa metadataegenskaper för användare på resursinformationsskärmen i [!UICONTROL Metadata Forms]-alternativet under [!DNL Settings]. Se [metadataformulär](metadata.md#metadata-forms).
* Olika felkorrigeringar och produktförbättringar, inklusive bättre prestanda vid överföring av en kapslad mapp med många undermappar.

### 2021.6.0-utgåvan {#june2021}

Den första utgåvan av [!DNL Assets Essentials], som släpptes 21 juni 2021, erbjuder lättviktiga funktioner för resurshantering. Det har stöd för följande huvudfunktioner och CRUD-åtgärder (skapa, läsa, uppdatera och ta bort):

* Överför och lägg till resurser, inklusive kapslade mappar. Förhandsgranska resurserna och versionerna.
* Fulltextsökning, nyansrika sökfilter och sparade sökningar för snabb resursidentifiering.
* Grundläggande resurshanteringsåtgärder som att uppdatera, ta bort, hämta och hantera metadata.
* [!DNL Assets Essentials] är tillgängligt för  [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).
