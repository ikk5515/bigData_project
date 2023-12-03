# 유튜브 랭크 사이트 크롤링을 통한 상위 1000명의 채널 데이터 분석 및 시각화
[유튜브 랭크](https://youtube-rank.com/board/bbs/board.php?bo_table=youtube) 사이트에 데이터를 바탕으로 진행하였습니다.
<br>

## 데이터 수집 방법
1. 웹 크롤링 도구 사용 (Selenium, BeautifulSoup)
2. 웹 페이지 접속
3. HTML 파싱 (BeautifulSoup)
4. 필요한 정보 추출 (BeautifulSoup)
5. 데이터 정리 및 저장 (title, category, subscriber, view, video)
6. 저장된 csv 확인
   <br><br>
   <img width="452" alt="image" src="https://github.com/ikk5515/bigData_project/assets/22267184/5544cc85-1684-42cb-b889-28880bb7c927">


## 데이터 전처리 
1. 데이터 로드
2. ‘subscriber’ 열 전처리
3. ‘video’ 열 전처리
4. 카테고리별 구독자 수 합과 카운트 계산

## 데이터 분석 및 시각화 내용
1. 각 카테고리별 구독자 비율
2. 각 카테고리의 비율
3. 각 카테고리별 영상 수 비율
4. 카테고리별 조회수
5. 상위 10개 채널의 구독자 수 및 카테고리 파악
6. 100만 구독자 이상과 미만의 채널 수
7. 100만 구독자 이상과 100만 구독자 미만의 카테고리별 비율
8. 구독자 수에 따른 평균 동영상 개수
