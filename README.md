# PogoSkill 台灣 SEO 文章助手

[下載完整安裝包 v1.0.0](./pogoskill-seo-assistant-1.0.0.zip?raw=true)

五角色研究 → 歷史查重與 SEO 策略 → 內容豐富的結構 Excel → 約 3,000 字繁中正文與 Word → 獨立複審 → 反思。可在同事自己的 Codex 設定每日台灣時間早上 9 點啟動，一天完成一篇後通知；可以更新既有文章，不強制新增 URL。

## 同事安裝

1. 請負責人先授予此私有倉庫的存取權。
2. 點上方下載完整安裝包並解壓，開啟其中的 `pogoskill-seo-assistant` 資料夾。**不要只下載本頁 README；完整程式、技能和模板都在安裝包裡。** 如果使用 GitHub 的 Code → Download ZIP，請再解壓裡面的安裝包一次。
3. 用自己的 Codex 開啟解壓後資料夾，貼上：

> 請讀 README.md，使用 scripts/install.py 將完整文章助手安裝到獨立本地工作區，檢查依賴、歷史總帳與 Word 渲染。不要覆寫既有資料。資料及工具齊備並手動試跑後，按 docs/setup-daily.md 在我的 Codex 設定每天台灣時間早上 9 點的完整文章任務，完成後通知我。先查既有任務，避免重複；設定完成後顯示任務和下次執行時間。

4. 從團隊內部取得最新版 `PoGoskillTW-文章上线记录.xlsx`，放到安裝輸出的工作區根目錄。總帳不在 GitHub 安裝包裡；缺少總帳不得宣稱完成歷史查重。
5. 按包內 `docs/setup-daily.md` 確認同事帳號的排程已啟用。早上 9 點是啟動時間，文章完成後才通知；電腦需開機、Codex 運作且工作區可存取。

## 安裝包內容與驗證

- 完整團隊規則、五角色職責、品牌及台灣用語、研究與寫作規範。
- 原始三欄結構 Excel、可攜式安裝器、歷史總帳只讀解析器、Excel／Word 匯出與逐頁渲染工具。
- 安裝與每日排程指引、SHA-256 清單、測試與反思紀錄。
- 已驗證標準虛擬環境安裝、實際歷史總帳六張工作表、Excel 內容與原始模板保留、Word 完整內容／超連結，以及中文渲染。

不含作者憑證、私人排程、既有文章或歷史總帳。原始碼隨安裝包完整附上，可自行檢查。安裝不等於已排程，必須在同事自己的帳號完成；同事環境的搜尋、獨立子代理和第一篇文章仍需實際試跑。

每篇交付 research、strategy、brief、structure.xlsx、draft、article.docx、review、reflection；審核未 PASS 或視覺 QA 未完成不得標記 Ready to Publish。通知在 Codex，不預設寄信、不自動上 CMS。

[安裝包 SHA-256](./SHA256SUMS) · 詳細操作與驗證紀錄位於安裝包的 README.md 和 docs/。
