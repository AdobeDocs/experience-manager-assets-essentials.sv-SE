---
title: Distribuera och hantera användare
description: Administrationsexempel, t.ex. distribution och användarhantering i [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: cbf75aaf05a0f3d798edf4d508325b28d9ca0dcb
workflow-type: tm+mt
source-wordcount: '1030'
ht-degree: 0%

---

# Distribuera [!DNL Assets Essentials] och lägga till användare {#administer}

[!DNL Adobe Experience Manager Assets Essentials] tillhandahålls av Adobe för sina kunder. Som en del av provisioneringen [!DNL Assets Essentials] läggs till i en kunds organisation i [!DNL Adobe Admin Console]. Kunderna har även tillgång till [!DNL Experience Manager Cloud Manager] som ett distributionsverktyg och [!DNL Admin Console] för att hantera användarrättigheter till [!DNL Assets Essentials] lösning.

## Automatisk driftsättning av Assets Essentials {#automatic-deployment-assets-essentials}

När Assets Essentials-lösningen har etablerats får administratören ett e-postmeddelande från Adobe. E-postmeddelandet innehåller ett välkomstmeddelande och en länk för att komma igång. Dessutom startar Adobe processen att automatiskt installera Assets Essentials. Distributionsprocessen tar en timme att slutföra.

Från länken i e-postmeddelandet kan du komma åt och logga in på [Admin Console](https://adminconsole.adobe.com). Om du har administratörsåtkomst till mer än ett organisationskonto väljer du lämplig organisation eller växlar till den med väljaren i det övre fältet. När den automatiska driftsättningsprocessen är slutförd kan du [!DNL AEM Assets Essentials] är synlig i [!DNL Admin Console].

![Driftsättning av Assets Essentials](assets/assets-essentials-deployment.png)

Administratörer måste utföra följande uppgifter när Assets Essentials-lösningen har distribuerats:

* [Hantera användaråtkomst](#add-users-to-essentials) för organisationsmedlemmar till [!DNL Assets Essentials].
* Valfritt, [visa tjänststatus och loggar](#view-logs).

>[!NOTE]
>
>Om Assets Essentials etableras före 6 januari 2022 kör du [distributionssteg i Cloud Manager](#deploy-essentials) innan du hanterar användaråtkomst för organisationsmedlemmar.


## Användarhantering {#add-users-to-essentials}

En administratör hanterar vilka användare som har åtkomst till [!DNL Assets Essentials]. Administratörer använder [!DNL Adobe Admin Console] för att lägga till eller ta bort användaråtkomst. [!DNL Assets Essentials] har följande två typer av användaråtkomst.

* **[!DNL Assets Essentials]Användare** har tillgång till hela användargränssnittet. Dessa användare kan överföra, ordna, tagga och hitta digitala resurser.
* **[!DNL Assets Essentials]Konsumentanvändare**: har tillgång till den inbäddade upplevelsen av resursval i [!DNL Adobe Journey Optimizer] e-postmallsredigerare. Mer information finns i [Använd [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

I [!DNL Admin Console], dessa två åtkomsttyper representeras av två [!UICONTROL Product Profiles]. Så här lägger du till och tar bort medlemmar i din organisation i någon av de två profilerna:

1. Åtkomst [!DNL Admin Console] för din organisation klickar du på **[!UICONTROL Products]** i det övre fältet klickar du på **[!UICONTROL AEM Assets Essentials]** och klicka sedan på [!DNL Assets Essentials] miljö. [!DNL Assets Essentials] har två produktprofiler som representerar åtkomst för vanliga användare och konsumentanvändare.

   ![Två profiler för två typer av användare](assets/adminconsole-user-types.png)

   *Bild: Det finns två profiler för att lägga till de två typerna av användare.*

1. Om du vill lägga till en användare i en grupp klickar du på gruppen och väljer **[!UICONTROL Add User]**, anger användarinformationen och klickar på **[!UICONTROL Save]**. När du lägger till en användare får användaren en e-postinbjudan om att komma igång. Du kan inaktivera e-postinbjudningarna i inställningarna för produktprofilen i [!DNL Admin Console].

   ![Lägg till en användare i [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Bild: Lägg till en användare i [!DNL Assets Essentials] från [!DNL Admin Console].*

1. Om du vill ta bort en användare från en grupp klickar du på gruppen, markerar en befintlig användare och väljer **[!UICONTROL Remove User]**.

>[!TIP]
>
>I [!DNL Admin Console]kan du hantera flera användare samtidigt med CSV-filer. Mer information finns på [[!DNL Admin Console] dokumentation](https://helpx.adobe.com/enterprise/using/accounts.html).

## Visa tjänststatus och åtkomstloggar {#view-logs}

Efter etablering distribuerar administratörer [!DNL Assets Essentials] bara en gång. Efter den första driftsättningen utför Adobe underhåll och uppdateringar av tjänsten. Administratörer kan använda [!DNL Cloud Manager] användargränssnitt för att kontrollera tjänstens status och för att hämta de senaste åtkomstloggarna.

1. När användare rapporterar problem ska du kontrollera tjänstens status för [!DNL Assets Essentials] i **[!UICONTROL Program Overview]** gränssnitt. Under den normala driften av lösningen är statusen `Running`. If [!DNL Cloud Manager] visar all annan status, skapa en supportanmälan i [!DNL Admin Console] supportavdelningen.

   ![Status för [!DNL Assets Essentials] in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Bild: Normal status för [!DNL Assets Essentials] in [!DNL Cloud Manager] är `Running`.*

1. Om du vill hämta de senaste åtkomstloggarna klickar du på ![alternativikon](assets/do-not-localize/options-ellipses-icon.png), markera **[!UICONTROL Download Logs]** och följ instruktionerna på skärmen. Du kan granska HTTPS-åtkomstbegäranden med hjälp av loggarna.

   ![ Möjlighet att ladda ned åtkomstloggarna](assets/cloudmanager-download-logs.png)

   *Bild: Möjlighet att hämta åtkomstloggarna.*

## Distribuera [!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>Utför endast dessa steg om Assets Essentials etableras före 6 januari 2022.

Efter etablering, [!DNL Assets Essentials] berättigande läggs till din organisation i [!DNL Admin Console]. Innan lösningen är tillgänglig för användaren måste en organisationsadministratör distribuera den. Administratören gör en engångsdistribution med [!DNL Cloud Manager] användargränssnitt. Efter den första driftsättningen utför Adobe underhåll och uppdateringar av tjänsten. När lösningen har etablerats får administratören ett e-postmeddelande från Adobe. E-postmeddelandet innehåller ett välkomstmeddelande och en länk för att komma igång. Så här distribuerar du:

1. Från länken i e-postmeddelandet kan du komma åt och logga in på [Admin Console](https://adminconsole.adobe.com). Om du har administratörsåtkomst till mer än ett organisationskonto väljer du lämplig organisation eller växlar till den med väljaren i det övre fältet. produktkortet för [!DNL Assets Essentials] är synlig i [!DNL Admin Console].

   ![[!DNL Assets Essentials] kort in [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Bild: [!DNL Assets Essentials] kort in [!DNL Admin Console].*

   >[!NOTE]
   >
   >Om du kan visa **[!UICONTROL AEM Assets Essentials]** i produktavsnittet istället för **[!UICONTROL AEM Assets Essentials - Cloud Manager]** driftsättningen av Assets Essentials är klar. Du kan hoppa över de återstående stegen.

1. Lägg till dig själv som administratör för `AEM Assets Essentials - Cloud Manager` produktprofil i [!DNL Admin Console]. I stället för att du själv kan lägga till en annan medlem i organisationen eller så kan du lägga till fler än en administratör.

1. Klicka ![lägg till ikon](assets/do-not-localize/add-icon.svg) till [!UICONTROL Select product profiles]och sedan markera [!UICONTROL Deployment Manager - Assets Essentials] som **[!UICONTROL product profile]**. Den användare som läggs till i det här steget får ett e-postmeddelande från Adobe med åtkomst till [!DNL Cloud Manager] och kan göra distributionen.

   ![Lägg till en administratör och välj en produktprofil i [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Bild: Lägg till en administratör och välj en produktprofil i [!DNL Admin Console].*

1. För åtkomst [!DNL Cloud Manager]klickar du på länken i e-postmeddelandet med åtkomst till [!DNL Cloud Manager]. Du kan även använda [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) i webbläsaren.

1. I användargränssnittet i Cloud Manager klickar du på **[!UICONTROL Add Program]** från det övre högra hörnet.

1. Ange ett namn och ladda upp en bild (den representerar programmet i [!DNL Cloud Manager]) och sedan klicka på **[!UICONTROL Create]**. [!DNL Cloud Manager] tar några minuter att konfigurera programmet.

1. Håll pekaren över plattan och klicka när programmet är klart ![lägg till miljöikon](assets/do-not-localize/add-environment-icon.png).

1. Lägg till [!DNL Assets Essentials] till din organisation, klicka **[!UICONTROL Add Environment]**, välj ett namn och en distributionsregion och klicka på **[!UICONTROL Save]**. Du kan inte ändra distributionsregionen senare. Försök att matcha distributionsregionen för [!DNL Assets Essentials] med distributionsregionen för den andra lösningen som du tänker använda [!DNL Assets Essentials]. Matchningen är att säkerställa snabb nätverksåtkomst till digitala resurser och lägsta möjliga fördröjning.

   ![Lägga till en miljö i [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Bild: Lägga till en miljö i [!DNL Cloud Manager] att börja använda [!DNL Assets Essentials].*

1. När miljön har skapats på flera minuter kan du öppna [!DNL Admin Console] och lägga till användare i din organisation [!DNL Assets Essentials] lösning. Klicka ![alternativikon](assets/do-not-localize/options-ellipses-icon.png) och väljer **[!UICONTROL Manage Access]** alternativ.

   ![Klar miljö i [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Bild: En miljö i [!DNL Cloud Manager] som är klar att användas.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] help](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] help](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
>* [Adobe Journey Optimizer-dokumentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [Versionsinformation](release-notes.md)
>* [Kom igång med [!DNL Assets Essentials]](get-started.md)

