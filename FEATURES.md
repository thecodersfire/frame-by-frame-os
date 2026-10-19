# Built-in features for frame-by-frame-os

Purpose: animation

1. **organize project files** — run frame-by-frame-os-workspace. It creates ~/Documents/frame-by-frame-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run frame-by-frame-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/frame-by-frame-os-session-plans/.
3. **check task readiness** — run frame-by-frame-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/frame-by-frame-os-workspace features/frame-by-frame-os-plan features/frame-by-frame-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for animation:

1. **GIMP** — org.gimp.GIMP
2. **Inkscape** — org.inkscape.Inkscape
3. **Kdenlive** — org.kde.kdenlive

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for animation:

1. **OBS Studio** — record or stream sessions (com.obsproject.Studio)
2. **VLC** — review media files (org.videolan.VLC)
3. **Audacity** — edit audio recordings (org.audacityteam.Audacity)
4. **Scribus** — lay out print-ready publications (org.scribus.Scribus)
5. **GNOME Sound Recorder** — capture voice and field notes (org.gnome.SoundRecorder)
6. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
7. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
8. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
9. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
10. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
