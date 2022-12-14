## SQL

---

관계형 데이터베이스의 데이터를 관리하기 위해 만들어진 언어, 데이터베이스와 소통하는 수단

### DCL

---

데이터 제어 언어, 데이터베이스에 접근하고 객체들을 사용하여 권한을 주고 회수하는 명령어

ex) grant, revoke

### DDL

---

데이터 정의어, 테이블과 같은 데이터 구조를 정의하는데 사용하는 언어

ex) create, alter, drop 등

### DML

---

데이터 조작어, 테이블에 데이터 입력, 수정, 삭제, 조회 시 사용

ex) insert, select, update, delete 등

조인 연산, 집합 연산도 포함

### SELECT

---

SELECT문은 테이블의 데이터를 조회하는 문법이다. SELECT, FROM, WHERE, GROUP BY, HAVING, ORDER BY 문법으로 구성된다.

실행 순서

FROM - WHERE - GROUP BY - HAVING - SELECT - ORDER BY

### 집계 함수

---

집계성 SQL에는 집계함수, 그룹함수, 윈도함수 등이 있다.

### JOIN

---

JOIN은 두 개의 테이블을 서로 묶어서 하나의 결과를 만들어 내는 문법이다. JOIN 문에는 INNER, OUTER, CROSS, SELF 조인 등이 있다.

### INNER JOIN(내부 조인)

---

두 테이블의 공통 데이터를 묶어서 조회, 두 테이블 모두 지정한 열의 데이터가 있어야 결과가 나온다.

INNER JOIN을 JOIN이라고만 써도 인식 된다.

### OUTER JOIN

---

두 테이블 조건(LEFT, RIGHT, FULL)에 따라 묶어서 조회, 두 테이블 중 한쪽에만 데이터가 있어도 결과가 출력된다.
