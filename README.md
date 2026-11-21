# Golds Yeeps Menu 🍋

**Experimental LemonLoader / MelonLoader DLL for Quest. This build has NOT been tested in Yeeps.**

## Download to Quest

**[Download GoldsYeepsMenu.dll](https://github.com/mmayteacher-tech/GoldsMenuforvr/raw/refs/heads/main/GoldsYeepsMenu.dll)**

In your **Quest browser**, open the link above, then use **CX File Explorer → Downloads** to find the downloaded file.

> A DLL is **not** an APK: it cannot be installed by tapping it in CX File Explorer. It must be loaded by a compatible MelonLoader/LemonLoader runtime. We have **not confirmed Yeeps 2.33.2 compatibility**. Do not patch or uninstall your original Yeeps game just to download this file.

## What v0.4 includes (coded, not tested in-game)

- A black-and-gold **Golds Yeeps Menu**, with optional green-and-gold **GMoney** theme.
- Dual lower-grip toggle, left-wrist pose, right-controller trigger/proximity UI interaction.
- Pages: Powers, Items, Spawner, Teleport, Theme and Debug.
- **Local Unity primitive object tests**: cube, sphere, capsule, cylinder; a maximum of 24 at a time, and Clear Props.
- Preview controls for powers, item favorites, player coordinates and teleport.

**It does not provide working Yeeps inventory/item spawning, unlocked items, real multiplayer abilities, anti-cheat evasion, or confirmed server compatibility.** Local geometric test objects are *not* Yeeps inventory items.

## Build

Built on Windows with **.NET SDK 11.0.100** targeting **net8.0**, referencing `LavaGang.MelonLoader 0.6.5`. Compilation completed with **0 errors and 0 warnings**. Successful compilation is **not** proof of a successful Quest runtime test.

**File:** `GoldsYeepsMenu.dll` — **28,160 bytes**.

**SHA-256:** `ED56CCA19B6E73C598A8764E8A5EB2A6FDC471280AFF792E5F7B9346E606F7E1`

## Safety and sharing

This repository contains only the experimental menu plugin and its project files, **not** the copyrighted Yeeps APK, any game assets, accounts, or login data. Keep personal backups before testing third-party Android modification tools.
