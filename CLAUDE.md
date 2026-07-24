# Emily Srichala — Media Kit (draft)

## What this is
A single-page media-kit / rate-card website for **Emily Srichala**, built as a
favor for William to show her ("see if she likes it"). Same structure/typography
as Jess's site (Fraunces + DM Sans + Noto Sans Thai) but a DISTINCT palette so
it's her own brand, not a coral clone. William asked for a "cute / flattering"
look: **soft lilac-orchid + blush/peach on a warm pink-white**
(--coral=#b26fc9 primary, --coral-deep=#8a45ad plum, --peach=#f6a58a,
--rose=#f7d5e8 blush, --dark=#2a1b30 deep plum, --cream=#fdf8fc). NB: the CSS
var names still say "coral" for minimal-diff reasons; only the values changed.
(History: was coral like Jess, then jade-green, now lilac/blush.)

## Bilingual EN / ไทย toggle
- Nav has an EN | ไทย pill toggle. Every translatable element carries
  data-en + data-th attributes; a small inline script swaps innerHTML on click
  and remembers the choice in localStorage. Numbers, prices, handles and email
  stay as-is in both languages.
- Deep-link a language with `?lang=th` (or `?lang=en`) so a Thai link can be
  sent directly. Serif Thai headings fall back to Noto Sans Thai (Fraunces has
  no Thai glyphs).
- The Thai copy is a solid first pass but SHOULD BE PROOFED BY EMILY (she's the
  ฝรั่งพูดไทย native-level creator). It's draft-safe to show her.

## Copy voice
- No em dashes anywhere (William's rule); no AI-sounding filler. Kept the copy
  plain and human in both languages.

## Hosting (free, no domain yet)
- GitHub repo: williamcoconut/emily-srichala (public)
- Live (GitHub Pages): https://williamcoconut.github.io/emily-srichala/
- **Push to main = deploy** (GH Pages auto-builds).
- Page has `<meta robots noindex>` — unlisted/not indexed until she approves.
- If she wants a real domain later: buy it, add a CNAME file + point DNS (same
  as Jess). Repo/site can be deleted anytime if she passes.

## REAL data (pulled live from her profiles 2026-07-23 — re-verify before quoting)
- British expat in Bangkok (from Surrey UK), speaks Thai 12+ yrs, food/culture/
  travel + "ฝรั่งพูดไทย" format; co-owns a Bangkok tattoo studio.
- TikTok @emily.srichala 1.2M (30.9M likes) · Facebook 608K · Instagram
  @emilysrichala.blog 472K (verified) · YouTube @Emilysrichala. 255K.
  Combined ≈ 2.5M. Business email: emilysrichalavlogs@gmail.com; LINE for work.
- Thai name: เอมิลี่ ศรีชะลา. Awards/TV (TikTok Awards TH '25 nominee, The
  Social Warrior S2) are secondary-source only — marked with * on the page.

## DRAFT status — William's call: rough draft to show Emily, then finalize
- **Rates** are plausible-for-her-size DRAFT numbers (William approved using
  these until she confirms): TikTok $4,000 · IG Reel $3,500 · FB $2,000 · YT
  $5,500 · Bundle $8,000 (save $1,500) · IG Story set $800 · UGC/Whitelisting
  $2,500 · Spark code $1,500. Swap for her real rates after she sees it.
- **Photos** are her REAL public images pulled online for the draft (William
  OK'd this): hero = Thai-dress at Wat Arun (her YT avatar shoot); content strip
  = 4 of her actual YouTube video thumbnails (img.youtube.com/vi/<id>). For the
  final, get her own higher-res/hand-picked shots. Files in images/ (hero.jpg,
  content1-4.jpg).
  - The old about photo (a couple shot with her husband) was REMOVED at
    William's request; the about column is now a designed "Why brands work with
    me" value panel (.about-panel), no photo. about.jpg deleted from the repo.
- EN/TH toggle is now LIVE (see the bilingual section above). Very on-brand
  since she's the "speaks Thai" creator.

## Files
- index.html — the whole site (self-contained, inline CSS).
- preview.png — local render (gitignored).
