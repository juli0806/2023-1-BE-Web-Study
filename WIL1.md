# 2023-1-BE-Web-Study

1. MVC 패턴이란 
M - model ꞉ 화면에 관련된 것을 담아서 넘겨주는 역할
V - view ꞉ 화면을 그리는 역할
C - controller ꞉ 비즈니스 로직과 관련이 있거나 내부적인 것을 처리하는 역할

기존 one-model 에서 각자의 역할을 떠앉고 분리된 모델

2. API와 서버

 API꞉ 응용 프로그램 인터페이스, 즉 운영체제와 응용 프로그램 사이 통신에서 사용되는 언어나 메시지 형식, 연결다리

 API 통신을 구현하기 위한 대표적인 어노테이션으로는 @ResponseBody 가 있다

@ResponseBody 란 HTTP BODY 부에 data를 그대로 전달하는 역할을 수행하며 이때 전달된 data가 객체일 경우 해당 객체를 json형태로 반환하여 전달한다
 
3. RESTful 이란?
Rest: Representational State Transfer
하나의 URI(자원)가 하나의 고유한 리소스를 대표하도록 설계된다는 개념

앞서 말한 @ResponseBody도 REST 방식의 처리 중 하나이다


*참고
C(생성)R(읽기)U(업데이트)D(삭제)


