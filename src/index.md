# 亂世數碼求生攻略

## 前言
國安法通過咗，依家連和平示威都無辦法啦。*佢哋*依家有更大權力去搜查，甚至截聽你嘅資料。

即使你以為自己無嘢好擔心，依家試下攞部電話出嚟，揭下相簿，你一定至少搵到一兩嘢唔想你屋企人／情侶見到嘅嘢。試想像下你部手機，有一班國安專家日以繼夜去搵你、家人、朋友同手足嘅**所有黑材料**。你，知驚未？

可能你唔係戰線上嘅手足，手機亦都無咩比人睇；但係假如*佢哋*捉咗你，*佢哋*晒時間爆開你手機，就係為其他手足爭取喘息嘅空間。

## 考慮風險
你要自行評估你自己會面對嘅威脅，再以作出行動。就一般而言，你可能會面對的風險包括：
1. 政府以搜查令要求雲端服務（例：Google Drive、Microsoft OneDrive、DropBox等）提供你的個人檔案（見[保護雲端上的檔案](#保護雲端上的檔案)）
2. 政府以搜查令／強行攞走你部電腦（見[保護電腦檔案](#保護檔案)）
3. 政府以搜查令／不法手段截取你的通話紀錄（見[保護通話](#保護通話)）
4. 政府以搜查令截取及／或記錄你的瀏覽紀錄（見[保護瀏覽紀錄](#保護瀏覽紀錄)）

:::success
:warning: **利申**
以下有部份連結，你用嚟註冊同升級之後，作者會收到回佣架。我唔可以話俾你聽啲錢會去邊架。 :shushing_face:
:::



### 保護檔案

### 一般守則
假如加密完，你部電腦最安全嘅時候就係**熄咗機**嘅時候。所以，假如*佢哋*上門，第一件事係**熄機**。開機時，系統會將用到嘅檔案解密，並放係RAM裡面；一旦熄機，RAM嘅資料會係再開機時洗走。

### 保護上的檔案
就電腦上的檔案嚟講，你應至少**將敏感檔案加密**。你更可以直接執行**全磁碟加密**進一步保障自己。

Windows 8.1/10 Pro用戶可以以[BitLocker進行全磁碟加密](https://youtu.be/b0NxnCrrFSM?t=66)。MacOS用戶可以[FileVault進行全磁碟加密](https://support.apple.com/zh-hk/HT204837)。

假如你無法使用上述方法，或者想跨平台使用加密硬碟／手指，可以使用 [VeraCrypt 建立加密虛擬分區](https://www.veracrypt.fr/en/Downloads.html)。


### 保護雲端上的檔案
**所有**你上傳到雲端的檔案應被當作**已經外洩**。你的目標應是透過加密，讓對方縱然取得你的檔案亦**得物無所用**。

[Cryptomater](https://cryptomator.org/downloads/)是一個開源的檔案加密軟件，以便於你的雲端網盤或本機上建立加密檔案庫。

假如你係前線手足，有文宣要交換，建議用[NordLocker](https://nordlocker.com/)，可以加密地協作。

## 保護通話紀錄
Telegram 當然是一個有效的加密通話軟件，然而考慮目前狀況，你亦應考慮以不同程式進行通訊。


### 即時通訊
- [Signal](https://www.signal.org/download/) 以同名的通訊制式（Signal Protocol）進行點對點加密通訊。
- [Matrix](https://keybase.io/download/) 以同名嘅分散式溝通制式（Matrix Protocol）制式保護你的通訊，支援多人加密通訊。
- [Keybase](https://keybase.io/download/) 以PGP（Pretty Good Privacy）制式保護你的通訊。
:::warning 
:confused: **注意事項**
雖然 Keybase 會以PGP保護你的資料，但最近 Keybase 被[懷疑與內地有關連](https://finance.yahoo.com/news/zoom-stock-privacy-china-connection-154032463.html)的 [Zoom 收購](https://keybase.io/blog/keybase-joins-zoom)。
:::

### 電郵服務
- [PrivateMail](https://privatemail.com/members/aff.php?aff=133) 以 PGP 制式保障你的電郵不受任何人截聽，包括 PrivateMail 自身。
- [TutaNota](https://mail.tutanota.com/signup) 以 AES 及 RSA 加密法保障你的電郵不受任何人截聽。
- [ProtonMail](https://protonmail.com/signup) 以同樣 PGP 制式保障你的電郵不受任何人截聽。


:::danger
:no_entry: **關於 Facebook／WhatsApp／Instagram**

Facebook 一直有意進軍中國，它們亦有意進行 **「中國式改造」**，不排除Facebook 會犧牲用戶私隱以取悅它們。

你應盡量避免使用任何 Facebook 及旗下服務，包括 Facebook／WhatsApp／Instagram／Oculus 等。Facebook 亦有經 Facebook Pixel 和「Like Button」等對用戶進行跨網站追蹤。你可以瀏覽器插件如 [Block Facebook (Chrome)](https://chrome.google.com/webstore/detail/block-facebook/gebclbfnlcebcljmgblacllmjkfidoef) 或者 [Facebook Blocker (Firefox)](https://addons.mozilla.org/en-US/firefox/addon/facebook_blocker/) 完全封鎖 Facebook。
:::

## 保護瀏覽紀錄

### 電腦上的記錄
你可以於瀏覽器設定中選擇自動刪除瀏覽紀錄，或者使用無痕模式上網。

### 電腦外的記錄
當你上網時，網絡服務供應商（ISP，如電訊盈科／HKT/PCCW、香港寬頻、和記電訊等）會知悉你瀏覽的網站，並有可能藉此進行篩查。就此，你可以透過使用虛擬私人網路（Virtual Private Network，VPN）加密從你的裝置到 VPN 公司伺服器的通訊。

:::danger
:warning: **你的資料並沒有那麼危險**
ISP 了解的資料其實很有限，假如你瀏覽`https://www.youtube.com/watch?v=SToLjzQEaaE`，ISP 只會了解你曾瀏覽`www.youtube.com`，但無法了解你曾觀看的影片、輸入的密碼等。

由於TLS（傳輸層安全性協定），你與大部分網站的通訊其實已經進行加密。只要你瀏覽網站的網址列上有 :lock: ，你瀏覽器與該網站之間經已建立加密通道。第三方（如ISP、政府等）亦無法窺視你的通訊。

然而，於加密通道未建立之前，你的裝置會以未加密方式查閱 IP 地址。這類型的資料仍然可能會被用作內容審查等用途。
:::

:::warning
:warning: **購買 VPN 服務時要注意**
1. **VPN 是否有零紀錄政策。** VPN 會代你傳達與網站之間的通訊，伺服器上保留的任何資料（包括連線紀錄、登入記錄等），就等同你電腦上瀏覽紀錄，均有可能成為傷害你權益的證據。所以選擇 VPN 時要肯定有**零紀錄政策**（包括登入記錄、連線紀錄、裝置記錄等等）
2. **小心細閱評價。** VPN市場多依賴網上評論和推薦作推廣。有部份網站會推高夥伴 VPN 的評價，甚至有公司會直接建立自己的評價網站作宣傳。你應仔細閱讀評價，並判斷該 VPN 是否適合自己的需要。
3. **留意 VPN 營運商資料。** 市面有部份 VPN 品牌[欠缺透明度](https://vpnpro.com/wp-content/uploads/Infographic-VPNpro-97-VPN-products-run-by-just-23-companies.pdf)。例如市面上很多 VPN 品牌其實是由同一公司營運。另外，有部份公司總部會位於中國或者與五／六／九／十四眼聯盟。同樣，你應仔細該 VPN 的資料並自行判斷。盡量避免 透明度不足（如未有指明紀錄政策、隱瞞公司資料／註冊地等）的 VPN。
:::

| VPN 服務                                                          | 公司總部     | 最優惠月費（美金） | 承諾期（月） |
| ----------------------------------------------------------------- | ------------ | ------------------ | ------------ |
| [NordVPN](https://nordvpn.com)                                    | 巴拿馬       | $3.49              | 36           |
| [ProtonVPN](https://protonvpn.com/)                               | 瑞士         | $6.63              | 24           |
| [Mullvad](https://mullvad.net/)                                   | 瑞典         | $5.50              | 1            |
| [SurfShark](https://surfshark.com/)                               | 英屬處女群島 | $2.49              | 24           |
| [Private Internet Access](https://www.privateinternetaccess.com/) | 曼島         | $2.85              | 14           |

### 實際使用
普遍的 VPN 服務都提供自己的應用程式。登入後就已經完成設定。但以備不時之需，你亦可以系統原生／非廠商指定軟件方式啟動 VPN。

常見的VPN制式包括IPSec（系統原生）、OpenVPN（較新制式，需另行安裝）和WireGuard（最新制式，最快，需另行安裝）。PPTP制式經已過氣，並有保安漏洞，不具任何安全性。

#### 下載網址
- **OpenVPN**
    - [Windows](https://openvpn.net/community-downloads/)
    - [MacOS (TunnelBlick)](https://tunnelblick.net/release/Latest_Tunnelblick_Stable.dmg)
    - [Android](https://f-droid.org/en/packages/de.blinkt.openvpn/)
    - [iOS](https://itunes.apple.com/us/app/openvpn-connect/id590379981?mt=8)
- **WireGuard**
    - [Windows](https://www.wireguard.com/install/)
    - [MacOS](https://itunes.apple.com/us/app/wireguard/id1451685025?ls=1&mt=12)
    - [Android](https://f-droid.org/en/packages/com.wireguard.android/)
    - [iOS](https://itunes.apple.com/us/app/wireguard/id1441195209?ls=1&mt=8)


## 兩手準備
以防應用程式被強行下架／封鎖，你應：
- 安裝所有可能需要的程式，並做好備份
- [Android] 準備以Play Store以外的方式安裝應用程式（安裝[F-Droid](https://f-droid.org/)／下載APK檔）
- 準備用不同方法連線到 VPN （以服務應用程式、系統原生／非廠商指定軟件連線）

## 技術資料
而到係你唔需要知，但係你可能好奇嘅嘢。唔睇都得。

### 乜嘢係AES同RSA？
AES同RSA都最常用同可靠嘅加密法，但係各自都有唔同。

#### AES
AES（Advanced Encryption Standard）係最常用，亦都係最可靠嘅**對稱式**加密法（Symmetric cryptography）。簡單而言，就係你知道密碼就可以加密同解密嘅加密法。

普遍加密程式會自行GEN一條好長嘅加密輪，然後叫你比個密碼去保護嗰條加密鑰。目前加密鑰長度至少要有*128 bit*。

#### RSA
RSA就係常用嘅**非對稱**加密法。RSA有*公鑰*同*私鑰*：加密用公鑰，解密用私鑰；所以私鑰自己收埋，公鑰比其他人睇。

目前加密鑰長度至少要有*2048 bit*。

#### 加密法總結
| 加密法 | 加密用               | 解密用           | 優點                               | 缺點                                   |
| ------ | -------------------- | ---------------- | ---------------------------------- |:-------------------------------------- |
| AES    | 加密鑰 | 加密鑰 | 加密速度快                         | 加密方會知道點解密，所以可以解密所有嘢 |
| RSA    | 公鑰                 | 私鑰             | 加密方唔知點解密（Zero Knowledge） | 加密速度慢                             |

### 乜嘢係PGP、Signal 或者 Matrix Protocol？
因為直接用加密法係幾困難嘅事（要交換公鑰之類），所以有一啲現成嘅**加密制式**簡化整個過程。

#### PGP／GPG
普遍用於電郵上，但係亦都可以用嚟做加密檔案傳輸。

斯洛登當時同記者溝通就係靠依個加密制式避過CIA調查。

大部分加密電郵都係靠依個技術保護你嘅電郵。

一般嚟講，公鑰只需交換一次，然後就會沿用落去，所以私鑰一旦外洩就要全組報廢。

#### Signal Protocol
比較近代嘅制式，有Perfect forward secrecy保障（俾*佢哋*截聽到一個信息就只有一個信息外洩），不過只限單對單通話。詳細解釋睇[依條片](https://www.youtube.com/watch?v=9sO2qdTci-s)。

#### Matrix Protocol
比較近代嘅制式，都有Perfect forward secrecy保障，支援多人解密通話。詳細解釋睇[依條片](https://youtu.be/DffJmQyBkR8?t=97)。

