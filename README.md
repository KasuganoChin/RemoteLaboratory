# RemoteLaboratory

An unofficial SCP: Secret Laboratory 11.2.1 modification with Normal Escape, Office Survival, AI opponents, accounts and experience progression.

**Creator:** KasuganoChin  
**AI development collaboration:** Codex (OpenAI)

## Download and play

Download **RemoteLaboratory-0.1.1-Windows-x64.zip** from [the latest release](https://github.com/KasuganoChin/RemoteLaboratory/releases/latest). This complete modification package includes client modifications, server AI, the account runtime and installer.

1. Obtain the pinned **11.2.1 Client and Server** using the separately provided DepotDownloader commands. Current Steam installations are not interchangeable with these depots.
2. Extract the complete RemoteLaboratory ZIP to a writable folder on Windows 10/11 x64.
3. Double-click **Install-And-Play.cmd**. If prompted, enter the folder containing **Client** and **Server**, or the parent of **Downloads**.
4. Wait while the originals are copied, patches are applied and AI navigation is prepared. The game opens automatically. Use the same entry point next time.

If you have not obtained the base game, leave the folder prompt blank to use the included download helper. DepotDownloader is a separate official tool and handles Steam authentication. A GitHub account and development tools are not required to install the modification.

## Included

- Normal Escape and Office Survival, reviewed difficulty settings and AI behavior.
- Portal, activity configuration, account and experience-shop menus.
- Registration, login, badges, experience progression and cloud settlement.
- A local server/client launcher, verified patches and a self-contained account runtime.
- Independently versioned client, server and runtime update components.

Local guest play is available offline. Online account features require access to the account service. This is a local single-player-with-AI distribution, not a public multiplayer hosting package.

## Updates

### Early Tester registration reward

Accounts registered before **November 8, 2026, 00:00 Beijing time (UTC+8)** automatically and permanently receive **Early Tester**. This includes registrations throughout November 7 and eligible existing accounts. Select it from your owned badges; your currently equipped badge is preserved. This cloud-side update does not require a new game download.

Local players already receive Remote Admin access independently of their badge. Using tracked gameplay-altering admin actions excludes that round from experience scoring; merely owning admin access does not.

Close the game and local server, then run **Start-RemoteLaboratory.cmd** to check for updates, update, repair managed distribution files or roll back. User settings and account caches are preserved. Keep the bootstrap files together. The default installation is the **RemoteLaboratory** subfolder beside the installer.

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
