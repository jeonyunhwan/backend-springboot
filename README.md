# OOP-springboot
/* 김영한 객체지향적 설계 

- 회원
   - 회원 가입 / 조회
   - 회원은 일반과 VIP 두 가지 등급을 가지고 있다.
   - 회원은 자체 DB 구축도 가능하고, 외부 시스템과 연동이 가능하다.
 
- 주문과 할인 정책
   - 회원은 상품을 주문할 수 있다.
   - 회원 등급에 따라 할인 정책을 적용할 수 있다.
   - 할인 정책은 모든 VIP 1000원 을 할인해주는 고정 금액 할인을 적용할 수 있다.
   - 할인 정책 변경 가능성 높으므로 오픈 직전에 변경 가능하다.
 
