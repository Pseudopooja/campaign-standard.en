---
title: Selecting an audience in a message
seo-title: Selecting an audience in a message
description: Selecting an audience in a message
seo-description: "Step-be-step procedure to choose audiences of an email: main target population and test profiles."
uuid: 6b5cb212-52b8-40ab-82d8-646a91735b42
contentOwner: sauviat
products: SG_CAMPAIGN/STANDARD
audience: audiences
content-type: reference
topic-tags: managing-audiences
discoiquuid: dbf6e982-126d-4295-839a-7d47d9284731
isreadyforlocalization: false
index: y
internal: n
snippet: y
---

# Selecting an audience in a message{#selecting-an-audience-in-a-message}

Selecting an audience in a message

Adobe Campaign lets you configure several profile types within a message's audience.

Audiences can be defined when creating the message via the creation wizard or from the message dashboard if the message has already been created.

>[!NOTE]
>
>If the audience has been built within a workflow and enriched with additional data, you will not be able to use these data to personalize a standalone delivery. They can only be used from a delivery executed in a workflow.

1. From the dashboard, go to the audience block to start.

   ![](assets/delivery_audience_definition_1.png)

   The screen to define the audiences then opens. It has two tabs that allow you to separately define each type of audience that will receive the message:

    * Target
    * Test profiles

   ![](assets/delivery_audience_definition_2.png)

1. Define the main **[!UICONTROL Target]** of the email. This is the regular target audience of the email.

   The target is defined in the **[!UICONTROL Target]** tab and is made up of identified profiles from your database.

   You can establish your main target using the [query editor](../../automating/using/editing-queries.md#creating-queries) functionalities.

   In this tab, the **[!UICONTROL Shortcuts]** palette only contains predefined filters and the audiences that have been defined in the identified profiles. The **[!UICONTROL Explorer]** tab allows you to access additional configurations.

   You can therefore re-use and combine existing audiences, apply additional filters to them, etc.

1. Define the **[!UICONTROL Test profiles]** you want to use for the email. The test profiles will receive the proofs that you can send before to test the email before sending it to the main target.

   For more information on configuring test profiles, refer to the [Test profiles](../../sending/using/managing-test-profiles-and-sending-proofs.md) section.

The audiences block is then updated and shows that a target and test profiles have been selected for the email in question.

![](assets/delivery_audience_definition_3.png)
