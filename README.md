# RemoteLaboratory

SCP: Secret Laboratory AI and PvE project by **KasuganoChin**.

**AI development collaboration:** Codex (OpenAI).

## Downloads

[Download the CLI installer preview](https://github.com/KasuganoChin/RemoteLaboratory/releases/tag/installer-v0.1.1).

**Current status: installer preview only. A complete playable game package is not available yet.** This preview establishes installation, component updates, repair and rollback; it does not include the enemy AI game payload.

1. Download `RemoteLaboratory-Installer-0.1.1.zip` from Releases.
2. Extract all files together.
3. Run `Start-RemoteLaboratory.cmd` on Windows.

Public downloads require no GitHub account or token. Game installation will become available when a reviewed game release catalog is published. Steam credentials, when needed for the base game, are entered directly into the official DepotDownloader.

## Updates

Client, server and runtime packages have independent versions. Existing installations download changed components only, preserve player settings and support rollback. Close the game and local server before updating.

This repository holds public distribution documentation and reviewed release artifacts. Installer development source and tests are maintained separately in a private repository. Future game packages will be distributed through Releases, not committed into this repository.

No original game binaries, SCP-173/SCP-1507 model resources, server secrets or player data are included in this installer preview. The base game is downloaded separately through Steam/DepotDownloader. Custom model integration points are planned for the game distribution.

Installer SHA-256:

```text
eab23fa126147d3b941f9f72f675a91e7b3bb0a5a9b21cf9993d94cec251f5b5
```
