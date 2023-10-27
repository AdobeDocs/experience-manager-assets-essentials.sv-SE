---
title: Massimportera resurser med Assets Essentials
description: Lär dig hur du kan massimportera resurser med det nya resursgränssnittet (Assets Essentials). Det ger administratörer möjlighet att importera ett stort antal resurser från en datakälla till AEM Assets.
exl-id: 5f5fc15e-959b-48b6-834a-42b213512b49
source-git-commit: 73721e8ee5c130ccad2ef2bdccba2e8412e031f2
workflow-type: tm+mt
source-wordcount: '1165'
ht-degree: 0%

---

# Massimportera resurser med Assets Essentials  {#bulk-import-essentials}

>[!CONTEXTUALHELP]
>id="assets_bulk_import"
>title="Massimportera resurser"
>abstract="Nu kan administratörer importera ett stort antal resurser från en datakälla till Experience Manager Assets med hjälp av Assets Essentials. Administratörerna behöver inte längre överföra enskilda resurser eller mappar till Experience Manager Assets. De molnlagringsleverantörer som stöds för bulkimport är bland annat Azure, AWS, Google Cloud och Dropbox."

Med massimport i AEM Assets Essentials kan administratörer importera ett stort antal resurser från en datakälla till AEM Assets. Administratörerna behöver inte längre överföra enskilda resurser eller mappar till AEM Assets.

>[!NOTE]
>
>Assets Essentials-bulkimporteraren använder samma serverdel som Assets as a Cloud Service bulk-importeraren. Assets Essentials har dock fler datakällor att importera från och en smidigare användarupplevelse.

Du kan importera resurser från följande datakällor:

* Azure
* AWS
* Google Cloud
* Dropbox

## Förutsättningar {#prerequisites}

| Datakälla | Förutsättningar |
|-----|------|
| Azure | <ul> <li>Azure Storage-konto </li> <li> Azure Blob Container <li> Azure Access Key eller SAS-token baserat på autentiseringsläge </li></ul> |
| AWS | <ul> <li>AWS </li> <li> AWS Bucket <li> AWS Access Key </li><li> AWS Access Secret </li></ul> |
| Google Cloud | <ul> <li>GCP Bucket </li> <li> E-postadress för GCP-tjänstkonto <li> Privat nyckel för GCP-tjänstkonto</li></ul> |
| Dropbox | <ul> <li>Klient-ID för Dropbox </li> <li> Dropbox Client Secret</li></ul> |

Förutom dessa krav som baseras på datakällan måste du vara medveten om källmappsnamnet som finns i datakällan och som innehåller alla resurser som behöver importeras till AEM Assets.

## Skapa bulkimportkonfiguration {#create-bulk-import-configuration}

Så här skapar du en bulkimportkonfiguration:

1. Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Bulk Import]** och klicka **[!UICONTROL Create Import]**.
1. Välj datakälla. De tillgängliga alternativen är Azure, AWS, Google Cloud och Dropbox.
1. Ange ett namn för bulkimportkonfigurationen i dialogrutan **[!UICONTROL Name]** fält.
1. Ange de specifika autentiseringsuppgifterna för datakällan, som anges i [Förutsättningar](#prerequisites).
1. Ange namnet på rotmappen som innehåller resurser i datakällan i **[!UICONTROL Source Folder]** fält.
1. (Valfritt) Välj **[!UICONTROL Delete source file after import]** om du vill ta bort originalfilerna från källdatalagret när filerna har importerats till Experience Manager Assets.
1. Välj **[!UICONTROL Import Mode]**. Välj **[!UICONTROL Skip]**, **[!UICONTROL Replace]**, eller **[!UICONTROL Create Version]**. Hoppa över är standardläget och i det här läget hoppar användaren över att importera en resurs om den redan finns.
   ![Importera källinformation](assets/bulk-import-source-details.png)

1. (Valfritt) Ange den metadatafil som ska importeras, som finns i CSV-format, i fältet Metadatafil och klicka på **[!UICONTROL Next]** navigera till **[!UICONTROL Location & Filters]**.
1. Definiera en plats i DAM där resurser ska importeras med **[!UICONTROL Assets Target Folder]** anger du en sökväg. Till exempel, `/content/dam/imported_assets`.
1. (Valfritt) I dialogrutan **[!UICONTROL Choose Filters]** anger du den minsta filstorleken för resurser i MB som ska inkluderas i inmatningsprocessen i **[!UICONTROL Filter by Min Size]** fält.
1. (Valfritt) Ange den maximala filstorleken för resurser i MB för att inkludera dem i överföringsprocessen i **[!UICONTROL Filter by Max Size]** fält.
1. (Valfritt) Välj de MIME-typer som ska inkluderas i intagsprocessen med hjälp av **[!UICONTROL Include MIME Type]** fält. Du kan välja flera MIME-typer i det här fältet. Om du inte definierar något värde inkluderas alla MIME-typer i inmatningsprocessen.

1. (Valfritt) Välj de MIME-typer som ska exkluderas i intagsprocessen med hjälp av **[!UICONTROL Exclude MIME Type]** fält. Du kan välja flera MIME-typer i det här fältet. Om du inte definierar något värde inkluderas alla MIME-typer i inmatningsprocessen.

   ![Filter för massimport](assets/bulk-import-location.png)

1. Klicka på **[!UICONTROL Next]**. Välj **[!UICONTROL Save & run import]** för att spara konfigurationen och köra bulkimporten. Välj **[!UICONTROL Save import]** för att spara konfigurationen så att du kan köra den senare.

   ![Kör bulkimport](assets/bulk-import-run.png)

1. Klicka **[!UICONTROL Save]** för att köra det valda alternativet.

### Hantera filnamn vid bulkimport {#filename-handling-bulkimport-assets-view}

När du importerar resurser eller mappar i grupp, [!DNL Experience Manager Assets] importerar hela strukturen för det som finns i importkällan. [!DNL Experience Manager] följer de inbyggda reglerna för specialtecken i resurs- och mappnamnen, och därför måste dessa filnamn saneras. För både mappnamn och resursnamn ändras inte titeln som definieras av användaren och lagras i `jcr:title`.

Vid bulkimport, [!DNL Experience Manager] leta efter de befintliga mapparna för att undvika att importera om resurserna och mapparna, och verifierar även rensningsreglerna som tillämpas i den överordnade mappen där importen sker. Om saneringsreglerna tillämpas i den överordnade mappen, tillämpas samma regler på importkällan. För ny import används följande saneringsregler för att hantera filnamnen på resurser och mappar.

Mer information om otillåtna namn, hantering av resursnamn och hantering av mappnamn vid bulkimport finns i [Hantera filnamn vid bulkimport](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/add-assets.html?lang=en#filename-handling-bulkimport).

## Visa befintliga bulkimportkonfigurationer {#view-import-configuration}

Om du väljer att spara konfigurationen efter att du har skapat den visas konfigurationen i **[!UICONTROL Saved Imports]** -fliken.

![Spara bulkimportkonfiguration](assets/bulk-import-save.png)

Om du väljer att spara och köra importen visas importkonfigurationen i dialogrutan **[!UICONTROL Executed Imports]** -fliken.

![Spara bulkimportkonfiguration](assets/bulk-import-executed.png)

Om du schemalägger en import visas den i **[!UICONTROL Scheduled Imports]** -fliken.

## Redigera bulkimportkonfiguration {#edit-import-configuration}

Om du vill redigera konfigurationsinformationen klickar du på ... som motsvarar konfigurationsnamnet och klickar på **[!UICONTROL Edit]**. Du kan inte redigera titeln för konfigurationen och importdatakällan när du utför redigeringsåtgärden. Du kan redigera konfigurationen med hjälp av flikarna Körd, Schemalagd eller Sparad import.

![Redigera bulkimportkonfiguration](assets/bulk-import-edit.png)

## Schemalägg engångs- eller återkommande importer {#schedule-imports}

Så här schemalägger du en enstaka eller återkommande bulkimport:

1. klicka ... som motsvarar konfigurationsnamnet som finns i **[!UICONTROL Executed Imports]** eller **[!UICONTROL Saved Imports]** och klicka **[!UICONTROL Schedule]**. Du kan också schemalägga om en befintlig schemalagd import genom att navigera till **[!UICONTROL Scheduled Imports]** och klicka **[!UICONTROL Schedule]**.

1. Ställ in ett engångsintag eller schemalägg ett timschema, ett dagligt eller ett veckoschema. Klicka på **[!UICONTROL Submit]**.

   ![Schemalägg bulkimport](assets/bulk-import-schedule.png)

## Utför en hälsokontroll vid import {#import-health-check}

Validera anslutningen till datakällan genom att klicka på ... som motsvarar konfigurationsnamnet och sedan klicka på **[!UICONTROL Check]**. Om anslutningen lyckas visas följande meddelande i Experience Manager Assets:

![Hälsokontroll för massimport](assets/bulk-import-health-check.png)

## Utför en torr körning innan du utför en import {#dry-run-bulk-import}

Klicka på ... som motsvarar konfigurationsnamnet och klicka på **[!UICONTROL Dry Run]** för att anropa en testkörning för massimportjobbet. Experience Manager Assets visar följande information om massimportjobbet:

![Hälsokontroll för massimport](assets/bulk-import-dry-run.png)

## Köra en bulkimport {#run-bulk-import}

Om du har sparat importen när du skapade konfigurationen kan du navigera till fliken Sparad import, klicka på ... för konfigurationen och klicka på **[!UICONTROL Run]**.

Om du behöver utföra en import som redan har slutförts går du till fliken Executed Imports, klickar på ... som motsvarar konfigurationsnamnet och klickar på **[!UICONTROL Run]**.

## Stoppa eller schemalägg en pågående import {#schedule-stop-ongoing-report}

Du kan schemalägga eller stoppa en pågående bulkimport med dialogrutan för status vid bulkimport som visas på startsidan för massimport under en import.

![Pågående import](assets/bulk-import-progress.png)

Du kan också visa de resurser som har importerats till målmappen genom att klicka på **[!UICONTROL View Assets]**.


## Ta bort en bulkimportkonfiguration {#delete-bulk-import-configuration}

Klicka på ... som motsvarar konfigurationsnamnet som finns i **[!UICONTROL Executed Imports]**, **[!UICONTROL Scheduled Imports]**, eller **[!UICONTROL Saved Imports]** och klicka på **[!UICONTROL Delete]** om du vill ta bort konfigurationen för massimport.

## Navigera till resurser när du har utfört bulkimport {#view-assets-after-bulk-import}

Om du vill visa målplatsen för resurserna där resurserna importeras efter att du har kört massimportjobbet klickar du på ... som motsvarar konfigurationsnamnet och klickar sedan på **[!UICONTROL View Assets]**.