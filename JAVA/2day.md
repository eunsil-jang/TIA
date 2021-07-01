# 1-13~16강
## 이클립스 단축키, 자동완성기능, 주석
>
    //ctrl + shift+L 단축키 전체 목록보기
		//ctrl + +,- 폰트 크기 증가/감소
		//ctrl + D 한 줄 삭제
		//ctrl+Alt+Shift+Down 행단위 복사			
		//Alt+Shift+A 멀티컬럼 편집 모드(토글) 
		//Alt + up , down 해당 커서의 행단위 이동
		//tab 누르면 들여쓰기 , shift+tab 누르면 내어쓰기 , ctrl+i 누르면 자동 들여쓰기
		// ctrl + /  주석처리		
		// /* 문자 어쩌고 저쩌고*/ => 문자 어쩌고 저쩌고 에 해당하는 내용이 주석처리됨 
		//ctrl+Space  자동완성
		//print() - 출력 후에 줄바꿈을 안함
		//println() - 출력 후에 줄바꿈을 합니다. 이거 차이점 
		※"hello" 따옴표 안에 있는 내용은 주석으로 변경이 안됨.
    자동완성 기능 변경방법 → " windows-preferences-java-editor-templates-sysout 찾아서 edit 클릭 - sop로 변경 - no 클릭 - apply and close "

<hr/>
# 1-17~19강<br>
## 책의 소스와 강의자료 다운로드, 소스파일 가져오기, 내보내기
>
<hr/>
# 2-1~2강<br>
## 화면에 글자 출력하기, 덧셈 뺄셈 계산하기

<hr/>
# 2-3강<br>
## 변수란? 변수의 선언과 저장<br>
1)변수란?(variable) = 하나의 값을 저장할 수있는 메모리 공간(=RAM)<br>
<br>
2)변수의 선언<br>
	변수를 선언하는 이유는요? 값을 저장할 공간을 마련하려고!<br>
<br>
변수의 선언방법<br>	
-변수타입 	변수이름;<br>
int age ; // 정수(int)타입의 변수 age를 선언 //정수(integer)<br>
<br>
3)변수에 값 저장하기<br>
	1)) 변수에 값 저장하기<br>
	 	age=25; // 변수 age 에 25를 저장<br>
 	2))변수의 초기화 - 변수에 처음으로 값을 저장하는것 지역변수는 읽기전에 꼭 초기화 해야된대★<br>
 		int x = 0; // 변수 x를 선언 후 0으로 초기화<br>
		int y = 5;// " y를 선언 후 5로 초기화<br>
		int x=0,y=5; //위의 두 줄을 한줄로 만들기<br>
<br>
4)변수의 값 읽어오기 ⊙이게 뭔소리지 <br>
	1))변수의 값이 필요한 곳에 변수의 이름을 적는다<br>
	  int year=0, age=14;		year 2014 age 15<br>
	     year=age+2000;<br>
	     year=2014;<br>
<br>
alt shift a 멀티컬럼 모드 설정해제 처리 <br>

<hr/>
# 2-4강<br>
## 변수의 타입<br>
1)변수란?(variable) = 하나의 값을 저장할 수있는 메모리 공간(=RAM)<br>
	1))int(정수타입) age = 25(정수); // age=3.14 같은 실수를 입력하면 값이 오류나서 출력이 안됨<br>

	2))저장할 값의 타입과 일치하는 타입으로 변수를 선언<br>
	char ch ='가'; //char 는 문자타입<br>
	double pi = 3.14 ; <br>
<br>
2)값의 타입<br>
	값 - 문자(가나다 or ABC)와 숫자(정수<1,2,3>or실수<3.14,-0.1>)가 있지<br>
	문자<br>
	숫자<br>
	정수 - byte, short, ★int 많이 쓰인대, long<br>
	실수 - float, double<br>
	논리 - boolean (true,false)<br>
