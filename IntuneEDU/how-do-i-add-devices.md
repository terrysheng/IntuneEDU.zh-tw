---
title: "新增裝置"
titleSuffix: Intune for Education
description: "了解如何設定適用於教育界的 Intune 的 Windows 10 裝置。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 7b5343d996868ceaf18a58812a4db14d626d2969
ms.contentlocale: zh-tw
ms.lasthandoff: 07/05/2017


---

# <a name="how-do-i-add-devices-to-intune-for-education"></a>如何將裝置新增至 Intune，適用於教育界？

設定適用於教育界的 Intune 設定您的資訊之後，例如學生記錄、 應用程式和裝置的設定 — 您需要將裝置連接到適用於教育界的 Intune。 您可以做為新的 Windows 10 裝置的安裝體驗的一部分。


> [!NOTE]
> 您的裝置需要存取網際網路，而且您的帳戶必須擁有足夠的 Intune 裝置教育版授權，無法完成安裝程式。 您可以進一步了解這在我們[授權文件](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)。

## <a name="add-devices-to-intune-for-education"></a>將裝置新增至 Intune，適用於教育界

您必須將執行下列工作來帶入適用於教育界的 Intune 所管理的 Windows 10 裝置：

1. 開啟新的 Windows 10 裝置，並開始標準 Windows 安裝程式。 當您來到**這部電腦的擁有者是誰？**畫面上，選取**我的工作或學校擁有**。

  ![「 誰擁有此電腦嗎？ 」 的螢幕擷取畫面 Windows 安裝程式中的螢幕](./media/devices-001-who-owns-this-pc.png)

2. 在**選擇您要如何連接**畫面上，選取**加入 Azure AD**。

  ![Windows 安裝程式中的 「 選擇如何連接 」 螢幕的螢幕擷取畫面](./media/devices-002-how-you-connect-pc.png)

3. 輸入用於教育管理 Intune 的帳戶詳細資料或**其他授與權限註冊使用者**選取**下一步**。

您的裝置將[向 Azure AD](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access)而且將會收到指派的應用程式和設定安裝程式完成之後。

註冊裝置的另一種方式是透過[可用__學校電腦設定__應用程式](how-should-i-enroll-devices.md)，快速地設定使用 USB 金鑰的電腦。 

## <a name="find-out-more"></a>深入了解
- [深入了解**學校電腦設定**應用程式](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)
- [了解完整的經驗，將裝置新增至 Intune 的詳細資訊](https://docs.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune)

