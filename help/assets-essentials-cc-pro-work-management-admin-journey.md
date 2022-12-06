---
title: Konfigurera Assets Essentials för Creative Cloud Pro med Work Management Solutions
description: I den här självstudiekursen introduceras en administratörsresa som gör det möjligt för Assets Essentials-program att integreras med Creative Cloud-datorprogram och Adobe Workfront-program. Creative Cloud-programmen omfattar Adobe Photoshop, Adobe Illustrator, Adobe InDesign och Adobe XD.
exl-id: a5e9e0c3-35ec-41de-9656-f4f0f88946c7
source-git-commit: 8920080944981fc1a990136af46c9258c5e8627c
workflow-type: tm+mt
source-wordcount: '941'
ht-degree: 0%

---

# Assets Essentials for Creative Cloud Pro med Work Management Solutions {#creative-cloud-enterprise-user-journeys}

![Inställning för växling av mörkt och ljust tema](assets/cce-next-banner-landing-page.png)

## Introduktion {#introduction}

Creative Cloud Pro for enterprise med Work Management Solutions integrerar kreativa verktyg, innehålls- och arbetshanteringsverktyg för att öka din förmåga att producera kreativt innehåll och snabbt uppnå affärsmålen. Lösningen innehåller följande komponenter:

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

I den här självstudiekursen introduceras en administratörsresa som gör det möjligt för Assets Essentials-program att integreras med Creative Cloud-datorprogram och Adobe Workfront-program. Creative Cloud-programmen omfattar Adobe Photoshop, Adobe Illustrator, Adobe InDesign och Adobe XD.

## Distributionstyper {#deployment-types}

Eftersom lösningen består av program och tjänster från både Creative Cloud och Adobe Experience Cloud kan de driftsättas i ett eller två Adobe-Admin Console för ditt företag.

Vid driftsättning i två Admin Console krävs ytterligare ett konfigurationssteg:

* Creative Cloud tjänster och program (Creative Cloud for enterprise Pro och valfria moduler) hanteras i [Adobe Admin Console för driftsättning i Creative Cloud](https://chl-author-preview.corp.adobe.com/content/help/en/enterprise/admin-guide.html).

* Adobe Workfront och Adobe Experience Manager Assets Essentials hanteras i [Adobe Admin Console för Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html).

För att kunna integrera Creative Cloud- och Assets Essentials-program måste de användare som är tillgängliga i Admin Console för Creative Cloud göras tillgängliga i Admin Console för Experience Cloud. Skapa en katalog som ska upprättas för att göra användare tillgängliga i Experience Cloud Admin Console [katalogförvaltning](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) mellan de två administratörskonsolerna.

![Creative Cloud användare](assets/creative-cloud-users.svg)

Som framgår av diagrammet görs Creative Cloud-användare automatiskt tillgängliga i Experience Cloud Admin Console baserat på ett förtroendeförhållande mellan de två konsolerna. Du kan sedan lägga till användarna i Assets Essentials produktprofiler. Det innebär att Creative Cloud kan komma åt programmet Adobe Asset Link som kan interagera med Assets Essentials-databasen. Mer information finns i [Integrera Assets Essentials med Creative Cloud](integrate-with-creative-cloud.md).

## Experience Manager Documentation Journeys {#documentation-journeys}

En dokumentationsresa knyter ihop många olika och kanske komplexa ämnen och funktioner genom att tillhandahålla en berättarröst som hjälper läsaren, som kan vara nybörjare på Assets Essentials, att förstå och lösa ett affärsproblem från början till slut, samtidigt som man antar minimala tidigare ämnesområden eller Assets Essentials kunskaper.

Dokumentation Journeys bygger på principer för god praxis, grundade på Adobe senaste forskning, beprövade implementeringserfarenheter från Adobe konsulter och återkoppling från kundprojekt.

## Förutsättningar

* [Tillgång till Adobe Admin Console för Experience Cloud-lösningar](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)

* [Tillgång till Adobe Admin Console för driftsättning i Creative Cloud för företag](https://helpx.adobe.com/enterprise/admin-guide.html)

## Administrera Experience Manager Assets Essentials {#administer-assets-essentials}

![Inställning för växling av mörkt och ljust tema](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials är en ny lättviktig utgåva av Adobe Experience Manager Assets. Assets Essentials erbjuder enhetlig resurshantering och samarbete med ett förenklat och enhetligt användargränssnitt. Tack vare den lättanvända tekniken kan fler kreatörer och marknadsförare lagra, upptäcka och distribuera digitala resurser.

Adobe Experience Manager Assets Essentials tillhandahålls av Adobe för sina kunder. Som en del av provisioneringen läggs Assets Essentials till i en kundorganisation i Adobe Admin Console.

Administratörer använder Admin Console för att hantera användarrättigheter för Assets Essentials-produkter:

* Lägg till användargrupper

* Lägga till användare i användargrupper

* Lägga till användare i Assets Essentials produktprofiler

När du har hanterat användarberättiganden i Admin Console kan administratörer använda Assets Essentials-programmet för att:

* Skapa en mappstruktur som bäst stöder organisationens behov

* Hantera behörigheter i mappstrukturen

* Konfigurera metadataformulär

[![Se guiden](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](deploy-administer.md)

Nu när du har konfigurerat och hanterat Assets Essentials-programmet [integrera Creative Cloud-program med Experience Manager Assets Essentials-programmet](integrate-with-creative-cloud.md).

## Integrera Creative Cloud-program med Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![Inställning för växling av mörkt och ljust tema](assets/cce-creative-cloud.png)

[Adobe Asset Link i apppanelen](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) ger kreatörer möjlighet att [!DNL Assets Essentials] databas från den databas som stöds [!DNL Adobe Creative Cloud] datorprogram. Panelen är tillgänglig för [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign]och [!DNL Adobe XD]. Det effektiviserar åtkomsten till resurser som i sin tur ökar innehållets hastighet.

Den här självstudiekursen vägleder dig att integrera [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign]och [!DNL Adobe XD] med Experience Manager Assets Essentials.

Mål:

* Skapa katalogförtroende mellan Creative Cloud och Experience Cloud Admin Console

* Lägga till Creative Cloud-användare i Assets Essentials produktprofiler

* Installera Adobe Asset Link

* Använd Adobe-resurslänk

[![Se guiden](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-creative-cloud.md)

Nu när du har integrerat Creative Cloud-programmen med Assets Essentials [integrera Adobe Workfront med Experience Manager Assets Essentials](integrate-with-workfront.md).

## Integrera Adobe Workfront med Experience Manager Assets Essentials {#administer-adobe-workfront}

![Inställning för växling av mörkt och ljust tema](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) är ett program för arbetshantering som hjälper dig att hantera hela arbetscykeln på ett och samma ställe. Integrationen mellan [!DNL Adobe Workfront] och [!DNL Assets Essentials] Med kan organisationer förbättra innehållets hastighet och time to market genom att knyta samman arbete och resurshantering. Inom ramen för hanteringen av sitt arbete har användarna tillgång till dokument och bilder som behövs i samma lösning.

I den här självstudiekursen får du hjälp att administrera Adobe Workfront och sedan integrera det med Experience Manager Assets Essentials.

Mål:

* Lägga till användare i Workfront produktprofiler

* Lägga till användare i Assets Essentials produktprofiler

* Konfigurera integrering med Experience Manager Assets Essentials

[![Se guiden](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-workfront.md)
