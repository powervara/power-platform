---
title: "Preview: Capacity add-ons for PowerApps and Flow  | MicrosoftDocs"
description: Introducing a new way to add capacity to your environments.
ms.date: 08/08/2019
ms.reviewer: 
ms.service: "power-platform"
ms.topic: "quickstart"
author: jimholtz
ms.author: jimholtz
manager: kvivek
search.audienceType: 
  - admin
search.app: 
  - D365CE
  - PowerApps
  - Powerplatform
---
# Preview: Capacity add-ons

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]

If your organization has purchased capacity add-ons, you have to allocate that capacity to any environment where you want to use it. You also have to make sure that your users have access to those environments and have the correct permissions before they can use the products for which you've purchased a capacity add-on.

> [!IMPORTANT]
> Capacity is allocated to environments, not to individual users. To provide capacity to a specific user, you have to allocate capacity to an environment where that user has access.

## View capacity add-ons in Power Platform Admin center

If your organization has purchased capacity add-ons, an **Add-ons** tile appears on the **Capacity** screen in the [Power Platform Admin center](https://admin.powerplatform.microsoft.com/). Sign into the Admin center, and select **Analytics > Capacity** in the left-side navigation pane.

The **Add-ons** tile shows summary information about the capacity add-ons that your organization has.

![Add-on tile](media/add-on-tile2.png "Add-on tile")

Each capacity has a usage gauge that shows how many units have been assigned compared to the available capacity. Capacities are measured in different ways depending on the product. For example, App passes are assigned individually, while AI Builder capacity is measured in credits. Refer to the product documentation for more information about metering.

## Allocate or change capacity in an environment

To allocate capacity to an environment:

1. Sign into the [Power Platform Admin center](https://admin.powerplatform.microsoft.com/). 
1. Select **Analytics > Capacity** in the left-side navigation pane.
1. On the **Capacity** screen, do one of the following things to open the **Manage add-ons** screen:
    - Select **Manage** on the top-right area of the **Add-ons** tile.
    - At the top area of the **Capacity** screen, select **Add-ons**, and then select **+Add to an environment** at the top of the screen.
4. Select the environment where you want to add capacity from the **Environment** drop-down menu, and then allocate from your available capacity.
![Manage add-ons](media/manage-add-ons.png "Manage add-ons")

## Permissions

In order for a user to have access to allocated capacity, an administrator for your organization has to assign that user to the environment with the correct permissions.