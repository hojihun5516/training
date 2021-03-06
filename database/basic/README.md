## Database Programming Basic

##### 

[뒤로가기](/database/README.md)

Oracle DBMS를 사용하여 데이터베이스를 구축하고, 모델링 툴(DA#, ERWin))을 사용하여 데이터 모델링하는 방법을 익혀보자.  

본 문서는 실제사례에 맞는 프로젝트를 구현하고, 국가 데이터 베이스 전문가 자격증인 데이터아키텍처 준전문가(DAsP) 자격증을 취득하는 것을 목적으로 한다.  

---

##### 학습 기대효과  

1. SQL 프로그래밍을 할 수 있다.  
2. 데이터 모델링 및 모델링 툴(DA#, ERWin)을 다룰 수 있다.  
3. 프로젝트를 통하여 실무적응력을 기른다.  
4. 정보 시스템의 밑단에 대한 지식을 쌓을 수 있다.  
5. DAsP 자격증을 취득하다. 향후 DAP 자격증 취득을 위한 기본적인 지식을 습득한다.  
6. DBA, DA, 데이터베이스 관련 분야에 취업에 도움이 된다.  

#### 데이터베이스?

데이터베이스는 기본적으로 '데이터가 들어가 있는 테이블의 집합'이라고 할 수 있다. 이러한 테이블은 2차원 배열로 구성되어 있고, 열(column)과 행(row)으로 구분된다.  

나누어진 열과 행은 '속성(attribute)'과 '객체(Object)'로 묶여 표현되는데, 이에 대해서는 차근차근 살펴보도록 하자.  

데이터베이스는 현실세계의 요소(Factor)를 다음과 같은 단계와 표현방법이 있다.  

1. 개념적 설계 - ERD(Entity-Relationship Diagram, 개체-관계 다이어그램), baker, IE 표기법  
2. 논리적 설계 - Relation Schema, 관계 스키마  
3. 물리적 설계  

이 셋 중 가장 중요한 단계는 개념적 설계이다. 그 이유는 개념적 설계가 되지 않으면 그 다음 단계가 엉망이 되기 때문이다.  

그리고 이러한 개념적 설계를 하는 것이 'DA(Data Architect)'가 하는 것이다. 더불어 DBA(DataBase Adminator)는 데이터베이스를 관리하는 일을 한다.  

> 2, 3단계의 논리적, 물리적 설계의 경우에는 만들어진 'Tool'이 자동으로 작업을 수행해준다.  

![database_build_flow](https://raw.githubusercontent.com/rjs1197/rjs1197.github.io/master/img/database_programming/database_build_flow.jpg)  

위에서 설명한 개념적 설계는 '정보 모델링', '개념화'라고 부르고, 논리적 설계는 '데이터 모델링', 물리적 설계는 '데이터 구조화'라고 이야기한다.  

위 그림에서는 '개념적 설계'와 '논리적 설계'를 하나로 묶어 '데이터 모델링으로 설명하니 참고하기 바란다.  

DB(DataBase)와 AP(APplication) 사이에는 '상관 모델링'이 진행된다.  

상관 모델링이란 시스템 구출을 위해 그 업무에 존재하는 '데이터'에 대해 어떤 프로세스가 있는지 정리하고, 이러한 프로세스에 의해 데이터가 어떻게 영향을 받는지 분석하는 것이다(결과적으로 데이터 모델링과 프로세스 모델링을 진행해 만드는 것이다).  

#### 참고자료  

[한국 데이터 진흥원](kttp://www.kdb.or.kr)  
[DB Guide](http://dasp.dbguide.net)  
[DA#](http://www.dator.co.kr)  
[ER Win](http://www.genesis.co.kr)  

