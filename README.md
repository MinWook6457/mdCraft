<p align="center">
  <img src="https://img.shields.io/badge/MDCRAFT-Markdown%20Editor-6c5ce7?style=for-the-badge&logo=markdown&logoColor=white" alt="MDCRAFT">
</p>

<h1 align="center">M↓ MDCRAFT</h1>

<p align="center">
  <strong>실시간 미리보기를 지원하는 온라인 마크다운 에디터</strong><br>
  작성과 동시에 렌더링 결과를 확인하고, PDF로 내보내고, 탭 문법까지 지원합니다.
</p>

<p align="center">
  <a href="https://minwook6457.github.io/mdCraft/">🚀 지금 사용하기</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#features">기능 소개</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#tab-syntax">탭 문법</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#shortcuts">단축키</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/vanilla-HTML%2FCSS%2FJS-f0db4f?style=flat-square" alt="Vanilla JS">
  <img src="https://img.shields.io/badge/deploy-GitHub%20Pages-222?style=flat-square&logo=github" alt="GitHub Pages">
</p>

---

## 🔗 바로가기

> **https://minwook6457.github.io/mdCraft/**

별도 설치 없이 브라우저에서 바로 사용할 수 있습니다.

---

<h2 id="features">✨ 주요 기능</h2>

### 📝 실시간 마크다운 편집

좌측 다크 테마 에디터에서 마크다운을 작성하면 우측 라이트 테마 패널에서 렌더링 결과가 **실시간으로** 반영됩니다. GFM(GitHub Flavored Markdown)을 완벽 지원하여 테이블, 체크리스트, 취소선 등을 자유롭게 사용할 수 있습니다.

### 🎨 코드 하이라이팅

`highlight.js` 기반으로 다양한 프로그래밍 언어의 구문을 자동 하이라이팅합니다. 코드블록은 macOS 스타일 헤더(트래픽 라이트 + 언어 라벨)로 렌더링되며, **Copy 버튼**으로 코드를 한 번에 복사하거나 **접기/펼치기**로 긴 코드를 관리할 수 있습니다.

### 📑 탭 UI 확장 문법

표준 마크다운에는 없는 **탭 블록 문법**을 자체 지원합니다. 대용량 데이터 분석, 단계별 가이드, 비교 자료 등을 탭으로 구분해 깔끔하게 표현할 수 있습니다. 자세한 문법은 [아래 섹션](#tab-syntax)을 참고하세요.

### 📄 PDF 내보내기

미리보기 영역을 **벡터 기반**으로 PDF 변환합니다. 브라우저 네이티브 인쇄 엔진을 활용하여 텍스트가 선명하게 출력되며, 코드블록 배경색/테이블 스타일도 그대로 유지됩니다.

### 📂 파일 열기 & 드래그 앤 드롭

`.md`, `.markdown`, `.txt` 파일을 **열기 버튼** 또는 **드래그 앤 드롭**으로 불러올 수 있습니다. 불러온 파일명은 하단 상태바에 표시되며, 저장 시 원본 파일명이 유지됩니다.

### 🕐 저장 이력 관리

저장할 때마다 이력이 자동으로 기록됩니다. 이력 패널에서 파일명, 저장 시간, 파일 크기, 내용 미리보기를 확인하고 **원클릭으로 복원**하거나 **개별 삭제**할 수 있습니다. 이력은 브라우저에 보관되어 재방문 시에도 유지됩니다(최대 30개).

### 🖥️ 유연한 레이아웃

분할 뷰 / 에디터 전용 / 미리보기 전용 세 가지 모드를 지원하며, 패널 경계를 **드래그**하여 비율을 자유롭게 조절할 수 있습니다. 모바일에서도 반응형으로 동작합니다.

---

<h2 id="tab-syntax">📊 탭 문법 가이드</h2>

`:::tabs`로 탭 블록을 열고, `::tab 탭이름`으로 각 탭을 구분한 뒤, `:::`로 닫습니다.

### 작성 예시

```markdown
:::tabs
::tab 개요

여기에 첫 번째 탭 내용을 작성합니다.

::tab 상세 분석

| 항목 | 값 |
|------|-----|
| 행 수 | 250,000 |
| 컬럼 수 | 500 |

::tab 결론

> 최종 정리 내용을 작성합니다.

:::
```

미리보기에서는 클릭으로 전환 가능한 탭 UI로 렌더링됩니다. 각 탭 내부에서 테이블, 코드블록, 리스트 등 모든 마크다운 문법을 그대로 사용할 수 있습니다.

---

<h2 id="shortcuts">⌨️ 단축키</h2>

| 단축키 | 기능 |
|--------|------|
| `Ctrl/⌘ + B` | 굵게 |
| `Ctrl/⌘ + I` | 기울임 |
| `Ctrl/⌘ + K` | 링크 삽입 |
| `Ctrl/⌘ + S` | .md 파일 저장 |
| `Tab` | 들여쓰기 (스페이스 2칸) |

---

## 🧰 툴바 기능

| 버튼 | 기능 | 버튼 | 기능 |
|------|------|------|------|
| **H1 H2 H3** | 제목 삽입 | **B** | 굵게 |
| **I** | 기울임 | **S** | 취소선 |
| `<>` | 인라인 코드 | 🔗 | 링크 삽입 |
| 🖼️ | 이미지 삽입 | 📊 | 테이블 삽입 |
| ☰ | 순서 없는 목록 | 1. | 순서 있는 목록 |
| ☑ | 체크리스트 | ❝ | 인용문 |
| `[code]` | 코드 블록 | ─ | 구분선 |
| 📑 | 탭 블록 삽입 | | |

---

## 🏗️ 기술 스택

| 구분 | 기술 |
|------|------|
| 코어 | Vanilla HTML / CSS / JavaScript |
| 마크다운 파서 | [marked.js](https://github.com/markedjs/marked) (GFM 지원) |
| 코드 하이라이팅 | [highlight.js](https://highlightjs.org/) |
| 폰트 | JetBrains Mono, Noto Sans KR, Playfair Display |
| PDF 변환 | 브라우저 네이티브 `window.print()` (벡터 렌더링) |
| 배포 | GitHub Pages |

외부 프레임워크 없이 **HTML 파일 하나**로 동작하며, CDN만 참조하므로 어디서든 바로 배포할 수 있습니다.

---

## 📁 프로젝트 구조

```
mdCraft/
├── index.html          # 에디터 전체 (HTML + CSS + JS 단일 파일)
└── README.md           # 이 문서
```

---

## 📜 라이선스

MIT License — 자유롭게 사용, 수정, 배포할 수 있습니다.

---

<p align="center">
  <strong>MDCRAFT</strong>
  <a href="https://minwook6457.github.io/mdCraft/">https://minwook6457.github.io/mdCraft/</a>
</p>
