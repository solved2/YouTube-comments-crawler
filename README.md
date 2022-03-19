# YouTube-comments-crawler

본 프로젝트는 Selenium의 기초를 공부하기 위해 수행되었습니다.

원하는 유튜브 채널의 모든 동영상에 접근하여 특정한 문자열을 포함하는 댓글 및 해당 댓글의 답글을 크롤링합니다.

## INPUT

- 특정 유튜브 채널의 '동영상' 카테고리 url를 설정합니다.
- 원하는 문자열 키워드를 지정합니다.

## OUTPUT

- 설정한 url에 접근하여 해당 유튜버의 모든 영상의 url을 저장합니다.
- 각 url의 모든 댓글을 탐색하면서 특정 문자열을 포함하는 댓글과 그 댓글의 답글을 크롤링합니다.

## NOTE

- 웹 페이지 로딩 및 기타 변수에 따라 제대로 동작하지 않을 수 있습니다.
- 본 어플리케이션을 사용하는 당시 크롬 버전을 지원하는 크롬 드라이버를 불러오도록 해야합니다. 현재 업로드 해놓은 크롬 드라이버는 89.x 버전입니다.
