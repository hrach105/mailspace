# Mailspace 0.3.4 — Clean Google sign-in finish beta








Multiple Gmail accounts, Calendar and Drive file-name search in one Windows and macOS desktop app.








[Website](https://mailspace-desktop.neatshark1024.chatgpt.site/) · [Download Windows installer 0.3.4](https://github.com/hrach105/mailspace/releases/download/v0.3.4-beta/Mailspace-0.3.4-Setup.exe) · [Release notes and checksum](https://github.com/hrach105/mailspace/releases/tag/v0.3.4-beta)








## Google sign-in finish

The local desktop OAuth callback redirects to a branded connected, cancelled or failed page with a clean website URL. No authorization code, state or account data is forwarded; the redirect suppresses the referrer. Install 0.3.4 manually to use this flow.

## Account switching


Account selection no longer toggles silently to All accounts. Inbox headings show the Gmail address. Old results are cleared, late replies ignored and Google mailbox identity checked before listing mail. A session mismatch requires reconnecting the selected Gmail.


## Updates & recovery




Settings → Updates & recovery checks new versions and creates/restores encrypted workspace backups. Install 0.3.4 manually once. Five recent snapshots stay local and require the original OS profile; restoring undoes later changes. Automatic installation remains disabled until publisher signing and real upgrade testing are complete. This is local data recovery, not automatic binary rollback.
