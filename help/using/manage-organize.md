---
title: Hantera era digitala resurser
description: Flytta, ta bort, kopiera, byta namn på, uppdatera och version av dina resurser i [!DNL Assets Essentials].
role: User,Leader
contentOwner: AG
exl-id: b01e98b9-0cc2-47c5-9f5b-79b8e6bef39f
source-git-commit: a49bfcdf3dbd6601ed15ae8a3309922c0483b3d7
workflow-type: tm+mt
source-wordcount: '1165'
ht-degree: 0%

---

# Hantera resurser {#manage-assets}

Du kan enkelt utföra olika DAM-åtgärder (Digital Asset Management) med det användarvänliga gränssnittet i [!DNL Assets Essentials]. När du har lagt till resurserna kan du söka efter, hämta, flytta, kopiera, byta namn på, ta bort, uppdatera och redigera dina resurser.

Använd [!DNL Assets Essentials] för att utföra följande resurshanteringsåtgärder. När du markerar en resurs visas följande alternativ i verktygsfältet högst upp.

![Alternativ i verktygsfältet när du väljer en resurs](assets/asset-options.png)

*Bild: Alternativ i verktygsfältet för en markerad bild.*

Du kan markera de resurser som visas i sökresultaten och göra följande:

* ![avmarkera ikon](assets/do-not-localize/close-icon.png) Avmarkera markeringen.

* ![sök liknande ikon](assets/do-not-localize/find-similar.svg) Hitta liknande bildresurser i resursgränssnittet baserat på metadata och smarta taggar.

* ![informationsikon](assets/do-not-localize/edit-in-icon.png) Klicka för att förhandsgranska en resurs och visa detaljerade metadata. När du förhandsgranskar kan du visa versionerna och redigera en bild.

* ![hämtningsikon](assets/do-not-localize/download-icon.png) Hämta den valda resursen till ditt lokala filsystem.

* ![lägg till samlingsikon](assets/do-not-localize/add-collection.svg) Lägg till den valda resursen i en samling.

* ![Fäst resurser, ikon](assets/do-not-localize/pin-quick-access.svg) Fäst en resurs för snabbare åtkomst när du behöver den senare. Alla fästa objekt visas i **Snabb åtkomst** i Min arbetsyta.

* ![redigera med Express-ikon](assets/do-not-localize/edit-e.svg) Redigera en bild i den integrerade Adobe Expressen i Adobe Experience Manager Assets.

* ![redigera resursikon](assets/do-not-localize/edit-e.svg) Redigera bilden med Adobe Express.

* ![dela resurslänkikon](assets/do-not-localize/share-link.svg) för en resurs med andra användare så att de kan komma åt och hämta den.

* ![ta bort ikon](assets/do-not-localize/delete-icon.png) Ta bort den markerade resursen eller mappen.

* ![kopieringsikon](assets/do-not-localize/copy-icon.png) Kopiera den markerade filen eller mappen.

* ![flytta ikon](assets/do-not-localize/move-icon.png) Flytta den markerade resursen eller mappen till en annan plats i databashierarkin.

* ![ikonen Byt namn](assets/do-not-localize/rename-icon.png) Byt namn på den markerade resursen eller mappen. Använd ett unikt namn, annars misslyckas namnbytet med en varning. Försök igen med ett nytt namn.
Du kan också klicka på titeln för en resurs eller en mapp för att byta namn på den. Ange den nya texten i dialogrutan **Byt namn på resurs** textruta och klicka **Spara**. Den här funktionen är tillgänglig i stödraster-, galleri-, vattenfalls- och listvyerna.

* ![ikon för vattenfallsvy](assets/do-not-localize/waterfall-view.png) [!UICONTROL Waterfall View].

* ![kopiera biblioteksikon](assets/do-not-localize/copy-icon.png) Lägg till en resurs i biblioteket.

* ![tilldelningsikon](assets/do-not-localize/review-delegate-icon.png) Tilldela uppgifter till andra användare för att samarbeta med en resurs.

* ![tilldelningsikon](assets/do-not-localize/watch-asset.svg) Övervaka åtgärder som utförs på en resurs.

Du kan visa samma alternativ för miniatyrbilder av resurser.

![Alternativ på miniatyrbild av resurs för att hantera en resurs](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] visar endast de relevanta alternativen i verktygsfältet som beror på vilken typ av resurs som har valts.

![Alternativ i verktygsfältet när du väljer en resurs](assets/toolbar-folder-selected.png)

*Bild: Alternativ i verktygsfältet för en vald mapp.*

![Alternativ i verktygsfältet när du väljer en resurs](assets/toolbar-pdf-selected.png)

*Bild: Alternativ i verktygsfältet för en markerad PDF-fil.*

## Hämta och distribuera resurser {#download}

Du kan välja en eller flera resurser eller mappar eller en kombination av båda och hämta urvalet till det lokala filsystemet. Du kan redigera resurserna och överföra dem igen eller distribuera resurserna utanför [!DNL Assets Essentials]. Du kan också [ladda ned renderingarna](/help/using/add-delete.md#renditions) av en tillgång.

## Resursversionshantering {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] versionerar resurserna när resurserna överförs igen som uppdateras eller redigeras. Du kan visa versionshistorik, tidigare versioner och återställa en tidigare version av resurser som den senaste versionen, som återställs till en tidigare version om det behövs. Resursversioner skapas i följande scenarier:

* Överför en ny resurs med samma filnamn som en befintlig resurs och i samma mapp som den befintliga resursen. [!DNL Assets Essentials] uppmanas att antingen skriva över den tidigare resursen eller spara den nya resursen som en version. Se [överföra duplicerade resurser](/help/using/add-delete.md#resolve-upload-fails).

  ![Skapa versioner vid överföring](assets/uploads-manage-duplicates.png)

  *Bild: När du överför en resurs som heter samma som en befintlig resurs kan du skapa en version av resursen.*

* Redigera en bild och klicka på **[!UICONTROL Save as Version]**. Se [redigera bilder](/help/using/edit-images.md).

  ![Spara redigerad bild som en version](assets/edit-image2.png)

  *Bild: Spara redigerad bild som en version.*

* Öppna versionerna av en befintlig resurs. Klicka **[!UICONTROL New Version]** och ladda upp en nyare version av resursen i databasen.

  ![Alternativ för att överföra en ny version av en resurs från versionshistoriken](assets/view-asset-versions2.png)

### Visa versioner av en resurs {#view-versions}

När du överför en duplicerad kopia eller en modifierad kopia av en resurs kan du skapa dess versioner. Med versionshantering kan du granska historiska resurser och återgå till en tidigare version om det behövs.

Om du vill visa versioner öppnar du en resurses förhandsgranskning och klickar på **[!UICONTROL Versions]** ![Versionsikon](assets/do-not-localize/versions-clock-icon.png) från höger sidospalt. Om du vill förhandsgranska en viss version markerar du den. Om du vill återgå till den klickar du på **[!UICONTROL Make Latest]**.

Du kan också skapa versioner från tidslinjen för versionerna. Välj den senaste versionen, klicka på **[!UICONTROL New Version]** och överför en ny kopia av resursen från det lokala filsystemet.

![Visa versioner av en resurs](assets/view-asset-versions1.png)

*Bild: Visa versioner av en resurs, återgå till en tidigare version eller överför en annan ny version.*

## Hantera resursstatus {#manage-asset-status}

**Behörigheter krävs:**  `Can Edit`, `Owner`eller administratörsbehörigheter för en resurs.

Med Assets Essentials kan du ange status för resurser som är tillgängliga i databasen. Ange en resursstatus som bättre styr och hanterar nedströmsanvändningen av digitala resurser.

Du kan ange följande status för resurser:

* Godkänd

* Avvisad

* Ingen status

### Ange resursstatus {#set-asset-status}

Så här anger du resursstatus:

1. Markera resursen och klicka på **[!UICONTROL Details]** i verktygsfältet.

1. I **[!UICONTROL Basic]** väljer du resursstatus på fliken **[!UICONTROL Status]** listruta. Möjliga värden är Godkänd, Avvisat och Ingen status (standard).

   >[!VIDEO](https://video.tv.adobe.com/v/342495)


### Ange förfallodatum för tillgång {#set-asset-expiration-date}

Assets Essentials kan även ange förfallodatum för resurser som är tillgängliga i databasen. Då kan du [filtrera sökresultaten](search.md#refine-search-results) baserat på en `Expired` status. Du kan dessutom ange ett förfallodatumintervall för resurser för att ytterligare filtrera sökresultaten.

Så här anger du förfallodatum för tillgång:

1. Markera resursen och klicka på **[!UICONTROL Details]** i verktygsfältet.

1. I **[!UICONTROL Basic]** anger du förfallodatum för resursen med hjälp av  **[!UICONTROL Expiration date]** fält.

The `Expired` tillgångskortsindikatorn åsidosätter `Approved` eller `Rejected` indikatoruppsättning för en tillgång.

Du kan även filtrera resurser baserat på en resursstatus. Mer information finns i [Söka efter resurser i Assets Essentials](search.md).

## Anpassa metadataformulär för att inkludera resursstatusfält {#customize-asset-status-metadata-form}

**Behörigheter krävs:** Administratör

Assets Essentials tillhandahåller många standardmetadatafält som standard. Organisationer har ytterligare metadatabehov och behöver fler metadatafält för att kunna lägga till företagsspecifika metadata. Med metadataformulär kan företag lägga till anpassade metadatafält i en resurs [!UICONTROL Details] sida. De företagsspecifika metadata förbättrar styrningen och identifieringen av dess resurser.

Mer information om hur du lägger till ytterligare metadatafält i metadataformuläret finns i [Metadata Forms](metadata.md##metadata-forms).

**Lägg till metadatafält för resursstatus i formuläret**

Om du vill lägga till metadatafältet Resursstatus i formuläret drar du **[!UICONTROL Asset Status]** från den vänstra listen till formuläret. Mappningsegenskapen fylls i automatiskt. Spara formuläret för att bekräfta ändringarna.

**Lägg till metadatafältet Förfallodatum i formuläret**

Om du vill lägga till metadatafältet Förfallodatum i formuläret drar du **[!UICONTROL Date]** från den vänstra listen till formuläret. Ange **Förfallodatum** som etikett och `pur:expirationDate` som mappningsegenskapen. Spara formuläret för att bekräfta ändringarna.

## Nästa steg {#next-steps}

* [Titta på en video om hur du hanterar resurser i Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/managing.html)

* Ge produktfeedback med [!UICONTROL Feedback] finns i användargränssnittet i Assets Essentials

* Ge feedback på dokumentationen med [!UICONTROL Edit this page] ![redigera sidan](assets/do-not-localize/edit-page.png) eller [!UICONTROL Log an issue] ![skapa ett GitHub-problem](assets/do-not-localize/github-issue.png) som finns till höger

* Kontakt [Kundtjänst](https://experienceleague.adobe.com/?support-solution=General#support)
