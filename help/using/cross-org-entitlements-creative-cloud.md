---
title: Korsorganisationers rättigheter i AEM Assets för integrering med Creative Cloud
description: Lär dig hur du konfigurerar korsorganisationsberättiganden i AEM Assets för integreringar med Creative Cloud. Anslut till ett berättigande för Creative Cloud som har tilldelats en annan IMS-organisation för att enkelt kunna använda de senaste Creative Cloud-integreringarna i AEM Assets, inklusive Express och Creative Cloud Libraries.
exl-id: 5a39b640-4195-4149-9757-2733ed70e616
source-git-commit: ebc49d5c29118cd09cf1f97e8f71f63df76b3779
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---

# Korsorganisationsberättiganden för integreringar med Creative Cloud  {#cross-org-entitlements}

Experience Manager Assets har möjlighet att ansluta till ett berättigande för Creative Cloud som tillhandahålls till en annan IMS-organisation för att enkelt kunna använda de senaste Creative Cloud-integreringarna i AEM Assets, inklusive Express och Creative Cloud Libraries.

Om dina Creative Cloud-produkter och AEM Assets har tilldelats separata IMS-organisationer kan du ansluta till en annan Creative Cloud-organisation för att kunna köra integrerade arbetsflöden mellan de två lösningarna.

## Förutsättningar {#prerequisites}

* Administratörsrättigheter till Experience Manager Assets

* Aktivt berättigande till Creative Cloud för samma användar-ID som används i Creative Cloud och Experience Manager. Tillstånd till personliga och externa ID:n med samma e-postadress behandlas som olika användar-ID:n.

## Ansluta till en ny Creative Cloud-organisation {#connect-to-creative-cloud-org}

Så här ansluter du till en ny Creative Cloud-organisation:

1. Navigera till **[!UICONTROL Settings]** > **[!UICONTROL Creative Cloud]**.

1. Markera den nya Creative Cloud-organisationen med hjälp av listrutan **[!UICONTROL Select new Creative Cloud org ID]**. I listan visas alla organisationer som du har tillgång till. Markera organisationen med aktiva Creative Cloud-berättiganden.

1. Klicka på **[!UICONTROL Switch orgs]** för att växla till den nya organisationen.

   ![Korsorganisationsberättiganden](assets/cross-org-entitlements.png)

## Begränsningar {#limitations}

* Du kan ansluta AEM Assets till en Creative Cloud-organisation åt gången. Anslutning till flera Creative Cloud-organisationer samtidigt stöds inte.

* Den Creative Cloud-organisation som du ansluter till inom AEM Assets gäller alla användare inom din organisation.
