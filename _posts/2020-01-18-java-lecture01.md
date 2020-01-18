---
title:        "java lecture 01"
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

    1. 정수형 변수 선언 전: ~~~ int ~~~

    2. 실수형 변수 선언 전: double (추천),

    float 는 변수를 선언한 뒤에 그 변수의 수를 지정한 후 'f'를 붙임

    3. 문자형 변수 선언 전: char

    4. 문자열형 변수 선언 전: string

    5. 참 거짓 변수 선언 전: boolean    