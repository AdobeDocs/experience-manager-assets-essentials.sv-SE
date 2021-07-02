---
title: Distribuera och hantera användare
description: Administrationsexempel, till exempel distribution och användarhantering i [!DNL Assets Essentials].
role: Administrator
source-git-commit: a9dfa9cc9e971faf24e5275c843fb1d0247d18c9
workflow-type: tm+mt
source-wordcount: '855'
ht-degree: 0%

---


# Distribuera [!DNL Assets Essentials] och lägg till användare {#administer}

[!DNL Adobe Experience Manager Assets Essentials] tillhandahålls av Adobe för sina kunder. Som en del av etableringen läggs [!DNL Assets Essentials] till i en kunds organisation i [!DNL Adobe Admin Console]. Kunderna har även tillgång till [!DNL Experience Manager Cloud Manager] som distributionsverktyg och till [!DNL Admin Console] för att hantera användarrättigheter till [!DNL Assets Essentials]-lösning.

Administratörer utför följande uppgifter:

* [Driftsätt  [!DNL Assets Essentials]](#deploy-essentials) för organisationen.
* [Hantera användaråtkomsten ](#add-users-to-essentials) för organisationsmedlemmar  [!DNL Assets Essentials].
* Du kan även [visa tjänstens status och loggar](#view-logs).

## Distribuera [!DNL Assets Essentials] {#deploy-essentials}

Efter etableringen läggs [!DNL Assets Essentials]-berättigandet till i din organisation i [!DNL Admin Console]. Innan lösningen är tillgänglig för användaren måste en organisationsadministratör distribuera den. Administratören gör en engångsdistribution med [!DNL Cloud Manager]-användargränssnittet. Efter den första driftsättningen utför Adobe underhåll och uppdateringar av tjänsten. När lösningen har etablerats får administratören ett e-postmeddelande från Adobe. E-postmeddelandet innehåller ett välkomstmeddelande och en länk för att komma igång. Så här distribuerar du:

1. Från länken i e-postmeddelandet kommer du åt och loggar in på [Admin Console](https://adminconsole.adobe.com). Om du har administratörsåtkomst till mer än ett organisationskonto väljer du lämplig organisation eller växlar till den med väljaren i det övre fältet. Produktkortet för [!DNL Assets Essentials] visas i [!DNL Admin Console].

   ![[!DNL Assets Essentials] kort in  [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Bild:  [!DNL Assets Essentials] kort in  [!DNL Admin Console].*

1. Lägg till dig själv som administratör för `AEM Assets Essentials - Cloud Manager`-produktprofilen i [!DNL Admin Console]. I stället för att du själv kan lägga till en annan medlem i organisationen eller så kan du lägga till fler än en administratör.

1. Klicka på ![lägg till ikon](assets/do-not-localize/add-icon.svg) i [!UICONTROL Select product profiles] och välj sedan [!UICONTROL Deployment Manager - Assets Essentials] som **[!UICONTROL product profile]**. Den användare som läggs till i det här steget får ett e-postmeddelande från Adobe med åtkomst till [!DNL Cloud Manager] och kan utföra distributionen.

   ![Lägg till en administratör och välj en produktprofil i  [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Bild: Lägg till en administratör och välj en produktprofil i  [!DNL Admin Console].*

1. Om du vill komma åt [!DNL Cloud Manager] klickar du på länken i e-postmeddelandet med åtkomst till [!DNL Cloud Manager]. Du kan även öppna [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) i webbläsaren.

1. Klicka på **[!UICONTROL Add Program]** i det övre högra hörnet i användargränssnittet i Cloud Manager.

1. Ange ett namn och överför eventuellt en bild (den representerar programmet i [!DNL Cloud Manager]) och klicka sedan på **[!UICONTROL Create]**. [!DNL Cloud Manager] tar några minuter att konfigurera programmet.

1. När programmet är klart håller du pekaren över rutan och klickar på ![ikonen för att lägga till miljö](assets/do-not-localize/add-environment-icon.png).

1. Om du vill lägga till tjänsten [!DNL Assets Essentials] i organisationen klickar du på **[!UICONTROL Add Environment]**, väljer ett namn och en distributionsregion och klickar på **[!UICONTROL Save]**. Du kan inte ändra distributionsregionen senare. Försök matcha distributionsregionen för [!DNL Assets Essentials] med distributionsregionen för den andra lösningen som du tänker använda [!DNL Assets Essentials]. Matchningen är att säkerställa snabb nätverksåtkomst till digitala resurser och lägsta möjliga fördröjning.

   ![Lägga till en miljö i  [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Bild: Lägg till en miljö i  [!DNL Cloud Manager] för att börja använda  [!DNL Assets Essentials].*

1. Efter flera minuter, när miljön har skapats, kan du komma åt [!DNL Admin Console] och lägga till organisationens användare i [!DNL Assets Essentials]-lösningen. Klicka på ![alternativikonen](assets/do-not-localize/options-ellipses-icon.png) och välj alternativet **[!UICONTROL Manage Access]**.

   ![Klar miljö i  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Bild: En miljö i  [!DNL Cloud Manager] som är klar att användas.*

## Användarhantering {#add-users-to-essentials}

En administratör hanterar vilka användare som har åtkomst till [!DNL Assets Essentials]. Administratörer använder [!DNL Adobe Admin Console] för att lägga till eller ta bort användaråtkomst. [!DNL Assets Essentials] har följande två typer av användaråtkomst.

* **[!DNL Assets Essentials]Användare** har tillgång till hela användargränssnittet. Dessa användare kan överföra, ordna, tagga och hitta digitala resurser.
* **[!DNL Assets Essentials]Konsumentanvändare**: har tillgång till den inbäddade upplevelsen av resursval i  [!DNL Adobe Journey Optimizer] e-postmallsredigeraren. Mer information finns i [Använd [!DNL Assets Essentials] i [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

I [!DNL Admin Console] representeras dessa två åtkomsttyper av två [!UICONTROL Product Profiles]. Så här lägger du till och tar bort medlemmar i din organisation i någon av de två profilerna:

1. Gå till [!DNL Admin Console] för din organisation, klicka på **[!UICONTROL Products]** i det övre fältet, klicka på **[!UICONTROL AEM Assets Essentials]** och sedan på [!DNL Assets Essentials]-miljö. [!DNL Assets Essentials] har två produktprofiler som representerar åtkomst för vanliga användare och konsumentanvändare.

   ![Två profiler för två typer av användare](assets/adminconsole-user-types.png)

   *Bild: Det finns två profiler för att lägga till de två typerna av användare.*

1. Om du vill lägga till en användare i en grupp klickar du på gruppen, väljer **[!UICONTROL Add User]**, anger användarinformationen och klickar på **[!UICONTROL Save]**. När du lägger till en användare får användaren en e-postinbjudan om att komma igång. Du kan inaktivera e-postinbjudningarna i inställningarna för produktprofilen i [!DNL Admin Console].

   ![Lägg till en användare i  [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Bild: Lägg till en användare  [!DNL Assets Essentials] från  [!DNL Admin Console].*

1. Om du vill ta bort en användare från en grupp klickar du på gruppen, markerar en befintlig användare och väljer **[!UICONTROL Remove User]**.

>[!TIP]
>
>I [!DNL Admin Console] kan du hantera flera användare samtidigt med CSV-filer. Mer information finns i [[!DNL Admin Console] dokumentationen](https://helpx.adobe.com/enterprise/using/accounts.html).

## Visa tjänststatus och åtkomstloggar {#view-logs}

Efter etableringen distribuerar administratörer bara [!DNL Assets Essentials] en gång. Efter den första driftsättningen utför Adobe underhåll och uppdateringar av tjänsten. Administratörer kan använda användargränssnittet [!DNL Cloud Manager] för att kontrollera tjänstens status och för att hämta de senaste åtkomstloggarna.

1. När användare rapporterar problem ska du kontrollera tjänststatusen för [!DNL Assets Essentials] i gränssnittet **[!UICONTROL Program Overview]**. Under det normala arbetet med lösningen är statusen `Running`. Om [!DNL Cloud Manager] visar någon annan status skapar du en supportanmälan i [!DNL Admin Console] supportavsnittet.

   ![Status för  [!DNL Assets Essentials] in  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Bild: Normal status för  [!DNL Assets Essentials] in  [!DNL Cloud Manager] är  `Running`.*

1. Om du vill hämta de senaste åtkomstloggarna klickar du på ![alternativikonen](assets/do-not-localize/options-ellipses-icon.png), väljer **[!UICONTROL Download Logs]** och följer instruktionerna på skärmen. Du kan granska HTTPS-åtkomstbegäranden med hjälp av loggarna.

   ![ Möjlighet att ladda ned åtkomstloggarna](assets/cloudmanager-download-logs.png)

   *Bild: Möjlighet att hämta åtkomstloggarna.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] help](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] help](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
>* [Adobe Journey Optimizer-dokumentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [Versionsinformation](release-notes.md)
* [Kom igång med  [!DNL Assets Essentials]](get-started.md)

