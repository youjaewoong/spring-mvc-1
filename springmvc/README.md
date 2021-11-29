


스프링 MVC - 기본 기능

요청 매핑 MappingController
* PathVariable 사용
* PathVariable 사용 다중
* 파라미터로 추가 매핑
* Content-Type 헤더 기반 추가 매핑 Media Type
* Accept 헤더 기반 Media Type


요청 매핑 - API 예시 MappingClassController
* 회원 목록 조회: GET '/users'
* 회원 등록: POST '/users'
* 회원 조회: GET '/users/{userId}'
* 회원 수정: PATCH '/users/{userId}'
* 회원 삭제: DELETE '/users/{userId}'

기본 해더 조회 - RequestHeaderController
* request, response, httpMethod, locale, headerMap, host, cookie