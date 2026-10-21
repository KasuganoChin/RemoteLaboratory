# RemoteLaboratory

An unofficial SCP: Secret Laboratory 11.2.1 AI and PvE game modification.

**Creator:** KasuganoChin  
**AI development collaboration:** Codex (OpenAI)

## Distribution

This public repository is reserved for reviewed, playable RemoteLaboratory releases. A game content package must work with the separately downloaded, matching client and dedicated server depots. It must include the project-authored runtime, enemy AI, Normal Escape and Office Survival modes, menus, account integration and required local installation patches.

**The complete game distribution is currently being prepared. No playable release is available yet.** An installer framework alone is not a game release.

## Installation requirements

- Windows and the exact supported SCP: Secret Laboratory 11.2.1 client and server depots, obtained separately using DepotDownloader.
- A reviewed RemoteLaboratory game release, once available.
- No development workspace, SDK, private repository access or maintainer credentials should be needed by players.

The installer is a supporting tool. Its development source and regression tests are maintained separately from this public game distribution.

## Release requirements

Each release must install and launch on a clean base-game installation, provide independently updateable client/server/runtime packages, preserve player settings and support rollback. Release notes must identify the required base version and verified installation procedure.

Original game binaries and SCP-173/SCP-1507 model resources are not bundled. Optional model integration points must tolerate missing user-provided resources.

Public packages must exclude privileged account-service credentials, personal account caches, player records, development logs and test fixtures.
