# MAFI plugin marketplace

The MAFI 2026 brand plugins for Claude. They work in Claude on the web, the desktop app (Chat and Cowork), mobile chat and Claude Code.

| Plugin | What it is |
|---|---|
| **MAFI 2026** | The complete MAFI brand pack: company, 26 products, voice, visual identity, creative playbook, approved assets and reference work |
| **MAFI 2026 – IQF Photos** | The 12 IQF top-view product photos in 4K, a companion to MAFI 2026 |

## Install in Claude (web or desktop app)
1. Go to **Customize → Plugins → Add → Add marketplace**.
2. Paste `https://github.com/the0genius/mafi-2026-plugins` and confirm.
3. Click **Install** on **MAFI 2026**, then on **MAFI 2026 – IQF Photos**.

The plugins follow your Claude account into chat, Cowork, mobile and Claude Code. You need a paid Claude plan.

## Install in Claude Code
If you installed from the Claude app above, the plugins already sync to Claude Code, so there's nothing more to do. To install from the command line instead:
```
/plugin marketplace add the0genius/mafi-2026-plugins
/plugin install mafi-2026@mafi
/plugin install mafi-2026-iqf-photos@mafi
```
The download is about 250 MB. Claude Code allows 2 minutes by default, so on a slower connection, set this environment variable before starting Claude Code: `CLAUDE_CODE_PLUGIN_GIT_TIMEOUT_MS=900000` (15 minutes).
