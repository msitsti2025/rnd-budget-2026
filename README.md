# 한 눈에 보는 2026년 정부 R&D 예산

> 2026년 국가연구개발사업 세부사업 예산을 10대 핵심투자분야 위주로 보여준다.

🔗 **라이브 데모**: [https://msitsti2025.github.io/rnd-budget-2026/](https://msitsti2025.github.io/rnd-budget-2026/)

---

## 📊 주요 기능

- **총 1,236개 세부사업** 예산 현황 조회 및 분석
- **국가전략기술 12개 분야**별 예산 배분 현황 시각화
  - 인공지능, 첨단바이오, 양자, 우주항공해양, 반도체/디스플레이, 첨단모빌리티, 첨단로봇제조, 차세대통신, 수소, 차세대원자력, 이차전지, 사이버보안
- **정책분야 8개 분야**별 예산 분류
  - 기초, 탄소중립, 국방, 출연직할, 재난안전, 지역, 기술사업화, 인력양성
- **33개 부처**별 R&D 예산 현황
- **10개 전문위원회**별 예산 분석
- 다중 필터링 (사업명 검색, 전문위, 부처, 전략기술, 정책분야)
- 실시간 KPI 및 차트 업데이트

## 🛠 기술 스택

- **Frontend**: Vanilla HTML/CSS/JavaScript (의존성 최소화)
- **차트 라이브러리**: [Chart.js](https://www.chartjs.org/) v4.4.0
- **데이터**: JSON (xlsx에서 변환)
- **배포**: GitHub Pages (정적 웹사이트)

## 📁 프로젝트 구조

```
rnd-budget-2026/
├── index.html      # 메인 플랫폼 (단일 파일)
├── data.json       # R&D 예산 데이터 (1,236개 세부사업)
└── README.md       # 문서
```

## 🚀 GitHub Pages 배포 방법

### 1단계: 저장소 생성
```bash
# GitHub에서 새 저장소 생성 (예: rnd-budget-2026)
# 또는 기존 저장소 사용
```

### 2단계: 파일 업로드
```bash
git init
git add .
git commit -m "초기 커밋: 2026 R&D 예산 분석 플랫폼"
git branch -M main
git remote add origin https://github.com/[username]/rnd-budget-2026.git
git push -u origin main
```

### 3단계: GitHub Pages 활성화
1. 저장소 → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main**, Folder: **/ (root)**
4. **Save** 클릭
5. 약 1~2분 후 `https://[username].github.io/rnd-budget-2026/` 접속 가능

## 📈 데이터 출처

- 국가과학기술자문회의 심의회의 제출 자료
- **2026년 국가연구개발사업 예산 배분·조정(안)** (세부사업 기준)
- 단위: 백만원

## 📝 라이선스

본 플랫폼의 코드는 MIT License를 따릅니다.  
데이터는 공공데이터 이용 정책을 따릅니다.
