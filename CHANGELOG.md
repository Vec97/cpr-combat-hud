# Changelog

All notable changes to **Cyberpunk RED - Combat HUD** are documented here.
This project adheres to [Semantic Versioning](https://semver.org/).

## [1.1.1] - 2026-07-04

### Added
- **Choose Target before attacking**: clicking Attack can now first enter a targeting mode - the cursor turns into a crosshair with a "Choose Target" label, and your next click on a token targets it before the roll (so the roll card and damage application key off that enemy). Right-click, Esc or clicking empty space cancels without rolling.
- New per-user setting **Choose target before attacking** with three modes: *Always ask* (default), *Only when nothing is targeted*, and *Off*.

## [1.0.0] - 2026-07-04

Initial public release.

### Added
- Persistent bottom combat HUD bar for the Cyberpunk RED - CORE system (Foundry VTT V12).
- **Identity**: portrait (opens the sheet), name, alias, roles and live wound state.
- **Hit points**: animated HP bar with -5/-1/+1/+5 buttons and direct entry; colour tracks the wound state.
- **Armor**: head/body SP and shield HP with one-click ablate/repair, synced to the sheet via the system's tracked-armor logic.
- **Vitals**: Humanity, LUCK (spend/regain), Death Save (click to roll, right-click to reset the penalty).
- **Stats**: all ten stats, one click rolls them through the system dialog (Ctrl-click skips the dialog).
- **Weapons**: equipped weapons incl. cyberware weapons and secondary-weapon upgrades, with Attack/Damage, reload, ammo swap and fire-mode toggles (Aimed / Autofire / Suppressive) plus an aimed-location selector.
- **Skills**: searchable flyout grouped by category with the full `STAT + level + mods` total; favourite skills via a star, shown in an expandable row inside the bar.
- **Role abilities** and **netrunner interface** flyout panels.
- **Combat**: roll initiative, current initiative display, and end turn (highlighted on your turn).
- **Weapon management** panel to cycle owned/carried/equipped without opening the sheet.
- Per-user client settings (enable, character fallback, scale, bottom offset) and a rebindable collapse keybind (`H`).
