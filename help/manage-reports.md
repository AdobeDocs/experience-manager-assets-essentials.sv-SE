---
title: Hantera rapporter i Assets Essentials
description: Använd informationen i rapporterna i Assets Essentials för att ta fram nyckeltal för att mäta användningen av resurser inom företaget och hos kunderna.
source-git-commit: 511b7904eca972e76f55e574c7c364dd88fb1721
workflow-type: tm+mt
source-wordcount: '493'
ht-degree: 2%

---

# Hantera rapporter {#manage-reports}

Med tillgångsrapportering kan administratörer bedöma nyttan av Adobe Experience Manager Assets Essentials-driftsättning. Rapporterna innehåller användbar information om hur användare interagerar med resurser som är tillgängliga i din distribution.

Använd informationen i rapporterna för att ta fram nyckeltal för att mäta användningen av resurser inom företaget och hos kunderna.

## Åtkomstrapporter {#access-reports}

Alla användare som är tilldelade till [Assets Essentials Administrators produktprofil](deploy-administer.md) har tillgång till statistik och rapporter i Assets Essentials.

## Visa livesstatistik {#view-live-statistics}

Med Assets Essentials kan du visa automatiskt genererade hämtningsdata för din Assets Essentials-distribution. Du kan välja att visa antalet hämtningar av mediefiler som har utförts under de senaste 30 dagarna eller under de senaste 12 månaderna.

![Alternativ i verktygsfältet när du väljer en resurs](assets/asset-reports-live-statistics.png)

Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Live Statistics]** för att visa automatiskt genererade nedladdningsdata.

## Skapa en rapport {#create-report}

Så här skapar du en rapport:

1. Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Reports]** och klicka **[!UICONTROL Create Report]**.

1. I [!UICONTROL Configuration] anger du en rubrik och en valfri beskrivning för rapporten.

1. Välj mappsökvägen, som omfattar de resurser som rapporten ska köras på, med hjälp av **[!UICONTROL Select Folder Path]** fält.

1. Välj datumintervall för rapporten.

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
      <td>Typ</td>
      <td>MIME-typen för resursen.</td>
     </tr>
     <tr>
      <td>Storlek</td>
      <td>Resursens storlek.</td>
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

## Visa listan med rapporter {#view-report-list}

Efter [skapa rapporten](#create-report)kan du visa listan med rapporter och välja att hämta dem i CSV-format eller ta bort dem.

Om du vill visa en lista med rapporter går du till **[!UICONTROL Settings]** > **[!UICONTROL Reports]**.

För varje rapport kan du visa rapportrubrik, rapporttyp, beskrivning som anges när rapporten skapas, rapportens status, e-post-ID för den som skapade rapporten och rapportens skapandedatum.

`Completed ` rapportens status visar att rapporten är klar för hämtning.

![Förteckning över rapporter](assets/list-of-reports.png)


## Hämta en CSV-rapport {#download-csv-report}

Så här hämtar du en rapport i CSV-format:

1. Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Reports]**.

1. Välj en rapport och klicka på **[!UICONTROL Download CSV]**.

Den valda rapporten hämtas i CSV-format. Kolumnerna som visas i CSV-rapporten beror på vilka kolumner som du markerar när [skapa rapporten](#create-report).

## Ta bort en rapport {#delete-report}

Så här tar du bort en rapport:

1. Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Reports]**.

1. Välj en rapport och klicka på **[!UICONTROL Delete]**.