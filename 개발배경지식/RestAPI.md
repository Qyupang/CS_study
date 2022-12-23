# REST API

## REST

> REST: 웹(HTTP)의 장점을 활용한 아키텍처

## REST(REpresentational State Transfer) 기본

---

### Method

- POST
- GET
- PUT
- DELETE

### Resource

- 모든 것을 Resource(명사)로 표현하고, 세부 Resouce에는 id를 붙임

### Message

- 메세지 포맷이 존재한다.
- JSON, XML과 같은 형태들이 있다. (최근에는 JSON을 많이 사용한다.)

## REST 특징

---

### Uniform Interface

- HTTP 표주만 맞는다면, 어떤 기술도 가능한 Interface
  -> REST API 정의를 HTTP + JSON으로 하였다면 특정 플랫폼이나 언어, 기술에 종속 받지 않고, 모든 플랫폼에 사용이 가능한 Loosely Coupling 구조를 가진다.

## Restful API

---

최근의 서버 프로그램은 여러 웹 브라우저는 물론이며, 아이폰, 안드로이드 애플리케이션과의 통신에 대응할 수 있어야 한다. 따라서 플랫폼에 맞추어 새로운 서버를 만드는 수고를 들이지 않기 위해 범용적으로 사용성을 보장하는 서버 디자인이 필요하게 되었다. RESTful APIs를 개발한는 가장 큰 이유는 client side를 정형화된 플랫폼이 아닌 모바일, pc, 어플리케이션 등 플랫폼에 제약을 두지 않는 것을 목표로 하게 되었다.

리소스를 중심으로 이름을 짓는다는 것이 특징이다. 하지만 리소스 중심으로 이름을 짓기 어려운 것들이 있어 이름을 짓기 어려운 경우도 있다는 단점이 있다. 리소스는 다 복수명으로 지어줘야한다.
