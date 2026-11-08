# Scanner Run

A radiographer-themed endless runner, inspired by the Chrome dinosaur game. Jump and duck past MRI and CT scanners, C-arms, trolleys, IV stands and MRI-unsafe oxygen cylinders.

## Controls

- Space or Up arrow: jump
- Down arrow: duck (or drop faster in mid-air)
- Touch: tap the game or use the on-screen buttons

## Leaderboard

Scores are saved to a Supabase table (rad_jump_scores) and the top 10 show under the game. The publishable key in index.html is safe to expose because row-level security only allows reading scores and adding new ones.

## Run locally

Open index.html in a browser. No build step or dependencies.

## Deploy

Static site. Import the repository into Vercel with the **Other** framework preset and leave the build command and output directory empty.
