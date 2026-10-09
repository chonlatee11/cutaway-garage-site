# Privacy policy — Cutaway Garage poster

Last updated: 2026-10-09

**What this tool is.** Cutaway Garage poster is a command-line program run by the owner of the Cutaway Garage YouTube
channel on the owner's own computer. It uploads videos made by the owner to the owner's own channel through the YouTube
Data API v3 and posts one comment on each video. It is used by exactly one person, the channel owner, and is not offered
to anyone else.

**Google user data it accesses.** With the owner's consent it uses the OAuth scopes
`https://www.googleapis.com/auth/youtube.upload` (upload videos and set their title, description, tags and publish
time) and `https://www.googleapis.com/auth/youtube.force-ssl` (post the comment, delete a scheduled video). It does not
read the channel's analytics, subscribers, other videos, comments by viewers or any data about other YouTube users.

**Storage.** The OAuth refresh token is stored in a plain file on the owner's computer, readable only by the owner.
The tool keeps a local log of the video ids it uploaded. Nothing is sent to any server other than Google's APIs.

**Sharing.** No data is shared with, sold to or transferred to any third party.

**Retention and deletion.** The owner can revoke the tool's access at any time at
https://myaccount.google.com/permissions, which invalidates the stored token. Deleting the local `.env` file removes the
token from the computer.

**YouTube API Services.** This tool uses YouTube API Services. By using it the owner agrees to the
[YouTube Terms of Service](https://www.youtube.com/t/terms) and acknowledges the
[Google Privacy Policy](https://policies.google.com/privacy).

**Contact.** Through the Cutaway Garage channel's About page.
