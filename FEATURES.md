# Built-in features for frame-by-frame-os

Purpose: animation

1. **organize project files** — run frame-by-frame-os-workspace. It creates ~/Documents/frame-by-frame-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run frame-by-frame-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/frame-by-frame-os-session-plans/.
3. **check task readiness** — run frame-by-frame-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/frame-by-frame-os-workspace features/frame-by-frame-os-plan features/frame-by-frame-os-check "$HOME/.local/bin/"
