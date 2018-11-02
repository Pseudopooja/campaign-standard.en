---
title: About opt-in and opt-out in Campaign
seo-title: About opt-in and opt-out in Campaign
description: About opt-in and opt-out in Campaign
seo-description: Opt-out (or blacklist) results in a profile no longer being targeted by any delivery or by deliveries from a specific channel.
uuid: d671f1da-f66d-4eb8-8b8a-f658c27f2c01
content-encoding: ISO-8859-1
aemsrcnodepath: /content/help/en/campaign/standard/audiences/using/about-opt-in-and-opt-out-in-campaign
contentOwner: sauviat
cq-designpath: /etc/designs/help
cq-lastmodified: 2018-07-25T09 29 19.518-0400
cq-lastreplicated: 2018-07-23T05 55 34.320-0400
cq-lastreplicatedby: sauviat
cq-lastreplicationaction: Activate
products: SG_CAMPAIGN/STANDARD
audience: audiences
content-type: reference
topic-tags: understanding-opt-in-and-opt-out-processes
cq-template: /apps/help/templates/article-3
discoiquuid: a8856a79-ff1c-4f0d-a35d-45d0f3a78c6b
firstPublishExternalDate: 2018-07-23T05:55:34.189-0400
herogradient: light
isreadyforlocalization: false
jcr-created: 2018-05-07T07 29 07.735-0400
jcr-createdby: admin
jcr-description: About opt-in and opt-out in Campaign
jcr-ischeckedout: true
jcr-language: en_us
lastPublishExternalDate: 2018-07-23T05:55:34.189-0400
lochandoffdate: 2018-07-25T09 29 19.517-0400
loclangtag: locales fr;locales de;locales ja
lr-lastreplicatedby: sauviat@adobe.com
navTitle: About opt-in and opt-out in Campaign
publishexternaldate: 2018-07-23T05 55 34.189-0400
publishExternalURL: https://helpx.adobe.com/campaign/standard/audiences/using/about-opt-in-and-opt-out-in-campaign.html
sha1: 2d85be0110d3ef79fdb93351d11a214530617491
topicBrowsingSortDate: 2018-07-23T05:55:34.189-0400
index: y
internal: n
snippet: y
---

# About opt-in and opt-out in Campaign

About opt-in and opt-out in Campaign

Opt-out (or blacklist) results in a profile no longer being targeted by any delivery or by deliveries from a specific channel.

To give profiles the ability to opt in or opt out, you have to create a dedicated landing page. For more on this, refer to [Setting up opt-in and opt-out landing pages](../../audiences/using/managing-opt-in-and-opt-out-in-campaign.md#setting-up-opt-in-and-opt-out-landing-pages).

Profiles can also be opted in or out manually by an operator. For more on this, refer to [Managing opt-in and opt-out from a profile](../../audiences/using/managing-opt-in-and-opt-out-in-campaign.md#managing-opt-in-and-opt-out-from-a-profile).

Opt-out profiles are automatically excluded during the delivery analysis in order to speed up deliveries (the error rate has a significant effect on delivery speed).

>[!NOTE]
>
>Opt-out applies to **Profiles**, as opposed to quarantine which is linked to an **email address** or **phone number**. Opting out a profile will therefore exclude from deliveries all the addresses linked to it. If a user has two profiles in the database, he will still be targeted by deliveries as only one of his profiles is opt-out. To make sure all his adresses are excluded, add them to the quarantines addresses. For more on this, refer to [this page](../../sending/using/understanding-quarantine-management.md#identifying-quarantined-addresses-for-the-entire-platform).

For more on services subscriptions, refer to [this page](../../audiences/using/about-subscriptions.md).