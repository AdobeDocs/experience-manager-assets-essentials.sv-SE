---
title: Integrering av
description: som är integrerade i AEM Assets och som finns i användargränssnittet i AEM Assets Essentials kan erbjuda kontext i en tillgångs historia, inklusive hur den har gjorts och vem som har deltagit i skapandet av den. Som en näringsetikett för digitalt innehåll kan  bidra till att öka transparensen och bygga förtroende hos målgrupperna.
role: User
source-git-commit: bb7a86c737f862411e2f06997d8b4d720d55a3c5
workflow-type: tm+mt
source-wordcount: '463'
ht-degree: 0%

---


# Content Credentials {#content-credentials}

Varumärken bryr sig mer än någonsin om innehållstransparens, AI-avslöjande och att förhindra manipulering av resurser. Content Authenticity Initiative (CAI) i Adobe skapar verktyg som är kompatibla med den tekniska standarden [Coalition for Content Provenance and Authenticity](https://c2pa.org/specifications/specifications/1.1/specs/C2PA_Specification.html#_trust_model) (C2PA). , som är en ny typ av krypterade, manipuleringssäkra metadata, kan hjälpa tittarna att förstå innehållets härkomst och säkerställa varumärkestillgångarnas integritet. De kan innehålla ett brett urval av härkomstdata som ger insikter i en digital resurs historik.

Den här informationen innehåller:

* **Utfärdare eller undertecknare:** Information om den enhet eller det företag som utfärdade den digitala signaturen för att certifiera eller signera resursen.
* **Utfärdandedatum:** Datumet då innehållsuppgifterna tillämpades på resursen.
* **Kredit och användning:** Information om resursens tillverkare, inklusive namn, referenser till sociala medier eller annan identitetsrelaterad information.
* **Process:** Poster för redigeringar eller ändringar som gjorts i resursen.
* **Enhetsinformation:** Information om programmet eller enheten som används för att skapa eller redigera resursen.
* **AI-verktyg som används:** Om generativ AI användes för att redigera eller skapa resursen kan namnet på den modell som används inkluderas.
* **Annan relevant information:** Ytterligare data kan också inkluderas för att ge mer kontext om en tillgångs historik.

Om du vill visa en fullständig bild kan [Verify](https://contentcredentials.org/verify) ge en mer omfattande inblick i resurshistoriken.

Adobe Experience Manager Assets har nu stöd för  vilket gör att användare kan se  direkt i Assets Essentials-gränssnittet i AEM. När du tittar på resursinformationen visas manifestinformationen på en dedikerad panel i en bild med  (till exempel de som skapats med GenAI-tjänster). Om resursen hämtas, publiceras eller delas förblir autentiseringsuppgifterna intakta för resursen.

![assetss](/help/using/assets/content-credentials.png)

## Åtkomst till  {#access-content-credentials}

1. Gå till användargränssnittet i Assets Essentials och klicka på **Assets** i den vänstra rutan.
1. Navigera till en mapp och välj önskad resurs.
1. Klicka på **Information** och välj `Cr pin` i rutan längst till höger. På fliken  visas följande information om resursen.
   1. **Genererad bild:** Datum och tid då  tillämpades.
   1. **Innehållssammanfattning:** Anger om resursen har genererats delvis eller helt av AI, eller hur den har redigerats.

      ![innehållssammanfattning](/help/using/assets/content-credentials1.png)
   1. **Process:** Visar information om programmet, enheten och AI-verktyget (t.ex. Adobe Firefly) som användes för att generera resursen, samt ändringar som gjordes senare.

      ![process](/help/using/assets/CR-Process.png)
   1. **Om den här :** Namn på utfärdaren tillsammans med datum och tidpunkt för utfärdande.

      ![utfärdare](/help/using/assets/CR-issuer.png)