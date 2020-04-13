# 우리동네 마스크

[우리동네 마스크](http://maskfind.com) / maskfind.com

진행: 2020-03-07 ~

## 1.0.0

2020-03-11 / 기본기능 추가

- 검색기능
- 지도 오버레이

## 1.1.0

2020-03-12 / aws workflow(ci)

- main.yml 작성

## 1.2.0 (issue 8)

2020-03-13 / 편의 기능추가

- 판매중인 곳만 목록으로 표시
- 모바일 최적화
- 데스크탑 animation 추가
- 재고 없는 곳 표시안함 버튼 추가
- 아이콘 수
  <img width="2032" alt="스크린샷 2020-03-13 오전 2 06 52" src="https://user-images.githubusercontent.com/16554536/76546711-5547d400-64cf-11ea-94d9-4b748bcd7760.png">

## 1.2.1

2020-03-13 / hotfix

- 판매중지 하는 곳 (break) 추가로 인한 hotfix

## 1.3.0

2020-03-14 기능추가

- 노티에서 동의 받을 경우 하루동안 보이지 않음
- 현재위치, 검색위치에 마커가 생성됨
- 새로고침 기능 추가(마커생성)
- 눈 아이콘(재고없음 표시안하기) acitve css 추가
- pagenation 제거 -> 스크롤로 변경 (스크롤 커스텀)
- seo(robots.txt, sitemap.xml) 추가
- 폰트추가(나눔고딕), vue-meta로 meta정보 추가
- favicon 수정
  <img width="1792" alt="스크린샷 2020-03-14 오전 1 31 31" src="https://user-images.githubusercontent.com/16554536/76640589-8be72280-6593-11ea-9d0d-a6341437b14f.png">

## 1.3.1

2020-03-15 버그

- 모아보기 기능 지도 위치 기준으로 보여지던것 수정(현재위치로 표시)
- 공지추가
- 마커색상 변경
- 위치 정보 없을 시 모아보기 지도 기준으로 변경

## 1.3.2

2020-03-16 주석, 코드 정리

- 주석추가
- 코드 정리

## 1.3.3

2020-03-18 bug

- 재고없음 표시 지우기 아이콘 활성화 표시 안되는거 수정

## 1.3.4

2020-04-13 aws, favicon, sourcemap

- aws s3 버킷, cloudfront 보안 사항 추가
- favicon 추가
- Production sourceMap 보안 설정
