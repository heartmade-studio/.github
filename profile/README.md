# Heartmade Studio

Vibe-coding & human-centric design. Small, honest software for people who would
rather work with people than with technology.

Run by [Paweł Jurewicz](https://github.com/pawel-jurewicz-heartmade) — 20+ years in
product management, now building hands-on with AI · [heartmade.pl](https://heartmade.pl/en/)

## Open source

Everything below is MIT-licensed, tested, and runs locally in minutes.

| Project | What it is | Stack |
| --- | --- | --- |
| [Heartshop Goods](https://github.com/heartmade-studio/Heartshop-Goods) | Self-hosted one-product shop for physical goods. PAYMOVE.io checkout with signed webhooks; shipments and invoice data handed to Furgonetka.pl. Seller panel, PL/EN storefront. | PHP 8.2+, SQLite |
| [Heartshop Vouchers](https://github.com/heartmade-studio/Heartshop-Vouchers) | Self-hosted shop for service gift vouchers. PAYMOVE.io checkout, printable voucher codes, redemption in the seller panel. | PHP 8.2+, SQLite |
| [Skryba](https://github.com/heartmade-studio/skryba) | Hold Fn, speak, and your words appear wherever you type. Free macOS dictation with cloud or local Whisper. | Swift, macOS 14+ |
| [Messenger-Native SaaS](https://github.com/heartmade-studio/messenger-native-saas) | Blueprint for products customers use inside a messenger (e.g. Telegram), with a coherent stack behind it. | TypeScript, Telegram, Supabase |

### Heartshop: built for real transactions

Two independent editions of one idea — a shop small enough to read in an
afternoon, serious enough to take real payments:

- Server-side pricing, immutable order snapshots, HMAC-verified webhooks, retry protection.
- No Composer, npm or database server: plain HTML/CSS/JS, PHP and SQLite.
- Full test suite (backend, frontend, real HTTP, Apache HTTPS boundaries) on PHP 8.2–8.5 in CI.
- Starts in local simulation; going live takes your own merchant accounts and the
  documented acceptance checks. A default clone cannot charge real money.

Try the hosted demos (test payments only):
[physical product](https://heartmade.pl/heartshop/) ·
[service voucher](https://heartmade.pl/heartshop/voucher/)

## What we build

- Web apps — first one: [MoonQ](https://moonq.app), a messenger-native app
- Native macOS apps
- Websites, landing pages and one-product shops

## Work with us

Prefer a shop set up for you — configuration, content and legal templates included?
See [Heartmade websites and stores](https://heartmade.pl/en/websites).
Building an app and stuck on "what next"? See [Heartmade Studio](https://heartmade.pl/en/studio).
