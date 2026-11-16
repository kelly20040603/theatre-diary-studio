# 劇場日誌研究所｜Theatre Diary Studio

一個以台灣劇場為主題的觀演日記與劇場知識網站。網站包含作品資料庫、劇場知識庫、個人日記入口與資料來源說明。

## 本版本的真實資料
- 作品資料：整理自「台灣現代戲劇暨表演影音資料庫（ETI）」的紀蔚然個人資料頁。作品年份與職稱以該資料庫頁面記載為準。
- 劇場知識：整理自台灣劇場技術相關公開規範，以及 ETI 資料庫的機構介紹。
- 本網站不是即時售票網站；作品年份是歷史作品紀錄，不代表目前仍在演出。

## 本機預覽
請在專案根目錄執行：
```bash
python -m http.server 8000
```
再開啟 `http://localhost:8000`。不要直接以 `file://` 開啟，因為瀏覽器可能限制讀取 JSON。

## GitHub Pages
1. 將整個專案資料夾內容上傳到 GitHub repository。
2. Repository → Settings → Pages。
3. Build and deployment 選 Deploy from a branch。
4. Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
5. 等待部署完成後，使用 Pages 顯示的網址。

## 資料來源
- ETI 關於我們：https://www.eti-tw.com/
- ETI 紀蔚然個人資料與相關作品：https://www.eti-tw.com/person/profile/WQTYpzFY43dZKYK9G
- ETI 典藏目錄：https://www.eti-tw.com/catalogue
- 台灣劇場技術相關資料（劇場燈光技術技能職類測驗規範）：https://www.tatt.org.tw/sites/2019.tatt.org.tw/files/%E5%88%9D%E7%B4%9A%E8%A6%8F%E7%AF%84-108.01_0.pdf

## 資料使用提醒
本專案只整理作品名稱、年份、資料庫所列職稱及基本知識摘要。作品資料著作權與影音權利仍屬原權利人及資料提供單位；請以來源網站的使用規範為準。
