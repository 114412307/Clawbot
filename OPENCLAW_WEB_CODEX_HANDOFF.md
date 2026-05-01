# OpenClaw Web Codex Handoff

This document captures a practical handoff flow for continuing the task **「下載 openclaw」** between Desktop Codex and Web Codex.

## Task Context

- Task name: `下載 openclaw`
- Local project path (desktop environment): `C:\Users\user\Documents\Codex\2026-05-01\openclaw`
- Repository: `https://github.com/openclaw/openclaw`
- Package: `openclaw`
- Version: `2026.4.30`
- Description: `Multi-channel AI gateway with extensible messaging integrations`

## Web Codex Prompt Template

Use this in a new Web Codex chat:

```text
我要接續我在程式版 Codex 的任務：「下載 openclaw」。

本機專案位置是：
C:\Users\user\Documents\Codex\2026-05-01\openclaw

專案資訊：
- package name: openclaw
- version: 2026.4.30
- repository: https://github.com/openclaw/openclaw
- description: Multi-channel AI gateway with extensible messaging integrations

請協助我繼續處理 OpenClaw 的下載、安裝、設定、啟動或同步到 GitHub/Web Codex 的流程。若需要同步檔案，請優先使用 GitHub repo 或 PR 作為桌面版與網頁版 Codex 的共同同步點。
```

## Recommended Sync Workflow

1. Ensure Git is installed and available on the desktop machine.
2. Commit local OpenClaw changes to a branch.
3. Push branch to GitHub.
4. Open the same repo/branch (or PR) in Web Codex.
5. Continue implementation and review via PR updates.

## Note

If desktop Codex cannot use `git` in the current shell, install/repair Git and restart the shell before retrying.
