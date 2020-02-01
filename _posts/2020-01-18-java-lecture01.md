---
title:        "java lecture 변수와 주석"
# jekyll-seo-tag
description:  "자바 강의 내용"
image:        ""
author:       "ys"
---







~~~
package lecture20191228;

public class Lecture01 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		//한줄주석
		/*
		 * 여러 줄 주석
		 */
		//변수 선언하기
		int number=0;//정수형 자료 int를 지정할 때
		char a='a';//문자형 자료 char을 지정할 때
		double b=3.0;//실수형 자료 double을 선언할 때
		float c=3.0f;//실수형 자료 float를 선언할 때: 실수 맨 끝에 f를 선언
		boolean d=false;//boolean 선언  시
		//변수 출력하기 ln:줄 건너뛰기
		System.out.println(number);
		System.out.println(a);
		System.out.println(b);
		System.out.println(c);
		System.out.println(d);
		System.out.println("안녕하세요 저는 이윤진입니다.");
	}

}

~~~

# 주석


## /주석이란?

    원하는 코드의 일부분을 생략하여 실행


## /주석 사용법

    1. 한줄주석: // 

    2. 여러줄주석:  /*     ->주석의 시작을 알림

                    *     ->주석을 계속할 때 작성

                    *

                    */    ->주석의 끝을 맺음 

## /자료형

    코드에서 변수를 선언할 때 그 이전에 그 변수의 형태가 무엇인지 적음

## /자료형의 여러가지 종류

    1. 정수형 변수 선언 전: int 

    2. 실수형 변수 선언 전: double (추천),

    float 는 변수를 선언한 뒤에 그 변수의 수를 지정한 후 'f'를 붙임

    3. 문자형 변수 선언 전: char

    4. 문자열형 변수 선언 전: string

    5. 참 거짓 변수 선언 전: boolean    


	~~~

package lecture20200201;

public class Lecture01 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int a = 113;
		int oiehfsf$453jdhl_horinkl3432 = 73678;
		// int int;    		*
		// int 3hfjkah;		*
		// int fjfi&**;		*-> 정의 불가능 ex)
		// int, long, short, string, char, double, float, boolean, for, if, else, else if;
		String b = "sjhheugsj";
		// string b = hfheuik; 		*
		// int a = "shfuiebhs";		*-> 정의 불가능 ex)
		float c = 32.32f;
		
		System.out.println(a);
		System.out.println(oiehfsf$453jdhl_horinkl3432);
		System.out.println(b);
		System.out.println(c);


~~~

# 변수

## /변수란?
	변수는 코드 제작자가 어떠한 코드 내에서 사용하기 위해 정의한 수학의 'x' 같은 미지수의 역할을 한다.

## /변수명

### 변수명의 가능한 예
	변수명으로 쓸 수 있는 경우는 위 코드의 주석 안 한 부분과 같이 코드 제작자 마음대로 지을 수 있다.

### 변수명이 가능한 조건
	위에서 변수명은 코드 제작자 마음대로 지을 수 있다고 언급했다만, 이것이 가능한 한도가 있다.

	쳣 번째로 주석 처리한 줄을 확인하면, 변수명으로 키워드를 사용할 수 없다는 것을 알 수 있다. 

	두 번째로 주석 처리한 줄을 확인하면, 변수명의 첫 번째 자리에 숫자를 집어넣을 수 없다는 것을 알 수 있다.

	세 번째로 주석 처리한 줄과 int 자료형으로 정의한 oiehfsf$453jdhl_horinkl3432에서 변수명에 '_' 와 '$' 외의 모든 특수문자를 사용하지 못한다는 것을 알 수 있다.

## /특이한 변수의 값 대입

### String 자료형 변수의 값 대입
	String 자료형으로 위에서 정의 했던 b 변수를 보면 b 변수에 대응하는 값으로 "sjhheugsj"을 썼다는 것을 알 수 있다. 이와 같이 자료형 String의 변수에 대응하는 값을 정의할 때, ""를 사용해야 한다.

### float 자료형 변수와 값 대입
	float 자료형으로 정의한 c를 보자.
	c에 대한 값의 맨 끝에 f가 붙어있는 것을 여러분들은 확인할 수 있을 것이다. 여러분들은 이 f가 내가 실수한 부분이라고 생각할 수 도 있겠으나, 사실 이것은 double 자료형 변수 대신 float 자료형 변수의 값을 선언할 때 필수적으로 필요한 요소이다.