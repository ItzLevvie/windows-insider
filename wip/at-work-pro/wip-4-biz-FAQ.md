---
title: Windows Insider Program for Business Frequently Asked Questions
description: Answers to your commonly asked Windows Insider Program for Business questions
author: arshields7
manager: arshields7
ms.topic: article
ms.prod: w10
ms.tgt_pltfrm: na
ms.devlang: na
ms.date: 10/24/2017
ms.author: arshields7
ms.localizationpriority: medium
---

# Windows Insider Program for Business Frequently Asked Questions
**Are the Windows Insider Program and Windows Insider Program for Business separate programs?**

No, in fact just the opposite. The Windows Insider Program was created in 2014 to help Microsoft engage with Windows Fans worldwide. Windows Insiders are the first to be able to try new Windows features that we introduce through Windows 10 Insider Preview Builds. At the same time, they can provide feedback through the Feedback Hub App which helps create even better versions of Windows for all users. The Windows Insider Program for Business enables you to incorporate Insider Preview builds into your deployment plans using your corporate credentials, deepen connections with the IT Pro community, collect feedback within your organization, and increase the visibility of your organization’s feedback – especially on features that support productivity and business needs. Together we can resolve blocking or critical issues to better support your organization’s needs sooner. Incorporating the Windows Insider Program for Business into your deployment plans enables you to prepare your organization for the next update of Windows 10, to deploy new services and tools more quickly, to help secure your applications, and to increase productivity and confidence in the stability of your environment. Windows Insider Program for Business participants collaborate with the Windows team to build and document features, infuse innovation, and plan for what’s around the bend. We’ve architected some great features together, received amazing feedback, and we’re not done.

**What Languages are available?**

Insider Preview builds are available in the following languages: 

English (United States), English (United Kingdom), Chinese (Simplified), Chinese (Traditional), Portuguese (Brazilian), Japanese, Russian, German, French, French (Canada), Korean, Italian, Spanish, Spanish (Latin America), Swedish, Finnish, Turkish, Arabic, Dutch, Czech, Polish, Thai, Catalan, Hindi, and Vietnamese

If your Windows build is not in one of the available base languages, you will not receive Insider Preview builds.

Hindi, Catalan, and Vietnamese can only be installed as a language pack over supported base languages.

> [!NOTE] 
> To learn how to install a language pack, see How to add an input language to your PC Additional.

**How do I register for the Windows Insider Program for Business?**

To register for the Windows Insider Program for Business, follow the steps below using your corporate account in Azure Active Directory (AAD). This account is the same account that you use for Office 365 and other Microsoft services. Check with your IT department before signing up.

1. Visit the [Windows Insider Program website](https://insider.windows.com) and select **Get Started**.

2. Sign-in with your corporate account in AAD (username/password) and follow the on-screen registration directions.

3. Enroll your Windows 10 PC to get the latest Windows 10 Insider Preview builds. Go to **Settings > Updates & Security > Windows Insider Program**. Select **Get Started**, enter your corporate credentials that you used to register, then follow the on-screen directions.

> [!NOTE] 
> Make sure that you have administrator rights to your machine and that it has latest Windows updates.

**Are there any management capabilities that allow an IT admin to manage settings for a corporate environment?**

Yes. Starting with Windows 10, version 1709, the Windows Insider Program for Business now enables administrators to apply the following group policies to help them manage their organization’s preview builds:

**Manage preview builds:** Administrators can enable or prevent builds from installing on a device. You also have an option to disable preview builds once the release is public.
**Branch Readiness Level:** Administrators can set the Windows readiness level, including Fast, Slow, Release Preview Rings of Windows Insider Preview) and allows administrators to defer or pause delivery of updates.

See more information on [Getting started with Windows Insider Program for Business](https://docs.microsoft.com/en-us/windows-insider/at-work-pro/wip-4-biz-get-started).

**How can I find out if my corporate account is on Azure Active Directory?**
On your PC, go to **Settings > Accounts > Access work or school**. If your organization has set up your corporate account in Azure Active Directory, and it is connected to your PC, you will see the account listed as highlighted in this image:

![alt text](https://docs.microsoft.com/en-us/windows/deployment/update/images/waas-wipfb-work-account.jpg "Device connected to work account")

**I have more than one Azure Active Directory account. Which should I use?**

Register for Windows Insider Program for Business with the same active account that you use to access your corporate email in Office 365 and other Microsoft services. To ensure you get the most benefit out of the Windows Insider Program for Business and that your company is fully represented, do not set up a separate tenant for testing activities. There will be no modifications to the AAD tenant to support Windows Insider Program for Business, and it will only be used as an authentication method.

**Can I register multiple users from my organization at the same time for the Windows Insider Program for Business?**

Yes. The Windows Insider Program for Business now allows organizations to register their domain and control settings centrally rather than require each user to register individually for Insider Preview builds. To register, follow the instructions on the [Register for the Windows Insider Program for Business](https://docs.microsoft.com/en-us/windows-insider/at-work-pro/wip-4-biz-register) page.

**My account is listed in Active Directory but not Azure Active Directory. Can I still register using my Active Directory credentials?**

No. At this point, we are only supporting Azure Active Directory as a corporate authentication method. If you’d like to suggest or upvote another authentication method, visit our [Answers forum](https://answers.microsoft.com/en-us/insider/forum).

**I just want to participate as a Windows Insider. Do I still need to register with my corporate account in Azure Active Directory?**

No. You can join the Windows Insider Program using your Microsoft account (MSA) with these [instructions on getting started](https://docs.microsoft.com/en-us/windows-insider/at-home/get-started). 

However, please note that if you want to access the benefits of the Windows Insider Program for Business, you will need to sign-up using your corporate account in Azure Active Directory. Check with your IT department before signing up with your corporate account.

**I am already a Windows Insider. I want to switch my account from my Microsoft account to my corporate account in Azure Active Directory. How can I do this?**

In just a few steps, you can switch your existing program registration from your Microsoft account to your corporate account in Azure Active Directory.

1. Visit the [Windows Insider Program website](https://insider.windows.com). If you're signed in with your Microsoft account, sign out then sign back in to register with your corporate account in AAD.
2. On your Windows 10 PC, go to **Settings > Updates & Security > Windows Insider Program**.
3. In your account, under Windows Insider account, select **Change** to open a pop-up box.
4. Select your corporate account and select Continue to change your account.

> [!NOTE] 
> Your corporate account must be connected to the device for it to appear in the account list.

**How do I sign into the Feedback Hub with my corporate credentials?**

Sign in to the Feedback Hub using the same AAD account you are using to flight builds.

**Am I going to lose all the feedback I submitted and badges I earned with my MSA?**

No. However, your feedback will not be transferred from your MSA to your AAD account. You can switch back to your MSA account in the Feedback Hub to access feedback you’ve submitted and badges you’ve earned.

**How is licensing handled for Windows 10 Insider builds?**

All PCs need to have a valid Windows 10 license. This requirement applies whether a device joins the Windows Insider Program using a Microsoft account or an Azure Active Directory account.

**Can I use the Software in a live operating environment?**

The software is a pre-release version, and we do not recommend that organizations run Windows Insider Preview builds outside of their test environments. This software may not work the way a final version of the software will. We may change it for the final, commercial version. We also may not release a commercial version.

**Can a single MSA or AAD account be used to register more than one PC in the program?**

Yes. If each PC has a valid Windows 10 or Windows 10 Mobile license you can use your MSA on as many devices as you’d like. However, the main concern would be that your feedback all looks like it comes from a single user. If multiple devices are experiencing problems with a build, you’ll want the ability to submit the same feedback from multiple people (or upvote the same piece of feedback.)
