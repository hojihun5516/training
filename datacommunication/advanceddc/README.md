## Advanced DC(Data Communication)  

##### 

[뒤로가기](/datacommunication/README.md)

개요  

데이터 통신은 정보 공유를 목적으로 문자, 숫자, 기호, 이미지, 영상 등으로 표현된 정보(데이터)를 전송매체를 통하여 한 장치에서 다른 장치로 전송하는 것이다.  

데이터란 사용자간에 합의된 임의의 형태로 형식화된 사실과 개념, 명령 등을 표현한 것으로 컴퓨터 시스템의 관점에서 보면 0과 1로 이루어진 디지털 2진 형태의 정보단위로 나타낸다.  

데이터 통신 시스템은 데이터를 정확하게, 적시에, 원하는 목적지에 전송해야 한다.  

#### 효과적인 데이터 통신 시스템의 세 가지 기본 특성  

1. 전달성  
2. 정확성  
3. 적시성  

데이터 통신 시스템의 다섯 가지기본 요소는 송신자, 수신자, 메시지, 전송매체, 프로토콜이다.  

#### 데이터 통신 시스템의 다섯 가지 구성 요소  

1. 메시지  
2. 송신자  
3. 수신자  
4. 전송매체 : 전송매체는 메시지가 송신자에서 수신자까지 전달되는 물리적인 경로를 말한다.  
5. 프로토콜 : 프로토콜은 데이터 통신을 제어하는 규칙들의 집합이다.  

네트워크는 전송매체에 의해 서로 연결된 노드(단말)와 링크의 집합이며, 하나의 작업을 여러 대의 컴퓨터가 분담하는 분산 처리에 사용한다.  

##### 분산처리 시스템의 장점  

1. 분산 데이터베이스  
2. 빠른 문제 해결  
3. 보안/캡슐화  
4. 중복에 의한 안전  
5. 공동 작업  

##### 네트워크 평가 기준

> 네트워크는 성능, 신리도, 보안성으로 평가된다.    

1. 성능 : 사용자 수, 전송매체의 종류, 연결된 하드웨어의 성능, 소프트웨어의 효율성 등 여러 요인에 따라 다를 수 있다.  
2. 신뢰도 : 고장 빈도수와 고장이 난 후 링크를 복구하는 데 소요되는 시간, 그리고 재난 상태가 발생했을 때 네티워크의 안전성 등으로 측정될 수 있다.  
3. 보안성 : 불법적인 접근이나 바이러스로부터 데이터를 보호해야 한다.  


##### 프로토콜의 주요 요소  

> 프로토콜은 데이터 통신을 제어하는 규칙의 집합으로, 프로토콜의 주요 요소는 구문, 의미, 타이밍이다.  

1.구문(what) : 데이터 구조나 형식, 부호화, 크기 등을 포함하여 무엇을 어떤 순서로 전송할 것인가에 관한 내용이다. 
> 간단한 예로 어떤 프로토콜에서 데이터의 처음 여덟 비트는 송신자 주소, 그 다음 여덟 비트는 수신자 주소를 의미하고, 나머지는 메시지를 의미한다.  

2. 의미(how) : 데이터의 특정 형태에 대해 어떻게 해석할 것인가와 그 해석에 따라 어떻게 동작을 취할 것인가 등 전송 제어 및 오류 처리를 위한 제어 정보 등을 포함한다.  

3. 타이밍(when) : 언제 데이터를 전송해야 할 것인가와 얼마나 빠른 속도로 전송할 것인가와 같은 내용을 포함한다.  


##### 표준의 목적과 분류  

> 표준은 서로 다른 제조업체에 의해 만들어진 제품이 서로 호환성을 가지고 동작하기 위해 필요하다.    

표준은 통신기기 시장을 개방적이고 경쟁적으로 만들기 위한 관리 문서이다.  

이러한 표준은 공공기관에서 만든 법률 표준과 업체에서 만든 사실 표준으로 나눌 수 있고, 사실 표준은 또다시 폐쇄 표준인 특허 표준과 개방 표준인 비특허 표준으로 나눌 수 있다.  

국제 표준기관으로는 ISO, ITU-T, ANSI, IEEE, EIA, NIST, 광대역포럼, 인터넷공학협의회, W3C, OMA 등이 있다.  

국내 표준 기관으로는 국가 기술 표준원, 한국 산업 표준원, (사)개방형 컴퓨터 연구회, 한국정보통신기술협회, ETRI 표준연구센터 등이 있다.  

주요 국제 표준기관  

1. ISO(International Standards Organization) : 162개국의 국가표준단체로 구성되어 있고, 개방 시스템 상호 연결(OSI) 모델을 만든 기관이다.  

2. ITU(International Telecommunication Union) ; 193개 회원국이 참여하고 있고, 3개의 중요한 섹터인 ITU-R(무선), ITU-T(유선), ITU-D(개발)로 구성되어 표준화 활동을 하고 있다. 이 중 ITU-T는 전화 전송, 전화 교환, 신호방법 등에 관한 여러 표준을 권고하고 있다. ITU-T 표준 중 데이터 통신과 관련된 것으로는 전화선을 이용한 데이터 전송을 규정한 V시리즈(V.32, V.33, V.42 등)와 공중 디지털망을 통한 전송을 규정한 X시리즈(X.25, X.400, X.500 등) 등이 있다.

3. ANSI(American National Standards Institute) : 대표적인 표준으로는 ASCII가 있다.

4. IEEE(Institute of Electrical Electronics Engineers) : 대표적으로는 ANSI와 함께 ANSI/IEEE 표준이 있고, 보통 ISO 표준 등 국제 표준으로 채택되기도 한다(ANSI와 IEEE는 미국 내의 학회에서 국제적인 규모로 성장한 것이기 때문에 미국을 대표하는 ISO의 회원이다).  

> 그 외 : EIA, NIST 등
  

##### 포럼  

정보통신 기술은 표준화 기구에서 표준을 제정하는 데 따른 시간이 필요함에 따라 발전속도를 따라가기가 어려운 실정에 있다.  

일반적으로 위원회는 절차가 까다로운 기구로서 현재 사용 중인 모델과 합의를 수용하고 표준화 작업을 촉진하기 위하여 트정 집단들은 관련 법인 대표로 구성된 포름(협의회)을 구성하여 운영한다.  

대표적으로는 광대역(broadband) 포럼과 인터넷(Internet) 포럼이 있다.  

> 그 외 : W3C(World wide wen Consortium), OMA 등
  

##### 주요 국내 표준기관  

1. KISC(Korea Industry Standard Certificate) : 한국 산업 표준원의 약자로 ISO 관련 시스템 인증과 KS, CE 등과 관련된 제품인증 등을 지원하고 있다.  

KATS(Korea Agency for Technology Standards) : 국가 기술 표준원의 약자로 우리나라의 ISO 대표기구로 참가하고 있으며, 여러 국가표준(한국산업표준, KS 표시인증제도, 단체표준 등)을 제정하고 있다.  
  
> 그 외 : TTA(Telecommunication Technology Associate), OSIA, ETRI 등  

##### 두 장치 간 데이터 전송 방식  

> 두 장치 간의 데이터 전송 방식에는 단방향, 반이중, 전이중이 있다.  

1. 단방향 전송 : 오직 한 방향으로만 데이터가 흐름을 의미한다.  

2. 반이중 전송 : 양방향 데이터의 흐름이 가능한데 동시에 할 수는 없다.  

3.  전이중 전송 : 동시에 양방향 데이터 흐름이 가능하다.  


##### 네트워크의 구분  
> 네트워크는 근거리 통신망(LAN), 도시 통신망(MAN), 광역 통신망(WAN), 개인 영역 통신망(PAN), 인체 통신망(BAN)으로 구성된다.  

1. 근거리 통신망(LAN) : 개인이 소유하거나 단일 사무실, 건물 혹은 학교 등에 있는 장치를 연결한 데이터 통신 시스템이다.  

2. 도시 통신망(MAN) : 큰 도시 또는 캠퍼스 등에 있는 장치들을 연결한 데이터 통신 시스템이다.
					  
3. 광역 통신망(WAN) : 국가 내에서 도시와 도시, 국가와 국가간 혹은 전 세계를 연결하는 데이터 통신 시스템이다.  
					  
4. 세계 통신망(GAN) : 최근에 등장한 용어로, Global Area Network의 약자이다. WAN이 모여 하나의 GAN을 이룬다.  

5. 개인 영역 통신망(PAN) : 댜갸 10m 언퍽의 개인 영역 내에 위치한 정보기술 장치들 간의 상호 통신을 말한다.  

6. 인체 통신망(BAN) : 주로 사람의 몸과 가까운 곳에서 일어나는 통신망을 말한다. 스마트폰, 웨어러블이 이것에 해당한다.  

> 네트워크 간 연결은 개별 네트워크들을 서로 연결한 네트워크를 총칭한다.

#### OSI 기본 참조 모델과 TCP/IP

국제 표준화 기구(ISO)는 서로 다른 시스템 간의 원활한 접속을 위해 개방 상호 시스템(OSI)이라는 7계층 모델을 만들었다.

##### OSI 7계층 모델  

1. physical layer(물리 계층) : 물리매체 상에 비트 흐름을 전송하기 위한 하드웨어와 소프트웨어 기능들을 조정한다. 전성회선의 기계적, 전자적 규격을 다룬다. bit 단위로 데이터가 이동한다.  

* physical layer의 고려사항 : 회선 구성, 데이터 전송 모드, 접속형태, 신호, 부호화, 인터페이스, 전송매체  

2. data link layer(데이터 링크 계층) : 오류 없이 한 지국에서 다음 지국으로 프레임을 전달하는 책임이 있다. 한 지국과 다음 지국 간의 오류 처리와 흐름 제어를 제공한다. frame 단위로 데이터가 이동한다.  

* data link layer의 고려사항 : 노드-대-노드 전달, 주소지정, 접근 제어, 흐름 제어, 오류 처리, 동기화  

3. network layer(네트워크 계층) : 데이터 패킷을 발산지에서 목적지까지 전달하는 책임이 있다. 교환과 경로지정을 다룬다. packet 단위로 데이터가 이동한다.  

* nerwork layer의 고려사항 : 발신지-대-목적지 전달, 논리 주소지정, 경로지정, 주소 변환, 다중화(Multiplexing)  

4. transport layer(전송 계층) : 한 응용에서 다른 응용으로의 전체 메시지의 발신지에서 목적지(끝에서 끝으로)까지 전달하는 책임이 있다. segment 단위로 데이터가 이동한다.  

* transport layer의 고려사항 :종단에서 종단으로 메시지 전달, 서비스 지점(포트) 주소지정, 단편화(segmentation)와 재조립(reaseembly), 연결 제어  

5. session layer(세션 계층) : 네트워크 대화 제어자이다. 통신 장치들 간의 상호 작용을 설정하고, 유지하며 동기화 한다.  

* session layer의 고려사항 : 세션 관리, 동기화, 대화 제어, 원활한 종료  

6. presentation layer(표현 계층) : 통신 장치들 사이의 상호 연동을 보장해 준다. 두 장치 간에 전송 내용을 같은 것으로 이해시키기 위해 서로 다르게 사용하는 제어 코드와 문자 및 그래픽 문자 등에 필요한 번역을 해준다.  

* presentation layer의 고려사항 : 변환, 암/복호화, 압축/압축해제, 보안  

7. application layer(응용 계층) : 사용자(사람 또는 소프트웨어)가  네트워크에 접근할 수 있도록 해준다. 사용자 인터페이스를 제공하며, 전자우편, 원격 파일 접근과 전송, 공유 데이터베이스 관리 및 여러 종류의 분산 정보 서비스를 제공한다.  

* application layer의 고려사항 : 네트워크 가상 터미널, 파일 접근, 전자우편 서비스, 디렉토리 서비스  

![osi7](https://www.google.co.kr/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=0ahUKEwjamJW-rfTWAhXFVZQKHRsBBB4QjRwIBw&url=http%3A%2F%2Fwww.escotal.com%2Fosilayer.html&psig=AOvVaw3uY-JbIWZCVj3oIbakjWOu&ust=1508216241732451)

하나의 개방 시스템 내에서 각 계층은 바로 아래 계층의 서비스를 요구한다.  

> 예를 들면, 세 번째 계층은 두 번째 계층에서 제공해 주는 서비스를 이용하여 , 네 번째 계층에 서비스를 제공한다.  

또한, 개방 시스템 간에는 한 시스템의 X번째 계층은 다른 시스템의 X번째 계층과 통신을 한다.  

이러한 통신은 협의된 규칙과 프로토콜이라는 규약애 의해 제어된다. 해당 계층에서 통신하는 각 시스템의 프로세스를 대등-대-대등 프로세스라고 한다.  

그러므로, 시스템간의 통신은 적절한 프로토콜을 사용하는 해당 계층의 대등 프로세스이다.  

TCP/IP는 OSI 모델 이전에 개발된 5계층의 계층 구조를 갖는 프로토콜 모음이다.  

그래서 OSI 7계층과는 정확하게 일치하지 않는다. TCP/IP는 physical, ddata link, network, trasport, application layer로 구성되어 있다.  

5계층 각각은 물리적인 표준, 네트워크 인터페이스, 네트워크 간 상호연결, 그리고 전송기능을 제공한다.  

OSI 7계층의 session, presentation, application layer가 application layer 하나로 분류된다.  

또한, TCP/IP를 사용하는 시스템은 물리, 논리, 포트의 세 가지 주소를 사용한다.  

> 흔히 '링크 주소'라고 알려진 '물리 주소'는 LAN과 WAN에서 지정된 노드의 주소를 말한다.
>
> IP(Internet Protocol) 주소는 인터넷상의 호스트를 유일하게 구분한다.
>
> 포트 주소는 호스트상의 프로세스를 구분한다.

추가적으로 network layer에는 IP가 있고, ICMP(인터넷 제어 메시지 프로토콜), IGMP(인터넷 그룹 메시지 프로토콜), ARP(주소변환 프로토콜)가 IP를 보조한다.  

Transport layer에는 SCTP(스트림 제어 전송 프로토콜), TCP(전송 제어 프로토콜), UDP(사용자 데이터그램 프로토콜)가 있으며 나머지 표준 프로토콜은 application lyaer에 해당된다.  

IANA(Internet Assigned Number Authority)에서는 포트 번호를 다음과 같이 세 개의 구간으로 나누었다.  

1. well-known port(잘 알려진 포트) : 0 ~ 1023사이의 번호가 할당되었고 IANA에 의해 통제된다.  

2. registeredd port(등록된 포트) : 1024 ~ 49,151의 범위를 가지며 IANA에 의해 할당되거나 통제를 받지 않는다. 중복 방지를 위해서 단지 IANA에 등록만 되어 있음.  

3. dynamic port(동적 포트) : 49,152 ~ 65,535 범위를 가지며 통제도 안ㄷ 되고 등록도 되어 있지 않다. 어떠한 프로세스에 의해서도 사용이 가능하고 이들을 임시 포트 번호(ephemeral port number)라 한다.  

####w 신호  

정보를 네트워크를 통해 전송하기 위해서는 전자기적 신호로 변환되어야 한다.  

> 변환하는 이유: 전송매체 혹은 기기 각각의 수단이 다르기 때문이다.  

예를 들어, 구리선은 전기신호를 보내지만 광 케이블은 빛을 이용하기 때문에 신호를 통일할 필요가 있다.  

정보와 신호는 아날로그(연속적인 값)나 디지털(이산적인 값)이 될 수 있다.  

예를 들어, 디지털 정보는 디지털 신호로, 아날로그 정보는 아날로그 신호로 변환된다.  

여기서 아날로그는 연속적인 값을, 디지털은 이산적인 값을 의미한다. 그래서 아날로그는 시간을 따라 연속적으로 변하고, 디지털은 순간적으로 변한다.  

또한, 정보를 신호로 변환시키는 것을 인코더(encoder), 신호를 정보로 변환시키는 것을 디코더(decoder)라고 한다.  

신호의 패턴이 연속적으로 반복되면 주기적이다.  

아날로그 신호와 디지털 신호는 주기(periodic) 또는 비주기(aperiodic라는 두 가지 형태 중 하나가 될 수 있다.  

##### 주기 신호  

주기 신호는 측정 가능한 시간 내에 특정 패턴이 만들어지고, 현 주기와 다음 주기가 동일한 패턴으로 반복되는 신호를 말한다.  

이처럼 하나의 완성된 패턴을 사이클이라고 한다. 주로 한 사이클을 마치는데 요구되는 시간으로 정의되는 주기는 'T'로 표기한다.  

##### 비주기 신호  

비주기 신호는 시간이 지나는 동안에 반복되는 사이클이나 패턴이 없는 신호를 말한다.  

그러나, 모든 비주기 신호는 무한 개의 주기 신호로 나뉠 수 있다는 것이 '푸리에 법칙'에 의해 증명되었다.  

따라서 주기 신호에 대해 이해하면 비주기 신호에 대해서도 이해할 수 있다.  

주기 신호는 정현파의 집합으로 분해될 수 있다.

> 정현파는 주기 아날로그 신호의 가장 기본적인 형태이다. 단순한 진동 곡선으로 나타낼 수 있다.  

각 정현파는 다음과 같이 특징지어질 수 있다.  

> 진폭 - 신호 파의 순간적인 높이  
> 주파수(주기) - 매 초당 생성되는 사이클의 수  
> 위상 - 시간 축에 따른 신호 파의 이동  

추가적으로 아날로그 신호는 단순 신호와 복합 신호로 분류된다. 정현파와 같이 단순 아날로그 신호는 더 단순한 신호로 나눌 수 없다.  

반대로 복합 아날로그 신호는 여러 개의 정현파로 나눌 수 있다.  

주파수와 주기는 서로 영이다.  

> 이 말의 의미는 반비례 관계라는 것이다. F(주파수) = 1/T(주기), T = 1/F 따라서, T * F = 1 이다.

##### 주기의 단위  

주기는 초(second)로 표현된다. 다음과 같은 다섯 개의 단위를 사용한다.
|단위|초 단위|
|:----:|:----:|
|Second|1 s|
|Millisecond|1^-3 s|
|Microsecond|1^-6 s|
|Nanosecond|1^-9 s|
|Picosecond|1^-12 s| 

##### 주파수의 단위  

주파수는 헤르츠(Hz)로 표현된다. 다음과 같은 다섯 개의 단위를 사용한다.
|단위|초 단위|
|:----:|:----:|
|Hertz|1 Hz|
|Kilohertz|1^3 Hz|
|Megahertz|1^6 Hz|
|Gigahertz|1^9 Hz|
|Terahertz|1^12 Hz| 

##### 주파수 심화  

만약 매우 짧은 기간 동안 신호 값이 변하면 그 주파수는 높고, 긴 시간 동안에 변하면 그 주파수는 낮다.  

또한, 신호가 전혀 변하지 않을 경우에는 0 Hz를, 신호가 순간적으로 변하는, 곧바로 한 준위에서 다른 준위로 뛰어오른다면 주파수는 무한대를 나타낸다.  

즉, 신호의 변화가 순간적일 때, 그 신호의 주기는 0이며, 주파수는 주기의 역이기 때문에, 이러한 경우에 주파수는 1/0, 곧 무한대이다.  

##### 위상(phase)  

위상은 첫 사이클의 상태를 표시한다. 즉, 시각 0시에 대해 파형의 상대적인 위치를 나타내는 것이다.  

위상은 각도나 라디안으로 측정되며 360도의 위상 이동은 완전한 한 주기만큼 이동한 것에 해당한다. 180도의 위상 이동은 반 주기의 이동에 해당하고, 90도는 1/4, 270도는 3/4주기의 이동에 해당한다.   

시간-영역 도면은 진폭을 시간의 함수로서 나타낸다.  

시간 영역 도면은 시간을 기준으로 신호 진폭의 변화를 보여준다(이것이 진폭 대 시간 도면이다).  

그런데 위상과 주파수는 시간-영역 도면에서는 명확하게 측정되지 않는다. 이 경우에는 다음에 설명할 주파수-영역 도면을 사용하는 것이 바람직하다.  

주파수-영역 도면은 주파수에 대한 각 정현파의 최고 진폭을 나타낸다.  

주파수-영역 도면은 세 가지 특성(진폭, 주파수, 위상) 간의 관계를 보여주기 위해서 사용할 수 있다.  

최대 진폭 대 주파수, 위상  대 주파수라는 두 종류의 주파수-영역 도면이 있다.  
  
##### 복합 신호  

지금까지는 단순 주기 신호(정현파)를 집중적으로 살펴보았다. 하지만 대부분의 유용한 파형은 불규칙적인 것들이 대부분이다.  

그러나 여기에서도 한 가지 명심해야 할 것은 아무리 복잡해도, 임의의 주기 신호는 각각 측정 가능한 진폭, 주파수, 위상을 가진 정현파들의 집합으로 분해될 수 있다는 것이다.  

신호의 대역폭은 신호가 차지하고 있는 주파수의 범위이다. 대역폭은 가장 높은 주파수 요소와 가장 낮은 주파수 요소의 차이에 의해 결정된다.  

> 신호의 대역폭은 주파수 구성요소들의 범위라고 할 수 있다. 대역폭을 구하려면 그 범위의 최고 주파수에서 최저 주파수를 빼면 된다.

신호의 스펙트럼은 신호를 구성하는 정현파들로 구성되어 있다.

또한, 신호가 포함하는 모든 주파수 요소의 집합으로 주파수 영역 도면을 사용하여 나타낼 수 있다.  

즉, 신호의 스펙트럼은 주파수 구성요소들의 범위 내에 있는 모든 구성요소를 말한다고 할 수 있다.  

비트율(매 초당 비트 수)과 비트 간격(한 비트의 존속 기간)은 디지털 신호를 나타내는데 사용되는 용어이다.  

대부분의 디지털 신호는 비주기적이어서 주기나 주파수를 사용할 수 없다.  

디지털 신호에서는 주파수 대신 '비트율'과 주기 대신 '비트 간격'이라는 두 개의 새로운 용어를 사용해 디지털 신호를 나타낸다.  

비트율(비트 전송율`bps`)은 시간당 비트 간격의 개수를, 비트 간격은 한 비트를 전송하는데 걸리는 시간을 나타낸다.  

디지털 신호는 무한 개의 정현파(조파라고 하는 정현파)로 분해될 수 있다.  

디지털 신호의 유효 스펙트럼은 해당 신호의 스펙트럼 중 일부로서 원래의 신호를 적절히 재생할 수 있는 부분이다.  

> 비록 디지털 신호의 주파수 스펙트럼이 서로 다른 진폭을 갖는 무한 개의 주파수를 포함하고 있지만, 만약 유효한 진폭을 갖는 구성 요소들만을 이용하여 전송하더라도 수신자 측에서는 어느 정도의 정확도를 가진 디지털 신호를 재생해 낼 수 있다.  

무한 스펙트럼 중에서 이 부분을 유효 스펙트럼이라 부르고, 그 대역폭을 유효 대역폭이라 부른다.

신호의 비트율은 전송매체가 전송할 수 있는 매체의 대역폭에 정비례한다.  

> 전송매체에는 대역폭의 제한이 있고, 이는 일정 범위의 주파수만을 전송할 수 있음을 의미한다. 

즉, 특정 대역폭을 갖는 전송매체는 그 매체의 대역폭보다 좁은 유효 대역폭을 갖는 디지털 신호만을 전송할 수 있다.
  
