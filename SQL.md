## SQL 
* DDL : 스키마, 뷰, 인덱스, 테이블 등을 정의할 떄 사용(데이터베이스 객체 정의시)
* DML : 데이터 조작어로, 삽입, 갱신, 삭제 등을 처리할 때 사용.
* DCL : 데이터 제어어로, 데이터의 보안*무결성*회복 등을 정의하는데 사용.

* Select 구문 에서 내부 처리 순서
  - Where -> Group By -> Having -> Select -> Order By 
* 데이터베이스 객체
  - DB 내에서 실체를 가지는 것. 'Insert', 'Update' 와 같은 질의어는 데이터베이스 객체가 아니다 질의어이다.
  - 테이블, 뷰, 인덱스 등 DB 내에 정의하는 모든 것을 말한다.
  - DB 객체는 스키마 안에서 만들어 진다. 그래서 스키마가 서로 다르면 테이블 이름 같아도 상관업다.
