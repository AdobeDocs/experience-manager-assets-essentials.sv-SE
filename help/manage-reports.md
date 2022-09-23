---
title: Hantera rapporter i Assets Essentials
description: Använd uppgifterna i rapportavsnittet i Assets Essentials för att utvärdera produkt- och funktionsanvändning och få insikter om viktiga framgångsmått.
exl-id: c7155459-05d9-4a95-a91f-a1fa6ae9d9a4
source-git-commit: 95001cb7b1d37807fcd1fed0e26333cca15bbfbd
workflow-type: tm+mt
source-wordcount: '720'
ht-degree: 2%

---

# Hantera rapporter {#manage-reports}

Resursrapportering ger administratörer insyn i Adobe Experience Manager Assets Essentials-miljöns aktivitet. Dessa data ger användbar information om hur användarna interagerar med innehållet och produkten.

## Åtkomstrapporter {#access-reports}

Alla användare som är tilldelade till [Assets Essentials Administrators produktprofil](deploy-administer.md) kan komma åt kontrollpanelen Live-statistik eller skapa användardefinierade rapporter i Assets Essentials.

## Visa livesstatistik {#view-live-statistics}

Med Assets Essentials kan du visa realtidsdata för din Assets Essentials-miljö med kontrollpanelen Live Statistics. Du kan visa händelsemått i realtid under de senaste 30 dagarna eller under de senaste 12 månaderna.

![Alternativ i verktygsfältet när du väljer en resurs](assets/assets-essentials-live-statistics.png)

Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Live Statistics]** om du vill visa följande automatiskt genererade diagram:

* **Nedladdningar**: Antalet resurser som laddats ned från Assets Essentials-miljön under de senaste 30 dagarna eller 12 månaderna visas i ett linjediagram.

* **Överföringar**: Antalet mediefiler som har överförts till Assets Essentials-miljön under de senaste 30 dagarna eller 12 månaderna visas i ett linjediagram.

* **Lagringsanvändning**: Lagringsanvändningen, i gigabyte (GB), för Assets Essentials-miljön under de senaste 30 dagarna eller 12 månaderna, visas i ett stapeldiagram.

## Skapa en nedladdningsrapport {#create-download-report}

Så här skapar du en hämtningsrapport:

1. Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Reports]** och klicka **[!UICONTROL Create Report]**.

1. I [!UICONTROL Configuration] -fliken, ange rapporttypen som **[!UICONTROL Download]**.

1. Ange en rubrik och en valfri beskrivning för rapporten.

1. Välj mappsökvägen, som omfattar de resurser som rapporten ska köras på, med hjälp av **[!UICONTROL Select Folder Path]** fält.

1. Välj datumintervall för rapporten.
   >[!NOTE]
   >
   > Assets Essentials konverterar alla lokala tidszoner till UTC (Coordinated Universal Time).

1. I [!UICONTROL Columns] markerar du de kolumnnamn du vill visa i rapporten.

1. Klicka på **[!UICONTROL Create]**.

   ![Hämta rapport](assets/download-reports-config.png)

I följande tabell förklaras användningen av alla kolumner som du kan lägga till i rapporten:

<table>
    <tbody>
     <tr>
      <th><strong>Kolumnnamn</strong></th>
      <th><strong>Beskrivning</strong></th>
     </tr>
     <tr>
      <td>Titel</td>
      <td>Namnet på resursen.</td>
     </tr>
     <tr>
      <td>Bana</td>
      <td>Mappsökvägen där resursen är tillgänglig i Assets Essentials.</td>
     </tr>
     <tr>
      <td>MIME-typ</td>
      <td>MIME-typen för resursen.</td>
     </tr>
     <tr>
      <td>Storlek</td>
      <td>Resursens storlek i byte.</td>
     </tr>
     <tr>
      <td>Hämtat av</td>
      <td>E-post-ID för den användare som hämtade resursen.</td>
     </tr>
     <tr>
      <td>Hämtningsdatum</td>
      <td>Det datum då hämtningsåtgärden för resursen utförs.</td>
     </tr>
     <tr>
      <td>Författare</td>
      <td>Resursens författare.</td>
     </tr>
     <tr>
      <td>Skapad</td>
      <td>Det datum då resursen överförs till Assets Essentials.</td>
     </tr>
     <tr>
      <td>Ändringsdatum</td>
      <td>Datumet då tillgången senast ändrades.</td>
     </tr>
     <tr>
      <td>Utgånget</td>
      <td>Tillgångens förfallostatus.</td>
     </tr>
     <tr>
      <td>Hämtat efter användarnamn</td>
      <td>Namnet på den användare som hämtade resursen.</td>
     </tr>           
    </tbody>
   </table>

## Skapa en överföringsrapport {#create-upload-report}

Så här skapar du en överföringsrapport:

1. Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Reports]** och klicka **[!UICONTROL Create Report]**.

1. I [!UICONTROL Configuration] -fliken, ange rapporttypen som **[!UICONTROL Upload]**.

1. Ange en rubrik och en valfri beskrivning för rapporten.

1. Välj mappsökvägen, som omfattar de resurser som rapporten ska köras på, med hjälp av **[!UICONTROL Select Folder Path]** fält.

1. Välj datumintervall för rapporten.

1. I [!UICONTROL Columns] markerar du de kolumnnamn du vill visa i rapporten.

1. Klicka på **[!UICONTROL Create]**.

   ![Överför rapport](assets/upload-reports-config.png)

I följande tabell förklaras användningen av alla kolumner som du kan lägga till i rapporten:

<table>
    <tbody>
     <tr>
      <th><strong>Kolumnnamn</strong></th>
      <th><strong>Beskrivning</strong></th>
     </tr>
     <tr>
      <td>Titel</td>
      <td>Namnet på resursen.</td>
     </tr>
     <tr>
      <td>Bana</td>
      <td>Mappsökvägen där resursen är tillgänglig i Assets Essentials.</td>
     </tr>
     <tr>
      <td>MIME-typ</td>
      <td>MIME-typen för resursen.</td>
     </tr>
     <tr>
      <td>Storlek</td>
      <td>Resursens storlek.</td>
     </tr>
     <tr>
      <td>Författare</td>
      <td>Resursens författare.</td>
     </tr>
     <tr>
      <td>Skapad</td>
      <td>Det datum då resursen överförs till Assets Essentials.</td>
     </tr>
     <tr>
      <td>Ändringsdatum</td>
      <td>Datumet då tillgången senast ändrades.</td>
     </tr>
     <tr>
      <td>Utgånget</td>
      <td>Tillgångens förfallostatus.</td>
     </tr>              
    </tbody>
   </table>

## Visa befintliga rapporter {#view-report-list}

Efter [skapa rapporten](#create-download-report)kan du visa listan över befintliga rapporter och välja att hämta dem i CSV-format eller ta bort dem.

Om du vill visa en lista med rapporter går du till **[!UICONTROL Settings]** > **[!UICONTROL Reports]**.

För varje rapport kan du visa rapportrubrik, rapporttyp, beskrivning som anges när rapporten skapas, rapportens status, e-post-ID för den som skapade rapporten och rapportens skapandedatum.

`Completed ` rapportens status visar att rapporten är klar för hämtning.

![Förteckning över rapporter](assets/list-of-reports.png)


## Hämta en CSV-rapport {#download-csv-report}

Så här hämtar du en rapport i CSV-format:

1. Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Reports]**.

1. Välj en rapport och klicka på **[!UICONTROL Download CSV]**.

Den valda rapporten hämtas i CSV-format. Kolumnerna som visas i CSV-rapporten beror på vilka kolumner som du markerar när [skapa rapporten](#create-download-report).

## Ta bort en rapport {#delete-report}

Så här tar du bort en rapport:

1. Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Reports]**.

1. Välj en rapport och klicka på **[!UICONTROL Delete]**.

1. Klicka **[!UICONTROL Delete]** igen för att bekräfta.
