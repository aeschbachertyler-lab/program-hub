# Program Hub

A single-page football staff tool for game day, practice and the playbook — offense, defense and special teams in one place. No install, no server: it's one `index.html` file.

## What's in it

**Game day**
- **Chart** — log every snap (O / D / K) by wristband #, call #, or by typing the call; down, distance and yard line advance automatically. A live "Read" card shows tendencies for the current down & distance.
- **Play log** — every snap, tap to edit, export to CSV.
- **Offense / Defense / Special teams / Players** — success rate, explosives, run/pass splits by down & distance, field zone, formation family, personnel, front, coverage, blitz; box score and individual stats.

**Practice**
- **Scripts** — reps with period/drill, hash, down & distance, field position, call # and scout look #. Paste straight from an Excel practice script (include the `MCS # · # · U · H · D · DIS · FP · P · WB · Full Play · Defensive call` header row).
- **Scout cards** — each rep drawn on a to-scale field (yard lines, numbers, hashes, ball on the scripted hash and yard line) with the scout look in red over your call, plus every player's responsibility. Full-screen flip mode and printable download.

**Playbook**
- **Library** — numbered calls for offense, defense and special teams, plus scout looks (opponent defenses, offenses, ST). Draw each one on the field, set every player's responsibility, and see its game results: times called, yards, success / def win, by down & distance, coverage, front, hash, every rep.
- **Call sheet** — situation boxes (Openers, Run game, 3rd & 4-5, High red, …) built from library calls, with tally and success filling in live. The box for the current situation lights up.

**Setup** — your own terminology (the call parser learns it), wristband cards per game (`wristband # = call #`), success/explosive rules, field zones, field style and hash marks (college / high school / NFL).

## Run it

- **Locally:** download `index.html` and open it in Chrome or Safari.
- **GitHub Pages:** repo **Settings → Pages → Deploy from a branch → `main` / root**. The app is then at `https://<your-username>.github.io/<repo-name>/`.

## Where data lives

Everything is saved in the browser you use (localStorage) — nothing is sent anywhere. That means:
- Data does **not** sync between devices or staff members yet.
- Clearing browser data erases it. Use **Play log → Download CSV** to back up a game.
- Uploaded play photos fill browser storage quickly; drawing in the app uses far less space.

## Sample data

The app opens with a made-up sample game, playbook and practice scripts so every screen has something in it. **Setup → Start blank game** and **Clear terminology** reset it for real use.

## Roadmap

- Accounts + shared storage so one person charts and the whole staff sees it live
- Practice results by rep (success by call vs. each scout look)
- Opponent film mode for scouting reports
- Special teams timer and workbook integration

---
© Ty Aeschbacher. All rights reserved.
