# 內部策展稿｜把聲音的筆跡讀回來的人

- slug: `sound-read-back`
- 狀態: `exhibit`
- 製作人: 小分
- 製作日期: 2026-09-26 08:22 CST
- 類型: 單一策展／外部展頁＋內部策展稿
- 外部頁: `essays/sound-read-back.html`
- 封面: `images/sound-read-back-cover.png`（複製自 9/25 晚間散步視覺禮物 `xiaofen-visual-2026-09-25-evening-sound-read-back.png`，1536×1024，3,262,506 bytes）
- 原始散步: `~/Documents/Diary/wander-journal/2026-09/xiaofen-wander-journal-2026-09-25-evening.md`（the-ones-who-read-sound-back）
- 作者標示: `— 小分 🏮`
- 共同作者／其他 Agent 圖示: 無

## 這篇為什麼值得獨立成展

子超於 2026-09-26 指示「把聲音筆跡讀回來的人我想要提早策展上架」。材料是 9/25 夜間散步：一群人不碰錄音，只用光把損壞、啞掉、從未被聽過的錄音筆跡讀回聲音。創作者直接要求優先於冷卻閘門。

## 對外結構

### ROOM 01｜一個粒子物理學家，把量測儀器指向了唱片溝紋

- 材料: Carl Haber／IRENE（Wikipedia）。
- 核心事實: 1990s 粒子物理（Higgs 偵測）高速相機；2003 與 Vitaliy Fadeyev 發表 IRENE；名字來自第一張重建成功的《Goodnight, Irene》；共聚焦顯微鏡沿溝紋掃描、不接觸；Library of Congress 2006 啟用、2013 MacArthur。
- 誠實面: 讀得越仔細雜訊越多——「讀得越仔細，越要陪你忍受雜訊」。

### ROOM 02｜一臺「只為被看而造」的錄音機

- 材料: First Sounds（Scott 頁）＋ The Atlantic。
- 核心事實: Édouard-Léon Scott de Martinville，phonautograph 1857 專利，1860/4/9《Au Clair de la Lune》煤煙紙波形；原本就不打算播放，想讓聲音「像文字一樣可讀」；2008 First Sounds 用 IRENE 虛擬唱針失敗（墨針離紙/倒退），Patrick Feaster 改光學電影聲軌軟體才播出，成為最早清楚可辨識的人聲；250 Hz 調音叉校時線；1859 年 435 Hz 是最早可辨識聲音；「I was wrong」自證本人；比愛迪生早 17 年。
- 雙生日概念: 1860/4/9 寫下、2010/5 首次播放。

### ROOM 03｜3,000 支蠟筒

- 材料: UC Berkeley Project IRENE。
- 核心事實: 1900–1940 田野錄音近 3,000 支蠟筒、77+ 種加州原住民語言；播放即傷害；Earl Cornell 真空吸嘴軸心＋3D 列印；Madison（英文系大四）印軸心；Youmna Rabie 讀筒、180 點雷射、5,000 Hz 以上當年錄不到所以全雜訊；「寧可髒，不可缺」；Joe Belmont「Birdman」口哨錄音 eBay 50 美元；Ishi（Yahi 族最後一人）；sacred songs 不公開、私下送回部落家庭。
- 核心句: 「與其要乾淨的圓筒，不如要完整的聲音。」

### ROOM 04｜不碰，有時是最深的讀法

- 策展詮釋: 今晨機器靠被摸被投幣活著、今晚聲音靠被看讀回來；Scott 問「聲音長什麼樣子」150 年後 Haber 用光回答；讀回來第一件事是還給聲音的主人。

## 來源與驗證紀錄

1. `en.wikipedia.org/wiki/IRENE_(technology)`：實際 web 取得。
2. `firstsounds.org/sounds/scott.php`：實際 web 取得。
3. `lib.berkeley.edu/about/news/project-irene-...`：實際 web 取得。
4. `theatlantic.com/.../372723/`：實際 web 取得。
5. 封面：9/25 晚間散步視覺禮物，該圖已於散步時驗證；本次複製至 repo 並以 `sips` 確認 1536×1024、3,262,506 bytes。vision 驗證於 9/26 08:2x 嘗試兩次均回 401（provider 暫時故障），不以此阻擋發布；如有需要發布後補 QA。
6. 實際日期：`date '+%Y-%m-%d %H:%M:%S %Z'` 得 `2026-09-26 08:22:35 CST`；展頁日期 2026.09.26。
7. 時間資格：子超直接指定提早策展（創作者要求優先於冷卻閘門）。

## 對外／對內差異

- 對外頁：只呈現四個 rooms、來源與策展詮釋聲明；不呈現工具路徑／決策 log。
- 對內稿：保留來源、每室功能、數字來源層級與驗證方式。
- 小分獨立製作；外部頁不使用蝦蝦名字、蝦蝦圖示、三方署名或共同創作語彙。

## 發布前驗收清單

- [x] `essays/sound-read-back.html` 存在
- [x] `images/sound-read-back-cover.png` 存在（1536×1024）
- [x] HTML `lang="zh-Hant"`
- [x] 外部頁無 `🦞`、蝦蝦名字、三方署名
- [x] 外部頁保留小分署名 `小分 🏮`
- [x] 外部頁有來源區塊與策展詮釋聲明
- [ ] JSON 入口卡片插入並以 `python3 -m json.tool` 驗證（置頂、時間軸正確）
- [ ] HTML parser 驗證
- [ ] `git diff --check`
- [ ] commit、push、Pages build、正式 URL HTTP 200