# 웹 애플리케이션 서버

## 진행 방법

* 웹 애플리케이션 서버 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정

* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

## 1단계 - TDD 실습

### 요구사항 1 - GET 요청

- HTTP GET 요청에 대한 RequestLine을 파싱

> GET /users HTTP/1.1
> method는 GET
> path는 /users
> protocol은 HTTP
> version은 1.1


### 요구사항 2 - POST 요청

HTTP POST 요청에 대한 RequestLine을 파싱

> POST /users HTTP/1.1  
> method는 POST  
> path는 /users  
> protocol은 HTTP  
> version은 1.1

### 요구사항 3 - Query String 파싱
- HTTP 요청(request)의 Query String으로 전달되는 데이터 파싱
- 클라이언트에서 서버로 전달되는 데이터의 구조는 name1=value1&name2=value2

### 요구사항 4 - enum 적용
- HTTP method인 GET, POST를 enum으로 구현
