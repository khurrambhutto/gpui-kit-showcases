# Scope

Scope shows every app on your Linux system in one place. It collects apps from APT, Snap, Flatpak, AppImage, and user-local desktop launchers into a single searchable list, so you no longer need to check each package manager separately.

## What it does

- **One list for every source.** APT, Snap, Flatpak, AppImage, and desktop launchers appear together, with source filters and a search bar.
- **Preview before change.** Uninstall and update actions show the exact effect first. Nothing runs until you confirm.
- **Clear details.** Expanded rows show what an app installs and, where it can be measured, how much space removal would free.
- **Privileged steps through Polkit.** Scope never sees your password. System changes go through the standard system authentication dialog.
- **Discovery where management is not yet supported.** AppImages and user-local desktop launchers are listed for discovery. Their update and uninstall actions stay disabled.

## Who it is for

Scope suits people on Ubuntu who install software from several sources and want one place to review, update, and remove it.

Project home and source code: [github.com/khurrambhutto/scope](https://github.com/khurrambhutto/scope).
