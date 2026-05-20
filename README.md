# 바비즈코리아 소개 페이지

> Birth of Happyfamily, **babiz** — 모자보건·육아 전문 기업 (주)바비즈코리아의 소개 홈페이지.
> 디지털 케어 브랜드 **맘곁(MomGyeot)** 을 중심으로 마더스베이비(Mothersbaby) 라인까지 함께 소개합니다.

## 미리보기

```bash
# 1) 로컬 HTTP 서버 띄우기 (이미지 로딩 확실히 됨)
python3 -m http.server 8765

# 2) 브라우저에서 열기
open http://127.0.0.1:8765/index.html
```

또는 `index.html` 파일을 더블클릭해 브라우저에서 바로 열어도 됩니다.

## 페이지 구성

| 섹션 | 설명 |
|---|---|
| **Hero (3-슬라이드 롤링 배너)** | ① Birth of Happyfamily / ② 마더스베이비 수유쿠션 / ③ 맘곁 앱 |
| **01. Company Overview** | (주)바비즈코리아 24년, 300+ 산후조리원, 100+ 공공기관 |
| **02. Momgyeot · Philosophy** | 임신맘곁 / 육아맘곁 — 태교 심리 기반 디지털 케어 |
| **In the App** | 맘곁 앱 폰 미리보기 3종 (모유수유 가이드 / 상담 / 인트로) |
| **03. Why Momgyeot** | 예비·임신·육아·산후 4단계 라이프사이클 + 가족 공동육아 |
| **04. Brands** | 맘곁 (Featured) + 마더스베이비 + 바비즈 그룹 |
| **05. Signature Products** | 수유쿠션 / 수유브라 / 유축기 / 압박밴드 / 바디필로우 |
| **06. Partnership** | 산부인과·산후조리원·공공기관·해외 브랜드 |
| **07. Culture** | 무료 강좌 + 사회공헌 (세이브더칠드런 2025.12) |

## 디자인

- **컬러**: 올리브 그린 `#5d6e2c` × 크림 `#f5f2e9`
- **타이포**: Pretendard / Noto Serif KR / Cormorant Garamond / Inter
- **반응형**: 데스크탑 / 태블릿 / 모바일 (햄버거 메뉴 포함)
- **상호작용**: Hero 자동 롤링 (6초), 수동 이전/다음/도트, 터치 스와이프

## 폴더 구조

```
.
├── index.html                # 단일 페이지 (모든 마크업/스타일/스크립트 포함)
├── images/
│   ├── hero-cushion.jpg            # Hero 슬라이드 #2 (수유쿠션 모델)
│   ├── momgyeot-app-*.png          # 맘곁 앱 스크린샷
│   ├── mothersbaby-*.jpg           # 마더스베이비 제품 컷
│   ├── nursing-cushion.jpg / breast-pump.jpg / nursing-bra-main.jpg
│   ├── compression-band.jpg / body-pillow.jpg
│   ├── partner-*.jpg               # 파트너십 4-grid 사진
│   ├── culture.jpg                 # 강좌 모임 사진
│   └── save-the-children.jpg       # 사회공헌 사진
└── README.md
```

## 링크

- 맘곁 — https://www.momgyeot.com
- 마더스베이비 — https://www.mothersbaby.co.kr
- 바비즈코리아 그룹 — https://www.babiz.co.kr

---
© 2026 Babiz Korea Co., Ltd. · 대표이사 최소라 · 설립 2002년
