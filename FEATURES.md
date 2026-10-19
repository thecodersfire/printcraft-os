# Built-in features for printcraft-os

Purpose: 3D printing

1. **prepare a creative project** — run printcraft-os-workspace. It creates ~/Documents/printcraft-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run printcraft-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/printcraft-os-session-plans/.
3. **check project and export readiness** — run printcraft-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/printcraft-os-workspace features/printcraft-os-plan features/printcraft-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for 3D printing:

1. **PrusaSlicer** — com.prusa3d.PrusaSlicer
2. **GIMP** — org.gimp.GIMP
3. **Inkscape** — org.inkscape.Inkscape

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for 3D printing:

1. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
2. **KiCad** — design circuits and PCBs (org.kicad.KiCad)
3. **Arduino IDE** — write and upload microcontroller sketches (cc.arduino.IDE2)
4. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
5. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
8. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
9. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)
10. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
