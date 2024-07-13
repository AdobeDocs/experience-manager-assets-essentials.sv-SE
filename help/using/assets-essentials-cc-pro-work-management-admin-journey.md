---
title: Konfigurera Assets Essentials för Creative Cloud Pro med Work Management Solutions
description: I den här självstudiekursen introduceras en administratörsresa som gör det möjligt för Assets Essentials att integrera-program med Creative Cloud-datorprogram och Adobe Workfront-program. Creative Cloud-programmen omfattar Adobe Photoshop, Adobe Illustrator, Adobe InDesign och Adobe XD.
exl-id: a5e9e0c3-35ec-41de-9656-f4f0f88946c7
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '870'
ht-degree: 0%

---

# Assets Essentials for Creative Cloud Pro med Work Management Solutions {#creative-cloud-enterprise-user-journeys}

![Inställning för att växla mörkt och ljust tema](assets/cce-next-banner-landing-page.png)

## Introduktion {#introduction}

Creative Cloud Pro for enterprise med Work Management Solutions integrerar kreativa verktyg, innehålls- och arbetshanteringsverktyg för att öka din förmåga att producera kreativt innehåll och snabbt uppnå affärsmålen. Lösningen innehåller följande komponenter:

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

I den här självstudiekursen introduceras en administratörsresa som gör det möjligt för Assets Essentials att integrera-program med Creative Cloud-datorprogram och Adobe Workfront-program. Creative Cloud-programmen omfattar Adobe Photoshop, Adobe Illustrator, Adobe InDesign och Adobe XD.

## Distributionstyper {#deployment-types}

Eftersom lösningen består av program och tjänster från både Creative Cloud och Adobe Experience Cloud kan de driftsättas i ett eller två Adobe-Admin Console för ditt företag.

Vid driftsättning i två Admin Console krävs ytterligare ett konfigurationssteg:

* Creative Cloud-tjänster och program (Creative Cloud for enterprise Pro och valfria moduler) hanteras i [Adobe Admin Console för din Creative Cloud-distribution](https://chl-author-preview.corp.adobe.com/content/help/en/enterprise/admin-guide.html).

* Adobe Workfront och Adobe Experience Manager Assets Essentials hanteras i [Adobe Admin Console för Experience Cloud-lösningar](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html).

För att kunna integrera Creative Cloud och Assets Essentials måste de användare som är tillgängliga i Admin Console för Creative Cloud göras tillgängliga i Admin Console för Experience Cloud. Om du vill göra användarna tillgängliga i Experience Cloud Admin Console skapar du en katalog som upprättar [katalogförtroendet](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) mellan de två administratörskonsolerna.

![Creative Cloud-användare](assets/creative-cloud-users.svg)

Som framgår av diagrammet görs Creative Cloud-användare automatiskt tillgängliga i Experience Cloud Admin Console baserat på ett förtroendeförhållande mellan de två konsolerna. Du kan sedan lägga till användarna i produktprofilerna för Assets Essentials. Det innebär att Creative Cloud-användare kan komma åt Adobe Asset Link-programmet som kan interagera med Assets Essentials-databasen. Mer information finns i [Integrera Assets Essentials med Creative Cloud-program](integrate-with-creative-cloud.md).

## Experience Manager Documentation Journeys {#documentation-journeys}

En dokumentationsresa knyter ihop många olika och kanske komplexa ämnen och funktioner genom att tillhandahålla en berättelse som hjälper läsaren, som kan vara nybörjare på Assets Essentials, förstå och lösa ett affärsproblem från början till slut, samtidigt som man utgår från minimala tidigare kunskaper i ämnet eller Assets Essentials.

Dokumentation Journeys bygger på principer för god praxis, grundade på Adobe senaste forskning, beprövade implementeringserfarenheter från Adobe konsulter och återkoppling från kundprojekt.

## Förutsättningar

* [Åtkomst till Adobe Admin Console för Experience Cloud-lösningar](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)

* [Åtkomst till Adobe Admin Console för Creative Cloud för företagsdistribution](https://helpx.adobe.com/enterprise/admin-guide.html)

## Administrera Experience Manager Assets Essentials {#administer-assets-essentials}

![Inställning för att växla mörkt och ljust tema](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials är en ny lättviktig utgåva av Adobe Experience Manager Assets. Assets Essentials erbjuder enhetlig resurshantering och smidigt samarbete med ett förenklat och enhetligt användargränssnitt. Tack vare den lättanvända tekniken kan fler kreatörer och marknadsförare lagra, upptäcka och distribuera digitala resurser.

Adobe Experience Manager Assets Essentials tillhandahålls av Adobe för sina kunder. Som en del av provisioneringen läggs Assets Essentials till i en kundorganisation i Adobe Admin Console.

Administratörer använder Admin Console för att hantera användarrättigheter för Assets Essentials:

* Lägg till användargrupper

* Lägga till användare i användargrupper

* Lägga till användare i produktprofiler för Assets Essentials

När du har hanterat användarberättiganden i Admin Console kan administratörer använda programmet Assets Essentials för att:

* Skapa en mappstruktur som bäst stöder organisationens behov

* Hantera behörigheter i mappstrukturen

* Konfigurera metadataformulär

[![Se guiden](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](deploy-administer.md)

Nu när du har konfigurerat och hanterat Assets Essentials-programmet kan [integrera Creative Cloud-program med Experience Manager Assets Essentials-programmet](integrate-with-creative-cloud.md).

## Integrera Creative Cloud-program med Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![Inställning för att växla mörkt och ljust tema](assets/cce-creative-cloud.png)

Med [Adobe Asset Link i apppanelen](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) kan kreativa proffs ansluta till [!DNL Assets Essentials]-databasen inifrån de [!DNL Adobe Creative Cloud] datorprogram som stöds. Panelen är tillgänglig för [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] och [!DNL Adobe XD]. Det effektiviserar åtkomsten till resurser som i sin tur ökar innehållets hastighet.

I den här självstudiekursen får du hjälp att integrera [!DNL Adobe Photoshop]-, [!DNL Adobe Illustrator]-, [!DNL Adobe InDesign]- och [!DNL Adobe XD]-program med Experience Manager Assets Essentials.

Mål:

* Skapa katalogförtroende mellan Creative Cloud och Experience Cloud Admin Console

* Lägga till Creative Cloud-användare i produktprofiler för Assets Essentials

* Installera Adobe Asset Link

* Använd Adobe-resurslänk

[![Se guiden](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-creative-cloud.md)

Nu när du har integrerat Creative Cloud-programmen med Assets Essentials, [integrerar Adobe Workfront med Experience Manager Assets Essentials](integrate-with-workfront.md).

## Integrera Adobe Workfront med Experience Manager Assets Essentials {#administer-adobe-workfront}

![Inställning för att växla mörkt och ljust tema](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) är ett arbetshanteringsprogram som hjälper dig att hantera hela arbetscykeln på ett och samma ställe. Tack vare den inbyggda integrationen mellan [!DNL Adobe Workfront] och [!DNL Assets Essentials] kan organisationer förbättra innehållets hastighet och time to market genom att knyta ihop arbete och resurshantering. Inom ramen för hanteringen av sitt arbete har användarna tillgång till dokument och bilder som behövs i samma lösning.

I den här självstudiekursen får du hjälp att administrera Adobe Workfront och sedan integrera det med Experience Manager Assets Essentials.

Mål:

* Lägga till användare i Workfront produktprofiler

* Lägga till användare i produktprofiler för Assets Essentials

* Konfigurera integrering med Experience Manager Assets Essentials

[![Se guiden](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-workfront.md)
