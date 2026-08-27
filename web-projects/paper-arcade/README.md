# Paper Arcade

A small, self-contained collection of six pencil-and-paper classics, built as a single HTML file. Monochrome by design, with one blue accent. Pass and play with a friend, or take on the built-in computer opponent.

Built by **vukosir**.

## Games

| # | Game | Board | Play |
|---|------|-------|------|
| 01 | **Tic Tac Toe** | 3 × 3 | 2 players or vs an unbeatable CPU |
| 02 | **SOS** | 6 × 6 | 2 players or vs CPU. Spell S, O, S in any line to score and play again |
| 03 | **Gomoku** | 15 × 15 | 2 players or vs CPU. First to five in a row wins |
| 04 | **Connect Four** | 7 × 6 | 2 players or vs CPU with Easy, Medium, Hard strength |
| 05 | **Dots & Boxes** | 3, 5 or 7 wide | 2 players or vs CPU. Close a box to claim it and go again |
| 06 | **Hangman** | Word guessing | Solo, with five categories and six wrong guesses allowed |

## Features

Everything lives in one file, `paper-arcade.html`, with no build step, no dependencies, and no server required. Highlights:

* **Monochrome design** in warm paper and ink tones, with a single blue accent for the second player, wins, and the active turn.
* **Light and dark themes** that follow your system setting, with a manual toggle in the top corner. Your choice is remembered on the device.
* **Two ways to play.** Every board game offers local pass-and-play, and most also offer a computer opponent. Tic Tac Toe plays a perfect game, Connect Four has three difficulty levels, and the rest use quick tactical heuristics.
* **Score tracking** that persists between rounds on the same device.
* **Responsive layout** that reflows for phones, tablets, and desktops.
* **Keyboard support** in Hangman, plus reduced-motion support for anyone who prefers fewer animations.

## Running it

**Locally.** Double-click `paper-arcade.html` and it opens in your default browser. That is all it needs.

**Online.** Because it is a single static file, you can host it almost anywhere. Rename it to `index.html` first so it loads at the root of your address, then use any of:

* **Netlify Drop** — drag the file onto [app.netlify.com/drop](https://app.netlify.com/drop) for an instant public link.
* **GitHub Pages** — add the file to a repository as `index.html` and enable Pages in the repository settings.
* **Vercel** or **Cloudflare Pages** — drag and drop, or connect a repository.
* **Your own hosting** — upload it over FTP or a control panel like any other web page.

The only thing that touches the internet is the web-font styling. If fonts are blocked or you are fully offline, the page falls back to clean system fonts and every game still works.

## Customizing

The look is controlled by CSS custom properties near the top of the file, inside the `:root` blocks. A few common tweaks:

* **Accent colour** — change `--accent` (and its dark-theme counterpart) to recolour the second player, wins, and highlights.
* **Connect Four board** — the board colour is set on `.c4board`.
* **Fonts** — swap the Google Fonts link and the `font-family` values for `Bricolage Grotesque`, `Instrument Sans`, and `Space Mono`.
* **Watermark** — the `vukosir` credit is the `.watermark` element near the end of the body, styled by the `.watermark` CSS rule.

## Browser support

Works in any current version of Chrome, Edge, Firefox, and Safari, on desktop and mobile.

## Credits

Designed and built by **vukosir**. Free to use and share.
