---
title: Redigera videoklipp
description: Redigera videoklipp med [!DNL Adobe Express] och spara uppdaterade videor som versioner.
role: User
exl-id: 8468d572-89f1-431d-be7f-01e583d06cd7
source-git-commit: 78187929a6baa0f1ab5d8675287408a24e1ada98
workflow-type: tm+mt
source-wordcount: '754'
ht-degree: 0%

---

# Redigera videoklipp i [!DNL Assets Essentials] {#edit-videos}

Det är enkelt för Assets-användare att skapa variationer av videoinnehåll med den inbäddade [!DNL Adobe Express] snabbåtgärder för video. Snabbåtgärder i [!DNL Assets Essentials] som drivs av [!DNL Adobe Express] innehåller användarvänliga videoredigeringsalternativ som beskära video, ändra storlek på video, klippa bort video och konvertera video till GIF.

Om du vill redigera en video går du till informationen i videon och klickar på [!UICONTROL Edit Video]. Du kan också markera resursen och klicka på detaljer och sedan klicka på ![sax](assets/do-not-localize/cut.svg) -ikonen i den högra rutan. När du har redigerat en video kan du spara den nya videon som en ny version eller som en ny resurs.

Läs mer om [förhandsgranskningsgränssnitt](/help/using/navigate-view.md#preview-assets).

## Förutsättningar {#prerequisites}

Tillstånd att få åtkomst [!DNL Adobe Express] och minst en miljö i AEM Assets. Miljön kan vara någon av databaserna i [!DNL Assets as a Cloud Service] eller [!DNL Assets Essentials].

## Redigera videofilmer med Adobe Express {#edit-video-using-express}

Det är enkelt att omvandla en video till en perfekt storlek och orientering med hjälp av inbäddade [!DNL Adobe Express] snabba åtgärder.

### Beskära video {#crop-video-using-express}

Du kan ta bort oönskade delar från videon med hjälp av inbäddade [!DNL Adobe Express] snabba åtgärder. Gör så här:

1. Markera en video och klicka på **[!UICONTROL Edit]**.
2. Klicka **[!UICONTROL Crop Video]** från de snabbåtgärder som är tillgängliga i den vänstra rutan.
3. Dra handtagen i hörnen av videon för att skapa önskad beskärning eller välj önskad skärmstorlek.
4. Du kan välja att stänga av eller slå på ljudet i videon.
5. Klicka på **[!UICONTROL Apply]**.
   ![beskära video med Adobe Express](/help/using/assets/adobe-express-crop-video.png)

   Den beskurna videon är tillgänglig för hämtning. Du kan antingen spara den redigerade resursen som en ny version av samma resurs eller spara den som en ny resurs. ![Spara video med Adobe Express](/help/using/assets/adobe-express-save-video.png)

### Ändra storlek på video {#resize-video-using-express}

Slutligt videoinnehåll i DAM behöver ofta storleksändras för distribution till specifika kanaler. [!DNL Assets Essentials] Med kan du enkelt ändra storlek på video så att den passar de dimensioner som vanliga sociala kanaler kräver, och du kan även ändra storlek till anpassade upplösningar. Ändra storlek på videon med [!DNL Assets Essentials]utför du stegen nedan:

1. Markera en video och klicka på **[!UICONTROL Edit]**.
2. Klicka **[!UICONTROL Resize Video]** från de snabbåtgärder som är tillgängliga i den vänstra rutan.
3. Välj lämpliga dimensioner från plattformen för sociala medier under **[!UICONTROL Resize for the]** listruta. Du kan också dra handtagen i hörnen av videon för att skapa önskad beskärning.
4. Skala videon, om det behövs, med **[!UICONTROL Video Scale]** fält.
5. Du kan välja att stänga av eller slå på ljudet i videon.
6. Klicka **[!UICONTROL Apply]** för att tillämpa ändringarna.
   ![Ändra storlek på video med Adobe Express](/help/using/assets/adobe-express-resize-video.png)

Den storleksändrade videon kan laddas ned. Du kan antingen spara den redigerade resursen som en ny version av samma resurs eller spara den som en ny resurs.

### Trimma video {#trim-video-using-express}

Om du behöver använda ett klipp av en större video kan du använda funktionen&quot;Trimma video&quot; för att markera och trimma ett avsnitt i videon. Utför stegen nedan:

1. Markera en video och klicka på **[!UICONTROL Edit]**.
2. Klicka **[!UICONTROL Trim Video]** från de snabbåtgärder som är tillgängliga i den vänstra rutan.
3. Ange start- och sluttid för videon för att trimma en viss del av den. Du kan också dra handtagen i hörnen av videon för att skapa önskad trimning.
4. Välj lämpliga dimensioner i dialogrutan **[!UICONTROL Size]** listruta.
5. Du kan välja att stänga av eller slå på ljudet i videon.
6. Klicka **[!UICONTROL Apply]** för att tillämpa ändringarna.
   ![Ändra storlek på video med Adobe Express](/help/using/assets/adobe-express-trim-video.png)

Din trimmade video är tillgänglig för hämtning. Du kan antingen spara den redigerade resursen som en ny version av samma resurs eller spara den som en ny resurs.

### Konvertera video till GIF {#convert-mp4-to-gif-using-express}

Du kan snabbt konvertera en MP4-video till ett GIF-format med Adobe Express. Utför följande steg:

1. Markera en video och klicka på **[!UICONTROL Edit]**.
2. Klicka **[!UICONTROL Convert to GIF]** från de snabbåtgärder som är tillgängliga i den vänstra rutan.
3. Välj lämplig filstorlek baserat på önskad kvalitet. Välj dessutom orientering för liggande, stående eller fyrkant.
4. Dra handtagen på hörnen av videon för att skapa önskad beskärning.
5. Klicka på **[!UICONTROL Apply]**.

   ![Konvertera video till GIF med Adobe Express](/help/using/assets/adobe-express-convert-video-to-gif.png)

Din video finns i GIF-format för nedladdning. Du kan antingen spara den redigerade resursen som en ny version av samma resurs eller spara den som en ny resurs.

## Begränsningar {#limitations-video-adobe-express}

* Det går bara att redigera videoklipp i MP4-format.

* Den maximala källfilsstorlek som stöds är 1 GB.

* De videofilmer som stöds är större än 46 pixlar och mindre än 3 840 pixlar på alla sidor.

* De webbläsare som stöds är Google Chrome, Firefox, Safari och Edge.

* Funktionen kan inte öppnas i inkodade lägen i en webbläsare.

### Nästa steg {#next-steps}

* Ge produktfeedback med [!UICONTROL Feedback] finns i användargränssnittet i Assets Essentials.

* Ge feedback på dokumentationen med [!UICONTROL Edit this page] ![redigera sidan](assets/do-not-localize/edit-page.png) eller [!UICONTROL Log an issue] ![skapa ett GitHub-problem](assets/do-not-localize/github-issue.png) som finns till höger.

* Kontakt [Kundtjänst](https://experienceleague.adobe.com/?support-solution=General#support).

>[!MORELIKETHIS]
>
>* [Redigera bilder i Assets Essentials](/help/using/edit-images.md)
>* [Förhandsgranska en resurs](/help/using/navigate-view.md#preview-assets)
