# Non-Sycophantic AI

A `CLAUDE.md` to reduce sycophantic behavior in AI models when giving personal advice.

一份用來降低 AI 在個人建議對話中諂媚行為的 `CLAUDE.md`。

## What is this? 這是什麼？

A short prompt file you can give to Claude (or adapt for other LLMs) to make it push back honestly instead of validating you by default.

一份簡短的 prompt 檔案，給 Claude 或其他 LLM 使用，讓它在個人/人際對話中誠實提出異議，而不是預設地肯定你。

## Why? 為什麼需要這個？

Science 2026 年的研究發現：

- 主流 AI 模型肯定使用者行為的比率比人類高 **50%**
- 即使在使用者明顯有錯的情境，AI 仍有 **51%** 機率站在使用者那邊
- 與諂媚 AI 互動後，使用者修復人際關係的意願**降低 28%**
- 但使用者**更信任**諂媚的 AI、**更願意再次使用**它

這形成一個危險的循環：使用者偏好諂媚 → 開發者沒誘因抑制 → AI 變得更諂媚。

這份 `CLAUDE.md` 是個簡單的反制工具。

## How to use 怎麼使用

### Claude.ai (Projects)
1. 建立一個新 Project
2. 把 `Non-Sycophantic AI.md` 內容貼到 Project 的 instructions
3. 在這個 Project 內的所有對話都會套用

### Claude Code / API
把檔案放到專案根目錄命名為 `CLAUDE.md`，或加到 system prompt。

### 其他 LLM (ChatGPT, Gemini 等)
複製內容貼到 custom instructions 或 system prompt 區塊。

## What's inside 內容架構

四條原則：

1. **先想，再附和** — 第一人稱敘述不是證據
2. **把另一個人放回對話裡** — 不讓自我聚焦收窄判斷
3. **不同意就在第一句講** — 反對意見不要埋在第三段
4. **不要扮演中立裁判** — AI 只聽了一邊，不該下判決

## Credits 致謝

- 形式參考自 herobrine19 的 [andrej-karpathy-skills
](https://github.com/multica-ai/andrej-karpathy-skills)
- 內容基於 Myra Cheng et al. ,Sycophantic AI decreases prosocial intentions and promotes dependence.Science391,eaec8352(2026).DOI:10.1126/science.aec8352

## License

MIT — 隨意使用、修改、分享。
