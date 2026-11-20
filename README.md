# CLIDE

**Clear IDE.** An IDE for code you didn't type yourself.

CLIDE keeps a plain-language account of every source file beside the code: what each function
does, why it exists, and where it is used. Every passage is tied to the exact lines it
describes, so checking a claim against the code is one hover away.

This repository holds the installers. Nothing else lives here.

## Download

Get the latest version from the [releases page](../../releases/latest) and pick the file for
your system:

| System | File |
| --- | --- |
| macOS, Apple silicon | `CLIDE-mac-arm64.dmg` |
| macOS, Intel | `CLIDE-mac-x64.dmg` |
| Windows | `CLIDE-windows-x64.exe` |
| Linux | `CLIDE-linux-x86_64.AppImage` |
| Debian and Ubuntu | `CLIDE-linux-amd64.deb` |

A release lists only the files that exist for it.

## Install

- **macOS:** open the downloaded file and drag CLIDE into Applications.
- **Windows:** run the downloaded installer.
- **Linux:** install the `.deb` on Debian or Ubuntu. Elsewhere, make the AppImage executable
  (`chmod +x CLIDE-linux-x86_64.AppImage`) and run it. The first time it runs it adds CLIDE to
  your applications, so afterwards you can find it by searching for it like any other app.

Your system may warn you the first time you open it. On Windows choose *More info*, then *Run
anyway*. On macOS open System Settings, then Privacy & Security, and choose *Open Anyway*.

## Using it

Open CLIDE and choose your project's folder. The outline, "Used in", search and writing by
hand work straight away and stay on your computer. To have accounts written for you, open
Settings and choose a plan.

CLIDE tells you in its status bar when a newer version is out.
