---
title: Integrera Assets Essentials med Creative Cloud
description: Integrera Assets Essentials med Creative Cloud-program så att du kan använda Adobe Asset-länken i appanelen för att ansluta till [!DNL Assets Essentials] databas från den databas som stöds [!DNL Adobe Creative Cloud] datorprogram.
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '852'
ht-degree: 0%

---


# Integrera Assets Essentials med Creative Cloud {#integrate-assets-essentials-creative-cloud-applications}

![Inställning för växling av mörkt och ljust tema](assets/cce-creative-cloud.png)

## Berättelsen hittills

Efter [konfigurera Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) i den här självstudiekursen kan du bygga vidare på upplevelsen för att integrera Creative Cloud-programmen med Assets Essentials.

## Syfte

* **Målgrupp**: Creative Cloud administratörer

* **Syfte**: Integrera Assets Essentials med Creative Cloud-program så att dina kreativa användare kan använda länken Adobe Asset i appen för att ansluta till [!DNL Assets Essentials] databas från den databas som stöds [!DNL Adobe Creative Cloud] datorprogram.

## Översikt

[Adobe Asset Link i apppanelen](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) ger kreatörer möjlighet att [!DNL Assets Essentials] databas från den databas som stöds [!DNL Adobe Creative Cloud] datorprogram. Panelen är tillgänglig för [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign]och [!DNL Adobe XD]. Det effektiviserar åtkomsten till resurser, vilket i sin tur hjälper till att öka innehållets hastighet.

Creative Cloud-användare kan bara använda Adobe Asset Link-panelen i appen när du integrerar Creative Cloud-programmen med Experience Manager Assets Essentials-databasen.

Utför följande uppgifter för att integrera Assets Essentials med Creative Cloud-program:

* [Skapa katalogförtroende mellan Creative Cloud och Experience Cloud Admin Console](#directory-trusting-cc-assets-essentials-consoles)

* [Lägga till Creative Cloud-användare i Assets Essentials produktprofiler](#add-cc-users-assets-essentials-product-profiles)

* [Installera Adobe Asset Link](#install-asset-link)

* [Använd Adobe-resurslänk](#use-asset-link)

## Skapa katalogförtroende mellan Creative Cloud och Experience Cloud Admin Console {#directory-trusting-cc-assets-essentials-consoles}

Om Creative Cloud används i en separat Adobe Admin Console jämfört med Assets Essentials (Experience Cloud) måste du lägga till en förtroenderelation mellan de två konsolerna.

För att kunna integrera Creative Cloud- och Assets Essentials-program måste de användare som är tillgängliga i Admin Console för Creative Cloud göras tillgängliga i Admin Console för Experience Cloud. Om Creative Cloud och Assets Essentials distribueras i separata Admin Console krävs det en förtroenderelation mellan dem för att detta ska kunna göras.

Klicka på Experience Cloud Admin Console **[!UICONTROL Settings]** och använder **[!UICONTROL Directories]** skapa en katalog att skapa [katalogförvaltning](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) mellan de två Admin Console.

## Lägga till Creative Cloud-användare i Assets Essentials produktprofiler {#add-cc-users-assets-essentials-product-profiles}

När du har upprättat ett katalogförtroende mellan Admin Console för Creative Cloud och Admin Console för Experience Cloud ska du tilldela Creative Cloud-användare till **[!DNL Assets Essentials]Användare** produktprofil under [!DNL Assets Essentials] produktkort i Experience Cloud Admin Console. Creative Cloud kommer att kunna komma åt Assets Essentials från sin plugin-panel för Adobe Asset Link, Dessutom får de tillgång till hela Assets Essentials webbanvändargränssnitt där de kan överföra, ordna, märka och söka efter digitala resurser via en webbläsare.

Andra Assets Essentials-produktprofiler - **[!DNL Assets Essentials]Administratörer** och **[!DNL Assets Essentials]Konsumentanvändare** - används för olika användarrättigheter (programadministratörer och användare som använder Assets Essentials via Experience Cloud).

Mer information om hur du tilldelar användare till Assets Essentials produktprofiler finns i [Tilldela användare till Assets Essentials produktprofiler](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Installera Adobe Asset Link {#install-asset-link}

[!DNL Adobe Asset Link] plugin-programmet kan installeras och göras tillgängligt för kreativa användare på två sätt:

* Creative-användare kan installera plugin-programmet från sina [!DNL Creative Cloud Desktop] program
* Creative Cloud-administratören kan lägga till plugin-programmet Asset Link i ett Creative Cloud-paket i Admin Console

Valet beror på organisationens IT-policyer.

**Installation med [!DNL Creative Cloud Desktop] program** beskrivs [här](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). Det finns två tillgängliga plugin-program och de finns på [Adobe Exchange](https://exchange.adobe.com/) Marketplace, beroende på Creative Cloud:

* För [!DNL Adobe Photoshop], [!DNL Adobe Illustrator]och [!DNL Adobe InDesign]: [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* För [!DNL Adobe XD]: [Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Installation med ett Creative Cloud-paket** görs av Creative Cloud-administratören i Admin Console, genom att plugin-programmet för tillgångslänk inkluderas när ett distributionspaket skapas, som senare kan distribueras till användardatorer. På den hanterade skärmen Välj plugin-program söker du efter **Adobe Asset Link** i **Aktuella företagsplugins** -avsnitt. Mer information finns i [paketera program via Admin Console](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## Använd Adobe-resurslänk {#use-asset-link}

Kreativa användare kan nu använda Adobe Asset Link med Photoshop, Illustrator, InDesign eller XD. Om du vill öppna panelen i InDesign eller Illustrator går du till Fönster > Tillägg > Länk till Adobe-resurs. I Photoshop går du till Fönster > Tillägg (äldre) > Adobe Asset Link.

Om du vill ha information om hur du konfigurerar Adobe Asset Link för Adobe XD klickar du på [här](https://helpx.adobe.com/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>När du arbetar med maskinvara från Apple Silicon/M1 måste Adobe Photoshop startas med kompatibilitetsläget Rosetta för att se till att kreativa användare har tillgång till panelen Adobe Asset Link, eftersom den byggs med CEP-tilläggstekniken. Mer information finns i [Photoshop for Apple Silicon](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


Använd Adobe Asset Link för att arbeta med och ändra resurser som lagras i Assets Essentials-databasen. Du kan utföra olika åtgärder, till exempel:

* Söka efter och bläddra bland resurser

* Överför resurser

* Sortera och filtrera resurser

* Montera, hämta och dra en resurs

* Checka ut och Checka in en resurs

* Visa versionshistorik och filinformation

Instruktioner om hur du utför dessa åtgärder finns i [Hantera resurser med Adobe Asset Link](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## What&#39;s Next

Nu när du har integrerat Creative Cloud-programmen med Assets Essentials [integrera Adobe Workfront med Experience Manager Assets Essentials](integrate-assets-essentials-workfront.md).
