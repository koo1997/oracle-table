제약조건 조회

SELECT * FROM    ALL_CONSTRAINTSWHERE    TABLE_NAME = '테이블명'; 


PK 제약조건 추가

ALTER TABLE '테이블명' ADD PRIMARY KEY ('칼럼명1, 칼럼명2...'); 

PK 제약조건 추가

(제약조건명 지정)ALTER TABLE '테이블명' ADD CONSTRAINT '제약조건명' PRIMARY KEY ('칼럼명1, 칼럼명2...'); 

테이블의 PK 제약조건 삭제

ALTER TABLE '테이블명' DROP PRIMARY KEY:
