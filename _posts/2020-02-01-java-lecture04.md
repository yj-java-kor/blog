---
title:        "java lecture 조건문과 반복문"
# jekyll-seo-tag
description:  "자바 강의 내용"
image:        ""
author:       "ys"
---



~~~


package lecture20200215;

public class Lecture_01 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		int a=8,b=1,i;
		
		if(a==8)System.out.println(a);
		
		if(a>10)System.out.println(a);
		else if(a<7)System.out.println(a);
		else System.out.println(a);
		
		for(i = 1; i <= 10; i++) {
			System.out.println(b);
			b++;
		}
	}

}


~~~


# 조건문  
## if
    if문은 괄호 안의 식이 true일 때만 실행된다.
## else if
    else if문은 if문에서의 괄호 안의 식이 false이고 else if문 괄호 안의 식이 true일 때 실행된다.
## else
    else 문은 if, else if문에서의 괄호안 식이 모두 다 false 일 때만 실행된다.  
    만약 else if 문이 존재하지 않을 시 if 문만 false 값이 나오면 성립한다.
# 반복문  
## for
    for문은 괄호 안의 식을 조건으로 중괄호 내의 식을 모두 계속해서 반복시키는 것이다.  
    (변수를 정의함; 변수의 조건을 명시; 한 턴이 지날때마다 변수의 상태변화)
