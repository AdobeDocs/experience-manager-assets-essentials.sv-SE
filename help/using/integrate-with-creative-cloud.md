---
title: Integrera Assets Essentials med Creative Cloud
description: Integrera Assets Essentials med Creative Cloud-program så att du kan använda Adobe Asset-länken i appanelen för att ansluta till  [!DNL Assets Essentials] databasen inifrån de  [!DNL Adobe Creative Cloud] skrivbordsprogram som stöds.
exl-id: 817bc955-0074-435e-83a8-3fd5f7f2505a
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '717'
ht-degree: 0%

---

# Integrera Assets Essentials med Creative Cloud {#integrate-assets-essentials-creative-cloud-applications}

Med [Adobe Asset Link i apppanelen](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) kan kreativa proffs ansluta till [!DNL Assets Essentials]-databasen inifrån de [!DNL Adobe Creative Cloud] datorprogram som stöds. Panelen är tillgänglig för [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] och [!DNL Adobe XD]. Det effektiviserar åtkomsten till resurser, vilket i sin tur hjälper till att öka innehållets hastighet.

Creative Cloud-användare kan bara använda Adobe Asset Link-panelen i appen när du integrerar Creative Cloud-programmen med Experience Manager Assets Essentials-databasen.

Utför följande uppgifter för att integrera Assets Essentials med program i Creative Cloud:

* [Skapa katalogförtroende mellan Creative Cloud och Experience Cloud Admin Console](#directory-trusting-cc-assets-essentials-consoles)

* [Lägga till Creative Cloud-användare i produktprofiler för Assets Essentials](#add-cc-users-assets-essentials-product-profiles)

* [Installera Adobe Asset Link](#install-asset-link)

* [Använd Adobe-resurslänk](#use-asset-link)

## Skapa katalogförtroende mellan Creative Cloud och Experience Cloud Admin Console {#directory-trusting-cc-assets-essentials-consoles}

Om din Creative Cloud används i en annan Adobe Admin Console än den med Assets Essentials (Experience Cloud) måste du lägga till en förtroenderelation mellan de två konsolerna.

För att kunna integrera Creative Cloud och Assets Essentials måste de användare som är tillgängliga i Admin Console för Creative Cloud göras tillgängliga i Admin Console för Experience Cloud. Om Creative Cloud och Assets Essentials distribueras till separata Admin Console krävs det ett förtroendeförhållande mellan dem för att detta ska kunna göras.

Klicka på **[!UICONTROL Settings]** på Experience Cloud Admin Console och använd fliken **[!UICONTROL Directories]** för att skapa en katalog som upprättar [katalogförtroendet](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) mellan de två Admin Console.

## Lägga till Creative Cloud-användare i produktprofiler för Assets Essentials {#add-cc-users-assets-essentials-product-profiles}

När du har etablerat katalogförtroende mellan Admin Console för Creative Cloud och Admin Console för Experience Cloud, tilldelar du Creative Cloud till produktprofilen **[!DNL Assets Essentials]Users** under produktkortet [!DNL Assets Essentials] i Experience Cloud Admin Console. Creative Cloud-användare kan komma åt Assets Essentials från sin plugin-panel för Adobe Asset Link. Dessutom får de tillgång till det fullständiga användargränssnittet för Assets Essentials för att ladda upp, ordna, tagga och hitta digitala resurser via en webbläsare.

Andra produktprofiler för Assets Essentials - **[!DNL Assets Essentials]administratörer** och **[!DNL Assets Essentials]konsumentanvändare** - används för olika användarberättiganden (programadministratörer och användare som använder Assets Essentials via Experience Cloud-integreringar).

Mer information om hur du tilldelar användare till produktprofiler för Assets Essentials finns i [Tilldela användare till produktprofiler för Assets Essentials](deploy-administer.md#add-users-to-product-profiles).

## Installera Adobe Asset Link {#install-asset-link}

Plugin-programmet [!DNL Adobe Asset Link] kan installeras och göras tillgängligt för kreativa användare på två sätt:

* Creative-användare kan installera plugin-programmet från sina [!DNL Creative Cloud Desktop]-program
* Creative Cloud-administratören kan lägga till plugin-programmet Asset Link i ett Creative Cloud-paket i Admin Console

Valet beror på organisationens IT-policyer.

**Installation med [!DNL Creative Cloud Desktop] application** beskrivs [här](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). Det finns två tillgängliga plugin-program på Marketplace i [Adobe Exchange](https://exchange.adobe.com/), beroende på vilket Creative Cloud-program som används:

* För [!DNL Adobe Photoshop], [!DNL Adobe Illustrator] och [!DNL Adobe InDesign]: [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* För [!DNL Adobe XD]: [Adobe-resurslänk](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Installation med ett Creative Cloud-paket** görs av Creative Cloud-administratören i Admin Console genom att plugin-programmet Resurslänk inkluderas när ett distributionspaket skapas, som sedan kan distribueras till användardatorer. På den hanterade skärmen Choose Plugins (Välj plugin-program) söker du efter **Adobe Asset Link** i avsnittet **Aktuella affärs-plugin-program**. Mer information finns i [paketera program via Admin Console](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## Använd Adobe-resurslänk {#use-asset-link}

Kreativa användare kan nu använda Adobe Asset Link med Photoshop, Illustrator, InDesign eller XD. Om du vill öppna panelen i InDesign eller Illustrator går du till Fönster > Tillägg > Länk till Adobe-resurs. I Photoshop går du till Fönster > Tillägg (äldre) > Adobe Asset Link.

Klicka [här](https://helpx.adobe.com/enterprise/using/adobe-asset-link-for-xd.html) om du vill ha information om hur du konfigurerar Adobe Asset Link för Adobe XD.

>[!NOTE]
>
>När du arbetar med maskinvara från Apple Silicon/M1 måste Adobe Photoshop startas i Rosetta-kompatibilitetsläge för att se till att kreativa användare har tillgång till panelen Adobe Asset Link, eftersom den är byggd med CEP-tilläggstekniken. Mer information finns i [Photoshop för Apple Silicon](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


Använd Adobe Asset Link för att arbeta med och ändra resurser som lagras i Assets Essentials. Du kan utföra olika åtgärder, till exempel:

* Söka efter och bläddra bland resurser

* Överför resurser

* Sortera och filtrera resurser

* Montera, hämta och dra en resurs

* Checka ut och Checka in en resurs

* Visa versionshistorik och filinformation

Instruktioner om hur du utför dessa åtgärder finns i [Hantera resurser med Adobe Asset Link](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).
