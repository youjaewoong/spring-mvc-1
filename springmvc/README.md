


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

HTTP 요청 파라미터 - RequestParamController
* response.getWriter().write("ok");
* @RequestParam
* defaultValue 사용
* @RequestParam Map, MultiValueMap
* @ModelAttribute
* HelloData helloData (@ModelAttribute 생략)

HTTP 요청 메시지 - 단순 텍스트
RequestBodyStringController
* inputStream 요청처리
* httpEntity 요청처리
* @RequestBody 요청처리

HTTP 요청 메시지 - JSON
RequestBodyJsonController
* InputStream objectMapper 변환 요청처리
* @RequestBody String 타입 objectMapper 변환 요청처리
* @RequestBody 객체 타입 요청처리
* HttpEntity<T> 타입 요청처리
* @RequestBody 객체 타입 요청 및 응답 처리