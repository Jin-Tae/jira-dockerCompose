Docker + jira  + mysql 설치


1. Docker 설치(Ubuntu)
 - 참고 주소 : https://monta010.tistory.com/49?category=1221923
2. Docker Compose 실행
 - 시작 : docker-compose up -d
 - 삭제 : docker-compose down

3. 접속
  - localhost:8080

##
Docker Compose 실행시 "jira_data, mysql_data" 자동으로 폴더 생성 완료
  > Docker 특성상 종료시 데이터 증발으로 로컬 폴더에 마운트 폴더 지정
  > 원하는 폴더명으로 변경하셔서 사용 하셔도 됩니다.


