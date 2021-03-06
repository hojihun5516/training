## git basic

##### git을 사용하는 기초적인 방법에 대해 살펴보자.  

[뒤로가기](/git/README.md)

우리가 대부분의 전자기기나 게임을 할 때 메뉴얼을 보지않고 사용하며 익숙해지는 것처럼 Git이라는 프로그램 또한, 사용하면서 익히도록 하자.

### Git 이란?

개발 과정의 작업 단위 순간을 기록하여 소스파일, 문서를 관리하는 도구.

History에 대한 관리를 제공해 프로그램이 개발되어 온 역사를 살펴볼 수 있고, 특정 시점으로 이동하여 입력, 수정, 삭제 등의 작업을 수행할 수 있다.

예를 들어, 게임에서 무한으로 세이브 포인트를 기록하는 것과 동일하다.

즉, Git은 History 관리 기능과 타임머신 기능을 가지고 있다.

### Git 실습 준비

#### 1. git 설치하기

* [Mac & Windows & Linux][M&W&L]

##### Linux terminal - Ubuntu

> apt-get install git 

[M&W&L]: https://git-scm.com/downloads

#### 2. Github [회원가입][join]

제목의 링크를 참고하여 회원가입을 진행하자.

[join]: https://github.com/join

#### 3. Editor

예제를 실행하는 editor는 개인의 취향에 맞게 선택하길 바란다.

> 필자의 경우는 linux환경에서 'VIM'이나 'Emacs'를 사용하는 것을 추천한다. 만약  Windows나 MacOS라면 본인 취향에 맞는 에디터를 선정하기 바란다.

#### 4. 실습 전 알아둬야 할 Git 필수 명령어

Git을 입문하기 위해서는 아래와 같은 3가지 명령어를 꼭 기억하고 있어야 한다.

> **add**: 커밋할 목록에 추가  
> **commit**: 커밋(History의 단위) 작성하기  
> **push**: 작업 시작부터 현재까지의 커밋을 Github에 밀어넣기

#### 5. 실습하기

이제는 직접 사용해보는 일만 남았다. 다양한 문서들을 활용하여 학습을 진행하고, 학습용 PC에서 이를 활용하여 본인의 프로젝트를 진행해보자.

또한, 위에서 언급한 필수 명령어는 예제를 따라가며 차근차근 배워보도록 하고, 우선은 [여기][git-tuto]의 과정을 진행하여 학습하도록 하자.

[git-tuto]: https://github.com/rjs1197/git-training/

> 이 문서에서는 실습에 대한 전반적인 사항을 언급하는 것보다 git에 대한 기초적인 이해를 돕는 것을 주 목적으로 할 것이다.
