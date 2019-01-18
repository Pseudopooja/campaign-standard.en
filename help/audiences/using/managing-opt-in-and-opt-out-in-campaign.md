---
title: Managing opt-in and opt-out in Campaign
seo-title: Managing opt-in and opt-out in Campaign
description: Managing opt-in and opt-out in Campaign
seo-description: Understand how opt-in and opt-out are managed in Adobe Campaign.
uuid: 8b079fba-2837-47f8-b58f-9048fad0eafb
contentOwner: sauviat
products: SG_CAMPAIGN/STANDARD
audience: audiences
content-type: reference
topic-tags: understanding-opt-in-and-opt-out-processes
discoiquuid: 10d6f604-3498-4c7b-b44b-3bd2d0d975f4
isreadyforlocalization: false
index: y
internal: n
snippet: y
---

# Managing opt-in and opt-out in Campaign{#managing-opt-in-and-opt-out-in-campaign}

Managing opt-in and opt-out in Campaign

## Managing opt-in and opt-out from a profile {#managing-opt-in-and-opt-out-from-a-profile}

Users can be opted in or out by an operator directly from the profile **[!UICONTROL General]** tab.

In the **[!UICONTROL No longer contact (blacklist)]** section, the selected checkboxes correspond to the channels from which the user chose to opt out. Select the channels according to the user's needs.

![](assets/optIn_landingPage_3.png)

## Setting up opt-in and opt-out landing pages {#setting-up-opt-in-and-opt-out-landing-pages}

To give users the ability to opt in or opt out, you have to create and publish a **[!UICONTROL Profile acquisition]** landing page. They will then be able to select the channels according to their needs. To do this, follow the steps below.

You can also set up a **[!UICONTROL BlackList]** landing page that will enable users to opt out from all deliveries. For more on this, refer to [Setting up a landing page to opt out from all deliveries](../../audiences/using/managing-opt-in-and-opt-out-in-campaign.md#setting-up-a-landing-page-to-opt-out-from-all-deliveries).

>[!NOTE]
>
>Landing pages can also be used to enable services subscription. For more on this, refer to [this page](../../channels/using/designing-a-landing-page.md#linking-a-form-to-a-service).

1. Create a **[!UICONTROL Profile acquisition]** landing page (see [this section](../../channels/using/about-landing-pages.md)).
1. Add a checkbox in the landing page content for each desired channel, then link it to the corresponding field from the Campaign database.

   ![](assets/optIn_landingPage_1.png)

1. Save the landing page and publish it.
1. In the landing page, the checkboxes are already selected according to the profile **[!UICONTROL General]** tab. The user can select or unselect the channels according to his needs and submit the form.

   ![](assets/optIn_landingPage_2.png)

1. Once the form submitted, the profile **[!UICONTROL General]** tab is updated according to the user's selection.

   ![](assets/optIn_landingPage_3.png)

### Setting up a landing page to opt out from all deliveries {#setting-up-a-landing-page-to-opt-out-from-all-deliveries}

To give users the ability to opt out from all deliveries, you have to create and publish a **[!UICONTROL BlackList]** landing page. For more on landing pages creation, refer to [this page](../../channels/using/about-landing-pages.md).

Once a user clicks on the landing page link, the **[!UICONTROL No longer contact (by any channel)]** option in the profile is automatically selected.

![](assets/blacklisting_allChannels.png)
