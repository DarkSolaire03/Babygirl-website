# Babygirl Website 💌

## 🌐 Live Site: [darksolaire03.github.io/Babygirl-website](https://darksolaire03.github.io/Babygirl-website/)

A tiny, interactive love-note website. Open it, tap the button, and a message for babygirl appears — with hearts, of course. 💖

## About

Babygirl Website is a small, sweet, single-page site built to say one simple thing in the nicest way possible. It was first built in April 2025 as a very plain page — just a button and a message — and has now been redesigned with a soft, romantic look while keeping the original idea exactly the same.

There is nothing to install, no account to make, and no tracking. It is just a page made to be shared with one very special person. Send her the live link, and the message does the rest.

## How It Works

1. Open the live site: https://darksolaire03.github.io/Babygirl-website/
2. Read the little note on the card and tap the rose-colored button, **"For you ♥"**.
3. The message **"i love you babygirl"** fades and scales in, in a large script font, with a burst of hearts.
4. A few extra sweet touches fade in underneath — a "forever & always" line and three little note cards.
5. Tap the **"♥ Show it again"** button any time to replay the reveal.

That is the whole experience, on purpose. One tap, one message, done beautifully.

## What's On The Page

- **Floating hearts** — soft hearts drift up the background the whole time you are on the page.
- **Romantic gradient** — a soft rose, pink, and lavender gradient replaces the old plain grey background.
- **Frosted-glass card** — the message sits in a centered, translucent card that works on phones and desktops alike.
- **Animated reveal** — the message appears with a smooth fade and scale-in, followed by a burst of heart confetti.
- **Three note cards** — small, heartfelt reasons that appear after the reveal:
  - "You make ordinary days better"
  - "Your smile is my favorite thing"
  - "Every love story is beautiful, but ours is my favorite"
- **Replay button** — tap again to watch the reveal and heart burst one more time.
- **Mobile-friendly** — the layout, text, and button are sized to be easy to tap on a phone.
- **Single file, no images required** — everything is in one `index.html` file; the only external asset is a Google Font.

## The Message

The heart of the site is the message revealed by the button, kept exactly as it was in the original version:

> **i love you babygirl**

Underneath it, after the reveal, it adds:

> — forever & always —

## How to Edit / Update It

You only need to edit one file: `index.html`.

1. Open this repository on GitHub and open `index.html`.
2. Click the pencil icon to edit it in the browser, or edit it locally and push your changes.
3. Change the wording, colors, fonts, or note cards — just keep the message text `i love you babygirl` and the tap-to-reveal idea if you want to stay true to the original.
4. Commit the change to the `main` branch.
5. GitHub Pages redeploys the site automatically. Wait a minute or two, then refresh the live site to see the update.

To change the button label, look for the button with the text `For you ♥` in `index.html`. To change the note cards, look for the three `<div class="note">` blocks. To change the revealed message, look for the line that sets the message text — but please keep it as `i love you babygirl`.

## Tech Notes

- **Single file:** the whole site is one `index.html` file with inline CSS and JavaScript. There is no build step, no framework, and no server code.
- **Fonts:** Great Vibes (for the revealed message) and Quicksand (for the rest of the text), loaded from Google Fonts. If the fonts cannot load, the page falls back to a cursive / system font and still works.
- **Hosting:** GitHub Pages, built from the `main` branch, root folder.
- **`.nojekyll`:** an empty `.nojekyll` file sits at the repo root so GitHub Pages serves the site as-is, without running it through Jekyll.
- **Files in this repo:**
  - `index.html` — the whole website
  - `README.md` — this file
  - `.nojekyll` — tells GitHub Pages not to use Jekyll

## My Other Sites

More sites by DarkSolaire03:

- **Network+ Quest** — https://darksolaire03.github.io/network-plus-quest/
- **Emberwrath Chronicles** — https://darksolaire03.github.io/emberwrath-chronicles/
- **Get To Know Juan** — https://darksolaire03.github.io/about-juan/

---

Made with ❤️ by DarkSolaire03
