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

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
2. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
3. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
4. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
5. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
6. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
7. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
8. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
9. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
10. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
11. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
12. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
13. **VSCodium** (com.vscodium.codium) — edit code and project files.
14. **GNOME Calendar** (org.gnome.Calendar) — schedule sessions, deadlines, and events.
15. **VLC** (org.videolan.VLC) — review media files.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Gwenview** (org.kde.gwenview) — review image sets and make quick crop, resize, and annotation edits.
2. **KolourPaint** (org.kde.kolourpaint) — make quick raster sketches, labels, and simple image edits.
3. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
4. **KDevelop** (org.kde.kdevelop) — edit, navigate, build, and debug software projects.
5. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
6. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
7. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
8. **Ark** (org.kde.ark) — open and create common project archive files.
9. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
10. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
11. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
12. **KDiff3** (org.kde.kdiff3) — compare and merge source files and directory trees.
13. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
14. **Kamoso** (org.kde.kamoso) — capture webcam photos and short video clips.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for 3D printing. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **Shotcut** (org.shotcut.Shotcut) — Edit multitrack video with filters, transitions, and titles.
2. **HandBrake** (fr.handbrake.ghb) — Transcode video files to common formats and presets.
3. **OpenShot** (org.openshot.OpenShot) — Assemble video clips on a multitrack timeline.
4. **Glaxnimate** (org.kde.glaxnimate) — Create vector animations, motion graphics, and animated SVG assets.
5. **Subtitle Composer** (org.kde.subtitlecomposer) — Create and synchronize captions for video projects.
6. **KPhotoAlbum** (org.kde.kphotoalbum) — Tag and organize large photo collections.
7. **Kid3** (org.kde.kid3) — Edit audio tags and album metadata in batches.
8. **Loupe** (org.gnome.Loupe) — View images and make simple crop, rotate, or flip edits.
9. **Kasts** (org.kde.kasts) — Subscribe to podcasts and manage playback queues.
10. **Jellyfin Desktop** (org.jellyfin.JellyfinDesktop) — Browse and play personal media from a configured Jellyfin server.
11. **KWave** (org.kde.kwave) — Record and edit audio waveforms.
12. **Elisa** (org.kde.elisa) — Organize and play a local music library.
13. **EasyEffects** (com.github.wwmm.easyeffects) — Adjust audio input and output with equalizers and effects.
14. **Audacity** (org.audacityteam.Audacity) — Record and edit audio tracks and voice recordings.
15. **Ardour** (org.ardour.Ardour) — Record and mix multitrack audio sessions.
