---
title: Överför resurser till databasen
description: Överför resurser till [!DNL Assets Essentials], visa överföringsstatus och åtgärda överföringsproblem.
role: User
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '729'
ht-degree: 0%

---


# Överför resurser {#add-assets}

Om du vill lägga till nya resurser att arbeta med överför du några resurser från det lokala filsystemet. <!-- TBD: Many of the [common file formats are supported](/help/supported-file-formats.md). -->

Du kan använda följande metoder för att överföra en eller flera resurser eller en mapp som innehåller resurser:

* Dra resurser eller mappar i användargränssnittet och följ instruktionerna på skärmen.
* Klicka på alternativet **[!UICONTROL Add Assets]** i verktygsfältet och lägg till några filer i dialogrutan för överföring.

<!-- TBD: Update this GIF
![Asset and nested folder upload demo](assets/do-not-localize/upload-assets.gif) -->

Du kan använda någon av dessa metoder för att överföra resurser när du har skapat en mapp. Om du vill skapa en tom mapp klickar du på **[!UICONTROL Create Folder]** i verktygsfältet. [!DNL Assets Essentials] har kraftfulla textsökningsfunktioner, men du kan också använda mappar för att ordna dina resurser bättre.

När du har markerat filerna visas en bekräftelsedialogruta där du kan lägga till fler filer eller ta bort redan markerade filer. Om du vill lägga till fler filer i en markering klickar du på **[!UICONTROL Browse]** och väljer **[!UICONTROL Browse files]** eller **[!UICONTROL Browse folders]**. Lägg till fler filer eller mappar från samma mapp eller från en annan mapp.

När alla filer är köade klickar du på **[!UICONTROL Upload]**.

![Överför filer och mappar](assets/upload-browse-files-folders.png)

*Bild: Innan du överför de valda resurserna kan du lägga till eller ta bort resurser från kön.*

>[!CAUTION]
>
>Använd resurser som inte har tomt utrymme i filnamnen. Svaren på kommentarer fungerar inte för sådana resurser.

## Visa överföringsförlopp och status {#upload-progress}

När du överför många resurser eller kapslade mappar till [!DNL Assets Essentials] kan vissa resurser inte överföras av olika anledningar, till exempel duplicerade resurser och nätverksproblem.

Om du vill spåra överföringsförloppet klickar du på **[!UICONTROL Upload Progress]** i verktygsfältet. En panel visar överföringsförloppet för alla resurser.

Om du vill visa en delmängd av resurser baserat på överföringsförloppet eller överföringsstatusen använder du filtret i sidofältet **[!UICONTROL Upload Progress]**. De olika filtren är att visa alla resurser, slutförda överföringar, pågående överföringar, köade resurser som ska överföras, pausade överföringar, duplicerade resurser och resurser som inte kunde överföras.

![Filtrera överföringsförloppet baserat på överföringsstatus](assets/filter-upload-progress.png)

*Bild: Filtrera de resurser som du försökte överföra baserat på deras överföringsstatus eller överföringsförlopp.*

Omedelbart efter att resurserna har överförts bearbetar [!DNL Assets Essentials] resurserna för att generera miniatyrbilder och bearbeta metadata. För många resurser tar bearbetningen tid. Om ingen miniatyrbild visas och du ser ett bearbetningsmeddelande på platshållarminiatyrbilden kontrollerar du mappen igen efter några minuter. Under bearbetningen genererar bland annat [!DNL Assets Essentials] renderingarna, lägger till smarta taggar och indexerar resursinformationen för sökning.

![Resurser är processer vid överföring och bearbetningen visas i plattan](assets/upload-processing.png)

*Bild: Överförda resurser visar bearbetningen på plattan som de bearbetas.*

## Resursåtergivningar {#renditions}

[!DNL Assets Essentials] bearbetar det överförda materialet i nära realtid och för många filtyper som stöds genereras renderingar. Återgivningarna skapas för bilder och ändrar storlek på versioner av den överförda bilden. Du kan inte bara hämta resursen utan även återgivningarna för att använda en lämplig version. Du kan visa alla återgivningar av en resurs när du [förhandsgranskar en resurs](/help/navigate-view.md#preview-assets).

![Återgivningar](assets/renditions-view-download.png)

*Bild: Visa och ladda ned renderingarna.*

## Hantera misslyckade överföringar {#resolve-upload-fails}

Om överföringen av en resurs som stöds av någon anledning misslyckas, klickar du på **[!UICONTROL Retry]** i rutan [!UICONTROL Upload Progress].

![Försök igen med en misslyckad överföring](assets/upload-retry.png)

*Bild: Försök igen om en fil som stöds inte kan överföras av någon anledning.*

Om du försöker överföra duplicerade resurser överförs inte resurserna förrän du uttryckligen bekräftar överföringen. Först markeras de duplicerade resurserna som misslyckade överföringar. Du kan lösa problemet genom att skapa en version, ta bort och ersätta befintliga resurser eller skapa en kopia genom att byta namn på resursen. Du kan lösa sådana fel från en resurs i taget eller göra det samtidigt för alla misslyckade dubbletter på en gång.

![Hantera duplicerade resurser en i taget](assets/uploads-manage-duplicates.png)

*Bild: Lös problemet med en resurs i taget för duplicerade resurser som inte kan överföras som standard.*

![Hantera alla misslyckade överföringar gruppvis](assets/upload-progress-manage-failed-uploads.png)

*Bild: Lös problem för alla resurser på en gång för duplicerade resurser som inte kan överföras som standard.*

>[!TIP]
>
>Du kan överföra resurser till DAM-databasen direkt från dina [!DNL Creative Cloud]-skrivbordsprogram. Se hur [[!DNL Assets Essentials] integreras med [!DNL Adobe Asset Link]](/help/integration.md).

## Ta bort resurser eller mappar {#delete-assets}

Användare kan ta bort enskilda resurser eller mappar som inte längre behövs. Gör något av följande om du vill ta bort en resurs eller en mapp:

* Använd alternativet som är tillgängligt på en resurs eller en mapps miniatyrbild.

   ![Alternativ på miniatyrbild av resurs för att hantera en resurs](assets/options-on-thumbnail.png)

   *Bild: Åtgärder för filer och mappar är tillgängliga på resurs- eller mapppanelen.*

* Markera en resurs eller en mapp och klicka på **[!UICONTROL Delete]** ![ikonen Ta bort](assets/do-not-localize/delete-icon.png) i verktygsfältet.
