##### 4-1~4
## 조건문 if 문과 if-else문
* 조건문과 반복문은 프로그램의 실행흐름을 바꾼다고해서 제어문이라고도 한다.
 (=flow control statment) <br>
* 조건문 : 조건을 만족할때만 { } 을 수행 (0~1번)
  * 예시 
if (score > 60) { <br>
	System.out.println("합격입니다. "); <br>
	System.out.println("축하드립니다. "); <br>
} <br>

* 반복문 : 조건을 만족하는 동안 { }을 수행 (0~n번)
  * 예시 
	int i = 10; <br>
	while (i-- > 0) { <br>
	       System.out.println(i); <br>
	} <br>

<hr/>

## 4-1 
### if 문
* 조건식이 참(true) 일때, 괄호{ }안의 문장들을 수행한다. <br>
  ▶ if (조건식){ <br>
	// 조건식이 참(true)일 때 수행될 문장들을 적는다. <br>
	} <br>
      if (score > 60) { <br>
   	System.out.println("합격입니다."); <br>
       } <br>

<hr/>

## 4-2 
### 조건식의 다양한 예

## 4-3
### 블럭 {  }
* 여러 문장을 하나로 묶어주는것 
  * if문이 참일 때 수행할 문장들을 하나로 묶어주는것 (=블럭)
  * 가독성을 높이기 위해 블럭 안의 문장들은 tab으로 들여쓰기 하는게 좋다.

<hr/>

## 4-4
### if -else 문 
* 둘 중의 하나 - 조건식이 참일 때와 거짓일 때로 나눠서 처리 <br>
▶if (조건식) {
	// 조건식이 참 (true)일 때 수행될 문장들을 적는다.
} else {
	// 조건식이 거짓(false)일 때 수행될 문장들을 적는다.
}

예) <br>
if(input =0) { <br>
	System.out.println("0입니다."); <br>
} <br>
if(input !=0) { <br>
	System.out.println("0이 아닙니다."); <br>
} <br>
		↓ <br>
if(input =0) { <br>
	System.out.println("0입니다."); <br>
} else { <br>
	System.out.println("0이 아닙니다."); <br>
} <br>

<hr/>

## 4-5
### if-else if 문
* 여러 개 중의 하나 - 여러 개의 조건식을 포함한 조건식 <br>
▶ if(조건식){ <br>
	//조건식1의 연산결과가 참일 때 수행될 문장들을 적는다. <br>
} else if(조건식 2) { <br>
	//조건식2의 연산결과가 참일 때 수행될 문장들을 적는다. <br>
} else if(조건식 3) {			// 여러개의 else if 를 사용할 수 있다. <br>
	//조건식3의 연산결과가 참일 때 수행될 문장들을 적는다. <br>
} else {	// 마지막은 보통 else 블럭으로 끝나며, else 블럭은 생략가능하다. <br>
	//위의 어느 조건식도 만족하지 않을 때 수행될 문장들을 적는다. <br>
} <br>

<hr/>

## 4-6
### if-else if문 예제
영상 2분 43초/ 명품자바 p.98 2-12예제와 같음

## 4-7
### 중첩 if문 : if 문 안의 if 문.
▶if (조건식) { <br>
	//조건식 1의 연산결과가 true일 때 수행될 문장들을 적는다. <br>
}	if (조건식2) { <br>
		//조건식 1과 조건식 2가 모두 true일 때 수행될 문장들 <br>
}	else { <br>
		//조건식1이 true이고, 조건식2가 false일때 수행되는 문장들 <br>
} else { <br>
	//조건식1이 false 일때 수행되는 문장들. <br>
} <br>
