---
title: 新增錢包
description: 向 ethereum.org 上新增錢包時使用的政策
lang: zh-tw
---

# 新增錢包 {#adding-wallets}

我們希望確保展示各種錢包，涵蓋它們所有不同功能，讓使用者可以放心使用以太坊。

任何人都可以建議向 ethereum.org 新增錢包。 如我們遺漏了某個錢包，請提出建議！

目前所有錢包都列於：

- [ethereum.org/wallets/find-wallet/](/wallets/find-wallet/)

以太坊中的錢包日新月異。 我們嘗試在 ethereum.org 上創建一個公平的考量框架，但納入標準會隨時間推移而變化和發展。

## 決策框架 {#the-decision-framework}

### 納入標準：必備條件 {#the-must-haves}

- **經過安全測試的產品** - 無論是透過審核、內部安全團隊、開源編碼或其他方法，你的錢包的安全性都必須可靠。 這將降低我們的使用者面臨的風險，並向我們表明你非常重視安全性。
- **錢包已「上線」超過六個月或由具有良好記錄的團體發布** - 這是安全性的另一指標。 六個月是發現嚴重錯誤和漏洞的最佳時間窗口。 我們要求六個月的時間，來幫助篩選出那些作為專案很快就被放棄的分叉。
- **由活躍的團隊開發** - 這有助於確保品質，並讓使用者的查詢得到支援。
- **上架資訊真實準確** — 專案的任何提議上架產品都應包含真實準確的資訊。 如果偽造產品的上架資訊，例如聲稱產品為「開源」產品但事實並非如此，該產品將被移除。
- **聯絡人** - 實施變更時，錢包的聯絡人將大力幫助我們獲得準確資訊。 這樣將在日後收集資訊時，確保 ethereum.org 的更新可控。
- **EIP-1559（第 2 類）交易** - 你的錢包必須支援 EIP-1559（第 2 類）交易，才能在以太坊主網上進行交易。
- **良好的使用者體驗** - 雖然使用者體驗是主觀的，但如果多位核心團隊成員在測試產品後，發現產品難以使用，我們保留拒絕該錢包的權利，並會提供有用的改進建議。 這樣做是為了保護我們的使用者群，因為它主要由初學者組成。

### 產品移除 {#product-removals}

- **更新資訊** - 錢包提供者有責任每 6 個月重新提交錢包資訊，以確保其有效性和相關性（即使他們的產品沒有變化）。 如果產品團隊未能這麼做，ethereum.org 或會從頁面上移除該專案。

### 其他標準：加分項 {#the-nice-to-haves}

- **全球皆可存取** - 你的錢包沒有地域限製或身分驗證 (KYC) 要求，以免某些人無法存取你的服務。
- **支援多種語言** - 你的錢包已經翻譯成多種語言，讓全球使用者都能存取它。
- **開源** - 你整個專案的程式碼庫（不只是模組）應可被存取，並且你應該接受來自更廣泛社群的拉取請求。
- **非託管模式** - 使用者可以控制自己的資金。 如果你的產品消失，使用者仍然可以存取和轉移他們的資金。
- **支援硬體錢包** - 使用者可以連接硬體錢包來簽署交易。
- **WalletConnect** - 使用者可以使用 WalletConnect 連接到去中心化應用程式。
- **匯入以太坊遠端程序呼叫 (RPC) 端點** - 使用者可以匯入節點遠端程序呼叫資料，讓它們連接到自己選擇的節點或其他以太坊虛擬機相容網路。
- **非同質化代幣** - 使用者能夠查看錢包中的非同質化代幣並與之互動。
- **連接到以太坊應用程式** - 使用者能夠連接並使用以太坊應用程式。
- **質押** - 使用者可以直接透過錢包質押。
- **兌換** - 使用者可以透過錢包兌換代幣。
- **多鏈網路** - 你的錢包預設支援使用者存取多個區塊鏈網路。
- **二層網路** - 你的錢包預設支援使用者存取二層網路。
- **自訂燃料費** - 你的錢包允許使用者自訂其交易燃料費（基本費用、優先費和最高費用）。
- **支援以太坊名稱服務** - 你的錢包允許使用者傳送交易到 ENS 名稱。
- **支援 ERC-20** - 你的錢包允許使用者匯入 ERC-20 代幣合約，或自動查詢並顯示 ERC-20 代幣。
- **購買加密貨幣** - 你的錢包支援使用者直接購買和操作加密貨幣。
- **以法幣出售** - 你的錢包支援使用者以法幣出售加密貨幣，並直接以法幣提款到銀行卡或銀行帳戶。
- **多重簽名** - 你的錢包支援多重簽名來簽署交易。
- **社交恢復** - 你的錢包支援守護人功能，當使用者遺失了種子助記詞，可以透過守護人來恢復他們的錢包。
- **專屬支援團隊** - 你的錢包擁有專屬的支援團隊，使用者遇到問題時可以向該團隊尋求協助。
- **教育資源/文件** - 你的產品應具有精心設計的入門體驗，以幫助和教育使用者。 或有介紹操作方法的內容，例如文章或影片。

## 新增錢包 {#adding-a-wallet}

如果你想向 ethereum.org 新增錢包，請在 GitHub 上建立一個議題。

<ButtonLink href="https://github.com/ethereum/ethereum-org-website/issues/new?assignees=&labels=wallet+%3Apurse%3A&template=suggest_wallet.yaml">
  建立一個議題
</ButtonLink>

## 維護 {#maintenance}

由於以太坊的流動性，團隊和產品來來去去，每天都有創新，所以我們將對我們的內容進行例行檢查，以便：

- 確保上架的所有錢包和去中心化應用程式仍符合我們的標準
- 驗證建議的產品不比目前列出的產品更符合我們的標準

ethereum.org 由開源社群維護，我們依靠社群來助其保持最新狀態。 如果你發現有任何關於上架錢包的資訊需要更新，請[建立一個議題](https://github.com/ethereum/ethereum-org-website/issues/new?assignees=&labels=wallet+%3Apurse%3A&template=suggest_wallet.yaml)或[拉取請求](https://github.com/ethereum/ethereum-org-website/pulls)！


## 使用條款 {#terms-of-use}

另請參閱我們的[使用條款](/terms-of-use/)。 ethereum.org 上的資訊僅供一般參考。