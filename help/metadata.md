---
title: Hantera metadata
description: Hantera metadata för resurser i [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: a1dc66213f602bce5b5a2ec0ba99084c7f7b1ee1
workflow-type: tm+mt
source-wordcount: '544'
ht-degree: 0%

---


# Metadata i [!DNL Assets Essentials] {#metadata}

Metadata innebär data eller beskrivning av data. Dina bilder som en resurs kan t.ex. innehålla information om kameran som användaren klickade på eller copyright-information. Den här informationen är bildens metadata. Metadata är avgörande för effektiv resurshantering. Metadata är en samling av alla data som är tillgängliga för en tillgång, men de kanske inte nödvändigtvis finns i den tillgången.

Metadata hjälper er att kategorisera resurser ytterligare och är till hjälp när mängden digital information växer. Det går att hantera några hundra filer baserat på bara filnamn, miniatyrbilder och minne. Den här metoden är dock inte skalbar. Den blir kort när antalet inblandade personer och antalet hanterade resurser ökar.

Med hjälp av metadata ökar värdet på en digital resurs eftersom resursen blir

* Mer åtkomligt - system och användare hittar det enkelt.
* Enklare att hantera - du kan hitta resurser med samma uppsättning egenskaper enklare och använda ändringarna på dem.
* Fullständigt - materialet innehåller mer information och sammanhang med fler metadata.

Av dessa anledningar ger Assets dig rätt sätt att skapa, hantera och utbyta metadata för dina digitala resurser.

## Visa metadata {#view-metadata}

Om du vill visa metadata för en resurs bläddrar du till resursen eller söker efter resursen, markerar resursen och klickar på **[!UICONTROL Details]** i verktygsfältet.

![Visa metadata för en resurs](assets/metadata-view1.png)

*Bild: Om du vill visa en resurs och dess metadata klickar du **[!UICONTROL Details]**i verktygsfältet eller dubbelklickar på resursen.*

Grundläggande metadata som titel, beskrivning och överföringsdatum finns på fliken [!UICONTROL Basic]. Fliken [!UICONTROL Advanced] innehåller mer avancerade metadata som kameramodell, objektivdetaljer och geotaggar. Fliken [!UICONTROL Tags] innehåller automatiskt tillämpade taggar baserat på bildens innehåll.

## Uppdatera metadata {#update-metadata}

Du kan uppdatera några metadatafält manuellt. Fälten innehåller [!UICONTROL Title], [!UICONTROL Description], [!UICONTROL Author] och [!UICONTROL Keywords].

## Taggar {#tags}

[!DNL Assets Essentials] använder artificiell intelligens från  [Adobe ](https://www.adobe.com/sensei.html) Senseto för att automatiskt lägga till relevanta taggar i alla dina överförda resurser. Dessa taggar, som kallas smarta taggar, ökar innehållshastigheten i dina projekt genom att hjälpa dig att snabbt hitta relevanta resurser. De smarta taggarna är ett exempel på metadata som inte finns i bilden.

De smarta taggarna används nästan i realtid och genereras baserat på bildens innehåll. När du överför en resurs visas [!UICONTROL Processing] på miniatyrbilden för resursen en tid i användargränssnittet. När bearbetningen är klar kan du [visa metadata](#view-metadata) och smarta taggar.

![Visa smarta taggar för en resurs](assets/metadata-view-tags.png)

*Bild: Om du vill visa smarta taggar för en resurs klickar du **[!UICONTROL Details]**i verktygsfältet eller dubbelklickar på resursen.*

Smarta taggar innehåller också ett konfidensintervall som ett procenttal. Det anger förtroendet som är kopplat till den tillämpade taggen. Du kan moderera de automatiskt tillämpade smarta taggarna.

## Lägga till eller uppdatera taggar {#manually-tag}

Du kan lägga till fler taggar i dina resurser, utöver de smarta taggar som läggs till automatiskt med den smarta [!DNL Adobe Sensei]-tjänsten. Öppna en resurs för förhandsgranskning, klicka på [!UICONTROL Tags] och skriv önskade nyckelord i fältet [!UICONTROL Keywords]. Om du vill lägga till taggen trycker du på Retur. [!DNL Assets Essentials] indexerar nyckelordet i nära realtid och ditt team kan snart söka efter uppdaterade resurser med de nya nyckelorden.

Du kan också ta bort taggar från [!UICONTROL Smart Tags]-avsnittet som automatiskt läggs till av [!DNL Assets Essentials] till alla överförda resurser.

<!-- TBD: Queries for PM and engg.

Can we edit the existing metadata in any form?

How to moderate smart tags?

Allow or deny list for smart tags?

What about Tags displayed just above Smart Tags in the UI?

Is there a detailed metadata tab. Where do the other details of an asset go?

How can one search based strictly on the metadata. Similar to AEM Assets GQL queries.
-->

<!-- TBD: Link to related articles if any.

>[!MORELIKETHIS]
>
>* [Search assets](search.md).
-->
