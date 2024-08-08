좋타 이거 (JoT iger)
=============
대기열을 서버를 만들때 도움을 주기 위한 프로젝트
-------------
* 실제 라이브 서비스에 적용중인 기술
* 서비스 사양
  * c5.4xlarge * 4대 와 cache.t3.micro Redis 1대로 10만명 컨트롤 중입니다.
1. 대기열 서버
   * https://github.com/fatherscott/JoTiger/wiki/queue-server
2. 운영툴 
   * https://github.com/fatherscott/JoTiger/wiki/AdminTool
3. 동접자
   * https://github.com/fatherscott/JoTiger/wiki/RPM-Or-AU
4. Game-Server-State-Service
   * https://github.com/fatherscott/JoTiger/wiki/Game-Server-State-Service
5. Queue-Server-State-Service
   * https://github.com/fatherscott/JoTiger/wiki/Queue-Server-State-Service
6. 필요한 이유
  * ### 웹 기반 게임 서버는 대게 대기열 서버가 존재 하지 않는다. 
  * ### 그런데 
  * ### 막 일본 애플 게임 차트에서 1등 정도 하면은 
  * ### 업데이트날 기존 트래픽의 10배 정도가 들어온다. 
  * ### 그 트래픽은 대게 4시간 안에 사라지며 
  * ### 개발사나 퍼블리셔는 그 10배를 처리하기 위해 
  * ### 서버를 스케일 업 하거나 
  * ### 대기열 서버로 막아야 한다.
  * ### 이 프로젝트에서는 대기열 서버로 막는 방법을 기술 한다.

