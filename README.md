# 美業 AI 技能包｜beauty-ai-skills

給**美容、芳療、美髮、美甲、美睫、紋繡**工作室用的 AI 技能，繁體中文、照台灣的法規與平台寫。
裝進 Claude 或 Codex 之後，跟它說「幫我寫這週的 IG」「這則客人訊息怎麼回」「幫我算打平線」，它就會照這裡寫好的步驟、格式和紅線做事，不用每次從頭教。

> 內容來自《AI 時代，美業人的逆襲指南》（王逸君 著）裡已經逐條查過官方來源的章節；紋繡那一支是書外補充，依衛福部公開文件整理。
> 技能只放「怎麼做」；背後的道理、案例和完整說明在書裡。

版本 0.5.0｜更新日 2026-09-26｜[更新紀錄](CHANGELOG.md)

---

## 裡面有什麼

| 技能 | 什麼時候用 | 書裡哪一章 |
|---|---|---|
| [salon-social-post](skills/salon-social-post/SKILL.md) | 寫 IG／FB／Threads 貼文、活動文案、一次排好一週 | 第 18 章 |
| [salon-reels-script](skills/salon-reels-script/SKILL.md) | 寫 30–60 秒短影音腳本 | 第 18 章 |
| [salon-review-reply](skills/salon-review-reply/SKILL.md) | 回 Google／臉書負評 | 第 18 章 |
| [line-sticker-maker](skills/line-sticker-maker/SKILL.md) | 用 AI 做店裡的 LINE 貼圖，從角色到上架 | 第 18 章 |
| [salon-booking-messages](skills/salon-booking-messages/SKILL.md) | 預約提醒、改期、爽約、空檔通知、預約表分析 | 第 19 章 |
| [salon-message-triage](skills/salon-message-triage/SKILL.md) | 客人訊息分紅黃綠燈，能回的先寫草稿 | 第 19 章 |
| [salon-receipt-bookkeeping](skills/salon-receipt-bookkeeping/SKILL.md) | 收據轉記帳表、月收支毛利、儲值預收台帳 | 第 19 章 |
| [difficult-client-roleplay](skills/difficult-client-roleplay/SKILL.md) | 跟 AI 對練難搞客人的話術，練完打分 | 第 20 章 |
| [cosmetic-ad-wording-check](skills/cosmetic-ad-wording-check/SKILL.md) | 貼文發出去前，檢查化粧品廣告的用詞風險 | 開門做生意篇・一 |
| [salon-breakeven](skills/salon-breakeven/SKILL.md) | 算每個月至少要幾位客人才打平 | 開門做生意篇・三 |
| [cosmetic-tattoo-consent](skills/cosmetic-tattoo-consent/SKILL.md) | 紋繡店的施作前同意書、術後注意事項單、每日衛生檢查表、廣告自查 | 書外補充（依衛福部公開文件） |
| [beauty-prompt-coach](skills/beauty-prompt-coach/SKILL.md) | 把一句話的需求改寫成好指令（文字 RTSC、出圖七要素），幫妳設定品牌助手 | 第 17 章 |
| [salon-ai-privacy-check](skills/salon-ai-privacy-check/SKILL.md) | 客人照片、資料丟給 AI 之前的檢查；AI 說的話怎麼查證 | 第 21 章 |
| [ai-inspo-photo-consult](skills/ai-inspo-photo-consult/SKILL.md) | 客人拿 AI 圖來：綠黃紅評估、諮詢說明、條款草稿、AI 客服能回什麼 | 第 14 章 |
| [salon-30-day-ai-plan](skills/salon-30-day-ai-plan/SKILL.md) | 完全不會 AI 也能開始：30 天每天一件小事 | 第 37 章 |
| [salon-client-memory](skills/salon-client-memory/SKILL.md) | 只記服務需要的客人偏好卡，預約前 30 秒服務小抄 | 第 32、19 章 |
| [salon-faq-keeper](skills/salon-faq-keeper/SKILL.md) | 常見問題回覆庫，每題有日期；改價後列出要跟著改的舊答案 | 第 19 章 |
| [salon-staff-trainer](skills/salon-staff-trainer/SKILL.md) | 把自己的 SOP 變成新人考題、學習卡、錯題重練 | 第 15、20 章 |
| [work-photo-consent](skills/work-photo-consent/SKILL.md) | 作品照用途勾選、同意書草稿、存檔與撤回紀錄 | 第 15、21 章 |

有些技能會建議「再用另一個技能檢查一次」。只裝一個也能用，技能裡都寫了沒裝另一個時要怎麼自己檢查。

---

## 一鍵網頁與二十二個小工具（不用裝、不用登入）

**直接點開就能用（手機、電腦都可以）：**
- 全部小工具：https://hourlight-skills.github.io/beauty-ai-skills/tools/
- 一鍵指令產生器：https://hourlight-skills.github.io/beauty-ai-skills/tools/one-click.html

想存在自己電腦、沒網路也能用：在這個頁面按綠色「Code」→「Download ZIP」，解壓縮後雙擊 `tools` 資料夾裡的 `index.html`。
（直接在 GitHub 上點下面的檔名，只會看到原始碼，不會開出工具；請用上面的網址。）

| 工具 | 做什麼 |
|---|---|
| `tools/one-click.html` **一鍵指令產生器** | **完全不懂 AI 也能用**：選一張卡、填幾格、按一下，完整指令就複製好，打開 ChatGPT／Claude／Gemini 貼上就好 |
| `tools/sticker-packer.html` LINE 貼圖打包器 | 拖進去背好的貼圖，自動裁透明邊、調成 LINE 規格、做主圖和標籤圖、打包 ZIP |
| `tools/ad-wording-check.html` 廣告字眼檢查器 | 貼上文案，標出需要再確認的用詞，給改寫方向 |
| `tools/breakeven.html` 打平線計算機 | 填數字就算出每月要幾位客人，分別看房租、耗材漲價後的變化 |
| `tools/client-data-cleaner.html` 客人資料清理器 | 預約表或客人名單丟進來，姓名換成客編、電話 email 生日刪掉，保留欄位裡夾帶的電話 email 也會遮掉；處理後比較不容易認出是誰，但不等於完全匿名 |
| `tools/service-margin.html` 服務時薪與折扣底線 | 每個服務每小時賺多少、打幾折會低於妳自己定的底線 |
| `tools/schedule-buffer.html` 排程空檔與清潔緩衝 | 排一天的預約，看哪裡撞到、哪裡有空檔（清潔時間妳自己填） |
| `tools/supply-expiry.html` 耗材效期與補貨 | 開封後還能用幾天、哪些快過期、哪些要補貨 |
| `tools/booking-policy-check.html` 預約須知體檢＋放鳥損失 | 標出預約須知裡容易吵起來的寫法，附消保法、民法與衛福部〈美容定型化契約應記載及不得記載事項〉原句；算放鳥一年損失；退還比例由妳自己填，不給法律結論 |
| `tools/price-quote.html` 透明價目表＋傳圖報價 | 基本價＋加價項目（含在基本價／另計），勾選產生報價文字與價目表；例子價格不能直接複製或下載 |
| `tools/prepaid-ledger.html` 儲值金／套票餘額本 | 只記客編：實付與贈送分開、每次扣抵、剩餘餘額與堂數；照衛福部原文提醒書面契約（總金額 1 萬以上）與履約保障（逾 5 萬）；不算退費 |

**通用小工具（不只美業，任何小店、接案的人都用得到）**

| 工具 | 做什麼 |
|---|---|
| `tools/ai-usage-hub.html` AI 訂閱與花費一頁看 | 付了幾家 AI、每月花多少、哪家快扣款排在一頁，超過預算提醒；各家用量頁一鍵打開。費用與扣款日是妳自己填的，工具讀不到各家真實用量 |
| `tools/prompt-box.html` 提示詞收藏盒 | 好用的 AI 指令存起來、分類、搜尋、一鍵複製，可備份還原 |
| `tools/ai-answer-checklist.html` AI 回答查核清單 | 貼上 AI 的回答，挑出數字、日期、金額、法條、研究，列成要回原始來源核對的清單；不替妳判斷對錯 |
| `tools/transcript-to-todo.html` 逐字稿轉待辦 | 會議、電話逐字稿整理成誰、做什麼、什麼時候；用關鍵字挑，一定會漏，也能產生給 AI 的整理指令 |
| `tools/line-faq-maker.html` LINE 常見問答產生器 | 填一次店家資料，生成一問一答貼進 LINE 官方帳號；只用妳填的內容，沒填的不生成 |
| `tools/post-checker.html` 貼文發出前體檢 | 字數（各平台上限）、連結與追蹤碼、主題標籤、要再確認的字眼、第一行；不保證觸及，也不等於合規審查 |
| `tools/one-post-five-platforms.html` 一篇變五個平台 | 一段原文產生給 AI 的指令，改成脆、IG、臉書、YouTube 說明欄、Podcast 描述；改好貼回來量字數 |
| `tools/posting-calendar.html` 30 天發文排程＋撞題檢查 | 選每週哪幾天發，排成 30 天日曆；跟以前發過的題目太像會提醒；下載 CSV |
| `tools/chapter-timestamps.html` 影片／Podcast 章節時間碼 | 有時間的逐字稿（含 .srt）→ 勾章節起點 → 檢查 YouTube 章節規則 → 複製；沒填片長時最後一章無法驗證，會明講 |
| `tools/utm-link-builder.html` 追蹤連結產生器（UTM） | 保留原網址參數、統一小寫、清單存瀏覽器、下載 CSV，告訴妳去 Google Analytics 哪裡看 |
| `tools/line-oa-cost.html` LINE 官方帳號費用試算 | 照 LINE 官方 2026 價格調整公告，算 2026/10/31 前後各方案每月多少（未稅），最省的是哪個；只發給部分好友省多少 |
| `tools/business-tax-threshold.html` 營業稅起徵點對照 | 每月營業額對照財政部起徵點（114 年起勞務 5 萬、貨物 10 萬，兼營合計達 100%），附原文；不判斷要不要登記 |

小工具的程式都在妳自己的瀏覽器裡跑，程式碼裡沒有把妳填的內容傳出去的功能。會記住內容的幾個（AI 訂閱、提示詞收藏盒、LINE 問答、發文排程、追蹤連結、價目報價、儲值金餘額本）只存在那台電腦的那個瀏覽器；無痕模式存不了，頁面會提醒。

---

## 怎麼裝（一步一步的說明在 [INSTALL.md](INSTALL.md)）

| 妳用的是 | 怎麼裝 |
|---|---|
| claude.ai 網頁 | Customize → Skills →「＋」→ Create skill → Upload a skill，上傳單一技能資料夾壓成的 ZIP |
| Claude Code | `/plugin marketplace add hourlight-skills/beauty-ai-skills` 再 `/plugin install beauty-ai-skills@hourlight-skills` |
| Codex | 把 `skills/` 裡的技能資料夾複製到 `~/.agents/skills/` |

裝好之後不用特別叫它，直接講妳要做的事，AI 會自己判斷要用哪一個技能。
書的每一章對到哪個技能，見 [book-map.md](book-map.md)；免費工具、官方法規、可商用素材，見 [resources.md](resources.md)。

---

## 用之前要知道的四件事

1. **客人的姓名、電話、email、生日、病史、照片，不要原封不動貼給 AI。** 先換成客編（例如 C023），照片先遮掉認得出是誰的地方。每個技能裡都寫了這條，也要求不把客人姓名寫進產出；但 AI 仍可能出錯，發出去前妳要再看一次。
2. **價格、法規、平台規格會變。** 技能裡的數字與法規依 2026-09 的官方資料寫；發出去、收錢、上架之前，以官方當下公告為準。
3. **AI 寫的是草稿。** 發給客人、報稅、上架之前，妳要自己看過。
4. **這不是法律、稅務或醫療意見。** 技能會在該停的地方叫妳去問衛生局、消保官、國稅局、記帳士或律師。

---

## 想一起讓它更好

- 發現錯誤、法規或價格過期：到 [Issues](https://github.com/hourlight-skills/beauty-ai-skills/issues) 開一則，**附官方網址與日期，不要附客人資料**
- 想改內容或新增技能：先看 [CONTRIBUTING.md](CONTRIBUTING.md)
- 用 AI 助手改這個專案：它會先讀 [AGENTS.md](AGENTS.md)

---

## 授權

[MIT License](LICENSE)：可以免費使用、修改、再分享，也可以商用；轉發或改作時，請保留 LICENSE 裡的著作權與授權聲明。
用技能產生的貼文、訊息，不需要標註本專案。
書的全文不在授權範圍內；「馥靈之鑰」「Hour Light」名稱與標誌屬作者所有，不因開源授權而開放使用。資源清單裡的第三方工具與素材，照各自的授權。

## 作者

王逸君｜馥靈之鑰 Hour Light　https://hourlightkey.com/
