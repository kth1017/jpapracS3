# jpapracS3
spring, jpa, thymeleaf / 기초적인 상품 관리 페이지 practice / 220306

# 개요
-SSR 방식의 스프링 mvc 기반 상품 관리 페이지 예제
-김영한님의 jpa 실전 강의 참고

-TRD를 비롯한 DB 설계 기초 학습
-간단한 페이지 작성을 위한 타임리프 기초 학습
-db는 h2, 조작은 orm인 jpa 사용

# 요약

@준비
- Client entity : member / item, category / order, delivery

@코드
- back component : entity, repository, service, controller
- view : thymeleaf

- ERD 및JPA사용 전 DB설계 학습
$PK, FK와 @OneToMany, @ManyToOne이 일대다 관계의 column에 어떻게 적용되는지 학습
$Fetchtype을 lazy로 해야하는 이유 학습
$영속화와 준영속, merge / cascade 학습

- back component 및 테스트코드
$@modelAttribute의 리팩토링 과정과 dto 객체 도입의 필요성 학습
$리포지토리에서 jpql 작성과 jpa 사용 학습
$서비스에서 도메인 모델과 스크립트 트랜잭션 차이 학습
$기초 테스트 코드의 작성법과 유닛테스트의 중요성, @SpringBootTest 학습
