---
title: The Home page of ISV Studio | Microsoft Docs
description: Learn about the home page capabilities provided by the ISV Studio portal.
ms.date: 04/01/2024
ms.reviewer: pehecke
author: angela21k
ms.author: angelakim
suite: powerapps
ms.topic: article
ms.subservice: developer
search.audienceType: 
  - developer
contributors: 
  - JimDaly
  - phecke 
---

# The Home page

[!INCLUDE [cc-isv-studio-deprecation](includes/cc-isv-studio-deprecation.md)]

After a user logs into the ISV Studio, they are presented with the landing page known as the *Home* page. A welcome message is displayed which defines the objective of this page.

If a user is associated with multiple publishers, all publishers are displayed and the first publisher is selected by default. All the metrics on this page are specific to the selected publisher. The user can toggle to a different publisher name to see the corresponding metrics for that publisher.

:::image type="content" source="media/isv-portal-homepage.png" alt-text="Home page":::

The Home page summary section contains the following graphs and metrics.

## Successful app package installs by tenant

The first graph visualizes the published apps and the tenants that the app's packages are installed into, and they are displayed in descending order based on the number of package installs.

When hovering over a tenant tile in the graph, the following information is shown:

1. App Name
2. Tenant Name and Tenant ID
3. Number of package installs of the app in the tenant

:::image type="content" source="media/isv-portal-homepage-graph1.png" alt-text="Package installs by tenant.":::

## Package install attempts by app (last 28 days)

This bar chart visualizes published apps and the number of successful vs. failed installations across all production environments over the last 28 days.

When hovering over an app in the graph, the following information is shown:

1. App Name
2. Status of package installation (Success vs Failures)
3. Count of package install attempts

:::image type="content" source="media/isv-portal-homepage-graph2.png" alt-text="Package install attempts by app (last 28 days).":::

## Additional insights

Below the summary section the user can access additional insights and can choose to further drill down into their install history through the lens of Certified Apps or Tenants.

**Top Certified Apps** and **Top Tenants** are visible on the page by default. The user can also select **See all** to show all the apps.

The App names and icons are from AppSource.

> [!IMPORTANT]
> With the January 2022 update, the **Total Installs** tile is now tracking the total number of unique environments where an app is installed instead of the previous cumulative total installs. While this update provides more meaningful information about an app's actual install base, the change may lead to a possible sharp drop in the install charts.

:::image type="content" source="media/isv-portal-homepage-seeall.png" alt-text="All apps.":::

### See also

[Introduction to ISV Studio for the Power Platform](index.md)<br/>
[App page](app.md)<br/>
[Tenant page](tenant.md)<br/>
[AppSource checker](appsource-checker.md)<br/>
[Connector Certification](connector-certification.md)
