# Contributing · 貢獻指南

Thanks for wanting to help! These projects are built by a hematologist-oncologist for clinicians, researchers and teachers. Contributions from anyone are welcome — code, docs, translations, bug reports and ideas.

謝謝你願意幫忙！這些專案由一位血液腫瘤科醫師開發，給臨床、研究與教學使用。程式、文件、翻譯、回報、想法都非常歡迎。

## Rounds in four steps · 四步查房

1. **Look before you scrub in.** Search open issues first. For anything bigger than a small fix, open an issue (📋 *Consult*) so we can agree on the approach before you spend time.
   先找有沒有相關 issue；改動較大時先開一張會診單討論。
2. **Read the chart.** Each repo's `README` and `AGENTS.md` / `CLAUDE.md` explain how to install, build and test. Follow them.
   先讀該 repo 的 README 與 AGENTS.md，照裡面的方式安裝與測試。
3. **Operate small.** One focused change per pull request. Add or update a test when you change behaviour.
   一個 PR 只做一件事；改了行為就補測試。
4. **Write the op note.** The PR template asks what, why and how you tested it. Two lines is often enough.
   PR 範本就是手術紀錄：做了什麼、為什麼、怎麼測。

## Ground rules · 基本規則

- **No patient data, ever.** Use synthetic or published data only. 只用模擬或已公開的資料。
- **No secrets.** Keys go in `.env` (never committed); see `.env.example` where it exists.
- **Clinical content is not medical advice.** If you change anything that produces clinical output, cite the source (guideline, paper, DOI).
  動到臨床內容時請附來源。
- **AI-assisted contributions are welcome** — please review what you submit as if you wrote every line.
  歡迎用 AI 協助，但送出前請像自己寫的一樣檢查過。

## Response time · 回覆時間

This is a one-person, after-hours effort. Expect a first reply within about a week. If a PR has waited longer, a polite ping in the thread is welcome.
這是下班後的個人專案，通常一週內回覆；等太久歡迎留言提醒。

By contributing you agree that your contribution is licensed under the repository's license, and you follow our [Code of Conduct](CODE_OF_CONDUCT.md).
