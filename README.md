# 집안일 일정 만드는 프로그램

## 소개
집안에서 엄마 외에 집안 일을 잘 안하며, 한다고 말만 하다가 넘어가는 일을 방지하기 위해 가족에 집안 일을 잘 분리해서 하루마다 누가 맡을 지 일정을 짜주는 프로그램.

## 기술 스택
- Java 17
- 향후 발전하게 된다면 웹이나 데이터베이스를 쓸 수도 있음

## 기능
- 구성원 4명 생성
  - 향후 구성원 숫자 변경 기능? 추가
- 집안일 크게 4가지 일정 랜덤 생성
  - 설거지 : 1일 2회
  - 빨래 : 3일 1회 
  - 화장실 청소 : 7일 2회(화장실이 두개라서), 매주 금요일 고정
  - 재활용 : 7일 1회, 매주 화요일 수요일 중에서만 가능
- 구성원 마다 안되는 날 미리 입력받음
- 집안일 계획 일정 화면 콘솔 출력
  - 달력 형식으로
- 가능하다면 pdf나 다른 프린트 가능한 파일로 저장 기능까지 구현

## 목표
- 자바의 많은 기능 사용해보기
  - 람다나 스트림
  - 인터페이스
- 디자인 패턴 사용해보기
  - MVC
- SOLID 생각해보기