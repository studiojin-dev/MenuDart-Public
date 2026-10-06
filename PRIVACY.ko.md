# MenuDart 개인정보처리방침

[English](PRIVACY.md) | 한국어

시행일: 2026년 10월 6일

스튜디오진(이하 "회사")은 macOS 메뉴 막대 앱 MenuDart를 만듭니다. 이 방침은 MenuDart가 이용자의 정보를 어떻게 다루는지 설명합니다. 요약하면, **MenuDart에는 회원 가입, 이용 분석, 광고, 행동 추적, 쿠키가 없습니다.** 인터넷은 업데이트 확인, 라이선스 확인, 그리고 구매 전 할인 행사 확인에만 사용합니다.

## Mac 안에서만 처리하는 정보

MenuDart는 손쉬운 사용과 화면 기록 권한으로 다음 정보를 읽습니다. 이 정보는 모두 이용자의 Mac 안에서만 쓰이며 외부로 보내지 않습니다.

- **앱 메뉴**: 팝업으로 보여 주기 위해 손쉬운 사용 권한으로 읽습니다.
- **메뉴 막대 아이콘**: 격자로 보여 주기 위해 화면 기록 권한으로 메뉴 막대 부분을 캡처합니다. 이미지는 팝업에 필요한 동안 메모리에만 두며, 디스크에 저장하거나 전송하지 않습니다.
- **설정**(단축키, 언어, 화면 모드 등): Mac의 사용자 기본값(user defaults)에 저장합니다.
- **라이선스 정보**(라이선스 키, 활성화 정보): Mac의 로그인 키체인에 저장합니다. 체험 시작일은 사용자 기본값에 저장합니다.

## 인터넷 연결과 전송하는 정보

MenuDart는 아래 목적으로만 인터넷에 연결합니다. 메뉴 내용, 화면 내용, 파일, 키 입력, 사용 기록은 보내지 않습니다.

| 목적 | 받는 곳 | 보내는 정보 | 시점 |
|---|---|---|---|
| 업데이트 확인 | GitHub (`raw.githubusercontent.com`, `github.com`) | 업데이트 목록 요청(요청 헤더에 MenuDart 버전 포함). 시스템 정보(system profile)는 보내지 않습니다. | 자동 확인이 켜져 있으면 하루 한 번(설정 → 업데이트에서 끌 수 있음), 그리고 "업데이트 확인"을 누를 때. 업데이트 파일도 GitHub에서 내려받습니다. |
| 라이선스 활성화·확인 | Lemon Squeezy (`api.lemonsqueezy.com`) | 라이선스 키, 활성화할 때 Mac의 컴퓨터 이름(여러 Mac을 구분하기 위함). 이후 확인 때는 라이선스 키와 활성화 ID. | 라이선스를 활성화·해제할 때, 활성화 후 약 하루 한 번. |
| 할인 행사 확인 | 스튜디오진 (`studiojin.dev`) | 현재 할인 행사 조회 요청만 보냅니다. 식별자나 라이선스 정보는 보내지 않습니다. | 라이선스를 활성화하기 전에만, 최대 36시간에 한 번. |

일반적인 인터넷 연결과 마찬가지로 위 서비스는 이용자의 IP 주소를 알 수 있습니다. 각 서비스가 받는 정보에는 해당 서비스의 개인정보처리방침이 적용됩니다:
[GitHub](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement) ·
[Lemon Squeezy](https://www.lemonsqueezy.com/privacy) ·
[Cloudflare](https://www.cloudflare.com/privacypolicy/)(`studiojin.dev` 호스팅).

## 구매

"구매"를 누르면 웹 브라우저에서 결제 페이지가 열립니다. 결제는 판매 대행사(merchant of record)인 Lemon Squeezy가 처리하며, 이메일 주소와 결제 정보는 Lemon Squeezy가 자체 개인정보처리방침에 따라 수집합니다. MenuDart 앱은 결제 정보를 다루지 않습니다.

## 문의

이메일이나 GitHub Issues로 문의하면, 보내 주신 내용은 답변하는 데에만 사용합니다. GitHub Issues는 공개되므로 개인정보나 라이선스 키를 올리지 마세요.

## 보관과 삭제

Mac에 저장된 정보는 이용자가 지울 때까지 남아 있습니다. 지우려면 MenuDart를 삭제하고, 원하면 설정 파일(`~/Library/Preferences/dev.studiojin.MenuDart.plist`)과 키체인 접근의 `dev.studiojin.MenuDart.license` 항목도 삭제하세요. 다른 Mac에서 라이선스를 쓰려면 먼저 설정에서 라이선스를 해제하세요. Lemon Squeezy에 있는 정보는 라이선스 제공과 법령에 필요한 기간 동안 보관되며, 열람이나 삭제를 원하면 아래 연락처로 요청해 주세요.

## 아동

MenuDart는 아동을 대상으로 하지 않으며, 아동의 정보를 알면서 수집하지 않습니다.

## 변경

이 방침이 바뀌면 이 페이지와 시행일을 갱신합니다. 중요한 변경은 릴리스 노트에도 안내합니다.

## 개인정보 보호책임자·연락처

스튜디오진(Studiojin) · 대표자 겸 개인정보 보호책임자: 김정진
support@studiojin.dev
