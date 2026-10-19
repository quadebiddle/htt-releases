# Head To Tail releases

Installers for the Head To Tail (HTT) film production apps. This repo holds only the installers and their release notes; there's no source code here.

## HTT - Ingest

Copies camera, sound and stills cards onto several drives at once and checks every copy before a card is marked safe to format.

**Windows:** download `HTT-Ingest-<version>-windows-setup.exe` from [Releases](../../releases) and run it. It installs for you only (no admin password), with a desktop shortcut.

The first time, Windows may say "Windows protected your PC", because the installer isn't code-signed yet. Click **More info**, then **Run anyway**.

After that, Ingest updates itself. The version button at the top right shows what's new, the update channel (Stable or Beta) and **Check for updates**. Updates need the internet only for the check; Ingest works fully offline.

**Mac:** coming later.

## How updates work

`updates.json` lists every release. Each installed app reads it to offer new versions, and checks each installer's size and SHA-256 against it before running it.

## Licence

Copyright (c) 2026 Head To Tail. All rights reserved.

These builds are shared for testing by invitation. Please don't redistribute, decompile or reverse engineer them.
