# The Ultimate Grind

Now or never.

Daily DSA + dev routine tracker with streaks, weekly stats, a reading log
(novel notes + word/phrase/sentence vocab), quote of the day, and a
one-click JPG daily report export.

## Data storage
All data is stored in the browser's `localStorage` on whichever device you
open the site on — nothing is sent to a server. This means:
- Data does NOT sync across devices/browsers automatically.
- Clearing browser data / private-browsing wipes it.
- Use the **Backup → export data** button regularly to download a JSON
  snapshot, and **import data** to restore it (e.g. after switching
  browsers or devices).

## Deploy
Static site, zero build step. Deploy as-is on Vercel:
1. Import this repo in Vercel.
2. Framework preset: "Other" (no build command needed).
3. Root directory: `/` — Vercel will serve `index.html` directly.
