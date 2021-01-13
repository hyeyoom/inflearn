# 0. 개요

인프런 강의. 듣는게 아니고 내가 함.  

## 0.1 강의 기조

강의의 기조는 다음과 같다.  

- 빡세게 배운다
  - 빡센 공부는 학습량이 능사가 아님. 특히 개발은. 생각의 양을 말함. 질적학습
  - 제드 쇼의 Learn Python 3 The Hard Way를 참고함
- 정확하게 배운다
  - 전달하는 지식에는 근거가 바탕이 되어야 함. 코드와 레퍼런스 필수
- 개발 환원주의
  - 추상화 된 것을 그대로 사용하는 것이 아닌 구현에 대해 고민

## 0.2. 강의 내용

강의 내용은 내가 매우매우 싫어하는 단어인 `full stack`이고 자바 + 스프링 스택임.  

개별 강의로 분리할 것이고 다음과 같음.  

1. Java
2. Understanding HTTP from scratch
3. Database
4. Spring Basic + Spring Advanced

프론트는 고민 중

## 0.3. 강의 대상

1. 배경지식 없는 비전공자
2. 웹에 대한 전체적인 그림을 그리기 힘든 사람
3. 개발을 포기할까 고민하는 신입 개발자

# 1. Java

자바 강의 방향
- 문법 중심보단 자바의 탄생 배경에 맞는 객체지향에 대해 설명
- 하나를 배우면 하나 이상을 실습
- 강의 전체를 관통하는 프로젝트
  - 를 뭘로 할 지 고민됨..

## 1.1. 목차

세부 사항에 대해서 기술함.

* 파트1: 자바에 국한 된 것이 아닌 일반적인 프로그래밍 기초
* 파트2: 객체 지향

### 파트1 - 프로그래밍 기초

1. 연습0: 준비
   1. Intellij Community 설치
   2. JDK 설치
   3. 첫 번째 프로그램 작성
2. 연습1: 화면에 출력해보기
   1. 해보자
   2. 더 해보자
   3. 생각하기
3. 연습2: 더 출력해보기
   1. 해보자
   2. 더 해보자
   3. 생각하기
4. 연습3: 이스케이프 문자와 주석
   1. 해보자
   2. 더 해보자
   3. 생각하기
5. 연습4: 변수에 데이터 저장하기
   1. 해보자
   2. 더 해보자
   3. 생각하기
6. 이론1: 변수와 타입
   1. 컴퓨터가 데이터를 표현하는 방법
   2. 양수와 음수 표현
   3. 소수점 표현
7. 연습5: 연산자로 숫자 다루기
   1. 해보자
   2. 더 해보자
   3. 생각하기
8. 연습6: 값을 수정해보자
   1. 해보자
   2. 더 해보자
   3. 생각하기
9. 연습7: 사용자에게 값을 입력 받기
   1. 해보자
   2. 더 해보자
   3. 생각하기
10. 연습8: 논리 연산자
    1.  해보자
    2.  더 해보자
    3.  생각하기
11. 연습9: 식(expression)과 조건식(boolean expression)
    1.  해보자
    2.  더 해보자
    3.  생각하기
12. 연습10: if문으로 결정하기
    1.  해보자
    2.  더 해보자
    3.  생각하기
13. 이론2: 코드 블록과 스코프
    1.  코드 블록이 뭘까?
    2.  스코프는 뭘까?
14. 연습12: if문 더 해보기
    1.  해보자
    2.  더 해보자
    3.  생각하기
15. 연습13: 스위치문으로 결정하기
    1.  해보자
    2.  더 해보자
    3.  생각하기
16. 연습14: while 루프로 반복해보자
    1.  해보자
    2.  더 해보자
    3.  생각하기
17. 실습1: 숫자 맞추기 게임
    1.  게임 설명
    2.  구현해보기
18. 연습15: for 루프로 반복해보자
    1.  해보자
    2.  더 해보자
    3.  생각하기
19. 연습16: 임의의 데이터를 생성해보자
    1.  해보자
    2.  더 해보자
    3.  생각하기
20. 실습2: 숫자 야구 게임(1)
    1.  게임 설명
    2.  구현 해보기
    3.  생각하기
21. 연습17: 연관 있는 데이터 뭉치를 하나로 다뤄보기 - 배열
    1.  해보자
    2.  더 해보자
    3.  생각하기
22. 실습3: 숫자 야구 게임(2)
    1.  개선해보자
    2.  생각하기
23. 연습18: 함수(메서드)를 호출해보자
    1.  해보자
    2.  더 해보자
    3.  생각하기
24. 연습19: 함수 더 깊게 고민하기
    1.  해보자
    2.  더 해보자
    3.  생각하기
25. 연습20: 자바에서 지원하는 함수(메서드)를 사용해보자
    1.  해보자
    2.  더 해보자
    3.  생각하기
26. 실습4: 숫자 야구 게임(3)
    1.  개선해보자
    2.  생각하기
27. 이론3: 식(expression)과 문(statement)
    1.  식이란 무엇인가
    2.  문이란 무엇인가
    3.  블록은 뭐지?
28. 실습5: 할 일 목록 애플리케이션 만들기
    1.  요구사항
    2.  구현 해보기
    3.  고민 해보기

### 파트2 - 객체지향

1. 이론4: SOLID