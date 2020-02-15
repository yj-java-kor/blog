---
title:        "java lecture 메소드"
# jekyll-seo-tag
description:  "자바 강의 내용"
image:        ""
author:       "ys"
---


~~~


package lecture20200215;

public class Lecture01 {
	
	public static int plus(int num1, int num2) {
		return num1 + num2;
	}
	
	public static double minus(double num1, double num2) {
		return num1 - num2;
	}
	
	public static double times(double num1, double num2) {
		return num1 * num2;
	}
	
	public static double per(double num1, double num2) {
		return num1 / num2;
	}

	public static int calc(int a, int b, String calculate) {
		if(calculate == "plus") return a + b;
		else if(calculate == "minus") return a - b;
		else if(calculate == "times") return a * b;
		else return a / b;
	}
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub

		int result = plus(10, 20);
		double result2 = minus(10.423, 8.34);
		double result3 = times(38.43, 4.3);
		double result4 = per(637.4351, 43.41);
		int result5 = calc(37, 93, "plus");
		
		System.out.println(result);
		System.out.println(result2);
		System.out.println(result3);
		System.out.println(result4);
		System.out.println(result5);
	}

}



~~~




# 메소드

## 메소드의 목적

    메소드는 자신이 소스코드를 적다 보면 중복해서 적는 경우가 생기는데, 같은 부분을 중복해서 적을 바에는 한 뭉치로 묶어 메소드를 작성하여 이를 줄이는 것이 현명한 일이다.

## 메소드 사용법

    메소드는 결국에 다른언어의 함수와 거의 동일한 것으로, 말 그대로 상자 안에 변수를 집어넣어 새로운 변수가 나오는 것이다.  
      
    변수 = 메소드 이름(변수2);

