<div align="center">

<img src="docs/images/icon.png" alt="MenuDart app icon" width="128">

# MenuDart

**See every app menu and every menu bar icon in a popup, even the ones that don't fit on your screen.**

English | [한국어](README.ko.md)

<img src="docs/images/demo-menu-bar-icons.gif" alt="MenuDart gathers menu bar icons into a grid popup and moves the pointer to the menu you open" width="720">

</div>

## Why MenuDart

On a small screen like a MacBook's, a menu bar runs out of room quickly. An app's menus don't all fit, and when many apps are running, their menu bar icons overflow and some end up hidden. The notch makes it worse.

<p align="center">
  <img src="docs/images/crowded-menu-bar.png" alt="A MacBook menu bar where only some of the menu bar icons fit and the rest are hidden" width="720">
</p>

<p align="center"><sub>My MacBook's menu bar. I have 18 menu bar icons. Only these few are visible; macOS tucks the rest behind the « button.</sub></p>

I'm the developer. I had been using another menu bar icon manager, but after I updated to macOS 27 Golden Gate it started behaving strangely. So I built my own, with a different approach. Instead of rearranging or hiding things inside the menu bar, MenuDart shows the menus and the icons in a popup, which doesn't depend on how the menu bar lays itself out.

I also wanted an icon's own menu to open somewhere more convenient, but I couldn't find a reliable way to do that. So MenuDart lets the menu open where it normally does and moves your pointer there for you.

## Watch the demo

A 50-second walkthrough: a cramped MacBook menu bar, an ultrawide monitor, both shortcuts, and the dart that carries the pointer to the menu you pick.

<p align="center">
  <a href="https://studiojin.dev/menudart/#demo"><img src="docs/images/demo-poster.png" alt="Watch the MenuDart demo video on studiojin.dev: the dart lands on a menu bar icon's menu" width="720"></a>
</p>

<p align="center"><a href="https://studiojin.dev/menudart/#demo">▶ Play the demo on studiojin.dev</a></p>

## What it does

MenuDart opens two popups from global keyboard shortcuts. You can also open either one from the MenuDart icon in the menu bar.

### App Menus

Shows the frontmost app's menu bar menus (Apple menu, File, Edit, and so on) in a popup next to the pointer. It works even when the menu titles don't fit in the menu bar.

<p align="center">
  <img src="docs/images/demo-app-menus.gif" alt="Opening the App Menus popup with a shortcut and navigating it with the keyboard" width="720">
</p>

<p align="center">
  <img src="docs/images/app-menus.png" alt="The App Menus popup showing TextEdit's Format › Font menu, with a breadcrumb at the top" width="720">
</p>

- Submenus open in place. A breadcrumb with the app's icon (TextEdit › Format › Font) shows where you are and lets you jump back to an earlier level.
- It looks like a system menu, including disabled items and separators. Each action appears once (Option-key alternates are hidden).
- The popup doesn't take focus from the app you're working in, so that app's menu bar stays as it is.

### Menu Bar Icons

Gathers the icons on the right side of the menu bar (status items and menu extras, including Control Center ones) into a grid, including icons hidden because the menu bar is too crowded or cut off by the notch.

<p align="center">
  <img src="docs/images/menu-bar-icons.png" alt="The Menu Bar Icons grid popup listing every menu bar icon, including the ones that don't fit in the menu bar" width="720">
</p>

- Pick an icon with the arrow keys or the pointer. MenuDart clicks the real icon for you, with a left click or a right click.
- On-screen icons are listed first. System icons keep their menu bar order.
- If clicking an icon changes nothing, a small toast in the popup tells you.

**How the pointer flight works.** After you pick an icon, its own menu still opens at its normal place under the menu bar. MenuDart does not move that menu and does not show it inside the popup. What it does is move your pointer onto the menu once it has opened, so you don't have to travel to the top of the screen. You can choose a pointer effect for the trip: Rocket, Trail, Dart, Ddoee (a flying cat), or No Effect.

<p align="center">
  <img src="docs/images/pointer-on-menu.png" alt="After choosing MenuDart in the grid, its menu is open under the menu bar and the pointer is already on it" width="720">
</p>

## Keyboard reference

**App Menus**

| Key | Action |
|---|---|
| <kbd>↑</kbd> / <kbd>↓</kbd> | Choose an item |
| <kbd>→</kbd> | Open the submenu |
| <kbd>←</kbd> | Go back |
| <kbd>Return</kbd> or <kbd>Space</kbd> | Run the item |
| <kbd>Esc</kbd> | Close |

**Menu Bar Icons**

| Key | Action |
|---|---|
| Arrow keys | Choose an icon |
| <kbd>Space</kbd> | Left click the icon |
| <kbd>Return</kbd> | Right click the icon |
| <kbd>Esc</kbd> | Close |

The Space and Return click assignments can be swapped in Settings. The pointer works in both popups too.

## Settings highlights

<p align="center">
  <img src="docs/images/settings.png" alt="The MenuDart Settings window" width="400">
</p>

- **Shortcuts.** There are none until you set them. The setup guide offers one-click defaults: <kbd>⌥</kbd><kbd>⌘</kbd><kbd>[</kbd> for App Menus, <kbd>⌥</kbd><kbd>⌘</kbd><kbd>]</kbd> for Menu Bar Icons, and an optional <kbd>⌥</kbd><kbd>⌘</kbd><kbd>\\</kbd> for Settings. You can record any combination that includes at least one modifier key.
- **Conflict check.** MenuDart warns you if a combination is already used by another MenuDart action or a macOS system shortcut, and lets you move it, register it anyway, or cancel.
- **Menu Bar Icons grid.** Set the number of icons per row (1 to 16) and where the pointer lands when the popup opens (center of the first item or center of the popup).
- **Pointer effect.** Rocket, Trail, Dart, Ddoee (a flying cat), or No Effect.
- **Appearance.** System, Light, or Dark. On macOS 26 and later the popups use Liquid Glass automatically.
- **Language.** English, Korean, Japanese, Simplified Chinese, Traditional Chinese, Portuguese (Brazil), Spanish, Hindi, Italian, German and French. The app restarts when you change it.

## Requirements and permissions

- macOS 14.0 or later
- Universal app (Apple silicon and Intel)

| Permission | Required? | What it's for | Without it |
|---|---|---|---|
| Accessibility | Yes | Reading the front app's menus and pressing menu bar icons | Neither popup works |
| Screen Recording | Recommended, optional | Showing the real menu bar icon images in the grid | The grid shows each app's own icon instead |

MenuDart captures only the menu bar icons it shows in the popup. It doesn't save those images or send them anywhere. MenuDart doesn't collect or send your data; the only network request is the update check, which contacts GitHub to fetch the update feed.

A step-by-step setup guide runs on first launch and covers permissions and shortcuts in about two minutes.

## Install

1. Download the latest `MenuDart-x.y.z.dmg` from [Releases](https://github.com/studiojin-dev/MenuDart-Public/releases).
2. Open the `.dmg` and drag MenuDart to the Applications folder.
3. Launch MenuDart and follow the setup guide.

MenuDart is signed with a Developer ID and notarized by Apple. It is distributed directly from this page, not through the Mac App Store. To update, choose **Check for Updates…** from the MenuDart icon in the menu bar.

## FAQ

### How do I allow Accessibility?

Open System Settings › Privacy & Security › Accessibility and turn on MenuDart. The setup guide walks you through this on first launch. Accessibility is required for both popups.

### How do I allow Screen Recording?

Open System Settings › Privacy & Security › Screen & System Audio Recording and turn on MenuDart. **Restart MenuDart afterward**, because the change only takes effect after a restart.

If the switch is on but MenuDart still shows "Needed", open Settings › Permissions › Setup Guide and choose **Reset and Request Again**.

### macOS says MenuDart is from an unidentified developer. Is it safe?

MenuDart is signed with a Developer ID and notarized by Apple, so it should open normally. If macOS still blocks it, open System Settings › Privacy & Security and choose **Open Anyway**. Also make sure you downloaded the app from the official [Releases](https://github.com/studiojin-dev/MenuDart-Public/releases) page.

### Which macOS versions are supported?

macOS 14.0 or later, on both Apple silicon and Intel Macs.

### An icon's menu still opens at the top of the screen. Is that a bug?

No. The icon's menu opens where the app and macOS put it, and MenuDart doesn't relocate it. What MenuDart does is move your pointer onto the menu after it opens, so you don't have to reach for it.

### Does MenuDart hide or rearrange my menu bar icons?

No. MenuDart doesn't change your menu bar at all. It shows what's there in a popup.

## Support

Found a bug or have a question? Please open an issue on [GitHub Issues](https://github.com/studiojin-dev/MenuDart-Public/issues). It helps to include your macOS version and your MenuDart version.

## License agreement

Using MenuDart requires agreeing to the [End User License Agreement](EULA.md) ([한국어](EULA.ko.md)). MenuDart asks for this on first launch. A 14-day free trial is available before purchase, so purchases aren't refundable for change of mind; see Section 7 of the agreement for refunds when MenuDart doesn't work as described.

## Privacy

MenuDart has no accounts, analytics, advertising, tracking or cookies. Your menus and menu bar icons are read on your Mac and never leave it. MenuDart goes online only to check for updates, to check your license and, before you buy, to check for a running sale. See the [Privacy Policy](PRIVACY.md) ([한국어](PRIVACY.ko.md)) for details.

## Business information

Studiojin (스튜디오진) · Representative: Jeongjin Kim  
Business registration number: 730-50-01333 · Mail-order business registration number: 2026-화성병점-0744  
407Ho-B16, 59 Yeongtong-ro, Byeongjeom-gu, Hwaseong-si, Gyeonggi-do, 18337, Republic of Korea  
support@studiojin.dev

---

© 2026 Studiojin
