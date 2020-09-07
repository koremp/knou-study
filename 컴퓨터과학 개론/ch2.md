# ch2 컴퓨터와 자료 (2)

## 자료의 개념


### 자료와 정보
I = P(D)
I = information 
P = Processer
D = Data

### 자료의 표현 형태

비트(BInary digiT) 패턴
bit, byte, kb, mb, gb, tb, pb, eb, zb, yb
word -> 32bit, 64bit

## 진법

수를 세는 방법 / 단위
r진법

(2진법 -> 8진법, 16진법), (10진법 -> 2진법) 등 변환 문제

## 정수 표현

* unsigned int
	* n bit => 0 ~ 2^n - 1
* signed int
	* 부호화-크기
	* 1의 보수
	* 2의 보수

## 실수 표현

부동소수점 방식 : (-1)^S * M * B^E
S = Significand
M = Magic Number?
B = Base
E = Exponent

초과표기법
* 부동소수점 방식의 `지수 부분`만을 표현하기 위한 방법
* 매직 넘버 2^(m-1) or 2^(m-1) - 1
* 정규화 : 가수를 표준화된 형식으로 표현하기 위한 방법
  * 
* 실수 표현의 예
* IEEE
  * single presicion : 4 byte
    * S - 1bit
    * M - 8bit 
  	* E - 23bit
  * double precision : 8 byte
    * S - 1bit
	* M - 11bit
    * E - 52bit

초과표기법

## 문자 표현

* ASCII
* UNICODE
* EBCDIC
* BCD
