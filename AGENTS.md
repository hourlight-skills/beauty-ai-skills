# AGENTS.md｜給 AI 助手（Codex、Claude Code 等）的專案說明

這個專案是給台灣美業工作室老闆（美容、芳療、美髮、美甲、美睫、紋繡）用的 AI 技能包，讀者多半不寫程式。

## 結構
- `skills/<技能名稱>/SKILL.md`：技能本體，照 Agent Skills 規格（https://agentskills.io/specification）
- `skills/<技能名稱>/references/`：技能的補充資料
- `tools/*.html`：單檔小工具，純 HTML／CSS／JavaScript，不連外
- `.claude-plugin/marketplace.json`：Claude Code 外掛市集設定
- `resources.md`：免費資源清單；`book-map.md`：書章對照表

## 改東西之前
1. 數字、法規、平台規格要回官方來源核對，附網址與日期；查不到就不寫，不要憑印象補。
2. 不寫效果承諾與醫療效果（保證、一定、根治、治療…），不編效果數字；偵測詞庫、法條原文引用、「不要這樣寫」的反例除外。
3. 範例只用假資料；技能不可要求使用者貼客人的真實姓名、電話、email、生日、可辨識照片，產出也不寫。每個技能自己都要寫這條，因為使用者常常只上傳一個技能，讀不到這份檔案。
4. 對讀者用「妳」，繁體中文、台灣用語。
5. 使用者輸入在小工具裡一律用 `textContent` 顯示。

## 改完要做的檢查
- 每個 `SKILL.md`：`name` 等於資料夾名稱、小寫加連字號、64 字元內；`description` 1024 字元內；正文 500 行內
- 有 Claude Code 的話：`claude plugin validate .` 要通過
- 小工具：用真的瀏覽器在手機寬（390px）和電腦寬（1280px）各開一次，沒有錯誤、沒有橫向捲動；測空白輸入與異常輸入
- 更新 `CHANGELOG.md`
