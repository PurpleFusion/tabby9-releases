# Tabby9 privacy statement

Tabby9 is a desktop app made by Vidos Consulting Pty Ltd. It runs on your computer and doesn't collect information about you. Specifically:

## What Tabby9 reads, on your computer only

- **Claude Code's own files** in `~/.claude`, such as conversation transcripts, to list your conversations, resume them and show usage figures.
- **Your project folders**, the ones you add in Settings, to list projects and show their git status.
- **What Claude's `/usage` screen shows** in a Tabby9 tab, so it can show your real limits.

This information stays on your computer. Tabby9 keeps its own settings, tabs and caches in `%APPDATA%\Tabby9`.

## What Tabby9 sends, and where

- **Update checks:** to GitHub (`github.com/PurpleFusion/tabby9-releases`), to see whether a new version is available and download it. GitHub sees the request as it would any download.
- **Supporters list:** when you open Settings → About & updates, Tabby9 downloads the public list of supporters from the same GitHub repo. Nothing is sent with the request.
- **GitHub features:** only if you use them, and only through your own GitHub CLI (`gh`) sign-in. Examples are creating repos, checking Dependabot alerts and cloning.
- **Claude:** Claude Code, which Tabby9 starts for you, talks to Anthropic under Anthropic's own terms. Tabby9 adds nothing to that.

Tabby9 doesn't send analytics, usage figures, project names, folder paths, conversation content or anything else to Vidos Consulting or anyone else.

## Install ID

Tabby9 creates a random install ID on first run, shown in Settings → About & updates. It contains nothing about you or your computer, and Tabby9 doesn't send it anywhere. If a future version uses it, for example for opt-in usage counts or a licence, you'll be told and asked first.

## Questions

Contact us via https://github.com/PurpleFusion.
