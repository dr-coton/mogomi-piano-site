# 공개 정적 페이지 / Published static pages

- `index.html`: 한국어·영어 지원·문의·FAQ. `support-ko.html`, `support-en.html`은 각 언어 별도 페이지.
- `privacy.html`: 한국어·영어 처리방침 전문. `privacy-ko.html`, `privacy-en.html`은 각 언어 별도 페이지. 시행일 **2026-11-18**(바이엘 랜드 주제 통과·보호자 바로가기 저장과 삭제 반영). 지원 FAQ 문구는 `tools/build_support_site.py`에 있다.
- 기존 모고미 색칠놀이 사이트의 크림 배경·카드·8개 방침 항목 형식을 따랐으며 피아노 기능으로 내용을 바꿨다. 색칠놀이 사이트는 수정하지 않았다.
- 개인정보 본문은 `shared/i18n/strings.json`의 `privacy.policy` 단일 원본을 사용한다. 수정 후 `.venv/bin/python tools/build_support_site.py`로 다시 만든다.
- JS·분석·광고·외부 폰트·외부 이미지·폼이 없다. 문의는 보호자가 직접 누르는 mailto 링크뿐이다. 공개 호스팅을 하면 호스팅 사업자가 HTTP 요청을 처리하므로 ‘공개 웹사이트에서도 네트워크가 전혀 없다’고 주장하지 않는다.
- **사용자 승인으로 공개 완료**: 지원 https://dr-coton.com/mogomi-piano-site/ , 처리방침 https://dr-coton.com/mogomi-piano-site/privacy.html . 공개 저장소 `dr-coton/mogomi-piano-site`의 GitHub Pages는 이 `site/`의 복사본이다. ko/en 별도 페이지도 같은 경로에서 제공한다. 이번 바이엘 랜드 수정분은 출시 대기 원고다. 공개 저장소에는 아직 복사하지 않았으며 출시 때 별도 반영한다. 스토어 콘솔 입력·제출은 별도 작업이다.
- 소스 검사만 수행. 브라우저·실기기 표시 확인을 했다고 주장하지 않는다.
