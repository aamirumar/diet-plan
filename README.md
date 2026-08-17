# 6-Week Fat-Loss Workout & Diet Plan

A single, plain-HTML page (no build step, no dependencies) with two tabs:

- **Plan** — the workout schedule, weekly split, exercises, 7-day food plan and nutrition targets.
- **Daily Tracker** — a form to log date, morning weight, steps, workout/diet adherence and notes. Entries are saved in the browser's `localStorage`, so they stay on whichever device/browser you use to log them. Use **Export CSV** any time to back up your data.

## Run locally

Just open [index.html](index.html) in a browser — no server needed.

## Publish with GitHub Pages

1. Create a new repo on GitHub (e.g. `diet-plan`) — don't initialize it with a README.
2. From this folder:
   ```
   git add .
   git commit -m "Initial diet plan site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source → Deploy from a branch**, pick `main` / `(root)`, save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Notes

- Tracker data lives only in the browser's localStorage — it is **not** synced across devices and is **not** pushed to GitHub. Clearing browser data/history will erase it, so export a CSV backup periodically if you care about the history.
- Everything is a single static `index.html` file, so future edits to the plan or tracker just mean editing that file and pushing again.
