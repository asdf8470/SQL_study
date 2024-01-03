# SQL_study
데이터베이스 스터디

### 명령어
데이터 조작어 (DML) <select, insert, delete, update> : auto save 불가능 <br>
데이터 정의어 (DDL) <create, alter, rename, drop> : atuo save 가능

### 테이블
<table>
  <tr>
    <th>명령어의 종류</th>
    <th>명령어</th>
    <th>설명</th>
  </tr>
  <tr>
    <td rowspan="2">데이터 조작어 (DML; Data Manipulation Language)</td>
    <th>SELECT</th>
    <td>데이터베이스에 들어 있는 데이터를 조회하거나 검색하기 위한 명령어를 말하는 것으로 RETRIEVE 라고도 한다.</td>
  </tr>
  <tr>
    <th>INSERT<br>UPDATE<br>DELETE</th>
    <td>데이터베이서의 테이블에 들어 있는 제이터에 변형을 하가는 종류의 명령어들을 말한다. 예를 들어 데이터 테이블에 새로운 형을 집어넣거나, 원하지 않는 데이터를 삭제하거나 수정하는 것들의 명령어들을 DML이라고 부른다.</td>
  </tr>
  <tr>
    <td>데이터 제어어 (DCL; Data Control Language)</td>
    <th>GRANT<br>REVOKE</th>
    <td>데이터베이스에 접근하고 객체들을 사용하도록 권한을 주고 회수하는 명령어를 DCL이라고 부른다.</td>
  </tr>
  <tr>
    <td>트랜젝션 제어어 (TCL; Transaction Control Language)</td>
    <th>COMMIT<br>ROLLBACK</th>
    <td>논리적인 작업의 단위를 묶어서 DML에 의해 조작된 결과를 작업단위(트랜젝션) 별로 제어하는 명령어를 말한다.</td>
  </tr>
</table>
