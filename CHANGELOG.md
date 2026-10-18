# Changelog

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
