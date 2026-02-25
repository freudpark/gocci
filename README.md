# PyhgoShift Security PDF Viewer (Gocci)

![Security Level](https://img.shields.io/badge/Security-MAXIMUM-red) ![Tech](https://img.shields.io/badge/Tech-HTML5_%2F_JS_%2F_CSS3-blue)

본 프로젝트는 경기도교육청 정보자원통합 중간보고회 자료를 보호하기 위해 구축된 **고보안성 웹 PDF 뷰어**입니다. 무단 다운로드, 복제, 스크린샷 캡처 및 비정상적인 접근을 차단하면서도 사용자에게 유려한 페이지 탐색 경험을 제공하는 것을 목표로 합니다.

## 🚀 주요 기능 (Features)

### 1. 전방위 보안 프로토콜 (Security Protocol)
- **우클릭 및 선택 차단**: 모든 마우스 우클릭 명령 및 텍스트 선택을 원천 차단합니다.
- **키보드 잠금 (Zero-Leak)**: `F12`(개발자 도구), `Ctrl+S`(저장), `Ctrl+P`(인쇄), `Ctrl+U`(소스 보기) 등의 모든 보안 취약 단축키를 비활성화합니다.
- **투명 보호막 (Interaction Wall)**: PDF Iframe 상단에 투명 오버레이를 배치하여 PDF 엔진 자체에 대한 직접적인 상호작용(저장 버튼 클릭 등)을 물리적으로 차단합니다.

### 2. 프리미엄 내비게이션 (Advanced UI/UX)
- **심볼 기반 탐색**: 텍스트 대신 직관적인 `▲`(이전), `▼`(다음) 심볼을 사용하여 간결하고 현대적인 인터페이스를 제공합니다.
- **슬라이딩 페이지 전환**: 페이지 이동 시 부드러운 하드웨어 가속 애니메이션을 통해 실제 종이를 넘기거나 스크롤하는 듯한 시각적 경험을 제공합니다.
- **스크롤바 제로 (Clean View)**: 모든 브라우저 및 뷰어 내부 스크롤바를 숨겨 자료에만 온전히 집중할 수 있는 환경을 조성합니다.
- **스마트 휠 서포트**: 보호막 위에서도 마우스 휠을 통해 자연스럽게 페이지를 넘길 수 있도록 이벤트 포워딩 기술을 적용했습니다.

### 3. 기술적 최적화 (Technical Excellence)
- **캐시 버스팅 (Cache Busting)**: 매 업데이트마다 고유한 타임스탬프 파라미터를 사용하여 사용자가 항상 최신 버전의 보고서를 확인하도록 강제합니다.
- **Iframe 격리**: PDF 로직을 독립된 컨테이너에서 실행하여 메인 보안 스크립트와의 간섭을 방지합니다.

## 🛠 사용 방법 (How to Use)

- **이동**: 화면 상단의 `▲`, `▼` 버튼을 누르거나 마우스 휠을 사용하세요.
- **키보드 단축키**: `ArrowUp/Down`, `PageUp/Down`, `Space` 키를 통해 페이지를 이동할 수 있습니다.
- **접근 주소**: [https://freudpark.github.io/gocci/report_no.html](https://freudpark.github.io/gocci/report_no.html)

## 📁 디렉토리 구조 (Structure)

```text
d:\park-ai\app\report_225\
├── geoci_225report.pdf   # 보안 대상 PDF 파일
├── report_no.html        # 고보안 PDF 뷰어 (Main)
└── README.md             # 프로젝트 명세서
```

---
**PyhgoShift Digital Workforce**
*Developed by The 7 Parks Group*
