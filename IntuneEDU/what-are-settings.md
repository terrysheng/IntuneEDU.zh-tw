---
title: "設定有哪些？"
titleSuffix: Intune for Education
description: "了解如何管理教育原則透過 Intune 設定。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: c7308ab88970c335a0c43d20f4558a54c9143fd9
ms.contentlocale: zh-tw
ms.lasthandoff: 07/05/2017



---

# <a name="what-are-settings"></a>設定有哪些？

_設定_可讓您用來定義您的使用者可以如何使用他們的裝置。 這可以修改使用者嘗試採取的動作，或只是停止執行的裝置上的使用者，裝置的回應方式。 教育設定 Intune 可讓您管理學校裝置上的功能。

設定會套用至群組。 因為群組已設定為與上述另一個群組的階層，任何[設定套用至群組會繼承其所有子群組](settings-inheritance.md)。 這可讓您更輕鬆地將設定套用至大型的使用者、 應用程式，以及裝置群組。

## <a name="manage-settings"></a>管理設定

有三種方法來管理適用於教育界的 Intune 中的設定：

* __Express 組態__： 選取的最常用的學校設定可在[Express 組態](how-do-i-manage-settings.md#manage-settings-with-express-configuration)這樣學生可以安全且更有生產力教室中使用的裝置。

* __群組__： 可以針對每個個別的群組管理的所有設定。 這是展開的相較於 Express 組態中可用的設定清單。 找出[此處可供您設定](available-settings.md)。

* __租用戶設定__： 租用戶設定會影響所有使用者和受管理的裝置。 這些設定只能與特定 admins 管理[適當的租用戶的存取層級](what-are-tenants.md)。

可以設定並指派給使用者和裝置群組設定。 已指派給群組中的使用者設定會留在那裡與使用者，無論他們用何種裝置。 不論登入裝置的裝置上，將會套用已指派給群組中的裝置設定。

## <a name="find-out-more"></a>深入了解

- [進一步了解如何保護應用程式和完整的管理體驗，在 Intune 中的資料](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)

