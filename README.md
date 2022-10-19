# ReactJS
리액트 배우기


## 2022.10.06
자바스크립트 기초부터

변수
const - 상수
let - 중복선언 불가능
var - 중복선언 가능

template literal
  
  let name = "준모";
  let str = `my name is ${name}`;

형변환의 이해
  -묵시적 형변환 : 자바스크립트 엔진 자동형변환
  -명시적 형변환 : 개발자가 직접 형변환

비교

== , != : 값 비교
=== , !== : 자료형 까지 비교

## 2022.10.07

if, switch case 조건문 

## 2022.10.19

함수 표현식 - 변수에 함수를 담아 사용
           - 호이스팅X 함수 아래에 호출해야함
함수 선언식 - 함수
           - 자동 호이스팅!


화살표 함수 - var hi = () => "ㅎㅇㅎㅇ";
             console.log(hi());
             마찬가지로 호이스팅X
             
콜백함수 실습 

const person = {
  name: "준모",
  age:"26"
}

person.location = "경기" 처럼 프로퍼티 추가 가능. person은 상수지만 프로퍼티 수정행위는 가능
person.name = null; 기존데이터 삭제
console.log(`name: ${"name" in person}`);  // true : in 연산자
