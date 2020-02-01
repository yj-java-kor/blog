---
title:        "java lecture 자료형"
# jekyll-seo-tag
description:  "자바 강의 내용"
image:        ""
author:       "ys"
---

~~~



package lecture20200201;

public class Lecture02 {

	public static void main(String[] args) {
		
		int a = 1;
		long b = 20202020202020l;
		short c = 488;
		
		double d = 9.2342;
		float e = 3.9382f;
		
		String f = "dhgksdjk";
		
		boolean g = 2==3;
		
		
		
		System.out.println(a);
		System.out.println(b);
		System.out.println(c);
		System.out.println(d);
		System.out.println(e);
		System.out.println(f);
		System.out.println(g);
	}

}

~~~


# 자료형

## 자료형이란?
    자료형이란 변수의 타입(형태)를 말하며, 이는 변수가 어떠한 정의가 되어 있는지 가르쳐 준다.

## 자료형의 종류

### 자료형의 종류_ 정수
    정수형 자료형은 int, short, long이 있다.

    먼저 int 자료형은 변수가 -2^31 ~ +2^31-1(-2,147,483,648 ~ 2,147,483,647) 범위의 정수값을 가질 수 있도록 한다.

    두 번째로 short 자료형은 변수가 -2^15 ~ +2^15-1(-32,768 ~ 32,767) 범위의 정수값을 가질 수 잇도록 한다.

    세 번째로 long 자료형은 변수가 -2^63 ~ +2^63-1(-9,223,372,036,854,775,808 ~ 9,223,372,036,854,775,807) 범위의 정수값을 가질 수 있도록 한다.

### 자료형의 종류_ 실수
    실수형 자료형은 float, double이 있다.

    먼저 float 자료형은 변수가 소수점 이하 6자리까지 범위의 실수값을 가질 수 있다.

    그러나 double 자료형은 변수가 소수점 이하 15자리까지 범위의 실수값을 가질 수 있다는 점에서 float보다 훨씬 많이 쓰인다.

### 자료형의 종류_ String
    String 자료형은 문자열 자료형으로써, 오직 한 문자만이 아닌 문자열 자체를 저장할 수 있는 자료형이다. 또한 이 범위는 컴퓨터의 하드웨어에서 지원하는 데까지 가능하다.

### 자료형의 종류_ boolean
    boolean 자료형은 참 거짓 여부를 확인하는 자료형으로써 값은 오로지 그 수식이 참인가 거짓인가에 따라 각각 "true" 와 "false" 로만 값이 나뉜다.