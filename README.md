|2021-05-04
생성자 함수와 프로토타입
# 프로토타입
*생성자 함수로 만든 객체는 프로토타입 공간에 메소드를 지정해서 모든 객체가 공유하도록 함, 해당 함수를 생성자 함수로 사용했을 때만 의미가 있음.

    // 생성자 함수
    function Product(name, price){
    this.name = name;
    this.price = price;
    }

    // 프로토타입에 메소드를 선언합니다.
    Product.prototype.print = function(){
    console.log(`${this.name}의 가격은 ${this.price}원 입니다.`);
    };

    // 상품 목록을 선언합니다.
    let products = [
    new Product('바나나', 1200),
    new Product('사과', 2000),
    new Product('배', 3000),
    new Product('고구마', 700),
    ]



|2021-05-03

배열 사용법
let array = ['사과', '바나나', '망고', '딸기'];

배열 접근법
array[0] = '사과'

객체
let product = { 
 since: '1980-01-01'
}

객체 접근
product['since'] -> '1980-01-01'

객체와 반복문
for in 반복문을 사용해서 객체에 반복문을 적용할 수 있다.

속성과 메소드
요소 : 배열 내부에 있는 값 하나하나
속성 : 객체 내부에 있는 값 하나하나

속성과 메소드

메소드 : 객체의 속성 중 자료형이 함수인 속성이다.

갱성자 함수와 프로토타입

객체 지향 프로그래밍 : 현실의 객체를 모방해서 프로그래밍

배열과 객체를 사용하면 여러 개의 데이터를 쉽게 다룰 수 있다.


프로토타입
생성자 함수로 만든 객체는 프로토타입 공간에 메소드를 지정해서 모든 객체가 공유 하도록 함, 해당 함수를 생성자 함수로 사용했을 때만 의미가 있다.

# 필기

## 주석
한 줄 주석 처리 //
여러 줄 주석 처리 /* */


## 출력 메소드
console.log("문자열")

## 기본 자료형
+ - * /

## 연산자 우선순위

## 문자열
" " , ' ' 

## 이스케이프 문자
\ (백슬레쉬를 사용한다.)


## 기본자료형
\t -> 수평 탭
\n -> 줄바꿈
\' -> 작은 따옴표
\" -> 큰 따옴표
\\ -> 역슬래시

## 문자열 합체

## 불
true false

## 논리 연산자
! 논리 부정
|| 논리합 연산자
&& 논리곱 연산자

## 변수 
 let 식별자;
  let pi; -> 변수 pi를 선언
      pi = 3.14; -> 변수 pi에 값을 항당
      
## 복합 대입 연산자
+= -> 숫자 덧셈 후 대입 연산자
-= -> 숫자 뺄셈 후 대입 연산자
*= -> 숫자 곱셈후 대입 연산자
/= -> 숫자 나눗셈 후 대입 연산자

## 문자열 대입 연산자
+= 임

## 증감 연산자
변수++
++변수
변수--
--변수

## 증감 연산자의 전위와 후위

## 자료형 확인 연산자
typeof 

ex) typeof 10 , typeof "문자열"

## undefined 자료형
변수를 선언했으나 초기화하지 않은 자료형


## 강제 자료형 변환

Number() 숫자를 자료형으로 변환
String() 문자열로 자료형을 변환
Boolean()불로 자료형 변환

## Number() 함수와 NaN

## Boolean( ) 함수
• 0 , NaN , ""[빈 문자열] , null , undefined
위의 요소들은 false를 반환한다.

## 숫자와 문자열 자료형 자동 변환.

## 불 자료형 자동 변환
! 연산자를 두 번 사용해서 Boolean()함수를 사용

## 일치 연산자
=== 자료형과 값이 같은지 비교
!== 자료형과 값이 다른지 비교

## 상수
🤦‍상수는 항상 같은 수 라는 의미, 변수와 반대되는 개념
🤦‍const : 상수를 만드는 키워드
🤦‍변하지 않을 대상에 상수를 적용















