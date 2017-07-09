---
title: "新增應用程式"
titleSuffix: Intune for Education
description: "了解如何將應用程式新增至適用於教育界的 Intune。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 7a2298d4a1b55d8a1355ca9e828d92c0a561eac8
ms.contentlocale: zh-tw
ms.lasthandoff: 07/05/2017


---

# <a name="how-do-i-add-apps-to-intune-for-education"></a>如何將應用程式新增至 Intune，適用於教育界？

您可以使用 Intune 適用於教育界的學校的裝置上安裝應用程式之前，這些應用程式必須加入您的 Intune 教育帳戶。

適用於教育界的 Intune 支援下列類型的應用程式：
- Web 應用程式，例如[線上 Microsoft Word](https://office.live.com/start/Word.aspx)
- 針對教育應用程式，也就是任何 Microsoft Store[透過市集散發的通用應用程式](https://technet.microsoft.com/itpro/windows/manage/apps-in-windows-store-for-business)
- 桌面應用程式，例如[獨立 Microsoft Office](https://products.office.com/products)

新增應用程式之後，您可以[安裝的應用程式](install-apps.md)上擁有的裝置群組。

設定會套用至群組，包括應用程式群組。 群組已設定為與上述另一個群組的階層，因為[指派給群組的任何應用程式會繼承其所有子群組](settings-inheritance.md)。

## <a name="add-web-apps"></a>新增 web 應用程式

A _web 應用程式_是由使用者以獨佔方式在瀏覽器存取的應用程式。 它們可輕鬆地指派，因為您只需要傳送給使用者是連結的網站，而不是將任何的安裝檔傳送給他們的裝置。

您可以指派 web 應用程式，為適用於教育界使用 Intune 的 Windows 10 裝置的 [開始] 功能表中的連結。 若要指派應用程式，您必須先將它加入 Intune 中的教育**管理應用程式**> 一節。

  ![加入新 web 應用程式頁面，提示使用者輸入的下列程序中所述的資訊。](./media/apps-001-add-webapp.png)

1. 在[適用於教育界的 Intune](https://intuneeducation.portal.azure.com)主控台中，選擇**應用程式**。

2. 在下**Web 應用程式**，選取**+ 新的應用程式**，然後輸入下列詳細資料：
 * **URL** — 您想要指派的應用程式的 URL
 * **應用程式名稱**— 在裝置上的 [開始] 功能表中顯示的應用程式名稱
 * **圖示**-上傳 PNG 或 JPG 從您的電腦，以作為應用程式圖示

3. 選擇 [儲存]。 現在準備好您的 web 應用程式。

4. 您現在可以[在裝置上安裝應用程式](install-apps.md)。

您也可以選擇隨時編輯應用程式**編輯**，以重新開啟其詳細資料頁面。

## <a name="add-desktop-apps"></a>加入桌面應用程式

您可以在上安裝桌面應用程式透過相同的介面**應用程式**頁面。 此程序類似於安裝 web 應用程式，但牽涉到 web 應用程式不需要安裝檔案。

![新的桌面應用程式畫面。](./media/apps-003-add-desktop-app.png)

1. 在[適用於教育界的 Intune](https://intuneeducation.portal.azure.com)主控台中，選擇**應用程式**。

2. 在下**桌面應用程式**，選取**+ 新的應用程式**。 這會開啟**新桌面應用程式**畫面，然後輸入下列詳細資料：
 * **應用程式檔案**-上傳應用程式的 MSI 安裝程式
 * **應用程式名稱**— 要顯示在裝置上的應用程式名稱
 * **描述**— 它是可協助您快速識別哪些應用程式的應用程式的描述
 * **發行者**— 應用程式發行者，以協助您快速識別誰開發應用程式的名稱
 * **圖示**-上傳 PNG 或 JPG 從您的電腦，以作為應用程式圖示

3. 選擇**儲存並上傳檔案**。

  ![新增新桌面應用程式畫面中，範例應用程式中，evernote 填寫所有欄位。](./media/apps-004-filled-out-desktop-app.png)

4. 應用程式將然後上傳至 Intune 教育。 上傳完成之後，您可以[在裝置上安裝應用程式](install-apps.md)。

> [!NOTE]
> 有時候您可能會遇到錯誤，指出 「 應用程式不會有安裝檔案 」 或 「 沒有應用程式安裝檔案已加入 」。 這表示檔案未正確上載。 嘗試儲存並上傳的檔案以修正這個錯誤。

## <a name="add-popular-apps"></a>新增熱門應用程式

您也快速可以從適用於教育界的 Microsoft 市集安裝受歡迎的教育性應用程式。 我們的目標是為了方便您尋找並安裝您喜愛的應用程式，為您的使用者。 因為它們是常用於教育學者，我們建議這些應用程式。 您可以找到這些應用程式，在 Express 組態中，或者在**管理應用程式**磚。

  ![表示組態中加入應用程式程序期間選擇的熱門應用程式。](./media/apps-005-popular-apps.png)

教育入口網站的 Intune 會顯示前 12 個教育 web 應用程式和前 12 個教育 Microsoft 市集教育應用程式，您尚未加入下**應用程式**管理。

> [!TIP]
> 如果您尚未設定教育帳戶將應用程式新增至 Intune，適用於教育界您 Microsoft 存放區，您可以了解如何進行這項[這裡](acquire-store-apps.md)。

1. 在[適用於教育界的 Intune](https://intuneeducation.portal.azure.com)主控台中，選擇**管理應用程式** > **新增應用程式** > **快速加入熱門應用程式**。 一份**Web 應用程式**和**Microsoft 市集應用程式**隨即出現。

  ![快速加入熱門應用程式畫面。](./media/apps-006-add-popular-apps.png)

2. 選取您想要新增，然後選擇 應用的程式**新增應用程式**。

  ![選取要加入至入口網站的多個熱門應用程式。](./media/apps-007-select-multiple-popular-apps.png)

3. 您的應用程式會在背景中加入，以及出現在左提要欄位中準備就緒時。

  ![您的應用程式加入螢幕。](./media/apps-008-your-popular-apps-are-being-added.png)

## <a name="find-out-more"></a>深入了解

- [進一步了解管理使用 Intune 的應用程式的完整體驗](https://docs.microsoft.com/intune/deploy-use/add-apps)

