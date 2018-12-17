---
title: "Use case: users & security"
seo-title: "Use case: users & security"
description: "Use case: users & security"
seo-description: Discover access and security management through a step-by-step use case.
page-status-flag: never-activated
uuid: c3efe8cc-066c-4954-9bf3-718fb05b261c
contentOwner: sauviat
products: SG_CAMPAIGN/STANDARD
audience: administration
content-type: reference
topic-tags: users-e-security
discoiquuid: f1f90dae-73b1-46da-b275-1870cba07ac3
isreadyforlocalization: true
index: y
internal: n
snippet: y
---

# Use case: users & security{#use-case-users-security}

Use case: users & security

>[!NOTE]
>
>Only users with administration rights have access to the configuration of users and security groups in the Admin console and in Adobe Campaign. Note that new Campaign Standard instances, as well as existing instances with no geographical units created, cannot have the geographical unit capability implemented starting 18.7 release.

Specialized in sportswear, Geometrixx wants to open new branches across the world: one for clothes in France called Geometrixx Clothes and another one for sports equipment in New York called Geometrixx Sport.

Each branch will assign a security group composed of a geographical and organizational unit. The French team will be in charge of running the publications whereas the New York team will work on workflows only.

The goal here is to start by creating geographical and organizational units in Adobe Campaign then create a security group with the different roles along with users in the Admin console.

To do this, you must follow these 4 steps:

* Create a geographical unit
* Create an organizational unit
* Create a security group and a product profile
* Create users

## Step 1: Create a geographical unit {#step-create-a-geographical-unit}

In order to define a hierarchical structure to give users a filtered view, Geometrixx will have to assign each brand to its respective country.

The user will then have read and write access to all objects within their units.

1. From the advanced menu, via the Adobe Campaign logo, select **Administration > Users & Security > Geographical Units**.
1. Click **Create** to add a new geographical unit.
1. Change the default Label and ID to the targeted country.
1. Select a **Parent element**. For example, France will be linked to Europe.

   ![](assets/geo_unit_1.png)

1. Click **Create**.

The geographical unit is created and can now be selected in the **Access management** properties of all entities.

## Step 2: Create an organizational unit {#step-create-an-organizational-unit}

Organization units can represent different brands or departments within your organization.

In this example, we use organization units to create two brands.

1. From the advanced menu, via the Adobe Campaign logo, select **Administration > Users & Security > Organizational Units**.
1. Click **Create** to add a new organizational unit.
1. Change the default Label and ID.
1. Select a **Parent element**.

   ![](assets/org_unit_2.png)

1. Click **Create**.

The organizational units are created and can now be selected in the **Access management** properties of all entities.

## Step 3: Create and manage a security group {#step-create-and-manage-a-security-group}

The security group must first be created in the Admin console then in Adobe Campaign using the exact same configuration name in order for them to be correctly synchronized.

1. From the Admin console dashboard, select your tenant then the **Products** tab.
1. Click the **New Profile** button to create a security group.

   ![](assets/create_security_1.png)

1. Type the Profile name by following this exact syntax: **Campaign Standard- tenantname - ID chosen in Adobe Campaign**.

   Add a description to your Product profile if needed.

   ![](assets/create_security_2.png)

1. Click **Save**.
1. From the advanced menu, via the Adobe Campaign logo, select **Administration > Users & Security > Security Groups**.
1. Click **Create** to add your security group.

   ![](assets/create_security_4.png)

1. Change the **Label** and **ID**. The chosen ID has to be the same as the one used for the product profile created in the Admin console.
1. Select the previously created organizational and geographical units.
1. In the** Roles** tab, add as many roles as your team needs using the **Add element** button.

   For example, the French Geometrixx team will be assigned the Datamodel role so that they can run publications and the American team will be assigned the Workflow role to access the workflows.

   ![](assets/create_security_5.png)

1. Click save to create your security group.

Your group is now created in Adobe Campaign and in the Admin console. You can now add users to it.

## Step 4: Create users {#step-create-users}

Users can only be managed from the Admin console. They are in read-only mode in Adobe Campaign.

You can add users to your different groups and invite them to use a specific Experience Cloud product.

1. From the **Products** tab of your tenant, click the **Add user** button.

   ![](assets/create_user_1.png)

1. Type in the email address or name of the user you want to add.
1. Select the previously created product profile in the drop-down menu to assign a security group to your user.

   ![](assets/create_user_3.png)

1. Click **Save** to create your new user. 

   ![](assets/create_user_2.png)

Once created, the user will automatically be synchronized with Adobe Campaign and assigned to the security group that you created.

The two branches will not have the same access to Adobe Campaign. For example, the French team will have access to the Administration menu but only the Development option in order to access the publications.

![](assets/create_user_4.png)

Whereas the New York team will not have access to the Administration menu since they only need to create workflows. 

![](assets/create_user_6.png)
