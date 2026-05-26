# 2026 동남아 부모님 동반 휴양지 가이드

정적 HTML 사이트 진입점은 `index.html`입니다.

GitHub Pages에 올릴 때는 저장소 설정에서 Pages source를 `Deploy from a branch`로 선택하고, branch의 `/docs` 폴더를 publish root로 지정하면 됩니다. 그러면 이 페이지는 `/travel/2026-sea-family-resort/` 경로로 접근할 수 있습니다.

현재 HTML은 2026년 9월/10월/11월 각각의 추천 1·2·3위를 먼저 보여주고, 항공권·이동 경로·동남아 부모님 여행팩·숙소·숙소별 가이드북·맛집·마사지·참고자료를 이어서 보여줍니다.

주요 데이터:

- `monthly_rankings.json`: 월별 1·2·3위
- `flights.json`: 월별/노선별 항공권 예상가와 저렴한 출발 패턴
- `image_pack.json`: 화면에 쓰는 실제 여행지 이미지 묶음
- `routes.json`: 공항, 숙소, 식당, 마사지 이동 경로
- `practical_travel_pack.json`: 건강·교통·통신·식사·우천·해변 안전 체크리스트
- `guidebook_insights.json`: 네이버 블로그와 구글 여행가이드 참고 후 일정 보정안
- `resort_guidebook.json`: 숙소별 이미지, 공식 사진 링크, 근처 갈만한 곳, 하루 동선
- `food_and_spa.json`: 맛집·마사지별 음식 이미지, 추천 메뉴, 가격대, 부모님 동선 팁
- `crawl_evidence.json`: 내부 분석용 검색 근거

전체 분석 데이터는 `C:\Users\guswn\opencrab-ontology-packs\sea_family_resort_2026_crawled_pack`에 생성됩니다.
