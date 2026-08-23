# misc — 교육 외 기타업무용 개인자료 (긴급 웹 공유)

학생자료(students/·reports/)와 같은 사이트에 올리되, **교육 자료가 아닌 기타 업무용 파일**(계약·분쟁 자료, 보고서 초안 등)을 급히 웹으로 공유해야 할 때만 쓰는 폴더.

규칙
- 항목마다 추측 불가능한 폴더명을 쓴다: `misc/<8자리 무작위 hex>/` (예: `misc/3f9a1c2e/`). 생성: `python3 -c "import secrets;print(secrets.token_hex(4))"`
- 이 폴더는 index.html·sitemap·어디에도 링크하지 않는다. HTML에는 `<meta name="robots" content="noindex,nofollow">` 를 넣는다.
- GitHub Pages 는 비밀번호가 없다 — URL 을 아는 사람은 누구나 본다. 공유가 끝나면 폴더를 지우고 커밋한다.
- URL: https://randomwalk1225.github.io/iwork-solutions/misc/<id>/
