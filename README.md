# D&D: Designers & Deadlines

A 20-minute classroom game about user-centred design for 2 to 10 teams.

## Files

- `index.html` – the **game board**. Project it. It holds the rules, the cards, the Project Inventory, the timers, the draws of setbacks and testers, the idea levels, the music and the final podium.
- `team.html` – the **team sheet**. Students open it on a phone (one per team) to record cards and purchases. It calculates the score automatically.
- `music/` – optional local copies of the soundtrack (see below).

## Scoring

- **Project Points (PP)** come from your base points, the items in your Project Inventory, combos, sabotages and your setback.
- Your idea level is a label only: Basic Idea (0–7 PP), Solid Idea (8–12 PP), Cool Idea (13+ PP).
- **Tester points:** +10 if you own the tester’s primary feature, +5 if you own only the secondary one, −5 if you own neither.
- **Final score: count your points!** Final score = Project Points + tester points. The Team Sheet calculates it automatically.

## Publish on GitHub Pages

1. Create a repository and upload `index.html`, `team.html` and (optionally) the `music` folder.
2. Go to **Settings → Pages**, choose the `main` branch and the root folder, then save.
3. Open `https://YOUR-NAME.github.io/REPO-NAME/` on the projector. The welcome screen shows a QR code that points students to `team.html`.

## Music

| Moment | Track | Local file |
| --- | --- | --- |
| How to play, 1st and 2nd Deadline, “You’ve got an idea!”, “You have turned your idea into a project!” | Game Show Loop | `music/explain.mp3` |
| Decision timers (closing, setbacks, Prototype and Test) | Ticking Shadows | `music/decision.mp3` |
| Winner reveal | Finché Resterà un Dado | `music/victory.mp3` |

Each track first looks for the local file, then tries the Suno CDN. For a reliable classroom session, download the three songs from Suno and put them in a `music` folder with the names above.

## Facilitator keys

- Right arrow, Page Down or Space: next
- Left arrow or Page Up: back
- T: start or pause the timer
- R: reset the timer
- N: speaker notes
- M: music on or off
