# RemoteLaboratory 0.1.2 - Online News

## Added

- A dedicated News tab after Accounts, with an unread count, read history and persistent per-account read state on each installation. The count disappears once all messages have been marked as read.
- Online announcements, with scheduled publication, pinning, expiry, withdrawal and offline caching. News checks run at startup, when opening News with a one-minute cooldown, and every five minutes while running.
- Confirmed badge notifications and automatic Gunfighter ownership after an accepted Hard Office Survival settlement with at least 15 completed waves. Your equipped badge is preserved; gameplay-altering RA actions remain excluded from scoring.
- A vertically scrollable Portal gallery with two disabled Coming Soon entries. These are placeholders, not playable activities.

## Download and update

New players: download **RemoteLaboratory-0.1.2-Windows-x64.zip**, extract the entire archive and run **Install-And-Play.cmd**. The exact separately obtained 11.2.1 Client and Server depots are still required.

Existing players: close the game and local server, then use **Start-RemoteLaboratory.cmd** to update. Player settings and account caches are preserved. Version 0.1.1 must be updated before it can receive in-game news.

A clearly labeled TEST ANNOUNCEMENT is available briefly for delivery verification. It grants no EXP, badge or permissions and expires automatically.

## Validation

- Public-only release account service received the live test announcement in a separate installation, without a privileged Supabase credential.
- Actual in-game read controls cleared the unread count; a full restart preserved read history and the zero-unread state.
- Anonymous publishing is denied; authenticated players have no announcement write grants. Scheduled private test content was invisible to the public role.
- 28 notification checks and 37 installer regression checks passed. Hard 14/15/30-wave and Normal 15-wave badge boundaries were checked in a rolled-back database transaction.
- Both server and client started from the updated distribution. These checks ran on the development computer, not on a second physical PC.

SCP-1507 remains disabled and the selectable SCP maximum remains seven. Imported SCP-173/SCP-1507 assets and private administration tools are excluded. News read state is local to each account and installation, not synchronized across computers.

Creator: KasuganoChin. AI development collaboration: Codex (OpenAI).
