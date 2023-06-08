---
title: Integrera Assets Essentials med Adobe Workfront
description: Integrera Assets Essentials med Adobe Workfront så att du får tillgång till Assets Essentials-databasen i Workfront.
exl-id: 47c2963d-57f0-463e-8d5b-5e5af9928f77
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '627'
ht-degree: 0%

---

# Integrera Assets Essentials med Adobe Workfront {#integrate-assets-essentials-workfront}

![Inställning för växling av mörkt och ljust tema](assets/cce-workfront.png)

## Berättelsen hittills

Efter [konfigurera Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) och [integrera Creative Cloud-programmen med Assets Essentials](integrate-assets-essentials-creative-cloud.md)kan du bygga vidare på för att integrera Adobe Workfront med Assets Essentials.

## Syfte

* **Målgrupp**: Adobe Workfront-administratörer

* **Syfte**: Integrera Assets Essentials med Adobe Workfront så att du får tillgång till Assets Essentials-databasen i Workfront.

## Översikt

[[!DNL Adobe Workfront]](https://www.workfront.com/) är ett program för arbetshantering som hjälper dig att hantera hela arbetscykeln på ett och samma ställe. Integrationen mellan [!DNL Adobe Workfront] och [!DNL Assets Essentials] Med kan organisationer förbättra innehållets hastighet och time to market genom att knyta samman arbete och resurshantering. Inom ramen för hanteringen av sitt arbete har användarna tillgång till dokument och bilder som behövs i samma lösning.

Utför följande uppgifter för att integrera Workfront med Experience Manager Assets Essentials:

* [Lägga till användare i Workfront produktprofiler](#add-users-to-product-profiles)

* [Lägga till användare i Assets Essentials produktprofiler](#add-workfront-users-assets-essentials-product-profiles)

* [Konfigurera integrering av Experience Manager Assets Essentials](#configure-assets-essentials-integration)

## Lägga till användare i Workfront produktprofiler {#add-users-to-product-profiles}

Så här lägger du till användare i Workfront produktprofiler:

1. Åtkomst [Admin Console](https://adminconsole.adobe.com) för din organisation klickar du på **[!UICONTROL Products]** i det övre fältet klickar du på **[!UICONTROL Workfront]** och klickar på den första förekomsten i listan. Klicka inte på den andra och tredje förekomsten i listan.

   ![Administratörsprofil för Admin Console](assets/workfront-instances.png)

   Admin Console visar den enda tillgängliga produktprofilen.

1. Om du vill lägga till en användare i en produktprofil klickar du på profilen och sedan på **[!UICONTROL Add User]**, anger användarinformationen och klickar på **[!UICONTROL Save]**.

   ![Lägg till administratörsprofil för användare](assets/add-users-workfront.png)

   När du lägger till en användare får användaren en e-postinbjudan om att komma igång. Du kan inaktivera e-postinbjudningarna i inställningarna för produktprofilen i [!DNL Admin Console].

1. Om du vill ta bort en användare från en grupp klickar du på gruppen, markerar en befintlig användare och väljer **[!UICONTROL Remove User]**.

Mer information om hur du skapar användare och systemadministratörer i Workfront med Adobe Admin Console finns i [Hantera användare i Adobe Admin Console](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus).

## Lägga till användare i Assets Essentials produktprofiler {#add-workfront-users-assets-essentials-product-profiles}

Tilldela Workfront-användare en av följande Assets Essentials-produktprofiler:

* **[!DNL Assets Essentials]Användare** har tillgång till Assets Essentials fullständiga användargränssnitt. Dessa användare kan överföra, ordna, tagga och hitta digitala resurser i Assets Essentials. Dessutom har användarna tillgång till den inbäddade resursexemplaret i [!DNL Adobe Workfront] program.
* **[!DNL Assets Essentials]Konsumentanvändare**: har tillgång till den inbäddade upplevelsen av resursval i [!DNL Adobe Workfront] program.

Dessutom finns det också **[!DNL Assets Essentials]Administratörer** produktprofil som ger administrativ åtkomst till programmet.

Mer information om hur du tilldelar användare till Assets Essentials produktprofiler finns i [Tilldela användare till Assets Essentials produktprofiler](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Konfigurera integrering av Experience Manager Assets Essentials {#configure-assets-essentials-integration}

När du har lagt till användare i Workfront- och Assets Essentials-produktprofilerna med Admin Console kan du [konfigurera integreringen av Experience Manager Assets Essentials med Adobe Workfront](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

När du har konfigurerat integreringen kan du:

* [Länka resurser och mappar från Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [Skicka ett dokument till Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [Korrektur för en länkad resurs för Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Visa eller hämta en länkad resurs från Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
