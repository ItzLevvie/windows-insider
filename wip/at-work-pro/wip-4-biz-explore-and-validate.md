---
title: Working with Preview builds 
description: Using Preview builds to explore and validate Windows
manager: eliotgra
ms.tgt_pltfrm: na
ms.devlang: na
ms.date: 11/06/2018
ms.author: v-colinmit
author: cdmm12
ms.localizationpriority: medium
ms.topic: article
ms.prod: w10
---

# Working with Windows 10 Insider Preview Builds 

Windows 10 Insider Preview Builds enable organizations to explore new features and validate apps and infrastructure compatibility well before a general Windows release. This can help accelerate your next Windows deployment and get more value out of Windows for your organization. 

![WaaS and Rings](images/trumpet2.png "ADD")

## Aligning rings to feature exploration and validation 

As part of [Windows as a service](https://docs.microsoft.com/windows/deployment/update/waas-overview), Insider Preview builds are typically released six months prior to each Semi-Annual Channel update across different release cadences or "rings”. 

Insider Preview builds in the Fast Ring are released first and contain the very latest features, making them ideal for feature exploration. Insider Preview builds in the Slow Ring are released later and are more stable than Fast Ring releases, making them better suited for validation with your apps and infrastructure. 

To support your broader Windows deployment, Microsoft recommends that all organizations have up to 1% of PCs enrolled in the Windows Insider Program. The guidance below provide suggestions for effective use of Insider Preview builds. 

### Explore new features in the Fast Ring

|   |   |
|-------|-----------|
|__Overview__|Insider Preview builds in the Fast Ring are released approximately weekly and provide the earliest access to new preview features in Windows.
|__Users__|Because Fast Ring builds often contain bugs and other issues, we recommend limiting feature exploration in your organization to IT administrators and developers running Insider Preview builds on secondary machines. 
|__Activity__| Try new features based on updates described in the [Windows Insider blog](https://blogs.windows.com/windowsexperience/tag/windows-insider-program/).<br/> Provide feedback in the Feedback Hub app. This helps us to make adjustments and enhancements to features as quickly as possible.
|__Monitoring__| Encourage users to sign into the Feedback Hub using their Azure AD work accounts. This enables you to track feedback submitted by users within your organization. (Note: This tracking is only visible to Microsoft and registered Insiders within your organization’s domain.) See [Submit and track feedback using the Feedback Hub](wip-4-biz-feedback.md).

### Validate applications and infrastructure in the Slow Ring
Early validation of application and infrastructure compatibility with Windows using Insider Preview builds in the Slow Ring has several benefits:
* Get a head start on your Windows validation process.
* Identify issues sooner to accelerate your Windows deployment.
* Engage Microsoft earlier for help with potential compatibility issues.
* Deploy Windows 10 Semi-Annual releases faster and more confidently.
* Maximize the support window that comes with each Semi-Annual release.

 |   |   |
|-------|-----------|
|__Overview__|Insider Preview builds in the Slow Ring are released approximately monthly for greater stability. These builds are supported with Quality Update service packages to fix key issues found in the Fast Ring and also receive the latest [Microsoft Security Response Center security fixes](https://msrc-blog.microsoft.com/category/msrc/). 
|__Users__|In addition to Insiders who may have participated in feature exploration in the Fast Ring, we recommend including a small group of application owners and users from each business department to ensure a representative sample. Slow Ring releases can be run on either secondary or primary production machines by skilled users.
|__Activities__|Run Insider Preview builds on representative hardware to confirm compatibility. <br/> Validate new Insider Preview builds against infrastructure to ensure machines can be managed once deployed. NOTE: Before validation, check our [Windows Insider blog](https://blogs.windows.com/windowsexperience/tag/windows-insider-program/) and [Windows Insider Tech Community](https://techcommunity.microsoft.com/t5/Windows-Insider-Program/bd-p/WindowsInsiderProgram) for updates on current issues and fixes. 
 







