# Ordivant documentation

[繁體中文](https://ordivant-ai.github.io/) · [English](https://ordivant-ai.github.io/en/) · [简体中文](https://ordivant-ai.github.io/zh-CN/)

文件來源及應用原始碼位於 [ordivant-ai/ordivant](https://github.com/ordivant-ai/ordivant) 的 `docs/`。此倉庫的 GitHub Actions 會讀取來源的確切 commit，驗證三語正文與連結，並發布 GitHub Pages。每 15 分鐘檢查來源變更；維護者也可手動執行 `Publish documentation` 工作流程。網站的 `source-revision.txt` 記錄已發布的來源 commit。

Documentation and application source live in `docs/` in [ordivant-ai/ordivant](https://github.com/ordivant-ai/ordivant). This repository's GitHub Actions reads an exact source commit, checks all three languages and local links, and publishes GitHub Pages. It checks for source changes every 15 minutes; maintainers can also run the `Publish documentation` workflow manually. The site's `source-revision.txt` records the published source commit.

文档及应用源代码位于 [ordivant-ai/ordivant](https://github.com/ordivant-ai/ordivant) 的 `docs/`。本仓库的 GitHub Actions 会读取来源的确切 commit，检查三语正文与链接，并发布 GitHub Pages。每 15 分钟检查来源变更；维护者也可以手动运行 `Publish documentation` 工作流程。网站的 `source-revision.txt` 记录已发布的来源 commit。

```sh
gh workflow run pages.yml --repo ordivant-ai/ordivant-ai.github.io
```

MIT License. Application services are self-hosted separately from this static documentation site.

維護變更須透過 Pull request，並通過文件建置檢查。PR 只驗證，不會發布；發布流程不寫入 `main`，版本記錄保存在網站的 `source-revision.txt`。

Maintenance changes require a pull request and a passing documentation build. Pull requests validate without deploying. Publication does not write to `main`; the published site retains its revision in `source-revision.txt`.

维护变更须通过 Pull request，并通过文档构建检查。PR 只验证，不会发布；发布流程不写入 `main`，版本记录保存在网站的 `source-revision.txt`。
