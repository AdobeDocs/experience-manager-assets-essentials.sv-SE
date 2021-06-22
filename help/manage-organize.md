---
title: Hantera era digitala resurser
description: Flytta, ta bort, kopiera, byta namn på, uppdatera och version av dina resurser i [!DNL Assets Essentials].
role: Business Practitioner,Leader
contentOwner: AG
source-git-commit: 3389908e3ba085362b48a18cd3c106e658484a96
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 0%

---


# Hantera resurser {#manage-assets}

Du kan enkelt utföra olika DAM-åtgärder (Digital Asset Management) med det användarvänliga gränssnittet i [!DNL Assets Essentials]. När du har lagt till resurserna kan du söka efter, hämta, flytta, kopiera, byta namn på, ta bort, uppdatera och redigera dina resurser.

Använd [!DNL Assets Essentials] för att utföra följande resurshanteringsåtgärder. När du markerar en resurs visas följande alternativ i verktygsfältet högst upp.

![Alternativ i verktygsfältet när du väljer en resurs](assets/toolbar-image-selected.png)

*Bild: Alternativ som är tillgängliga i verktygsfältet för en markerad bild.*

* ![avmarkera ](assets/do-not-localize/close-icon.png) ikonAvmarkera markeringen.
* ![details ](assets/do-not-localize/edit-in-icon.png) iconKlicka för att förhandsgranska en resurs och visa detaljerade metadata. När du förhandsgranskar kan du visa versionerna och redigera en bild.
* ![hämtningsikon](assets/do-not-localize/download-icon.png) Hämta den valda resursen till det lokala filsystemet.
* ![ta bort ](assets/do-not-localize/delete-icon.png) ikonTa bort den markerade resursen eller mappen.
* 

   <!-- ![checkout icon](assets/do-not-localize/checkout-icon.png) --> Checkout an asset.
* ![kopiera ](assets/do-not-localize/copy-icon.png) ikonKopiera den markerade filen eller mappen.
* ![flytta ](assets/do-not-localize/move-icon.png) ikonFlytta den markerade resursen eller mappen till en annan plats i databashierarkin.
* ![Byt namn på ](assets/do-not-localize/rename-icon.png) ikonByt namn på den markerade resursen eller mappen. Använd ett unikt namn, annars misslyckas namnbytet med en varning. Du kan försöka igen med ett nytt namn.
* 
   <!-- ![assign task icon](assets/do-not-localize/assign-task-icon.png) --> Assign tasks to other users to collaborate on an asset.

Du kan visa samma alternativ för miniatyrbilder av resurser.

![Alternativ på miniatyrbild av resurs för att hantera en resurs](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] visar endast de relevanta alternativen i verktygsfältet som beror på vilken typ av resurs som har valts.

![Alternativ i verktygsfältet när du väljer en resurs](assets/toolbar-folder-selected.png)

*Bild: Tillgängliga alternativ i verktygsfältet för en vald mapp.*

![Alternativ i verktygsfältet när du väljer en resurs](assets/toolbar-pdf-selected.png)

*Bild: Alternativ i verktygsfältet för en markerad PDF-fil.*

## Hämta och distribuera resurser {#download}

Du kan välja en eller flera resurser eller mappar eller en kombination av båda och hämta urvalet till det lokala filsystemet. Du kan redigera resurserna och överföra dem igen eller distribuera resurserna utanför [!DNL Assets Essentials]. Du kan även [hämta återgivningarna](/help/add-delete.md#renditions) för en resurs.

## Resursversionshantering {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] versionerar resurserna när resurserna överförs igen som uppdateras eller redigeras. Du kan visa versionshistorik, tidigare versioner och återställa en tidigare version av resurser som den senaste versionen, som återställs till en tidigare version om det behövs. Resursversioner skapas i följande scenarier:

* Överför en ny resurs med samma filnamn som en befintlig resurs och i samma mapp som den befintliga resursen. [!DNL Assets Essentials] uppmanas att antingen skriva över den tidigare resursen eller spara den nya resursen som en version. Se [överföra duplicerade resurser](/help/add-delete.md#resolve-upload-fails).

   ![Skapa versioner vid överföring](assets/uploads-manage-duplicates.png)

   *Bild: När du överför en resurs som heter samma som en befintlig resurs kan du skapa en version av resursen.*

* Redigera en bild och klicka på **[!UICONTROL Save as Version]**. Se [redigera bilder](/help/edit-images.md).

   ![Spara redigerad bild som en version](assets/edit-image2.png)

   *Bild: Spara den redigerade bilden som en version.*

* Öppna versionerna av en befintlig resurs. Klicka på **[!UICONTROL New Version]** och överför en senare version av resursen till databasen.

   ![Alternativ för att överföra en ny version av en resurs från versionshistoriken](assets/view-asset-versions2.png)

### Visa versioner av en resurs {#view-versions}

När du överför en duplicerad kopia eller en modifierad kopia av en resurs kan du skapa dess versioner. Med versionshantering kan du granska historiska resurser och återgå till en tidigare version om det behövs.

Om du vill visa versioner öppnar du förhandsgranskningen av en resurs och klickar på **[!UICONTROL Versions]** ![Versionsikon](assets/do-not-localize/versions-clock-icon.png) i den högra sidofältet. Om du vill förhandsgranska en viss version markerar du den. Klicka på **[!UICONTROL Make Latest]** om du vill återgå till den.

Du kan också skapa versioner från tidslinjen för versionerna. Välj den senaste versionen, klicka på **[!UICONTROL New Version]** och överför en ny kopia av resursen från det lokala filsystemet.

![Visa versioner av en resurs](assets/view-asset-versions1.png)

*Bild: Visa versioner av en resurs, återgå till en tidigare version eller överför en annan ny version.*
