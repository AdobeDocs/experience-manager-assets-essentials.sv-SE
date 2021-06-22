---
title: Söka efter och identifiera resurser i [!DNL Assets Essentials]
description: Sök och upptäck resurser i [!DNL Assets Essentials].
role: Business Practitioner
source-git-commit: 3389908e3ba085362b48a18cd3c106e658484a96
workflow-type: tm+mt
source-wordcount: '386'
ht-degree: 1%

---


# Sök efter resurser i [!DNL Assets Essentials] {#search-assets}

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

* Filtyp: Filtrera sökresultaten efter de filtyper som stöds, `Images`, `Documents` och `Videos`.
* MIME-typ: Filtrera efter ett eller flera filformat som stöds. <!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* Bildstorlek: Ange en eller flera av de minsta och högsta måtten för att filtrera bilder. Storleken anges i pixeldimensioner och är inte bildens filstorlek.
* Skapa datum: Skapandedatumet för resursen enligt metadatan. Standarddatumformatet som används är `yyyy-mm-dd`.
* Ändringsdatum: Senaste ändringsdatum för resurserna. Standarddatumformatet som används är `yyyy-mm-dd`.

Du kan sortera de sökda resurserna i stigande eller fallande ordning `Name`, `Relevancy`, `Size`, `Modified` och `Created`.

## Sparade sökningar {#saved-search}

Sökfunktionen är mycket enkel att använda i [!DNL Assets Essentials]. I sökrutan kan du inte bara skriva ett nyckelord och trycka på Retur för att se resultatet. Du kan också snabbt söka igen efter dina nyligen sökta nyckelord med ett enda klick.

Du kan också filtrera sökresultaten baserat på specifika villkor runt metadata och resurstyp. För filter som används ofta kan du spara sökparametrarna med [!DNL Assets Essentials] för att förbättra sökupplevelsen. Du kan sedan markera den sparade sökningen och använda filtret med bara ett klick.

Om du vill skapa en sparad sökning söker du efter en resurs, använder ett eller flera filter och klickar på [!UICONTROL Save Search] på panelen [!UICONTROL Filters].

![Sparad sökning från panelen Filter](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->
