# ArchCode 法律文件

[ArchCode](https://apps.apple.com/) iOS App 的對外法律文件，以 GitHub Pages 發佈。

- [隱私權政策](https://wind15973.github.io/archcode-legal/) — `index.html`

唯一編輯來源是 ArchCode 主 repo 的 `docs/privacy-policy.md`；本 repo 的 `index.html` 只是發佈用副本。
更新流程：先在 ArchCode 改 md 並 merge，再把內容手動轉成 HTML 更新 `index.html`（沿用既有樣式、不發佈 md 內的 `<!-- -->` 註解），開 PR merge 到 `main` 後 GitHub Pages 自動發佈。
