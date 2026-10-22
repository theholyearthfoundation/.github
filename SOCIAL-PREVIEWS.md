# 🔄 Social previews: refresh guide + share-image ledger

When a link to one of The Holy Earth Foundation's GitHub Pages sites is pasted into a chat app, the app shows a
preview card (title, description and a share image) that it fetched **once** and then **cached**.
After a share image or title changes, old previews keep showing until each app is told to look again.
This file lists how to do that for each app, and which pages have their own tailored share image.

*Generated 2026-10-22 by the arrival kit's `social/social-previews.mjs` (canonical copy in
[my-template](https://github.com/drasticstatic/my-template/tree/main/changelog-template/arrival/social)).
Re-run it after deploys that add pages or change share images.*

## 🧰 How to refresh each app

| App | How to make it re-fetch | Notes |
|---|---|---|
| ✈️ **Telegram** | Message [@WebpageBot](https://t.me/WebpageBot) the link (you can send several links, one per line) | The bot replies with the fresh preview; new shares use it right away |
| 💼 **LinkedIn** | Paste the link into [Post Inspector](https://www.linkedin.com/post-inspector/) | Inspecting re-scrapes the page |
| 📘 **Facebook / Messenger** | Paste into the [Sharing Debugger](https://developers.facebook.com/tools/debug/) and press **Scrape Again** | Also accepts a batch of links |
| 💬 **Discord** | No refresh tool. Share the link with a harmless suffix such as `?v=2` | Discord caches per exact URL, so a new suffix gets a new preview |
| 🟪 **Slack** | No refresh tool. Use the `?v=2` suffix trick | Old messages keep their old unfurl |
| 🐦 **X (Twitter)** | No public validator any more. Use the `?v=2` suffix, or wait (cards refresh on their own, roughly a week) | |
| 🟢 **WhatsApp** | No refresh tool. Use the `?v=2` suffix | WhatsApp caches aggressively |
| 🦋 **Bluesky** / 🐘 **Mastodon** | Fetched when a post is written; nothing to clear | Each Mastodon server fetches its own copy |
| 💬 **iMessage** | Fetched on the sender's phone at send time | Nothing to clear |

**Rule of thumb:** after changing a share image, refresh Telegram (@WebpageBot), LinkedIn and
Facebook for the pages listed below. Use the `?v=2` suffix anywhere else.

## 🖼️ Share-image ledger

32 pages checked: **30 tailored**, 2 using the default card,
0 with no share image.

### ✨ Pages with their own tailored share image

| Page | Title | Share image |
|---|---|---|
| [theholyearthfoundation.github.io/donate/](https://theholyearthfoundation.github.io/donate/) | Donate — The Holy Earth Foundation on GitHub | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/page/donate.jpg) |
| [theholyearthfoundation.github.io/pledge/](https://theholyearthfoundation.github.io/pledge/) | A pledge of support — The Holy Earth Foundation on GitHub | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/page/pledge.jpg) |
| [theholyearthfoundation.github.io/map/](https://theholyearthfoundation.github.io/map/) | Map — The Holy Earth Foundation on GitHub | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/page/map.jpg) |
| [theholyearthfoundation.github.io/plants-and-miracles/](https://theholyearthfoundation.github.io/plants-and-miracles/) | Plants & Miracles — Flight of the Eagle and the Condor | [image](https://theholyearthfoundation.github.io/plants-and-miracles/plants-and-miracles-card.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog](https://theholyearthfoundation.github.io/changelog-astro-public/changelog) | Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/library](https://theholyearthfoundation.github.io/changelog-astro-public/library) | Library | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/page/library.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/teachings](https://theholyearthfoundation.github.io/changelog-astro-public/teachings) | Teachings — The Holy Earth Foundation | [image](https://theholyearthfoundation.github.io/plants-and-miracles/plants-and-miracles-card.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/ledger](https://theholyearthfoundation.github.io/changelog-astro-public/ledger) | Ledger: every public change — THEF AstroLog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/ledger.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/iamoneself](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/iamoneself) | I Am One Self — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/david-amaringo](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/david-amaringo) | David Amaringo — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation) | The Foundation's GitHub home — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-22-kenneys-own-contacts-a-pledge-and-a-call-for-love](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-22-kenneys-own-contacts-a-pledge-and-a-call-for-love) | Kenney's own contacts, a pledge of support, and David's story told as a call for love — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/foundation/2026-10-22-kenneys-own-contacts-a-pledge-and-a-call-for-love.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in) | A navbar on every page, a map with pictures, and one window for every way to reach Kenney — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/foundation/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-choose-how-you-arrive](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-choose-how-you-arrive) | Choose how you arrive: a welcome guide, one search for everything, and a twin vine that follows you — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/foundation/2026-10-12-choose-how-you-arrive.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-plants-and-miracles-flyer-becomes-living-pages](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-plants-and-miracles-flyer-becomes-living-pages) | Kenney's Plants & Miracles flyer now lives in the library: one link instead of a PDF — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/foundation/2026-10-12-plants-and-miracles-flyer-becomes-living-pages.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-teachings-a-room-of-their-own](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-teachings-a-room-of-their-own) | Kenney's teaching moves into Teachings, a room of its own — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/foundation/2026-10-12-teachings-a-room-of-their-own.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-the-ledger-reading-mode-whats-new](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-the-ledger-reading-mode-whats-new) | The ledger: every public change in plain words, plus reading mode and what's new since your last visit — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/foundation/2026-10-12-the-ledger-reading-mode-whats-new.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-11-foundation-sites-get-their-own-look](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-11-foundation-sites-get-their-own-look) | The foundation's GitHub home and this changelog get their own look: the canopy at first light — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/foundation/2026-10-11-foundation-sites-get-their-own-look.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/david-amaringo/2026-08-27-david-amaringo-real-donations-policy](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/david-amaringo/2026-08-27-david-amaringo-real-donations-policy) | Donations are real wallet connections — never a placeholder address — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/david-amaringo/2026-08-27-david-amaringo-real-donations-policy.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/david-amaringo/2026-08-27-david-amaringo-site-real-content](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/david-amaringo/2026-08-27-david-amaringo-site-real-content) | David Amaringo's site went live with real content — bio, gallery, services — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/david-amaringo/2026-08-27-david-amaringo-site-real-content.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/iamoneself/2026-08-26-partner-retreats-giving-is-receiving](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/iamoneself/2026-08-26-partner-retreats-giving-is-receiving) | Retreat bookings route through our partners, not a direct checkout — and why — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/iamoneself/2026-08-26-partner-retreats-giving-is-receiving.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/changelog/iamoneself/2026-06-25-iamoneself-site-search-fixed](https://theholyearthfoundation.github.io/changelog-astro-public/changelog/iamoneself/2026-06-25-iamoneself-site-search-fixed) | Site search now actually works — Changelog | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/changelog/iamoneself/2026-06-25-iamoneself-site-search-fixed.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/library/backdrop-filter-containing-block-bug](https://theholyearthfoundation.github.io/changelog-astro-public/library/backdrop-filter-containing-block-bug) | The backdrop-filter containing-block bug — Library | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/library/backdrop-filter-containing-block-bug.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/library/pagefind-es-module-search-fix](https://theholyearthfoundation.github.io/changelog-astro-public/library/pagefind-es-module-search-fix) | The Pagefind ES-module search fix — Library | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/library/pagefind-es-module-search-fix.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles](https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles) | Plants & Miracles — Teachings | [image](https://theholyearthfoundation.github.io/plants-and-miracles/plants-and-miracles-card.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-the-eagle](https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-the-eagle) | Plants & Miracles · The Eagle — Teachings | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/teachings/plants-and-miracles-the-eagle.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-the-condor](https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-the-condor) | Plants & Miracles · The Condor — Teachings | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/teachings/plants-and-miracles-the-condor.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-their-union](https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-their-union) | Plants & Miracles · Their Union — Teachings | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/teachings/plants-and-miracles-their-union.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-path-of-awakening](https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-path-of-awakening) | Plants & Miracles · The Path of Awakening — Teachings | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/teachings/plants-and-miracles-path-of-awakening.jpg) |
| [theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-with-isaiah-kenney](https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-with-isaiah-kenney) | Plants & Miracles · With Isaiah Kenney — Teachings | [image](https://theholyearthfoundation.github.io/changelog-astro-public/og/teachings/plants-and-miracles-with-isaiah-kenney.jpg) |

### 🪪 Pages using the default card

- [theholyearthfoundation.github.io/](https://theholyearthfoundation.github.io/)
- [theholyearthfoundation.github.io/changelog-astro-public/](https://theholyearthfoundation.github.io/changelog-astro-public/)

## 📋 Copy-paste list for @WebpageBot

```
https://theholyearthfoundation.github.io/
https://theholyearthfoundation.github.io/donate/
https://theholyearthfoundation.github.io/pledge/
https://theholyearthfoundation.github.io/map/
https://theholyearthfoundation.github.io/plants-and-miracles/
https://theholyearthfoundation.github.io/changelog-astro-public/
https://theholyearthfoundation.github.io/changelog-astro-public/changelog
https://theholyearthfoundation.github.io/changelog-astro-public/library
https://theholyearthfoundation.github.io/changelog-astro-public/teachings
https://theholyearthfoundation.github.io/changelog-astro-public/ledger
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/iamoneself
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/david-amaringo
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-22-kenneys-own-contacts-a-pledge-and-a-call-for-love
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-choose-how-you-arrive
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-plants-and-miracles-flyer-becomes-living-pages
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-teachings-a-room-of-their-own
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-12-the-ledger-reading-mode-whats-new
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/foundation/2026-10-11-foundation-sites-get-their-own-look
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/david-amaringo/2026-08-27-david-amaringo-real-donations-policy
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/david-amaringo/2026-08-27-david-amaringo-site-real-content
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/iamoneself/2026-08-26-partner-retreats-giving-is-receiving
https://theholyearthfoundation.github.io/changelog-astro-public/changelog/iamoneself/2026-06-25-iamoneself-site-search-fixed
https://theholyearthfoundation.github.io/changelog-astro-public/library/backdrop-filter-containing-block-bug
https://theholyearthfoundation.github.io/changelog-astro-public/library/pagefind-es-module-search-fix
https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles
https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-the-eagle
https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-the-condor
https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-their-union
https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-path-of-awakening
https://theholyearthfoundation.github.io/changelog-astro-public/teachings/plants-and-miracles-with-isaiah-kenney
```
