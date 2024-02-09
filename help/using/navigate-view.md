---
title: "[!DNL Assets Essentials] användargränssnitt"
description: Förstå användargränssnittet för och navigering i [!DNL Assets Essentials].
role: User
exl-id: 534a8084-88f7-410e-b872-719e47e62b10
source-git-commit: c56e4950e85efd671260c5235ebb54d95b13606c
workflow-type: tm+mt
source-wordcount: '973'
ht-degree: 0%

---

# Navigera till filer och mappar och visa resurser {#view-assets-and-details}

<!-- TBD: Give screenshots of all views with many assets. Zoom out to showcase how the thumbnails/tiles flow on the UI in different views. -->

<!-- TBD: The options in left sidebar may change. Shared with me and Shared by me are missing for now. Update this section as UI is updated. -->

## Förstå [!DNL Assets Essentials] användargränssnitt {#understand-interface-navigation}

[!DNL Assets Essentials] har ett intuitivt och användarvänligt gränssnitt. Det rena gränssnittet gör det enkelt att hitta och komma ihåg resurser och relaterad information.

När du loggar in [!DNL Assets Essentials]visas följande gränssnitt.

![[!DNL Assets Essentials] användargränssnitt](assets/essentials-interface.png)

    *S: Vänster sidofält för att bläddra i databasen och ger tillgång till några andra alternativ*
    *B: Visa eller komprimera vänster sidospalt för att öka resursens visningsområde*
    *C: Filtrera sökresultat*
    *D: Markera allt innehåll i den markerade mappen*
    *E: Alternativ för att sortera resurser*
    *F: Sökruta*
    *G: Överför eller dra och släpp filer med `Add Assets` knapp*
    *H: Skapa en ny mapp*
    *I: Växla mellan olika vyer*

<!-- TBD: Need an embedded video here with narration. It has to be hosted on MPC to be embeddable. -->

## Bläddra bland och visa resurser och mappar {#browse-repository}

Du kan bläddra bland mapparna från huvudanvändargränssnittet eller från vänster sidofält. När du bläddrar kan du använda gränssnittet för att visa miniatyrbilder av resurser för att visuellt bläddra i databasen eller visa resursinformation för att snabbt hitta den resurs du vill ha. De alternativ som är tillgängliga i den vänstra sidlisten är:

* [Min arbetsyta](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/my-workspace.html?lang=en): Resurserna innehåller nu en anpassningsbar arbetsyta med widgetar för smidig åtkomst till viktiga delar av användargränssnittet och den information som är mest relevant för dig. Den här sidan är en helhetslösning som ger en översikt över dina arbetsobjekt och ger snabb åtkomst till viktiga arbetsflöden. Mer lättåtkomlig åtkomst till dessa alternativ ökar effektiviteten och ökar innehållets hastighet.
* [Uppgifter](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/my-workspace.html?lang=en): Du kan visa de uppgifter som du har tilldelats under **Mina uppgifter** -fliken. De uppgifter som du har skapat kan visas under **Tilldelade uppgifter** -fliken. Dessutom finns de uppgifter du utför under **Slutförda uppgifter** -fliken.
* [Resurser](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/manage-organize.html?lang=en): Lista över alla mappar i en trädvy som du har åtkomst till.
* **Nyligen visade**: Lista med resurser som du nyligen förhandsvisade. [!DNL Assets Essentials] visar bara de resurser som du förhandsgranskar. Det visar inte de resurser som du bläddrar förbi när du bläddrar bland databasfilerna eller databasmapparna.
* [Samlingar](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/manage-collections.html?lang=en): En samling är en uppsättning resurser, mappar eller andra samlingar i Adobe Experience Manager Assets Essentials. Använd samlingar för att dela resurser mellan användare. Till skillnad från mappar kan en samling innehålla resurser från olika platser. Du kan dela flera samlingar med en användare. Varje samling innehåller referenser till resurser. Resursernas referensintegritet bevaras i alla samlingar.

* [Insikter](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/manage-reports.html?lang=en#view-live-statistics): I [!DNL Assets Essentials]kan du visa realtidsinsikter på din instrumentpanel. Med Assets Essentials kan du visa realtidsdata för din Assets Essentials-miljö med Insikter-instrumentpanelen. Du kan visa händelsemått i realtid under de senaste 30 dagarna eller under de senaste 12 månaderna.

* **Papperskorgen**: Lista de resurser som tagits bort från roten **[!UICONTROL Assets]** mapp. Du kan markera en resurs i papperskorgen och antingen återställa den till dess ursprungliga plats eller ta bort den permanent. Du kan ange ett nyckelord eller använda filter som resursstatus, filtyp, MIME-typ, bildstorlek, datum när resursen skapades, ändrades och förfallodatum samt filtrera efter resurser som tagits bort av den aktuella användaren. Du kan också använda anpassade filter för att söka efter lämpliga resurser i papperskorgen. Mer information om hur du använder standardfilter och anpassade filter finns i [sökresurser i Assets Essentials](search.md).

* **Inställningar**: Du kan konfigurera olika alternativ för Assets Essentials med **Inställningar**, t.ex. Metadataformulär, rapporter och taxonomihantering.

<!-- TBD: Not sure if we want to publish these right now. CC Libs are beta as per Greg.
* **Libraries**: Access to [!DNL Adobe Creative Cloud Team] (CCT) Libraries view. This view is visible only if the user is entitled to CCT Libraries.
-->

<!-- TBD: My Work Space shows task inbox and it is not visible on AEM Cloud Demos as of now. It is the source of truth server hence not documenting My Work Space option for now.
-->

Du kan öppna eller komprimera det vänstra sidofältet om du vill öka det tillgängliga området för visning av resurser.

I [!DNL Assets Essentials]kan du visa resurser, mappar och sökresultat i fyra olika typer av layouter.

* ![ikon för listvy](assets/do-not-localize/list-view.png) [!UICONTROL List View]
* ![ikon för stödrastervyn](assets/do-not-localize/grid-view.png) [!UICONTROL Grid View]
* ![gallerivy, ikon](assets/do-not-localize/gallery-view.png) [!UICONTROL Gallery View]
* ![ikon för vattenfallsvy](assets/do-not-localize/waterfall-view.png) [!UICONTROL Waterfall View]

Om du vill hitta en resurs kan du sortera resurserna i stigande eller fallande ordning efter `Name`, `Relevancy`, `Size`, `Modified`och `Created`.

Om du vill navigera till en mapp dubbelklickar du på mappens miniatyrbilder eller väljer mappen från vänster sidopanel. Om du vill visa information om en mapp markerar du den och klickar på Information i verktygsfältet högst upp. Om du vill navigera uppåt och nedåt i hierarkin använder du vänster sidospalt eller de synliga spåren högst upp.

![Bläddra bland mappar](assets/browsing-folders.png)

*Bild: Om du vill bläddra i hierarkin använder du vägbeskrivningarna högst upp eller till vänster.*

## Förhandsgranska resurser {#preview-assets}

Innan du använder, delar eller hämtar en resurs kan du visa den närmare. Med förhandsvisningsfunktionen kan du visa inte bara bilderna utan även några andra resurstyper som stöds.

Om du vill förhandsgranska en resurs markerar du den och klickar på [!UICONTROL Details] ![informationsikon](assets/do-not-localize/edit-in-icon.png) i verktygsfältet högst upp. Du kan inte bara visa resursen utan även visa detaljerade metadata och vidta andra åtgärder.

![Förhandsgranska en resurs](assets/preview-asset-2.png)

*A: Återgå till aktuell mapp eller aktuellt sökresultat i databasen*
*B: Namn och format för filen som du förhandsgranskar*
*C: Tilldela uppgifter*
*D: Hämta resurs*
*E: Förhandsgranska resurs och visa metadatainformation*
*D: Avancerade metadata*
*E: Nyckelord och smarta taggar*
*F: Kommentera och kommentera*
*G: Visa aktiviteter som är relaterade till den valda resursen*
*H: Visa och hantera versioner*
*I: Visa återgivningar av bilden*
*J: Redigera bild*
*K: Grundläggande metadata*
*L: Avancerade metadata*
*M: Nyckelord och smarta taggar*
*N: Förhandsgranska närmare. Zooma, helskärm och andra alternativ*
*O: Gå till föregående eller nästa resurs i den aktuella mappen utan att gå tillbaka till mappen*

Du kan också förhandsgranska videoklipp.

![Videoförhandsgranskning](/help/using/assets/preview-video.png)

Om du förhandsgranskar en resurs explicit [!DNL Assets Essentials] visar det som en nyligen visad resurs.

<!-- TBD: Describe the options.

Explicitly previewed assets are displayed as recently viewed assets. Give screenshot of this.
Other use cases after previewing.
-->

## Konfigurera visning av kolumner för resurslista-vyn {#configure-columns-list-view}

Du kan markera de kolumner som visas i resurslista, t.ex. Status, Format, Dimensioner, Storlek och så vidare:

1. Välj **[!UICONTROL Assets]** i det vänstra navigeringsfönstret växlar du till resurslista-vyn och klickar på ![inställningsikon](assets/settings-icon.svg).

1. Markera de kolumner som du vill visa i listvyn och klicka på **[!UICONTROL Confirm]**.

   ![Konfigurera kolumner](/help/using/assets/configure-columns.png)

## Nästa steg {#next-steps}

* Ge produktfeedback med [!UICONTROL Feedback] finns i användargränssnittet i Assets Essentials

* Ge feedback på dokumentationen med [!UICONTROL Edit this page] ![redigera sidan](assets/do-not-localize/edit-page.png) eller [!UICONTROL Log an issue] ![skapa ett GitHub-problem](assets/do-not-localize/github-issue.png) som finns till höger

* Kontakt [Kundtjänst](https://experienceleague.adobe.com/?support-solution=General#support)

>[!MORELIKETHIS]
>
>* [Visa versioner av en resurs](/help/using/manage-organize.md#view-versions).
