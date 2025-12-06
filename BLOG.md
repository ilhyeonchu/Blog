# 블로그 제목(title): Chu-rious Enough to Learn Everything...  including regex

## 블로그 tagline : A Fool's Study Log

## 블로그 user 정보
1. email: ilhyeonchu@gmail.com
2. github username: ilhyeonchu
3. timezone: Asia/Seoul
4. language: kr, en

## 블로그 전체 구조

1. 특정 글을 선택하지 않은 경우

| 프로필(tagline + 이름) | 블로그 제목 | 글 검색 기능|
| ------ | --------------------- | ----------- |
| 신규 글 작성 버튼 | 최근 업데이트된 글 목록 or 선택한 카테고리, tag의 글 목록 | 최근 업데이트 |
| 카테고리 tag 목록 | 최근 업데이트된 글 목록 or 선택한 카테고리, tag 글 목록 | trending tags |

2. 특정 글을 선택한 경우

| 프로필(tagline + 이름) | 블로그 제목 | 글 검색 기능|
| ------ | --------------------- | ----------- |
| 신규 글 작성 버튼 | 선택한 글이 해당하는 카테고리, tag의 글 목록 | 최근 업데이트 |
| 카테고리 tag 목록 | 선택한 글 본문 | trending tags |


카테고리 또는 tag 목록은 트리 형태로 폴드, 언폴드 가능하도록 구현
제목은 카테고리로 카테고리가 우선 정렬되고 거기에 트리 형태로 하위 카테고리나 tag들이 정렬되도록
카테고리 선택시 1번 구조지만 본문에 나오는 글 목록 업데이트 
원하는 글을 선택 시 2. 구조로 넘어가도록 구현
