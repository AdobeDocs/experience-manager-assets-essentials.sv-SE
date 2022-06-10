---
title: Sök efter och hitta resurser i [!DNL Assets Essentials]
description: Sök efter och hitta resurser i [!DNL Assets Essentials].
role: User
exl-id: be9597a3-056c-436c-a09e-15a03567c85a
source-git-commit: 8fe62d7073b313da9a5ca4c365636933d44d24c4
workflow-type: tm+mt
source-wordcount: '744'
ht-degree: 1%

---

# Sök resurser i [!DNL Assets Essentials] {#search-assets}

[!DNL Assets Essentials] innehåller effektiva sökfunktioner som bara fungerar som standard. Sökningen är omfattande eftersom den består av fulltextsökning. Med de kraftfulla sökfunktionerna kan du snabbt hitta rätt resurs och hjälpa dig att förbättra innehållets hastighet. [!DNL Assets Essentials] innehåller fulltextsökning och till och med sökningar via metadata som smarta taggar, titel, skapad den och copyright.

Om du vill söka efter resurser

* Klicka i sökrutan högst upp på sidan. Som standard söker programmet i den mapp som du just nu bläddrar i. Gör något av följande:

   ![sökruta](assets/search-box.png)

   * Sök med nyckelord och ändra mapp om det behövs. Tryck på Retur.

   * Börja arbeta med en nyligen visad resurs genom att söka direkt efter den. Klicka i sökrutan och välj en nyligen visade resurs bland förslagen.

## Filtrera sökresultaten {#refine-search-results}

Du kan filtrera sökresultaten baserat på följande parametrar.

![Sökfilter](assets/filters1.png)

*Bild: Filtrera sökningar efter resurser baserat på olika parametrar.*

* Resursstatus: Filtrera sökresultaten med en `Approved`, `Rejected`, eller `No Status` tillgångsstatus.

* Filtyp: Filtrera sökresultaten efter de filtyper som stöds, det vill säga `Images`, `Documents`och `Videos`.
* MIME-typ: Filtrera efter ett eller flera filformat som stöds. <!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* Bildstorlek: Ange en eller flera av de minsta och högsta måtten för att filtrera bilder. Storleken anges i pixeldimensioner och är inte bildens filstorlek.
* Skapa datum: Skapandedatumet för resursen enligt metadatan. Standarddatumformatet som används är `yyyy-mm-dd`.
* Ändringsdatum: Senaste ändringsdatum för resurserna. Standarddatumformatet som används är `yyyy-mm-dd`.

Du kan sortera de sökda resurserna i stigande eller fallande ordning efter `Name`, `Relevancy`, `Size`, `Modified`och `Created`.

## Hantera anpassade filter {#custom-filters}

**Behörigheter krävs:**  `Can Edit`, `Owner`eller Administratör.

Med Assets Essentials kan du också lägga till egna filter i användargränssnittet. Du kan sedan använda dessa anpassade filter utöver [standardfilter](#refine-search-results) för att förfina sökresultaten.

Assets Essentials har följande anpassade filter:

<table>
    <tbody>
     <tr>
      <th><strong>Eget filternamn</strong></th>
      <th><strong>Beskrivning</strong></th>
     </tr>
     <tr>
      <td>Titel</td>
      <td>Filtrera resurser med resursens titel. Du kan använda en jokerteckenoperator (*) för att aktivera Assets Essentials för att visa resurser i resultat som delvis matchar sökvillkoren. Om du till exempel definierar <b>ma*</b> som sökvillkor visar Assets Essentials resurser med titel, som marknad, marknadsföring, man, manchester osv. i resultaten.</td>
     </tr>
     <tr>
      <td>Namn</td>
      <td>Filtrera resurser med resursfilens namn. Du kan använda en jokerteckenoperator (*) för att aktivera Assets Essentials för att visa resurser i resultat som delvis matchar sökvillkoren.</td>
     </tr>
     <tr>
      <td>Resursstorlek</td>
      <td>Filtrera resurser genom att definiera ett storleksintervall, i byte, i sökvillkoren för en resurs som ska visas i resultaten.</td>
     </tr>
     <tr>
      <td>Förutsedda taggar</td>
      <td>Filtrera resurser med den smarta resurstaggen. Du kan använda en jokerteckenoperator (*) för att aktivera Assets Essentials för att visa resurser i resultat som delvis matchar sökvillkoren. Du kan ange flera smarta taggar avgränsade med kommatecken i sökvillkoren.</td>
     </tr>    
    </tbody>
   </table>

### Lägga till egna filter {#add-custom-filters}

Så här lägger du till anpassade filter:

1. Klicka på **[!UICONTROL Filters]**.

1. I **[!UICONTROL Custom Filters]** avsnitt, klicka **[!UICONTROL Edit]** eller **[!UICONTROL Add Filters]**.

   ![Lägga till egna filter](assets/add-custom-filters.png)

1. På **[!UICONTROL Custom filters management]** väljer du de filter som du vill lägga till i den befintliga filterlistan. Välj **[!UICONTROL Custom Filters]** om du vill markera alla filter.

1. Klicka **[!UICONTROL Confirm]** för att lägga till filter i användargränssnittet.

### Ta bort egna filter {#remove-custom-filters}

Så här tar du bort anpassade filter:

1. Klicka på **[!UICONTROL Filters]**.

1. I **[!UICONTROL Custom Filters]** avsnitt, klicka **[!UICONTROL Edit]**.

1. På **[!UICONTROL Custom filters management]** avmarkerar du de filter som du vill ta bort från den befintliga filterlistan.

1. Klicka **[!UICONTROL Confirm]** för att ta bort filtren från användargränssnittet.


## Sparade sökningar {#saved-search}

Sökfunktionen är mycket enkel att använda i [!DNL Assets Essentials]. I sökrutan kan du inte bara skriva ett nyckelord och trycka på Retur för att se resultatet. Du kan också snabbt söka igen efter dina nyligen sökta nyckelord med ett enda klick.

Du kan också filtrera sökresultaten baserat på specifika villkor runt metadata och resurstyp. För filter som används ofta, för att förbättra sökupplevelsen, [!DNL Assets Essentials] I kan du spara sökparametrarna. Du kan sedan markera den sparade sökningen och använda filtret med bara ett klick.

Om du vill skapa en sparad sökning söker du efter en resurs, använder ett eller flera filter och klickar på [!UICONTROL Save Search] i [!UICONTROL Filters] -panelen.

![Sparad sökning från panelen Filter](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->

## Nästa steg {#next-steps}

* [Titta på en video där du kan söka efter resurser i Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/using.html)

* Ge produktfeedback med [!UICONTROL Feedback] finns i Assets Essentials användargränssnitt

* Ge feedback på dokumentationen med [!UICONTROL Edit this page] ![redigera sidan](assets/do-not-localize/edit-page.png) eller [!UICONTROL Log an issue] ![skapa ett GitHub-problem](assets/do-not-localize/github-issue.png) som finns till höger

* Kontakt [Kundtjänst](https://experienceleague.adobe.com/?support-solution=General#support)
