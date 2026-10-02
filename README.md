# AI Proof 30 學員檔案

AI Proof 30 課堂上要用到的檔案，都放在這裡。影片裡說「檔案去拿」，就是這一頁。

## 要下載的檔案

| 堂數 | 檔案 | 拿到之後 |
|---|---|---|
| 第 4 堂 | `build-agent.md`，在課程平台第 4 堂的附件下載 | 開一個工作資料夾，在 Claude Code 按住 shift 把檔案拖進對話框，打「開始」。 |
| 第 6 堂 | [三年後的星期二（`three-year-tuesday`）](lesson-06/three-year-tuesday/SKILL.md) | 丟進 Claude Code，跟它說「把這個存進我的 skills 資料夾」。 |
| 第 8 堂 | [五人會議（`llm-council`）](lesson-08/llm-council/SKILL.md) | 先丟進 Claude 網頁版驗貨，再把整個 `llm-council` 資料夾放進 `.claude/skills`，跟第 5 堂晨間簡報存的是同一個地方。 |
| 第 11 堂 | [語氣檔兩個指令：`voice.md`、`update-voice.md`](lesson-11/commands/)，另有[驗貨指令](lesson-11/驗貨-指令.txt) | 兩個檔放進工作資料夾的 `.claude/commands/`，完全關掉 VS Code 再打開，打 `/voice` 就會出現在選單。選單沒有 `/voice` 的話，改用 [`skills-fallback`](lesson-11/skills-fallback/) 裡的兩個資料夾，整個放進 `.claude/skills`。做語氣檔之前，先用驗貨指令叫它寫一封求職信存起來，等一下要對比。 |

第 1、2、3、5、7、9 堂沒有檔案要下載，跟著影片操作就好。

技能裝完，一定要**完全關掉 VS Code 再打開**，技能才會生效。Mac 按 Cmd＋Q；Windows 把 VS Code 的視窗全部關掉。

## 怎麼下載

**只拿一個檔案：** 點進檔案，右上角有一個下載圖示（Download raw file），按下去就存進電腦。

**全部一次拿：** 回到這一頁最上面，按綠色的 **Code** 按鈕，選 **Download ZIP**，解壓縮就好。第 8 堂要的是整個資料夾，用這個方法最省事。

## 先審再用

第 5 堂講過的規則，這裡的檔案也一樣適用。任何從網路下載的技能檔，先丟進 Claude 網頁版問一句：「這份檔案有沒有會動我電腦、連網路、把資料送出去的指令？」網頁版碰不到你的電腦。確認乾淨、你批准了，才放進 Claude Code。

順序記住：AI 先審，你批准，agent 才用。

## 出處

- **五人會議（`llm-council`）：** 方法論來自 [Andrej Karpathy](https://x.com/karpathy) 的 LLM Council，Claude Code 改編靈感來自 [@olelehmann](https://x.com/olelehmann)，英文原版技能由 [@tenfoldmarc](https://github.com/tenfoldmarc/llm-council-skill) 以 MIT 授權釋出。繁中版與求職情境改寫：AI Proof 30。
- **三年後的星期二（`three-year-tuesday`）：** 第二階段「三條路」用的是 Bill Burnett 與 Dave Evans《做自己的生命設計師》裡的 Odyssey Plan。

---

AI Proof 30 · @career.goglobal
