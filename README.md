# 🎮 NEON DROP — Tetris

> 캡스톤디자인 과제 | 사이버펑크 네온 테마 테트리스 게임

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## 📖 소개

**NEON DROP**은 클래식 테트리스를 사이버펑크/네온 테마로 재해석한 웹 기반 게임입니다.  
순수 HTML, CSS, JavaScript만으로 제작되었으며, 별도의 라이브러리 없이 동작합니다.

## ✨ 주요 기능

- **SRS (Super Rotation System)** — 표준 테트리스 회전 시스템 및 벽차기(Wall Kick) 구현
- **고스트 피스** — 블록이 떨어질 위치를 미리 표시
- **홀드 시스템** — 현재 블록을 보관하고 나중에 사용
- **Next Queue** — 다음에 나올 3개의 블록 미리보기
- **7-Bag 랜덤 시스템** — 공정한 블록 분배
- **콤보 & 레벨 시스템** — 연속 라인 클리어 시 보너스 점수
- **파티클 이펙트** — 라인 클리어 시 화려한 파티클 애니메이션
- **DAS/ARR** — 부드러운 좌우 이동 (Delayed Auto Shift)
- **반응형 디자인** — 모바일 터치 컨트롤 지원

## 🎮 조작법

| 키 | 동작 |
|---|---|
| `←` `→` | 좌우 이동 |
| `↑` | 시계 방향 회전 |
| `Z` | 반시계 방향 회전 |
| `↓` | 소프트 드롭 |
| `Space` | 하드 드롭 |
| `C` | 홀드 |
| `P` | 일시정지 |

모바일에서는 화면 하단의 터치 버튼으로 조작할 수 있습니다.

## 🚀 실행 방법

### 방법 1: 직접 열기
```
index.html 파일을 웹 브라우저에서 열기
```

### 방법 2: GitHub Pages로 배포
1. 이 저장소를 GitHub에 Push
2. Settings → Pages → Source를 `main` 브랜치로 설정
3. `https://<username>.github.io/<repo-name>` 에서 플레이

## 📁 프로젝트 구조

```
tetris/
├── index.html    # 게임 전체 (HTML + CSS + JS)
└── README.md     # 프로젝트 설명
```

## 🎯 점수 시스템

| 라인 클리어 | 기본 점수 |
|---|---|
| 1줄 (Single) | 100 × 레벨 |
| 2줄 (Double) | 300 × 레벨 |
| 3줄 (Triple) | 500 × 레벨 |
| 4줄 (Tetris) | 800 × 레벨 |

- **소프트 드롭**: 칸당 1점
- **하드 드롭**: 칸당 2점
- **콤보 보너스**: 50 × 콤보 수 × 레벨

## 🛠️ 기술 스택

- **HTML5 Canvas** — 게임 렌더링
- **CSS3** — 네온 글로우 이펙트, 애니메이션, 반응형 레이아웃
- **Vanilla JavaScript** — 게임 로직, 물리 엔진
- 외부 라이브러리 없음 (Zero Dependencies)

## 📜 라이선스

MIT License
