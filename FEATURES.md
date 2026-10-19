# Built-in features for printcraft-os

Purpose: 3D printing

1. **prepare a creative project** — run printcraft-os-workspace. It creates ~/Documents/printcraft-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run printcraft-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/printcraft-os-session-plans/.
3. **check project and export readiness** — run printcraft-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/printcraft-os-workspace features/printcraft-os-plan features/printcraft-os-check "$HOME/.local/bin/"
