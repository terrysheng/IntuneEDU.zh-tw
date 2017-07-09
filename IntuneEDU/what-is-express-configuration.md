---
title: "什麼是 Express 組態？"
titleSuffix: Intune for Education
description: "使用 Express 設定來快速地設定您在適用於教育界的 Intune 中的群組。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 796782e6c0cf9fa975bd9c8f3a94314bb00d8d89
ms.contentlocale: zh-tw
ms.lasthandoff: 07/05/2017


---

# <a name="what-is-express-configuration"></a>什麼是 Express 組態？

您會看到當您第一次登入 Intune 適用於教育界的圖格的其中一個快速設定。

  ![Express 設定並排顯示，指出啟動 Express 設定-按一下這裡，以選擇應用程式和群組的設定。](./media/express-config-001-launch-tile.png)

快速組態，可協助您快速地提供給使用者和裝置的應用程式和所需的設定。 它不是，您只能只使用一次。每當您想要變更任何您所管理的群組，您可以使用它。 我們選擇某些應用程式，我們認為您的預設設定有所助益。 您可以變更這些選擇，以符合您的需求。

## <a name="choose-a-group"></a>選擇群組

您會先選取要設定的群組。

  ![選擇群組畫面，要求使用者選取的群組。](./media/express-config-004-choose-group.png)

A_群組_在 Intune for 教育是裝置或使用者，並組織以便於了解誰或您要在主控台中設定的集合。 這可能是裝置 (例如_第六個等級電腦購物車_) 或使用者 (例如_第四個年級的學生_或_生物學老師_)。 適用於教育界的 Intune 隨附預設群組，根據您提供的學校資訊。 我們有群組中可用的詳細資訊我們[群組文章](what-are-groups.md)。

我們建議您先指派設定，您知道**所有使用者**必須，例如密碼需求，或封鎖快顯視窗的 Microsoft Edge。

選取群組的設定，然後選擇 **下一步**才能繼續。

## <a name="choose-apps"></a>選擇應用程式

現在，您會選擇要指派給這個群組的應用程式。

  ![應用程式指派 畫面中。 應用程式會依不同的類型，包括 web 應用程式及 Microsoft Store 教育應用程式的作業。](./media/express-config-005-choose-apps.png)

有幾種可以安裝在裝置的應用程式：

* [Web 應用程式](how-to-add-apps.md#add-web-apps)
* [桌面應用程式](how-to-add-apps.md#add-desktop-apps)
* [Microsoft 市集教育應用程式](acquire-store-apps.md)

適用於教育界的 Intune 也會顯示[熱門應用程式，從 Microsoft 儲存區適用於教育界](how-to-add-apps.md#add-popular-apps)從跨所有 Intune 教育使用者。

選取要指派到這個群組中，然後選擇 應用程式**下一步**才能繼續。

## <a name="choose-settings"></a>選擇設定

接下來，您會選擇您想要套用至裝置或使用者群組中的設定。

  ![選擇 [設定] 畫面中。 設定會組織成的摺疊的清單，包括例如裝置共用、 基本裝置設定、 應用程式設定、 瀏覽器設定，以及多個分區。](./media/express-config-006-choose-settings.png)

快速組態會顯示設定，您可能想要取得您準備就緒的群組。 我們選擇這些設定，以方便您快速開始使用其裝置的使用者。 您沒有進行任何修改，如果您想要使用我們的建議，或您可以自訂這些設定，以符合特定需求。

您可以變更 Express 組態選擇在任何時間，以符合您需要進行，任何變更，並自訂您更進一步使用完整的設定[可用設定清單的一部分適用於教育界的 Intune](available-settings.md)。

## <a name="finish-up"></a>完成

在您選取之後，您有機會檢閱應用程式和您所選擇的設定。 然後您可以選擇**完成**按鈕，或返回以任何步驟，以修改這些設定。

  ![檢閱您選擇的螢幕。 它會顯示應用程式和 Express 設定期間選取的設定。](./media/express-config-007-save-changes.png)

選擇之後**完成**，您可以**設定多個群組**或**全部完成**。

  ![[完成] 畫面中。 它會顯示設定多個群組和已完成的選項。 完成的所有選項都提供處理程序，包括新增到 Intune，適用於教育界的裝置，方式是將它們加入 Azure Active Directory 中的下一個的簡短的說明。](./media/express-config-008-all-done.png)

當您完成之後時，您將前往教育儀表板的 Intune 可以繼續管理您的裝置、 使用者和應用程式。 您可以返回 Express 組態隨時從儀表板或導覽功能表來加入、 移除或修改應用程式和設定的任何群組。

## <a name="next-steps"></a>後續步驟

您已設定您的應用程式和所需的設定群組之後，您已準備好開始使用適用於教育界搭配 Intune 的裝置。

## <a name="find-out-more"></a>深入了解
- [進一步了解 Intune 中的完整管理體驗中可用的設定](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)

