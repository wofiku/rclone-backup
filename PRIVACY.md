# Privacy Policy

_Last updated: 2026-10-27_

## What this application is

`rclone-backup` is a private, single-user OAuth client for the open-source tool
**rclone**. It is used by its owner to upload age-encrypted backups of the owner's
servers to the owner's own Google Drive.

## What data it accesses

- **Google Drive** (`https://www.googleapis.com/auth/drive` or a narrower scope):
  used only to list, create and delete files in the folder `Бэкапы` of the
owner's own Drive.
- OAuth credentials (access and refresh tokens) are stored locally, on the
owner's machine and server, in `rclone.conf` with file permissions `600`.

## What it does not do

- No analytics, telemetry, advertising or tracking.
- No collection of personal data beyond the OAuth token needed for the operation.
- No sharing, sale or transfer of data to any third party.
- No access to any Drive other than the owner's own account.

## Data retention and removal

Data stored in Google Drive remains there until the owner deletes it, and can be
removed at any time via rclone or the Drive web interface. The OAuth grant can be
revoked at any moment at <https://myaccount.google.com/permissions>, which
immediately invalidates the stored tokens.

## Contact

Repository owner: <https://github.com/wofiku>
