---
title: "設定繼承是什麼？"
titleSuffix: Intune for Education
description: "了解如何管理使用適用於教育界的 Intune 裝置群組的設定。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 388e4f4468c3184d4dd941c74f8524a6302694f3
ms.contentlocale: zh-tw
ms.lasthandoff: 07/05/2017


---

# <a name="what-is-settings-inheritance"></a>設定繼承是什麼？

設定會套用至群組。 因為群組已設定為與上面的另一個，任何設定套用至群組的一個群組的階層，會繼承其所有子群組。 這可讓您更輕鬆地將設定套用至大型的使用者、 應用程式，以及裝置群組。

  ![群組和子群組樹狀結構。](./media/groups-002-inheritance.png)

這表示，包含其下方的子群組的任何群組，子群組會自動繼承其上方的群組進行任何變更。 這稱為_繼承_。

## <a name="can-i-configure-subgroups-differently-after-inheriting-settings-from-another-group"></a>我可以設定子群組以不同的方式從另一個群組繼承設定之後？

子群組個別設定，即使它們繼承設定自其上方的群組。 您可以只設定需要的設定，然後將它們儲存覆寫至繼承的設定。

## <a name="can-i-ever-end-up-with-settings-that-do-not-work-together"></a>我曾最後會具有無法一起運作的設定嗎？

當有多個設定已套用至相同的群組時，每個設定是由適用於教育界的 Intune 個別分析。 強制使用者執行動作，讓他們的裝置符合您的設定某些設定將一律優先於其他設定。

子群組，請考慮*第十二個等級 AP 電腦科學*，群組*第十二個等級*。 您知道 AP 電腦科學類別將需要下載不需要安全性掃描、 一些 JavaScript 檔案，但您想要確定，整個等級不會嘗試執行相同的動作。 如果您不覆寫更嚴格的設定繼承*第十二個等級*設定將套用到中的使用者*第十二個等級 AP 電腦科學*。

## <a name="find-out-more"></a>深入了解

  - [在 Intune 中找的出更多有關完整群組體驗](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)

