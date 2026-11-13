<p align="center"><img src="logo.svg" width="88" alt="Bragging Wall logo"></p>

<h1 align="center">Bragging Wall</h1>
<p align="center"><em>Every win, pinned where you can see it.</em></p>
<p align="center"><a href="https://erikafulgencio.github.io/bragging-wall/"><strong>Open Bragging Wall →</strong></a></p>

---

Bragging Wall is a private place to record your work wins every day, so they're ready when you need them for a resume, a salary or promotion conversation, or a reminder of what you're capable of on a hard day.

## What you can do

- **Pin a win every day.** Log what you did, its area (Delivery, Quality & Testing, Leadership, Process, Learning, Collaboration, Recognition, Personal), how big it was, and the result or proof.
- **See it on a calendar.** Day, week, month and year views, each with a summary of totals, big wins, top areas and highlights. The year view is a heatmap.
- **Keep notebooks.** Journals, planners and work notebooks with rich-text pages, checklists, and templates for daily plans, meeting notes, QA test sessions, weekly reviews and 1:1 prep. The last two pull in your logged wins automatically.
- **Export PDFs** of a single page, a whole notebook, or your achievement report.
- **Build a report** for a salary or promotion review, your resume, or a cheer-me-up recap, for any date range. Edit the text before you export it.
- **Cheer yourself up** with a random past win.
- **Search** everything with Ctrl/Cmd + K.


### Email your brags
Send a branded PDF brag sheet for one brag, or for every brag in a day, week, month or year. Bragging Wall builds the PDF (logo, header band, sticky-note cards, photos, page footers) and opens Gmail, Outlook or your email app with the subject and a summary already filled in. You attach the PDF there. On phones, **Share PDF** can hand it straight to your mail app. A web page can't send email by itself, so nothing ever leaves your device without you pressing send.

### Braddy, your supporter
Every win gets a comment from **Braddy from Bragging Wall**: an honest, friendly take on the win, notes on your attachments, an animated sticker, a look at your journey (chips and a six-month chart) and one piece of honest advice. In the claude.ai version Braddy is written by Claude and saved with the win (encrypted like everything else). On GitHub Pages, Braddy gives a quick take made on your device.

## Privacy and security

- **Your wall stays in your browser.** There's no server and no account. Entries are stored in this browser on this device, and nothing is sent anywhere.
- **Optional passcode lock with encryption.** Each entry is encrypted in the browser with AES-256-GCM. The key is protected by your passcode (PBKDF2-SHA256, 600,000 iterations) and by a one-time recovery code. The passcode itself is never stored. The wall locks again after a period of inactivity that you choose.
- **Encrypted backups.** Backup files are always encrypted, using either your passcode or a password you set for the file. Restoring a backup is also how you move your wall to another device or browser.
- **If you forget both your passcode and your recovery code, nobody can recover your entries.** Keep the recovery code somewhere safe.
- **Spreadsheet (.csv) exports aren't encrypted**, so keep them private.

> Because entries live in one browser, clearing that site's browser data erases them. Download an encrypted backup regularly.

## Design

- **Name and logo:** a wall of bricks with a marigold star on top, for a wall you build one win at a time.
- **Color:** a warm off-white ground (inspired by Pantone's 2026 Cloud Dancer), deep teal for actions and progress, and marigold kept for brag-worthy wins. Light and dark themes are both fully designed.
- **Type:** Fraunces, an expressive variable serif, for headings; Instrument Sans for reading; Caveat for the handwritten notes.
- **Freedom wall:** the background is a Filipino-style freedom wall of sticky notes, taped index cards, pushpins and doodles with encouraging messages ("Kaya mo 'yan!", "Laban lang!", "Proud of you!"). Your three newest wins are pinned as notes on the home screen.
- **Layout:** a bento-style wall of solid cards over the freedom wall, with one localized glow per screen instead of full-page gradients.
- **Motion:** used only to guide the eye (entrances, progress, saving). It's turned off automatically when your device asks for reduced motion.
- **Accessibility:** keyboard-friendly controls, visible focus states, and text contrast designed for both themes.

## Run it yourself

It's a single file. Open `index.html` in a modern browser, or serve the folder with any static host. On GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

PDFs are generated in the browser with [jsPDF](https://github.com/parallax/jsPDF). Fonts come from Google Fonts.
