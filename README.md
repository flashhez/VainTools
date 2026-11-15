# Vain Tools

Windows tools for a gaming PC, made by VAIN: a toolbox for the system and the GPU driver, a task manager that sets priorities and affinity per game, a Start menu and taskbar of their own, and screenshots made for sharing results.

This page holds the released files. The source is not public.

## Install

Vain Tools is made for Windows set up by the [Vain Playbook](https://github.com/flashhez/Vain-Playbook) and is installed only by it, as one of its steps. It isn't meant for a system set up any other way.

## What's in it

- **Vain Toolbox**: installs and cleans up the GPU driver, keeps NVIDIA and AMD tuning profiles, sets interrupt affinity for every device, and handles Windows settings: startup apps, power plan, network, sound, display, optional features, Store apps and cleanup.
- **Vain Governor**: a task manager that shows every process and thread with its priority, and sets CPU affinity and scheduler behaviour per app. Its Thread Director (early beta) puts a game's busiest threads on the best cores while it runs.
- **Vain Tools**: runs in the tray and brings the rest together: the hotkeys, the GPU profiles, the Governor's rules, screenshots, the taskbar and window tweaks.
- **Vain Start**: a Start menu of its own, in place of the one in Windows.
- **Vain Shell**: Vain's look for the Windows 11 taskbar, the context menus and File Explorer, with icons of its own.

What changed in each release: the [Vain Playbook's changelog](https://github.com/flashhez/Vain-Playbook/blob/main/CHANGELOG.md).

## Updates

Vain Toolbox > Home > the download button in the top right corner. It checks this page and updates only the files that changed, so updating the Governor restarts only the Governor.

## Windows warnings

The programs are signed with VAIN's own certificate, so Windows shows their publisher as unknown.

## Licences

Vain Tools is free to use, personally and commercially; see [LICENSE.txt](vain/LICENSE.txt). Please share the link to this page or to the playbook rather than the files themselves. It includes Microsoft's Windows App SDK and other third-party software under their own licences, listed in [THIRD-PARTY-NOTICES.txt](vain/THIRD-PARTY-NOTICES.txt). Both are installed with Vain Tools, in `C:\Program Files\vain`.

[vain.zone](https://vain.zone)
