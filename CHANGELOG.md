# Changelog

## 1.2.2 — 2026-10-22

- **⌘Tab switcher**: the selected app's name now appears in a small bubble under its icon, the way the Menu Bar Icons popup names the icon you point at, instead of in a band at the bottom of the panel.

## 1.2.2 — 2026-10-22 (한국어)

- **⌘Tab 전환기**: 선택한 앱의 이름이 패널 아래쪽 띠 대신, 메뉴 막대 아이콘 팝업에서 포인터를 올린 아이콘의 이름을 보여 주는 것처럼 아이콘 아래 작은 말풍선에 표시됩니다.

---

## 1.2.1 — 2026-10-22

- **⌘Tab switcher**: on some Macs, choosing an app did nothing: the switcher closed but the app and its window stayed where they were. MenuDart now switches the way the Dock does and raises the app's window, and an app with no open window gets a new one. To switch, let go of ⌘, press Return after moving with the keys, or click an icon.
- **Menu Bar Icons**: moving to an icon with the arrow keys now shows its name, the way pointing at it does, when icon names are hidden or the name was cut short.

## 1.2.1 — 2026-10-22 (한국어)

- **⌘Tab 전환기**: 일부 Mac에서 앱을 골라도 전환기만 닫히고 앱과 창은 그대로인 문제를 고쳤습니다. 이제 Dock처럼 전환하고 앱의 창을 앞으로 올리며, 열린 창이 없는 앱은 새 창을 엽니다. ⌘에서 손을 떼거나, 키로 옮긴 뒤 Return을 누르거나, 아이콘을 클릭하면 전환됩니다.
- **메뉴 막대 아이콘**: 아이콘 이름을 숨겼거나 이름이 잘려 보일 때, 방향키로 옮겨 간 아이콘의 이름을 포인터를 올렸을 때처럼 보여 줍니다.

---

## 1.2.0 — 2026-10-22

- New **⌘Tab app switcher** (off by default). Turn on **Use MenuDart for ⌘Tab** in Settings → Shortcuts and ⌘Tab shows your open apps in several rows on a glass panel, centred on the screen with the pointer, instead of one long row. While holding ⌘, use Tab, ⇧Tab or ` and the arrow keys to move, let go of ⌘ to switch, Esc to cancel, and Q or H to quit or hide the selected app. Needs Accessibility.
- New **tutorial** that walks through every feature with its keys, options and screenshots. It opens once after setup (if you already use MenuDart, it asks once), has a **Don't show this again** option, and opens any time from Settings → General → Tutorial.
- **Menu Bar Icons**: while the list refreshes, Coco the cat looks through the menus in the popup's title bar, then curls up for a nap when it's done.
- **App Menus**: with **Show scroll bars** set to **Always** in System Settings, the first item of a submenu is no longer cut off under the header.

## 1.2.0 — 2026-10-22 (한국어)

- 새 **⌘Tab 앱 전환기**(기본값 꺼짐). 설정 → 단축키에서 **⌘Tab에 MenuDart 앱 전환기 사용**을 켜면 ⌘Tab을 눌렀을 때 열린 앱이 긴 한 줄 대신, 포인터가 있는 화면 가운데의 유리 패널에 여러 줄로 나옵니다. ⌘를 누른 채 Tab, ⇧Tab, `와 방향키로 옮겨 다니고, ⌘에서 손을 떼면 전환됩니다. Esc는 취소, Q와 H는 선택한 앱을 종료하거나 가립니다. 손쉬운 사용 권한이 필요합니다.
- 모든 기능을 키·옵션·화면과 함께 소개하는 **튜토리얼**이 생겼습니다. 설정을 마친 뒤 한 번 열리고(이미 쓰고 있다면 한 번 물어봅니다), **다시 보지 않기**를 고를 수 있으며, 설정 → 일반 → 튜토리얼에서 언제든 열 수 있습니다.
- **메뉴 막대 아이콘**: 목록을 새로 고치는 동안 고양이 코코가 팝업 제목 막대에서 메뉴를 살펴보다가, 끝나면 몸을 말고 낮잠을 잡니다.
- **앱 메뉴**: 시스템 설정에서 **스크롤 막대 보기**가 **항상**일 때 하위 메뉴 첫 항목이 헤더에 가려지던 문제를 고쳤습니다.

---

## 1.1.0 — 2026-10-19

- **App Menus** popup gets a new **Outline** layout (Settings → App Menu → Layout). Every menu shows as one tree you can expand and collapse, and typing searches every menu item, submenus included, with the menus it lives in (Format › Font). Case and accents are ignored and Korean initial consonants match too. Press → to show a result in the tree, or Return to run it. An Apple button beside the search field, and a matching setting, choose whether the Apple menu is searched.
- New **Theme** setting in Settings → General for the popups and the Settings window. **Classic** looks like macOS menus. **Smoke** is smoked glass: what's behind shows through, blurred, with a lit edge and a glossy selection, and a **Transparency** slider sets how much shows through. Popups no longer use Liquid Glass; choose Smoke for a glass look.
- **Menu Bar Icons**: new **Show Icon Names** option. Turn it off to show the icons alone, like the Dock; point at an icon to see its name. The Smoke theme always shows icons alone.
- The search fields in both popups now look the same.

## 1.1.0 — 2026-10-19 (한국어)

- **앱 메뉴** 팝업에 새 **아웃라인** 보기 방식이 생겼습니다(설정 → 앱 메뉴 → 보기 방식). 모든 메뉴를 펼치고 접을 수 있는 트리 하나로 보여 주고, 입력하면 하위 메뉴까지 모든 메뉴 항목을 검색해 어느 메뉴에 있는지(Format › Font) 함께 보여 줍니다. 대소문자와 악센트는 구분하지 않고 초성 검색도 됩니다. →를 누르면 트리에서 위치를 보여 주고, Return을 누르면 바로 실행합니다. 검색 칸 옆 Apple 버튼과 같은 이름의 설정으로 Apple 메뉴를 검색할지 정합니다.
- 설정 → 일반에 팝업과 설정 창의 **테마**가 생겼습니다. **클래식**은 macOS 메뉴처럼 보이고, **스모크**는 뒤에 있는 화면이 흐리게 비치는 스모크 유리로 가장자리에 빛이 들고 선택한 항목이 광택 있게 표시됩니다. **투명도** 슬라이더로 비치는 정도를 정합니다. 팝업에 더 이상 Liquid Glass를 쓰지 않으며, 유리 느낌을 원하면 스모크를 고르세요.
- **메뉴 막대 아이콘**: **아이콘 이름 표시** 옵션이 생겼습니다. 끄면 Dock처럼 아이콘만 보이고, 포인터를 올리면 이름이 나타납니다. 스모크 테마에서는 항상 아이콘만 보입니다.
- 두 팝업의 검색 칸 모양이 같아졌습니다.

---

## 1.0.8 — 2026-10-19

- **Menu Bar Icons** popup gets a search field. Start typing as soon as it opens to narrow the icons by name or app; the first match is selected, so Space or Return opens it right away. Case and accents are ignored, input methods such as Korean, Japanese and Chinese work as usual, and Korean initial consonants match too (ㅅㄱ finds 시계).

## 1.0.8 — 2026-10-19 (한국어)

- **메뉴 막대 아이콘** 팝업에 검색 칸이 생겼습니다. 팝업이 열리면 바로 글자를 입력해 아이콘이나 앱 이름으로 찾을 수 있고, 첫 번째 결과가 선택되므로 Space나 Return으로 바로 엽니다. 대소문자와 악센트는 구분하지 않고, 한글·일본어·중국어 입력기도 그대로 쓸 수 있으며, 초성 검색도 됩니다(ㅅㄱ → 시계).

---

## 1.0.7 — 2026-10-18

- **App Menus** popup: when you open a menu, the first command is no longer half hidden under the title bar.
- **App Menus** popup: a newly opened menu now starts on its top item, instead of whichever item happened to be under the pointer. At the first level it starts on the app's own first menu rather than the Apple menu.
- **Menu Bar Icons**: "Icons per row" is now a slider from 3 to 15. It warns you when the popup would be too wide for your smallest display.
- **Menu Bar Icons**: the popup can no longer be shrunk until the icons become too small to read.

## 1.0.7 — 2026-10-18 (한국어)

- **앱 메뉴** 팝업: 메뉴를 열었을 때 첫 번째 명령이 제목 막대에 반쯤 가려지지 않습니다.
- **앱 메뉴** 팝업: 새로 연 메뉴는 포인터 아래 항목이 아니라 맨 위 항목부터 선택됩니다. 첫 단계에서는 Apple 메뉴 대신 앱의 첫 메뉴가 선택됩니다.
- **메뉴 막대 아이콘**: "한 줄 아이콘 수"가 3~15 슬라이더로 바뀌었습니다. 가장 작은 화면에 비해 팝업이 너무 넓어지면 경고를 보여 줍니다.
- **메뉴 막대 아이콘**: 아이콘을 알아볼 수 없을 만큼 팝업을 작게 줄일 수 없습니다.

---

## 1.0.6 — 2026-10-15

- The **Menu Bar Icons** popup now lists icons in the same order every time: icons built into macOS (Control Center, Wi‑Fi, battery, clock and so on) first by name, then other apps' icons by app name. Before, the order could change after you picked an icon.
- New option in Settings → Menu Bar Icons: **Show Built-in macOS Icons**. Turn it off to list only other apps' icons. It's on by default.
- Improved stability.

## 1.0.6 — 2026-10-15 (한국어)

- **메뉴 막대 아이콘** 팝업이 항상 같은 순서로 아이콘을 보여 줍니다. macOS 내장 아이콘(제어 센터, Wi‑Fi, 배터리, 시계 등)이 이름순으로 먼저 나오고, 그다음 다른 앱의 아이콘이 앱 이름순으로 나옵니다. 이전에는 아이콘을 고른 뒤 순서가 바뀌는 경우가 있었습니다.
- 설정 → 메뉴 막대 아이콘에 **macOS 내장 아이콘 보이기** 옵션이 생겼습니다. 끄면 다른 앱의 아이콘만 보입니다. 기본값은 켜짐입니다.
- 안정성을 향상시켰습니다.

---

## 1.0.5 — 2026-10-12

- New **Speed** and **Size** sliders for the pointer effect in Settings → Menu Bar Icons. The flight plays at 50–200% of its normal speed, and the rocket, trail, dart or Ddoee and its landing burst are drawn at 50–300% of their normal size. Both start at 100%.
- Buy buttons now tell the checkout page which button you used (Settings, the sale notice, or the trial-ended alert). It's a plain label with no identifier. See the [Privacy Policy](PRIVACY.md).

## 1.0.5 — 2026-10-12 (한국어)

- 설정 → 메뉴 막대 아이콘에 포인터 효과의 **속도**와 **크기** 슬라이더가 생겼습니다. 날아가는 속도를 보통의 50~200%로, 로켓·궤적·다트·또이와 착지 효과의 크기를 보통의 50~300%로 바꿀 수 있습니다. 기본값은 둘 다 100%입니다.
- 구매 버튼이 결제 페이지에 어느 버튼(설정, 할인 알림, 체험 종료 알림)에서 왔는지 알려 줍니다. 식별자가 없는 단순한 이름표입니다. 자세한 내용은 [개인정보처리방침](PRIVACY.ko.md)을 참고하세요.

---

## 1.0.4 — 2026-10-06

- The **Menu Bar Icons** popup opens instantly. MenuDart keeps the icon list ready in the background (when apps open or quit, and when your Mac wakes) and refreshes it while the popup is open, with an "Updating…" badge in the title.
- New option in Settings → Menu Bar Icons: **Refresh Icons Periodically**, every 1 to 30 minutes. It's off by default.
- New option in Settings → General: **Hide Dock Icon When Settings Closes**. It's on by default.
- Buy buttons now open checkout through `studiojin.dev`, so partners who referred you get credit. See the [Privacy Policy](PRIVACY.md).

## 1.0.4 — 2026-10-06 (한국어)

- **메뉴 막대 아이콘** 팝업이 바로 열립니다. MenuDart가 아이콘 목록을 백그라운드에서 미리 준비해 두고(앱을 열거나 닫을 때, Mac이 잠자기에서 깨어날 때), 팝업이 열려 있는 동안 제목에 "업데이트 중…"을 표시하며 새로 고칩니다.
- 설정 → 메뉴 막대 아이콘에 **아이콘 목록 주기적으로 새로 고침** 옵션이 생겼습니다(1~30분). 기본값은 꺼짐입니다.
- 설정 → 일반에 **설정 창을 닫으면 Dock에서 아이콘 숨기기** 옵션이 생겼습니다. 기본값은 켜짐입니다.
- 구매 버튼이 `studiojin.dev`를 거쳐 결제 페이지를 엽니다. 추천한 파트너가 수수료를 받을 수 있게 하기 위해서입니다. 자세한 내용은 [개인정보처리방침](PRIVACY.ko.md)을 참고하세요.

---

## 1.0.3 — 2026-10-06

- New **Get beta updates** option in Settings → Updates. Turn it on to try new features before they're released. It's off by default.
- If you're on a beta and turn the option off, MenuDart moves to the next release when it's out, or you can download the latest release right away.
- Settings → About now links to the new [Privacy Policy](PRIVACY.md). MenuDart doesn't track you: it goes online only for updates, license checks and, before you buy, sale info.

## 1.0.3 — 2026-10-06 (한국어)

- 설정 → 업데이트에 **베타 업데이트 받기** 옵션이 생겼습니다. 켜면 정식 출시 전에 새 기능을 먼저 써 볼 수 있습니다. 기본값은 꺼짐입니다.
- 베타를 쓰다가 옵션을 끄면 다음 정식 버전이 나올 때 그 버전으로 넘어가며, 바로 최신 정식 버전을 내려받을 수도 있습니다.
- 설정 → 정보에서 새 [개인정보처리방침](PRIVACY.ko.md)을 볼 수 있습니다. MenuDart는 사용자를 추적하지 않으며, 인터넷은 업데이트·라이선스 확인과 구매 전 할인 안내에만 사용합니다.

---

## 1.0.2 — 2026-10-05

- New pointer effect: **Ddoee**, a caped cat that flies your pointer to the menu. Choose it in Settings → Menu Bar Icons → Effect.

## 1.0.2 — 2026-10-05 (한국어)

- 새 포인터 효과 **또이**: 망토를 두른 고양이가 포인터를 메뉴까지 날라다 줍니다. 설정 → 메뉴 막대 아이콘 → 효과에서 고를 수 있습니다.

---

## 1.0.1 — 2026-10-05

- Before you buy, MenuDart lets you know about a running sale and when it ends, at most once a day. You can turn it off for that sale.
- During a sale, Buy buttons open checkout with the discount code already filled in.

## 1.0.1 — 2026-10-05 (한국어)

- 구매 전이라면 할인 행사가 진행 중일 때 할인 내용과 종료 시각을 하루에 한 번까지 알려 줍니다. 해당 할인은 다시 보지 않도록 끌 수 있습니다.
- 할인 기간에는 구매 버튼을 누르면 할인 코드가 입력된 결제 화면이 열립니다.

---

## 1.0.0 — 2026-10-05

First release.

- **App Menus** popup: shows the frontmost app's menus next to the pointer, even when they don't fit in the menu bar. Submenus open in place with a breadcrumb.
- **Menu Bar Icons** popup: gathers every menu bar icon into a grid, including icons hidden by a crowded menu bar or the notch, and moves the pointer to the menu you open.
- Global keyboard shortcuts for both popups, plus keyboard navigation.
- Available in 11 languages: English, Korean, Japanese, Simplified Chinese, Traditional Chinese, Portuguese (Brazil), Spanish, Hindi, Italian, German and French.
- 14-day free trial, then a one-time license.
- Automatic update checks (once a day; can be turned off in Settings).

---

## 1.0.0 — 2026-10-05 (한국어)

첫 릴리스.

- **앱 메뉴** 팝업: 맨 앞 앱의 메뉴를 포인터 옆에 보여 줍니다. 메뉴 막대에 다 들어가지 않는 메뉴도 볼 수 있고, 하위 메뉴는 그 자리에서 열리며 경로(breadcrumb)가 표시됩니다.
- **메뉴 막대 아이콘** 팝업: 메뉴 막대가 붐비거나 노치에 가려 숨겨진 아이콘까지 모든 메뉴 막대 아이콘을 격자로 모아 보여 주고, 연 메뉴로 포인터를 옮겨 줍니다.
- 두 팝업 모두 전역 단축키로 열고 키보드로 탐색할 수 있습니다.
- 11개 언어 지원: 영어, 한국어, 일본어, 중국어(간체·번체), 포르투갈어(브라질), 스페인어, 힌디어, 이탈리아어, 독일어, 프랑스어.
- 14일 무료 체험 후 1회 구매 라이선스.
- 자동 업데이트 확인(하루 한 번, 설정에서 끌 수 있음).
