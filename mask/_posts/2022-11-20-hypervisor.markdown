---
layout: post
title:  "하이퍼바이저(Hypervison)"
date:   2022-11-19 05:05:36 +0900
categories: jekyll update
---
**하이퍼바이저**  
* 가상 머신 모니터라고도 불리며 가상 머신을 생성하고 실행하는 프로세스이다.  
* 호스트 컴퓨터에서 다수의 운영 체제를 동시에 실행하기 위한 논리적 플랫폼이다.  
* 하나의 가상머신을 실행하는 컴퓨터는 호스트가 되고 각 가상 머신들은 게스트가 된다.  
* 단일 하드웨어에서 여러 다른 가상 머신을 호스팅할 수 있는 프로그램이다.  


**하이퍼바이저를 사용해야하는 이유**  

하이퍼바이저를 사용하면 게스트로 여러 VM을 실행할 수 있으므로 기반 호스트 머신의  
물리적 리소스를 훨씬 더 효율적으로 사용할 수 있다. 각 VM은 각 서비스, 앱 또는  
운영 체제를 위한 전용 머신 역할을 수행할 수 있다. 따라서 , 여러가지 OS를 단일  
서버에서 실행하는 등의 작업을 수행할 수 있다. 또한 하이퍼바이저는 VM을 논리적으로  
분리하므로 동일한 하이퍼바이저의 다른 개별 VM에 중단, 오류 또는 보안 공격 등의  
문제가 발생할 경우 이러한 문제의 영향으로부터 각 VM이 보호된다.

**하이퍼바이저에는 두가지 유형이 있다.**  

![Bare-Metal]({{site.baseurl}}/assets/images/BM.PNG)

위에 유형은 Bare metal이며, 가상 시스템 또는 게스트 운영 체제 중 하나의 문제가  
하드웨어에서 실행 중인 다른 게스트 운영 체제에 영향을 미치지 않는다.  
다른 하이퍼바이저의 유형은 밑의 그림과 같다.  

![Bare-Metal]({{site.baseurl}}/assets/images/TYPE2.PNG)

호스트 된 하이퍼바이저라고도 하는 호스팅유형은 시스템의 다른 응용 프로그램과 마찬가로  
일반적인 OS에서 실행된다. 이 경운 게스트 OS는 호스트에서 프로세스로 실행되는 반면  
하이퍼 바이저는 게스트 OS와 호스트 OS를 분리한다.
운영에 있어 호스트 운영 체제에 전적으로 의존한다.  
기본 운영 체제에서 실행되는 하이퍼바이저가 안전하더라도 기본 운영 체제의 모든 문제는 전체 시스템에 영향을 준다.  
이 유형의 하이퍼바이저는 10일차에 사용했던 VirtualBox에 해당한다.  

`YEAR-MONTH-DAY-title.MARKUP`
