---
title: "Support end for Internet Explorer | MicrosoftDocs"
description: Information about support end for Internet Explorer.
ms.service: power-platform
ms.component: pa-admin
ms.topic: conceptual
ms.date: 06/30/2021
ms.author: aorth 
author: adrianorth
ms.reviewer: jimholtz
search.audienceType: 
  - admin
search.app:
  - D365CE
  - PowerApps
  - Powerplatform
  - Flow
---
# Support end for Internet Explorer

Microsoft Internet Explorer support ends August 17th, 2021 and Microsoft Edge Legacy support ended in March 2021. This topic outlines the experience that administrators and end users will see related to the support end. 

Users moving to Microsoft Edge (based on Chromium) or another supported modern browser will have a significantly improved experience.  Microsoft Edge (based on Chromium) and Chrome are twice as fast as Internet Explorer. 

## Administrator experience 

To prepare for Internet Explorer support ending, administrators in the Power Platform Admin center and in the model-driven apps Advanced Settings will see an informational message like the following *before* August 17th, 2021 and a warning message *starting* August 17th, 2021 if their tenant has Internet Explorer users.  These messages will appear regardless of the browser the administrator is using. 

> [!CAUTION]
> Before August 17th, 2021
> Internet Explorer support will end on August 17th, 2021. Ensure users switch to a modern browser.

> [!CAUTION]
> After August 17th, 2021
> Internet Explorer support ends August 17th, 2021. Ensure users have switched to a modern browser.

## User experience 

Starting August 17th, 2021, all users using model-driven apps in Internet Explorer will see a warning message at the top of the app.  By switching to Microsoft Edge Chromium or another modern browser, the user will not see this message.  

> [!CAUTION]
> Internet Explorer support has ended. Please switch to Microsoft Edge or another modern browser.

Some users using model-driven apps in Internet Explorer might see an informational message like the following at the top of the app if their administrators have enabled it. 

> [!CAUTION]
> Internet Explorer support ends August 17th, 2021. Please switch to a modern browser.

With the 2022 Wave 1 release, users opening model-driven apps in Internet Explorer will be blocked and see a message like this. 

> [!CAUTION]
> **Unsupported Browser Version**
> Microsoft Dynamics 365's Unified Interface requires Microsoft Internet Explorer 11 or a later version. Upgrade or install Internet Explorer or a later version and try again.

Administrators wanting to block Internet Explorer for users earlier can request this through support. 

Prior to the 2022 Wave 1 release blocking Internet Explorer, users using model-driven apps in Internet Explorer will see an error message at the top of the app like the following.  

> [!CAUTION]
> Internet Explorer support has ended and will be blocked. Please switch to a modern browser.
