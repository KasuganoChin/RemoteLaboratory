# RemoteLaboratory 0.1.0

First complete playable modification distribution for the pinned SCP: Secret Laboratory 11.2.1 client and server.

## Install

Download **RemoteLaboratory-0.1.0-Windows-x64.zip**, extract all files and run **Install-And-Play.cmd**. When asked, enter the folder containing the downloaded Client and Server folders. The installer preserves the original downloads and starts the local game after preparing AI navigation.

Requires Windows 10/11 x64 and the exact base-game depots listed in the README. Base-game downloads are separate. Online account features require access to the configured account service.

## Contents

- Normal Escape and Office Survival gameplay, AI, difficulty settings and menus.
- Account registration/login, badges, cloud experience and experience shop.
- Client/server patches and a self-contained account runtime.
- CLI bootstrap 0.2.0 with install, launch, update, repair and rollback controls.

The complete ZIP is the recommended player download. Individual component ZIPs and `release-catalog.json` support launcher updates; they are not standalone installers. `SHA256SUMS.txt` covers the downloadable packages.

## Verification

Installed into a separate clean directory using verified original depot files. Normal Escape and Hard Office Survival entered actual game rounds. Four-character-password registration, login, nickname projection, experience settlement, duplicate-submission protection and session restoration were checked. Installer checks: 37 passed; gateway validation checks: 22 passed. A second physical computer remains a separate acceptance test.

## Model compatibility

Imported SCP-173 and SCP-1507 assets are not distributed. Original base-game 173 and the original Tutorial appearance for role 21 are used. The in-game legacy build label is separate from the distribution version.

Creator: **KasuganoChin**. AI development collaboration: **Codex (OpenAI)**.
