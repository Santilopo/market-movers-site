# Market Movers website: how to edit and publish

This folder is the complete Market Movers website as plain HTML. No special software or account is needed to edit it.

## What's in the folder

| File | Page |
|---|---|
| `index.html` | Main page (English) |
| `es.html` | Main page (Spanish) |
| `story.html` | Santilopo's story (English) |
| `historia.html` | Santilopo's story (Spanish) |
| `huncho-story.html` | Huncho's full story (English) |
| `huncho-historia.html` | Huncho's full story (Spanish) |
| `*.jpg` | Photos and payout / eval certificates |
| `PROJECT-BRIEF.md` | Everything decided so far: offer, pricing, mentors, course, to-do list |

## How to look at it
Double-click `index.html`. It opens in your browser.

## How to edit it

**Option A: edit with ChatGPT**
1. Upload `PROJECT-BRIEF.md` first so ChatGPT knows the project.
2. Upload the page you want to change (for example `index.html`).
3. Ask for the change, e.g. *"Change the founding price from $300 to $350 everywhere and give me the full updated file."*
4. Save the new file over the old one (same file name).

Rule: **any change to `index.html` should also be made in `es.html`** (and `story.html` ↔ `historia.html`, `huncho-story.html` ↔ `huncho-historia.html`), so English and Spanish stay the same.

**Option B: edit by hand**
Open the file in any text editor (VS Code is free). Text is written directly in the HTML, so you can search for a sentence and change it.
- Gold accent color: `#E3B04B` (search and replace to change it everywhere)
- Images: upload new ones next to the pages and point to them as `your-file.jpg`

## How to put it online (free)
1. Go to **app.netlify.com/drop**.
2. Drag this whole folder onto the page. It goes live in seconds with a free netlify.app address.
3. To use your own domain (e.g. marketmoverstrading.com): in Netlify, open the site, go to **Domain management**, add the domain, and follow the steps it shows at your domain provider.
4. To update later: drag the updated folder in again (Deploys tab).

## Working on it together
If both Santilopo and his friend will edit it, put the folder in a free **GitHub** repository and connect it to Netlify. Every saved change then updates the live site, and you can see who changed what.

## Links used on the site
- Checkout (Whop): https://whop.com/market-movers-9d17/market-movers-huncho-santilopo
- Discord: https://discord.com/invite/D5mgzZWaJ
- Santilopo: https://www.youtube.com/@xcom2santi · https://www.instagram.com/xcom2santi/
- Huncho: https://www.instagram.com/mrktmver/

## Things still to fill in
- Huncho's payout certificates (look for text in [brackets])
- Terms and Privacy pages (footer links are placeholders)
