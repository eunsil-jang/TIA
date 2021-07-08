데이터 베이스의 장점:보안/잘못된 데이터가 들어가는것을 방지하는것(무결성유지) <br>
-ex)주민번호,학번...

<hr/>

##### p.108 
## 서브쿼리(SubQuery)를 사용한 SELECT문 
* SELECT 절에 포함된 또 다른 SELECT 문장을 서브쿼리라고 한다.
* 서브쿼리는 알려지지 않은 데이터의 값을 검색하기 위해 사용한다.

<br>

* 구문 
&nbsp;&nbsp;    SELECT select_list <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    FROM 테이블명 <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    WHERE 수식 연산자 (SLECT select_list <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FROM 테이블명);

(where 절+ select from)

<hr/>

##### p.114
## ★조인 (일차키+외래키)
* WHERE 절에 반드시 테이블들의 조인 조건을 명시해야한다

<hr/>

##### P.129
## DDL(Date Definition Language)
* "데이터 정의어" 라고 하며, 데이터베이스 내에 객체(Object)를 <b>생성</b>,<b>변경</b>,<b>삭제</b>하기 위해 사용하는 <br>
<b>CREATE,ALTER,DROP 명령어</b> 등을 포함한다. 

* 테이블 생성(CREATE TABLE)
  * CREATE 문은 테이블을 구성하고, 속성과 속성에 관한 제약 그리고 기본키 및 외래키를 정의한다.
  * 테이블을 생성하기 위해서는 테이블명을 정의하고, 테이블을 구성하는 칼럼의 데이터 타입과 무결성 제약조건 등을 정의해야 한다.
  * 또한, 테이블을 생성하기 위해서는 테이블 생성 권한이 있어야하며, 제약 조건에서 참조되는 테이블은 동일한 데이터 베이스에 있어야한다.
  
* 구문 
  * CREATE TABLE 테이블명 <br>
(칼럼명 datatype [DEFAULT 식] [[CONSTRAINT 제약조건명] 제약조건유형 <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [CONSTRAINT 제약조건명] 제약조건유형.....,] <br>
[칼럼명 datatype,....,] <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [CONSTRAINT 제약조건명 제약조건유형(칼럼명,....)]); <br>

* 문자 데이터
- <b>CHAR(n), VARCHAR2(n),LONG(n)</b> 은 문자 데이터를 처리하고자 할 때 사용한다. <br>
- n : 자리 수. <br>
-  
<hr/>

##### p.155 
1. create <br>
테이블 변경 : 새로운 칼럼 추가 <br>
ALTER TABLE ...ADD 명령으로 새로운 칼럼추가 <br>
MODIFY <br>

##### P.156 예제1
ALTER TABLE DROP COLUMN ~~ <br>

1)테이블 만들고 <br>
→CREATE TABLE 테이블명 <br>
  (칼럼명 datatype [, 칼럼명 datatype,....]) <br>
2)열추가하고  <br> 
→ <br>

 
3)열크기 변경하고 <br> 
4)열 이름 변경하기 <br>
