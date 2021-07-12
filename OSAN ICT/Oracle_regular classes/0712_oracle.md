##### p.179 _ 7/12(월) <br>
## 오리지널 테이블(오라클에서 제공되는 Table)
* ex) emp, dept,salgrade. <br>

## 뷰 (VIEW) 
* 테이블이나 다른 뷰를 기초로 하여 생성되는 논리적인 가상 테이블 <br>
 &nbsp;→ 실제 데이터가 저장되지 않기에 별도의 기억공간이 존재하지 않는다.<br>

* 뷰의 필요성
  * 하나의 테이블 혹은 여러 테이블에 대해 특정 사용자나 조직의 관점에서 데이터를 바라볼 수 있도록 해주는 수단. <br>
  &nbsp;&nbsp; ex) 사원정보 – 인사팀(사번,이름,입사일자) 기획실(사번,이름근무부서,담당업무) 사내복지팀(사번,이름,생년월일,주소)

  * 목적 <br>
    * 1) 보안 
    * 2) 편리성
<br>

* 기본 테이블과 칼럼명이 같은 뷰 생성
  * CREATE VIEW <br> 
  ▶ CREATE [OR REPLACE] VIEW 뷰명
 &nbsp; &nbsp; &nbsp; &nbsp;AS 서브쿼리;
 
  * 뷰를 정의하는 질의어에는 ORDER BY 절을 쓸 수 없다.
<br>

<hr/>

##### p.191
## 시퀀스(SEQUENCE)
* 중요하긴한데 시간상 생략하고 넘어간다고 하심.

##### P.199
## 인덱스(INDEX) 목차.
* 빠르게 검색하기. 
* 중요하긴한데 시간상 생략하고 넘어간다고 하심.

<hr/>

# DML(Data Manipulation Language)
##### p.209
### DML (Data Manipulation Language) : 데이터 조작어

<br>

## INSERT (데이터 추가 명령어) <br>
  ▶ INSERT INTO (칼럼명, 칼럼명, ....) <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;VALUES(값, 값, ...); <br>
  * 한 번에 한 행만 추가된다.

<hr/>

##### p.215
## UPDATE 
  * 테이블에 입력된 데이터를 변경할 수 있다. <br>
  ▶ UPDATE 테이블명 // 테이블의 모든 행 변경. <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SET 칼럼명=값{, 칼럼명=값}' <br>
  
  * 테이블의 특정 데이터 변경 <br>
  ▶ UPDATE empcopy <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SET 칼럼명=값 <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;WHERE 조건; <br>

<hr/>  
 
##### p.218 
## DELETE 
* 모든 데이터 삭제
  * 테이블에 입력되어 있는 데이터를 삭제한다. <br>
  ▶ DELETE FROM 테이블명 <br>
  
* 특정 데이터 삭제 명령어
  * 테이블에 입력되어 있는 데이터를 삭제한다. <br>
  ▶ DELETE FROM 테이블 명 <br> 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;WHERE 조건; <br>

