# RemoteLaboratory

An unofficial SCP: Secret Laboratory 11.2.1 modification with Normal Escape, Office Survival, AI opponents, accounts and experience progression.

**Creator:** KasuganoChin  
**AI development collaboration:** [Codex](https://github.com/codex) (OpenAI)  
[Contributors](CONTRIBUTORS.md)

## Download and play

Download **RemoteLaboratory-0.1.3-Windows-x64.zip** from [the latest release](https://github.com/KasuganoChin/RemoteLaboratory/releases/latest). This complete modification package includes client modifications, server AI, the account runtime and installer.

1. Obtain the pinned **11.2.1 Client and Server** using the separately provided DepotDownloader commands. Current Steam installations are not interchangeable with these depots.
2. Extract the complete RemoteLaboratory ZIP to a writable folder on Windows 10/11 x64.
3. Double-click **Install-And-Play.cmd**. If prompted, enter the folder containing **Client** and **Server**, or the parent of **Downloads**.
4. Wait while the originals are copied, patches are applied and AI navigation is prepared. The game opens automatically. Use the same entry point next time.

If you have not obtained the base game, leave the folder prompt blank to use the included download helper. DepotDownloader is a separate official tool and handles Steam authentication. A GitHub account and development tools are not required to install the modification.

## Included

- Normal Escape with playable Nightmare difficulty: disabled account bonuses, double SCP health, x50 EXP and a 250000 round limit.
- Office Survival, reviewed difficulty settings and AI behavior.
- Portal, activity configuration, account and experience-shop menus.
- Online News with unread indicators, read history, offline caching and confirmed badge notifications.
- Automatic Gunfighter unlock after accepted Hard Office Survival results with at least 15 completed waves.
- Registration, login, badges, experience progression and cloud settlement.
- A local server/client launcher, verified patches and a self-contained account runtime.
- Independently versioned client, server and runtime components, all included inside the complete ZIP.

Local guest play is available offline. Online account features require access to the account service. This is a local single-player-with-AI distribution, not a public multiplayer hosting package.

## Updates

### Early Tester registration reward

Accounts registered before **November 8, 2026, 00:00 Beijing time (UTC+8)** automatically and permanently receive **Early Tester**. This includes registrations throughout November 7 and eligible existing accounts. Select it from your owned badges; your currently equipped badge is preserved. This cloud-side update does not require a new game download.

Local players already receive Remote Admin access independently of their badge. Using tracked gameplay-altering admin actions excludes that round from experience scoring; merely owning admin access does not.

To upgrade from **0.1.2 or earlier**, close the game and local server, download the complete 0.1.3 ZIP and extract it into the same folder as your existing **Install-And-Play.cmd**, replacing the launcher files and keeping the **RemoteLaboratory** game subfolder. Run **Install-And-Play.cmd** to update before launching. Custom install paths can be supplied with **Install-And-Play.ps1 -InstallDirectory**. Settings and account caches are preserved; no new base-game download is needed.

Version 0.1.3 distributes one complete ZIP instead of separate component attachments. The older updater requires this first manual bundle upgrade. The included newer **Start-RemoteLaboratory.cmd** supports future complete-bundle updates, repair and rollback. Keep all bootstrap files together.

The first full game distribution is **0.1.0**; its CLI bootstrap is **0.2.0**. The in-game legacy build label is separate from the distribution version.

## Base game and models

Original game executables and complete original DLL/resource files are not included. Patches apply locally to verified Steam depot inputs:

| Component | App | Depot | Manifest |
| --- | --- | --- | --- |
| Client | 700330 | 700331 | 193310193313059048 |
| Server | 996560 | 996561 | 9041139426033264575 |

Imported SCP-173 and SCP-1507 models, animation, textures and audio are excluded. SCP-173 uses the base game's original appearance; SCP-1507 is disabled until its model is available. The maximum selectable SCP roster is seven. Optional model importing is not included in this release.

The archive includes credits and runtime license notices. This project is not affiliated with or endorsed by Northwood Studios.

This repository contains reviewed public distribution information and release attachments. Installer and development source are maintained separately.
