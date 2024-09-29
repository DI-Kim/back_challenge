# 설계

1. 책 정보 생성하기(POST)
   `/books`
2. 책 목록 가져오기(GET)
   `/books`
3. 책 정보 읽기(POST)
   `/books/:id`
4. 책 정보 갱신하기(PUT)
   `/books/:id`
5. 책 정보 삭제하기()
   `/books/:id`

---

# REST 란?

1. HTTP URI를 통해 리소스를 명시 : HTTP URI
2. HTTP 메소드(get, post, put, delete 등)을 통해 : HTTP Method
3. 해당 리소스에 대한 CRUD를 적용하는 것을 의미 : HTTP Message Payload

### CRUD

Create: 생성(POST)
Read: 조회(GET)
Update: 수정(PUT, PATCH)
Delete: 삭제(DELETE)

# REST API 란?

rest의 원리를 따르는 api를 의미

## 설계 규칙

1. 동사보다는 명사, 대문자 보다는 소문자 사용
2. 마지막에 슬래시를 포함하지 않음
3. `_`대신 `-` 사용
4. 파일확장자는 URI에 포함하지 않음
5. 행위(crud같은) 용어를 포함하지 않음

# RESTful 이란?

REST 설계 규칙을 올바르게 지킨 시스템을 의미
