# 붉은 달의 성채
게임 세이브 파일을 관리하는 REST API 서버입니다

## 기능
- 게임 세이브 파일 생성
- 세이브 파일 목록 조회
- 특정 세이브 파일 조회
- 세이브 파일 이름 수정
- 세이브 파일 삭제

## 기술 스택
- Java
- Spring Boot
- Spring Data JPA
- MySQL

## API
- 게임 세이브 파일 생성\
  `POST /games`
- 세이브 파일 목록 조회\
`GET /games`
- 특정 세이브 파일 조회\
`GET /games/{gameId}`
- 세이브 파일 이름 수정\
  `PUT /games/{gameId}`
- 세이브 파일 삭제\
  `DELETE /games/{gameId}`
