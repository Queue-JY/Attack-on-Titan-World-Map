# 🗺️ Attack on Titan World Map

> 진격의 거인 세계관을 인터랙티브 지도로 표현한 팬 사이트입니다.

🔗 **[라이브 데모 보기]([https://queue-jy.github.io/frontend/](https://queue-jy.github.io/Attack-on-Titan-World-Map/))**

---

## 📌 프로젝트 소개

진격의 거인(Attack on Titan)의 세계관 — 마레, 파라디 섬, 세 개의 벽 — 을 클릭 가능한 인터랙티브 지도로 구현했습니다.  
각 지역을 클릭하면 해당 지역의 상세 페이지로 이동합니다.

---

## 🖥️ 주요 기능

| 기능 | 설명 |
|------|------|
| 🌊 **바다 (Sea)** | 지도 전체 클릭 시 바다 페이지로 이동 |
| 🏙️ **마레 (Marley)** | 마레 지역 클릭 시 마레 페이지로 이동 |
| 🧱 **월 마리아 (Wall Maria)** | 가장 바깥쪽 벽 페이지로 이동 |
| 🧱 **월 로제 (Wall Rose)** | 중간 벽 페이지로 이동 |
| 🧱 **월 시나 (Wall Sina)** | 가장 안쪽 벽 페이지로 이동 |
| 👁️ **방문자 카운터** | CounterAPI를 통한 실시간 방문자 수 표시 |

---

## 📁 프로젝트 구조

```
frontend/
│
├── index.html                  # 메인 월드맵 페이지
│
├── pages/                      # 각 지역별 상세 페이지
│   ├── maria.html              # 월 마리아
│   ├── rose.html               # 월 로제
│   ├── sina.html               # 월 시나
│   ├── marley.html             # 마레
│   └── sea.html                # 바다
│
└── assets/
    ├── css/                    # 스타일시트
    └── images/                 # 지역별 이미지
        ├── maria/
        ├── marley/
        ├── rose/
        ├── sea/
        └── sina/
```

---

## 🛠️ 기술 스택

- **HTML5** — 시맨틱 마크업
- **CSS3** — 레이아웃 및 인터랙티브 스타일링
- **JavaScript (Vanilla)** — 클릭 이벤트 및 API 연동
- **Font Awesome 6** — 아이콘
- **CounterAPI** — 방문자 수 집계

---

## 🚀 로컬 실행 방법

별도의 빌드 과정 없이 바로 실행 가능합니다.

```bash
# 저장소 클론
git clone https://github.com/queue-jy/frontend.git

# 폴더 이동
cd frontend

# index.html을 브라우저에서 열기
open index.html
```

> ⚠️ 방문자 카운터는 외부 API를 사용하므로 인터넷 연결이 필요합니다.

---

## 📄 라이선스

이 프로젝트는 **팬 사이트**로, 비상업적 목적으로 제작되었습니다.

> Attack on Titan © Hajime Isayama / Kodansha. All rights reserved.  
> 원작의 저작권은 이사야마 하지메 및 코단샤에 있습니다.
