# MenuDart Privacy Policy

English | [한국어](PRIVACY.ko.md)

Effective date: October 6, 2026

Studiojin ("we") makes MenuDart, a macOS menu bar app. This policy explains what MenuDart does with your information. In short: **MenuDart has no accounts, no analytics, no advertising, no tracking and no cookies.** It goes online only to check for updates, to check your license and, before you buy, to check for a running sale.

## What stays on your Mac

MenuDart needs Accessibility and Screen Recording permission to do its job. Everything it reads with them is used on your Mac and is never sent anywhere.

- **App menus** are read through Accessibility so MenuDart can show them in a popup.
- **Menu bar icons** are captured from the menu bar with Screen Recording so MenuDart can show them in a grid. The images are kept in memory only while the popup needs them and are never saved to disk or uploaded.
- **Settings** (shortcuts, language, appearance and so on) are saved in macOS user defaults on your Mac.
- **License information** (your license key and activation) is saved in your login keychain on your Mac. The trial start date is saved in user defaults.

## When MenuDart goes online

MenuDart connects to the internet only for the purposes below. It does not send your menus, screen contents, files, keystrokes or usage.

| Purpose | Sent to | What is sent | When |
|---|---|---|---|
| Update check | GitHub (`raw.githubusercontent.com`, `github.com`) | A request for the update feed, with MenuDart's version in the request header. MenuDart does not send a system profile. | Once a day if automatic checks are on (you can turn them off in Settings → Updates), and when you choose Check for Updates. Downloading an update also comes from GitHub. |
| License activation and check | Lemon Squeezy (`api.lemonsqueezy.com`) | Your license key, and your Mac's computer name when you activate (so you can tell your Macs apart). Later checks send the license key and the activation ID. | When you activate or deactivate a license, and about once a day after activation. |
| Sale check | Studiojin (`studiojin.dev`) | A plain request for the current sale. No identifier or license information is sent. | Only before you activate a license, at most once every 36 hours. |

As with any internet connection, these services can see your IP address. Their own privacy policies apply to what they receive:
[GitHub](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement) ·
[Lemon Squeezy](https://www.lemonsqueezy.com/privacy) ·
[Cloudflare](https://www.cloudflare.com/privacypolicy/) (hosts `studiojin.dev`).

## Purchases

When you choose Buy, MenuDart opens the checkout page in your web browser. The purchase is handled by Lemon Squeezy, our reseller and merchant of record, which collects your email address and payment details under its own privacy policy. MenuDart itself never sees your payment details.

## Support

If you contact us by email or GitHub Issues, we use what you send only to answer you. GitHub Issues are public, so please don't post personal information or your license key there.

## Retention and deletion

Information on your Mac stays until you delete it. To remove it, delete MenuDart and, if you want, its settings (`~/Library/Preferences/dev.studiojin.MenuDart.plist`) and the `dev.studiojin.MenuDart.license` item in Keychain Access. Deactivate your license in Settings first if you want to free it for another Mac. Information held by Lemon Squeezy is kept as required for the license and by law; to ask about it or have it deleted, contact us at the address below.

## Children

MenuDart is not directed at children and does not knowingly collect information from them.

## Changes

If this policy changes, we'll update this page and its effective date. Significant changes will be noted in the release notes.

## Contact

Studiojin (스튜디오진) · Representative and privacy officer: Jeongjin Kim
support@studiojin.dev
