<div align="center">

# gakuen-imas-localify-zh-TW
> 學園偶像大師 本地化插件（開發中）

[![Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/gkmas)](https://discord.gg/gkmas)

</div>

# Usage

- 這是一個 XPosed 插件，已 Root 用戶可以使用 [LSPosed](https://github.com/LSPosed/LSPosed)，未 Root 用戶可以使用 [LSPatch](https://github.com/LSPosed/LSPatch)。
- LSPosed 相對複雜很多

## 使用 `Shizuku` 安裝 `LSPatch` 的指引

### 步驟 1: 安裝 Shizuku
   - 從 [Google Play 商店](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api) 安裝 `Shizuku`。
   - 打開 `Shizuku` 並按照指示啟動服務。

### 步驟 2: 安裝 LSPatch
   - 訪問 [LSPatch GitHub 儲存庫](https://github.com/LSPosed/LSPatch/releases/latest) 以下載最新的 APK。
   - 在您的設備上安裝 `LSPatch`。

### 步驟 3: 使用 Shizuku 配置 LSPatch
   - 打開 `Shizuku` 並確保服務正在運行。
   - 打開 `LSPatch`
   - 您應該會看到一個提示，要求授予 `Shizuku` 權限。
   - 按照螢幕上的指示授予必要的權限。

### 步驟 4: 使用 LSPatch
   - 安裝 `gakuen-imas-localify-zh-TW`
   - 打開 `LSPatch` 並導航到第二個標籤 `管理`，您可以在這裡添加應用程式（先選取儲存目錄後，就能選學マス的應用程式進行修改）。
   - 添加新的模組並選擇 `学マス`，然後選取 `模塊作用域` 後，勾選 `Gakumas.Localify`。

     **僅使用** `本地補丁模式`

     **破解簽名校驗一定要設定成** `lv0: 關閉`**，否則會無法開啟遊戲。**

     **確保模組在** `LSPatch` **中已啟用**

# 資源設置說明
在插件內有「資源設置」區域，非必要不須更動，如果動過了，可以按照建議配置改回
## 建議配置
- 檢查內建數據更新：開
- 清除遊戲目錄內的插件資源：關
- 使用遠程 ZIP 數據：關
- 替換文件後刪除下載快取：關
## 配置說明
- 檢查內建數據更新：插件本體會包入一個預設的資源包，打開這個選項會自動確認目前裝置內的資源版本與插件本體的是否一致，並自動更新成插件本體的版本。
- 清除遊戲目錄內的插件資源：只把這個選項打開後就能移除所有的插件資源，變成沒有翻譯的狀態。若要卸載本插件，可以先單獨打開本選項並打開遊戲運行插件後，確認沒有被翻譯後再卸載，確保卸載完全。
- 使用遠程 ZIP 數據：用於開發測試用，不需打開。
- 替換文件後刪除下載快取：用於開發測試用，不需打開。

# Download
[下載最新版 zip](https://nightly.link/yotv2000tw/gakuen-imas-localify-zh-TW/workflows/build/main/GakumasLocalify-zh-TW.zip)

# Translate
[GakumasTranslationData_zh-TW](https://github.com/yotv2000tw/GakumasTranslationData_zh-TW)

# 本地化相關

- 本地化文件放在 `app/src/main/assets/gakumas-local` 內
- `version.txt` 記錄翻譯版本號。每次插件啟動都會檢查 `asset` 內的版本和本地的版本是否一致。不一致會覆蓋文件到 `/data/data/com.bandainamcoent.idolmaster_gakuen/files/gakumas-lical/` 文件夾內
- `local-files/localization.json` 為 localization 翻譯
- `local-files/generic.json` 為 localization 未覆蓋部分的翻譯
- `local-files/genericTrans` 文件夾內所有 `.json` 文件作用同 `generic.json`，文件夾名/檔案名可自訂，方便區分翻譯內容
- `local-files/resource` 文件夾存放資源文件，目前可以替換所有同名的 txt 文件。獲取遊戲原始資源可以查看：[gkmasToolkit](https://github.com/kishidanatsumi/gkmasToolkit)



# 特別感謝

- [gakuen-imas-localify](https://github.com/chinosk6/gakuen-imas-localify)
- [Gakumas-Localify-EN](https://github.com/NatsumeLS/Gakumas-Localify-EN)
- [gkmasToolkit](https://github.com/kishidanatsumi/gkmasToolkit)
- [UmaPyogin-Android](https://github.com/akemimadoka/UmaPyogin-Android)
- [UnityResolve.hpp](https://github.com/issuimo/UnityResolve.hpp)
- You

