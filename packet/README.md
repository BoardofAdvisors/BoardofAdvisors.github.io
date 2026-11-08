# BA Q4 Agenda Packet (2026-11-08)

Everything McCoy needs for the Q4 Summit agenda page and the agenda email, in one place. No artifact login needed.

## Live pages
- Members' agenda (live, V149): https://boardofadvisors.github.io/
- Agenda email, web view (V7.59): https://boardofadvisors.github.io/email/q4-agenda.html

## Files in this repo
- `index.html` (repo root) = the live members' page, self-contained (images inlined).
- `agenda/data/agenda.V149.json` = the agenda data of record (69 sessions, config, days, CTAs).
- `email/q4-agenda.html` = the Mailchimp campaign HTML (merge tags such as `*|UNSUB|*` show raw in the browser; Mailchimp fills them on send).
- `packet/q4-agenda-packet-2026-11-08.zip` (8 MB) = the full source set:
  - `agenda/index.html` = page source with external images (not inlined), `agenda/bg/`, `agenda/images/` (advisor portraits, brand marks), `agenda/data/agenda.V149.json` + `agenda.json`
  - `email/EmailAgenda-V7.59-mailchimp.html` + the email's hosted assets (day headers, icons, portraits)
  - `text/` = the members' MMS copy (text-exit-track-agenda-V1.04.txt), its hero image and a phone read-back

## Notes for hosting
- The page is static HTML; serve `index.html` at the mask URL (baagenda.com) with a 301 or a projection feed; no build step.
- Logo link = https://www.boardofadvisors.com; CTA buttons = www.RSVPBA.com, www.BARooms.com, www.BAInvite.com, www.ExitTrack.com; Support = Team@BoardofAdvisors.com.
- The data of record is the Agenda (Master) board; the page is re-projected from `agenda.V149.json` on each batch. Later versions land here as `agenda/data/agenda.V15x.json` and a new `index.html`.

Questions: Team@BoardofAdvisors.com
