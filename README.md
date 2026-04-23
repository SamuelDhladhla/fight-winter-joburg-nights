# Studio Bananaaaa — FIGHT WINTER: JOBURG NIGHTS

## Files
- `fight-winter-joburg-nights-supabase.html` — final game file
- `fight-winter-supabase.sql` — leaderboard table and policies

## What is already wired in
- Supabase project URL
- Supabase publishable key
- player name input
- score submission on knockout
- live leaderboard fetch from Supabase
- local fallback if Supabase is unavailable

## Deploy
1. Rename `fight-winter-joburg-nights-supabase.html` to `index.html`.
2. Upload `index.html` to your GitHub repo root.
3. Commit and push.
4. In GitHub, open Settings → Pages.
5. Set source to deploy from the main branch.
6. Save and wait for the site to publish.

## Supabase
1. Open SQL Editor in Supabase.
2. Run the contents of `fight-winter-supabase.sql`.
3. Done.

## Leaderboard fields
- player_name
- fighter_name
- score
- round
- created_at

## Notes
- If Supabase is unavailable, scores still save locally in the browser.
- Player names are trimmed to 12 characters and forced to uppercase.
