## FreeNet 오픈소스 라이브러리 사용 C# 온라인 게임 서버 실습

### 주요 특징
- 멀티스레딩과 비동기 처리
  - C#의 멀티스레딩과 비동기 처리 기능을 활용 서버의 동시 처리 능력을 극대화.
  - 이를 통해 고성능의 온라인 게임 서버 구현.

- 네트워킹 최적화
  - TCP/IP 기반의 소켓 프로그래밍을 통해 효율적인 네트워크 통신 구현.
  - 패킷 처리 과정에서의 최적화를 통해 저지연 및 고신뢰성을 보장하는 게임 서버 개발.

- 리소스 관리 및 서버 성능 최적화
  - 게임 서버가 다루는 대량의 동시 연결과 데이터 처리를 위해 C#의 고급 리소스 관리 기법을 적용.
  - 가비지 컬렉션 관리, 메모리 할당 최적화 등을 통해 서버의 성능과 안정성을 높임.

- 서버 아키텍처 설계
  - 클라이언트의 수와 서버 부하에 따라 유연하게 확장 가능한 서버 아키텍처를 설계 및 구현.
  - 로드 밸런싱, 분산 처리 등의 기술을 적용하여 대규모 사용자를 지원하는 게임 서버를 구축.

- 실시간 데이터 동기화
  - 멀티플레이어 게임에서 중요한 실시간 데이터 동기화 기능을 효율적으로 구현.
  - 이는 게임 내 플레이어 간의 원활한 상호작용과 실시간 게임 플레이 경험 가능.

- 유연한 게임 로직 구현
  - 게임 서버에서 처리하는 핵심 게임 로직을 C#을 이용해 유연하게 구현.
  - 이를 통해 게임 개발 과정에서의 요구사항 변화에 빠르게 대응하고, 게임의 확장성 및 유지보수성 향상.

### 주요 소스코드 구현
- 게임에 접속한 유저를 나타내는 클래스 [CGameUser.cs](https://github.com/eliotjang/Online_Game_Server_with_TCP_Socket/blob/main/viruswar/server/GameServer/CGameUser.cs)
- 게임 서버 객체 [CGameServer.cs](https://github.com/eliotjang/Online_Game_Server_with_TCP_Socket/blob/main/viruswar/server/GameServer/CGameServer.cs)
- 게임 방을 관리하는 매니저 [CGameRoomManager.cs](https://github.com/eliotjang/Online_Game_Server_with_TCP_Socket/blob/main/viruswar/server/GameServer/CGameRoomManager.cs)
- 게임 로직이 구현되어 있는 게임 방 [CGameRoom.cs](https://github.com/eliotjang/Online_Game_Server_with_TCP_Socket/blob/main/viruswar/server/GameServer/CGameRoom.cs)

### 참고자료
- [유니티 개발자를 위한 C#으로 온라인 게임 서버 만들기, 이석현 저](https://www.hanbit.co.kr/store/books/look.php?p_code=E6015792502)
- [FreeNet 오픈소스 라이브러리](https://github.com/sunduk/FreeNet)
