---
title: The user name or password is incorrect when you use connect-MSOLService
description: Fixes an issue in which you receive an error when you use connect-MSOLService to connect to Office 365.
author: MaryQiu1987
manager: dcscontentpm
localization_priority: Normal
search.appverid: 
  - MET150
audience: ITPro
ms.topic: troubleshooting
ms.author: v-maqiu
ms.custom: CSSTroubleshoot
appliesto: 
  - Cloud Services (Web roles/Worker roles)
  - Azure Active Directory
  - Office 365
  - Microsoft Intune
  - CRM Online via Office 365 E Plans
  - Azure Backup
  - Office 365 User and Domain Management
  - Office 365 Identity Management
ms.date: 3/31/2022
---

# "The user name or password is incorrect" when you use connect-MSOLService to connect to Office 365

[!INCLUDE [Branding name note](../../../includes/branding-name-note.md)]

## Problem 

When you try to use the connect-MSOLService cmdlet in the Microsoft Azure Active Directory Module for Windows PowerShell to connect to a Microsoft cloud service such as Microsoft Office 365, Azure, or Microsoft Intune, your attempt is unsuccessful. Additionally, you may receive the following error message:

**Connect-MsolService : The user name or password is incorrect. Verify your user name, and then type your password again.**

## Cause 

This issue may occur if the user name or password that you're using is incorrect or if there's a problem with the user account. 

## Solution 

To resolve this issue, see [You can't sign in to your organizational account such as Office 365, Azure, or Intune](https://support.microsoft.com/help/2412085).

## More information 

Still need help? Go to [Microsoft Community](https://answers.microsoft.com/) or the [Azure Active Directory Forums](https://social.msdn.microsoft.com/forums/azure/home?forum=windowsazuread) website.