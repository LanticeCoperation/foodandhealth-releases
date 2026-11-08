# Body Lab releases

Body Lab 的安裝檔，只放 release assets。程式碼在 private repo `LanticeCoperation/foodandhealth`。

固定網址（永遠是最新版）：https://github.com/LanticeCoperation/foodandhealth-releases/releases/tag/latest

- **body_lab.apk**：Android。手機瀏覽器下載後開啟安裝，第一次要允許「安裝未知來源 App」。簽名固定，之後可直接覆蓋安裝；App 啟動時會自動提示新版本。
- **body_lab-unsigned.ipa**：iOS，未簽名。Windows 用 Sideloadly 以自己的 Apple ID 重新簽名後裝進 iPhone；免費 Apple ID 7 天到期後重裝一次即可。
- **version.json**：App 啟動時讀這個檔比對 build number。
