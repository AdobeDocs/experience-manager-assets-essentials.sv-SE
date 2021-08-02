---
title: Versionsinformation
description: Versionsinformation och kända fel i [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: cbeb6f6f59da164115af52dfdbb97023b84bc1d1
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 0%

---


# Versionsinformation om [!DNL Assets Essentials] {#release-notes}

Den aktuella versionen är den första offentliga versionen av [!DNL Assets Essentials] som gjordes tillgänglig den 21 juni 2021. [!DNL Assets Essentials] har funktioner för resurshantering med låg vikt och den första versionen har stöd för följande viktiga funktioner och CRUD-åtgärder (skapa, läsa, uppdatera och ta bort):

* Överför och lägg till resurser, inklusive kapslade mappar. Förhandsgranska resurserna och versionerna.
* Fulltextsökning, nyansrika sökfilter och sparade sökningar för snabb resursidentifiering.
* Grundläggande resurshanteringsåtgärder som att uppdatera, ta bort, hämta och hantera metadata.
* Integrering med [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

För närvarande är [!DNL Assets Essentials] tillgängligt för [[!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer.html)-kunder.

Mer information om lösningen finns i [introduktionen till [!DNL Assets Essentials]](introduction.md). Information om hur du börjar använda funktionerna finns i [komma igång](/help/get-started.md).

## Aktuell version {#release-notes-current}

Den aktuella versionen av Assets Essentials är 2021.7.0, släppt 29 juli 2021, med följande uppdateringar:

* Du kan skapa och hantera anpassade metadataformulär som ska användas för att visa metadataegenskaper för användare på resursinformationsskärmen i [!UICONTROL Metadata Forms]-alternativet under [!DNL Settings]. Se [metadataformulär](metadata.md#metadata-forms).
* Olika felkorrigeringar och produktförbättringar, inklusive bättre prestanda vid överföring av en kapslad mapp med många undermappar.

## Kända fel {#known-issues}

Listan över kända fel i [!DNL Assets Essentials]-erbjudandet revideras och uppdateras fortlöpande:

* Om du vill överföra en mapp eller resurser placeras överföringen automatiskt i en av undermapparna när du drar objekten till en mapp med undermappar i databasen. Du kan lösa problemet genom att klicka på [!DNL Upload assets] och dra det till dialogrutan. <!-- CQ-4327753 -->
* När du har överfört en mapp kan nya mappar ibland visas felaktigt i den vänstra listen i stället för att visas i trädvyn. Du kan lösa problemet genom att uppdatera webbläsaren. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

Om du stöter på problem eller till och med förbättringsförfrågningar kan du [ge feedback](#provide-feedback) till teamet.
