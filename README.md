# Gigaverse "The Awakening" — Hard Core Payout Calculator

A single-page calculator that estimates what your Hard Cores (HC) are worth as a
share of the prize pot. HC convert into fixed-cost boxes that pay cash from the
pot; the pot splits across every box opened.

Enter a **minimum box cost**, **your HC**, the **prize pot**, and a **projected
total HC** — it computes value per box, your payout, your share, and (from the
real leaderboard distribution) how many boxes exist and how much HC is wasted
(whole-boxes-only: HC below a full box is wasted).

**Data:** on load it fetches the public Gigaverse API live
(`gigaverse.io/api/itempools/public` + `.../leaderboard/id/8`); if that's
unreachable it uses a built-in snapshot so the page still works. No wallets or
usernames are stored in this page — the fallback holds HC amounts only.

Static site — just `index.html`. Served via GitHub Pages.
