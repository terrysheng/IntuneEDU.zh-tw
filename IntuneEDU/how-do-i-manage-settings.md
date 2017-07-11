---
title: "如何管理設定？"
titleSuffix: Intune for Education
description: "請遵循下列步驟以管理透過 Intune 教育原則設定。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 20c0f6c9-f1de-4048-aa96-5b0a068c1b75
searchScope:
- IntuneEDU
.md#ms.tgt_pltfrm: 
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: a8a9619476315459d49dc128e14c3bc0f2f7794e
ms.contentlocale: zh-tw
ms.lasthandoff: 07/05/2017



---

<a id="how-do-i-manage-settings" class="xliff"></a>

# 如何管理設定？

您可以管理各種不同的使用者、 應用程式及使用 Intune 的裝置設定。 它是您將會變更裝置將如何回應使用者動作的方式。

設定會套用到裝置群組，使用者會受到影響時從該群組存取裝置。 如果設定會套用到使用者群組，

裝置的設定套用至群組中的所有裝置。 設定**未設定**允許使用者定義其設定在他們自己的裝置。

<a id="manage-settings-for-groups" class="xliff"></a>

## 管理群組設定

您可以使用下列步驟來管理適用於教育界的 Intune 中設定的完整清單：
1. 在[適用於教育界的 Intune](https://intuneeducation.portal.azure.com)主控台中的，在左側瀏覽功能表中，選擇**群組**。
2. 選取您想要管理其設定的群組。 如需完整清單，請參閱[可用的設定](what-are-settings.md)。
3. 按一下**設定**頁面以檢視可用設定的完整清單頂端。
4. 展開類別，並修改所選群組的個別設定。
5. 按一下**儲存**儲存該群組的變更。 設定會自動傳送至該群組中的裝置。

<a id="manage-settings-with-express-configuration" class="xliff"></a>

## 管理使用 Express 設定的設定

快速組態，可以方便您迅速開始使用，但也可協助您進行快速變更到您的裝置。

  ![表示組態設定修正](./media/express-config-006-choose-settings.png)

1. 在[適用於教育界的 Intune](https://intuneeducation.portal.azure.com)主控台中，選擇**啟動 Express 組態**。 檢閱 **褖畫惎**頁面上，然後選擇 **開始**。
2. 檢閱**取得學校資訊**頁面。 如果您已新增學校資訊，請選擇**下一步**。
3. 選取您想要管理，然後選擇 設定值的群組**下一步**。
4. 檢閱應用程式的清單，然後選擇**下一步**。
5. 在**設定**頁面上，依序展開 可用的設定類別目錄：
  * [基本裝置設定](available-settings.md#basic-device-settings)
  * [Microsoft Edge 設定](available-settings.md#microsoft-edge-settings)
  * [裝置更新設定](available-settings.md#device-update-settings)
  * [無線設定](available-settings.md#wireless-settings)
  * [應用程式設定](available-settings.md#app-settings)
  * [登入設定](available-settings.md#sign-in-settings)

  展開類別目錄，並切換以修改設定，然後選擇控制項**下一步**。

6. 檢閱您的選擇，然後選擇**完成**儲存您的變更更新它們在所選群組中的裝置上。

<a id="can-i-ever-have-settings-that-dont-work-together" class="xliff"></a>

## 不可以有無法一起運作的設定嗎？

它有可能不相容的設定套用至相同的群組。 這些 inconsistences 造成錯誤，當使用者或裝置正在設定具有不同設定的多個位置。 這會因使用者或裝置多個群組的成員。

比方說，Esperanza 所屬*第 6 等級*群組，並也是稱為群組成員*地球科學*。 如果您設定首頁，並將指派給*第 6 等級*，而且您設定不同的首頁上的設定，並將它指派給*地球科學*，她現在有兩個衝突的首頁設定指派給其使用者。 這樣會造成不一致的設定指派導致錯誤。 您可以找到哪些裝置和使用者已使用的設定錯誤[設定錯誤報告](what-are-reports.md)。

<a id="find-out-more" class="xliff"></a>

## 深入了解

- [進一步了解在 Intune 中的完整的原則管理體驗](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)

