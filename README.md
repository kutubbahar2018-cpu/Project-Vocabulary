# Project শব্দ

**প্রতিদিন নতুন শব্দ, প্রতিদিন নতুন তুমি · New words every day. A new you.**

A free vocabulary app for English learners in Bangladesh, with English and Bengali (বাংলা) support. Learn words level by level, check them with quizzes, and watch your progress grow.

**Live app:** https://kutubbahar2018-cpu.github.io/Project-Vocabulary/

## Features

- **Levels from easiest to hardest.** Level 1 has the easiest words and the last level has the hardest.
- **Difficulty tag on every level** (Easy, Medium, Hard, Very hard).
- **Word collections**
  - IBA & Job: Word Smart 1 & 2, GRE Hit Parade, SAT Hit Parade (20 words per level)
  - Vocabulary for Varsity: Vocabulary for Varsity, Idioms and Phrases, GRE and SAT lists
  - Master Collection: The 2400 (coming soon)
- **Quizzes:** a practice quiz after each level, a Mega Quiz after every 5 levels, and a Final Quiz for the whole section.
- **Active recall:** words you have learned come back for review, and tricky words come back sooner.
- **Progress page:** streak, quiz average, 14-day activity, skills and levels.
- **English / বাংলা switch** across the whole app.
- **Works offline** after the first visit, and can be installed on a phone or computer.

## Install it as an app

- **Android (Chrome):** tap the install button in the app, or open the ⋮ menu and choose **Install app**.
- **iPhone (Safari):** tap **Share**, then **Add to Home Screen**.
- **Computer (Chrome or Edge):** click the install icon at the right of the address bar.

## Files in this repository

| File | What it does |
|---|---|
| `index.html` | The whole app (pages, word lists, quizzes and styles) |
| `manifest.webmanifest` | Name, colors and icons for installing the app |
| `sw.js` | Lets the app open offline |
| `icons/` | App icons (`icon-192.png`, `icon-512.png`, `maskable-512.png`, `apple-touch-icon.png`) |

Keep `manifest.webmanifest`, `sw.js` and the `icons` folder in the same place as `index.html`.

## Update the app

1. Open this repository on GitHub and choose **Add file → Upload files**.
2. Upload the new file with the **same name** (for example `index.html`). It replaces the old one.
3. Click **Commit changes**.
4. Wait a minute, then hard-refresh the live page (Ctrl+Shift+R, or clear the site's data on a phone).

If people still see an old version after an update, open `sw.js` and change the version name in its first line (for example `shabdo-v6` to `shabdo-v7`), then commit.

## Where progress is saved

Progress, favorites and quiz history are saved **only in each learner's own browser**. Nothing is sent to a server. Clearing the browser's site data, using a private tab, or switching to another device or browser starts fresh.

## Credits

Created by **Md Kutub Uddin Bahar**, BBA (Banking & Insurance), University of Dhaka.
Contact: kutubbahar2018@gmail.com
