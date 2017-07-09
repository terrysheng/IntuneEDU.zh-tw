---
title: "群組有哪些？"
titleSuffix: Intune for Education
description: "了解如何管理裝置與 Intune 適用於教育界的群組。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 925fee7b2807a340d2b4d0e1e9aa4ca069875f84
ms.contentlocale: zh-tw
ms.lasthandoff: 07/05/2017


---

# <a name="what-are-groups"></a>群組有哪些？

您使用_群組_來管理使用者、 應用程式，以及適用於教育界的裝置在 Intune 中。 您可以在使用者或裝置在一起，而不必個別管理每個裝置群組。 這可讓您輕鬆地將應用程式和設定指派給大量的使用者和裝置。

當您建立群組時，請考慮如何套用的設定和應用程式給使用者和裝置。 例如，您可能要禁止使用定位服務所有裝置的應用程式。 一種替代方法是如何特定群組可能需要某些動作，例如提供學生都[AP 電腦科學](https://www.tealsk12.org)編輯其程式碼的應用程式。

設定會套用至群組。 群組已設定為與上述另一個群組的階層，因為[任何設定套用至群組會繼承其所有子群組](settings-inheritance.md)。 這可讓您更輕鬆地將設定套用至大型的使用者、 應用程式，以及裝置群組。

適用於教育界的 Intune 會自動建立__所有裝置__和__所有使用者__時建立您的租用戶。 這些預設群組代表範圍最廣泛的類別目錄的使用者和裝置在您的學校或學區和[無法移動](what-are-groups.md#why-cant-i-move-certain-groups)。


## <a name="managing-groups-and-subgroups"></a>管理群組和子群組

您可以建立群組，請瀏覽至**群組**，然後選取**建立群組**從群組清單的頂端。 您可以建立，以進一步組織群組*子群組*下任何群組中，除了__所有裝置__或__所有使用者__。

  ![建立子群組頁面上，子群組建立的兩個位置 — 群組名稱和 [資訊看板] 頂端，以紅色轉動一](./media/groups-007-create-subgroup.png)

1. 在[教育主控台 Intune](https://intuneeducation.portal.azure.com)，選取**管理使用者和裝置群組**。
2. 選取您想要建立子群組其下方的群組。
3. 按一下**建立子群組**，然後輸入**群組名稱**。

## <a name="making-changes-to-groups"></a>變更群組

在您建立群組後，很可能您要編輯其成員資格 — 比方說，如果需要將裝置傳送到您的地區中的另一個學校。

  ![編輯群組中的裝置](./media/groups-008-edit-group-membership.png)

1. 選取您想要編輯其成員的群組。
2. 選取**裝置** 索引標籤。
3. 選取**編輯裝置**按鈕，然後選擇 **新增裝置**從清單中加入更多裝置或**X**旁邊的裝置，將它刪除。

如果您要重新命名群組，請選取 需要重新命名的群組則**重新命名**按鈕來編輯名稱。

## <a name="move-a-group"></a>移動群組

您可以移動您的群組結構內的群組或**階層**。

  ![移動群組 按鈕以紅色轉動一](./media/groups-010-move-groups.png)

1.  在[教育入口網站的 Intune](https://intuneeducation.portal.azure.com)，選擇**管理群組**。
2. 選取要移動的群組。
3.  按一下**移動群組**功能表清單中，或選擇**移動群組** 按鈕。
4.  選取您要搜尋的群組名稱，或選取階層中移動群組的群組位置。
5.  選取**確定**以儲存變更。

## <a name="why-cant-i-move-certain-groups"></a>為什麼無法移動特定群組？

適用於教育界的 Intune 提供一組預設群組，所以無法移動的**所有使用者**和**所有裝置**，當您[建立租用戶](what-are-tenants.md)。 **所有的老師**和**所有學生**學校的資料同步處理已經資料匯入 student 與老師適用於教育界的 Intune 之後所建立的預設群組。

很少，這可能會造成的問題，可能會包含兩個群組下方的子群組。

  ![在多個群組的錯誤訊息的子群組隨即出現](./media/groups-012-subgroup-is-under-two-groups-warning.png)

如果發生這種情況，您必須選擇單一群組，將放在這個子群組上方。

## <a name="delete-a-group"></a>刪除群組

當您刪除群組時，適用於教育界的 Intune 中移除應用程式和設定的任何裝置，該群組的成員的集合。 刪除群組不會移除這些使用者或裝置管理。

  ![刪除群組轉動一以紅色標示的按鈕](./media/groups-011-delete-groups.png)

1.  在[教育入口網站的 Intune](https://intuneeducation.portal.azure.com)，選擇**管理群組**。
2. 選取您想要刪除的群組
3.  按一下**刪除群組**工作清單中。

## <a name="find-out-more"></a>深入了解

- [進一步了解完整的群組管理體驗，在 Intune 中](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)

