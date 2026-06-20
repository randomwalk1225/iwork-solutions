# iwork-solutions

아이워크수학(iWork Math) 학생들의 수학 경시대회 풀이 **채점 리포트 & 단계별 해설** 모음.
GitHub Pages 로 공개 게시.

- 공개 사이트: https://randomwalk1225.github.io/iwork-solutions/
- 정답 기준: 각 대회 공식 아카이브(예: HMMT) solutions.pdf
- 형식: 자체 완결형 HTML(MathJax v3, MaruBuri/Noto Serif KR) — 영어·한글 단계별 풀이 + 심화

## 구조

```
index.html              # 리포트 카탈로그(랜딩)
reports/                # 개별 채점·해설 리포트 (self-contained HTML, PDF)
  hmmt-2024-general-yunje.html / .pdf
  hmmt-2025-general-yunje.html
.nojekyll               # Jekyll 처리 비활성(파일 그대로 서빙)
```

## 새 리포트 추가

1. 채점 리포트 HTML 생성(생성기: myclass `students/<학생>/build_*.py`, 표준 = HTML 해설 하네스 룰 25)
2. `reports/` 에 ASCII 파일명으로 복사 (`<대회>-<연도>-<라운드>-<학생>.html`)
3. `index.html` 카탈로그에 카드 추가
4. commit & push → Pages 자동 반영

원장 이상열 · 무단복제 금지
