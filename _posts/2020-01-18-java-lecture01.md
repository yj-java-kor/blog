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