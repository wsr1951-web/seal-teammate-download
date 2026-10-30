<p align="center"><img src="icon.png" width="96" alt="海豹神隊友圖示"></p>

<h1 align="center">海豹神隊友 下載</h1>

<p align="center">Chrome 用的使用者腳本管理器：在指定網站上自動執行工作腳本，<br>例如自動填表、自動建單、自動列印。</p>

<p align="center">
  <a href="https://github.com/wsr1951-web/seal-teammate-download/releases/latest/download/seal-teammate-installer.zip"><b>⬇️ 下載最新版安裝包</b></a>
</p>

---

## 安裝步驟（Windows + Chrome，約 2 分鐘）

1. 點上面的「**下載最新版安裝包**」，下載 `seal-teammate-installer.zip`。
2. 在下載的 zip 上按右鍵 →「**解壓縮全部**」。
   > 一定要先解壓縮，直接點開 zip 裡面的檔案沒辦法安裝。
3. 在解壓縮後的資料夾中，對 **`install.bat`** 按兩下。
   如果出現藍色的「Windows 已保護您的電腦」，按「其他資訊」→「仍要執行」。
4. Chrome 會自動打開擴充功能頁，接著：
   1. 打開右上角的「**開發人員模式**」。
   2. 按「**載入未封裝項目**」，在視窗上方的路徑列按 `Ctrl+V` 貼上路徑（已經自動複製好），按 Enter，再按「選擇資料夾」。
   3. 在「海豹神隊友」卡片上點「**詳細資料**」，打開「**允許使用者指令碼**」。
      > 沒有打開的話，腳本不會執行。
   4. 點 Chrome 右上角的拼圖圖示，把海豹神隊友**釘選**到工具列上。

安裝完成後，打開別人提供給你的腳本網址（結尾是 `.user.js`），海豹神隊友會跳出安裝畫面，按「安裝」即可。

## 更新到新版

再點一次上面的「下載最新版安裝包」→ 解壓縮 → 按兩下 `install.bat` → 到 `chrome://extensions` 按海豹神隊友卡片上的「重新載入」箭頭 ↻。
腳本和設定都會保留。

## 注意事項

- 安裝後會產生「使用者資料夾\海豹神隊友」，這個資料夾**不要刪除或搬移**，Chrome 每次啟動都會從這裡讀取。
- 如果電腦也裝了竄改猴（Tampermonkey），同一支腳本不要兩邊同時開著，否則會被執行兩次。
- Chrome 啟動時偶爾會提醒「停用開發人員模式擴充功能」，按「保留」或直接關掉即可，不要按停用。
- 海豹神隊友不收集、不傳送任何使用資料；腳本與設定只儲存在你自己的瀏覽器中。

## 出處與授權

海豹神隊友改自開源專案 [Violentmonkey（暴力猴）](https://github.com/violentmonkey/violentmonkey)，依 MIT 授權使用與修改，授權聲明見 [`LICENSE`](LICENSE)。

所有版本：[Releases](https://github.com/wsr1951-web/seal-teammate-download/releases)
