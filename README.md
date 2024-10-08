# iOSDevStudy

출처: [Jercy's Interview Questions for iOS Developers](https://github.com/JeaSungLEE/iOSInterviewquestions?tab=readme-ov-file)

---


1. [컴퓨터 구조와 관련하여 CPU, RAM, 저장장치의 역할과 상호 작용에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/2#issue-2554719222) 

- 캐시 메모리의 개념과 종류, 역할에 대해 설명해주세요.
- CPU 아키텍처의 종류(예: ARM, x86)와 특징에 대해 설명해주세요.
- iOS 기기에서 사용되는 AP(Application Processor)의 특징과 역할에 대해 설명해주세요.

2. [운영체제의 역할과 iOS에서의 운영체제 구조에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/3#issue-2554720065)

- 프로세스와 스레드의 차이점, iOS에서의 프로세스와 스레드 관리 방법에 대해 설명해주세요.
- 메모리 관리 기법 중 iOS에서 사용되는 방식과 그 특징에 대해 설명해주세요.
- iOS의 샌드박스(Sandbox) 개념과 역할, 앱 간 데이터 공유 방법에 대해 설명해주세요.

3. [iOS에서의 메모리 구조와 관리 방식에 대해 자세히 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/4#issue-2554721850)

- iOS 앱의 메모리 구조(힙, 스택, 코드 영역 등)와 각 영역의 특징에 대해 설명해주세요.
- 힙 영역에서 객체가 어떻게 할당되고 관리되는지 설명해주세요.
- 스택 영역에서 함수 호출과 로컬 변수의 메모리 할당 및 해제 과정을 설명해주세요.

4. [네트워크 프로토콜 스택과 iOS에서의 네트워크 통신 방식에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/5#issue-2554722021)

- HTTP와 HTTPS의 차이점, iOS에서의 보안 통신 방법에 대해 설명해주세요.
- TCP와 UDP의 차이점에 대해서 설명해 주세요.
- 소켓 통신에 대해 설명해주세요.
- REST API와 iOS에서의 네트워크 요청 및 응답 처리 방법에 대해 설명해주세요.
- REST API에서 Method들의 차이점을 설명해주세요.
- HTTP 상태 코드에 대해서 설명해주세요.

5. [iOS에서 메모리 사이즈와 관련된 개념과 고려 사항에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/6#issue-2554722164)

- iOS 디바이스의 메모리 제약과 앱 메모리 제한에 대해 설명해주세요.
- 메모리 워드(word) 크기와 데이터 정렬(alignment)이 메모리 액세스 성능에 미치는 영향에 대해 설명해주세요.
- 포인터 크기(32비트, 64비트)에 따른 메모리 사용량 차이와 고려 사항에 대해 설명해주세요.
- iOS 앱에서 대용량 데이터를 다룰 때 메모리 사이즈를 고려한 최적화 방안에 대해 설명해주세요.

6. [알고리즘의 시간 복잡도와 공간 복잡도의 개념, 빅오 표기법에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/7#issue-2554722278)

- 자주 사용되는 정렬 알고리즘(예: 퀵 정렬, 병합 정렬)의 동작 원리와 시간 복잡도를 설명해주세요.
- 이진 탐색의 원리와 시간 복잡도에 대해 설명해주세요.
- 다이나믹 프로그래밍(Dynamic Programming)의 개념을 설명해주세요.

7. [자료구조의 종류와 iOS 개발에서 자주 사용되는 자료구조에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/8#issue-2554722379)

- 배열, 연결 리스트, 스택, 큐의 특징과 iOS에서의 구현 방법을 설명해주세요.
- 해시 테이블의 개념, 충돌 해결 방법을 설명해주세요.
- 트리 자료구조의 종류(예: 이진 트리, 이진 탐색 트리, AVL 트리)을 설명해주세요.

8. [동시성 프로그래밍의 개념과 iOS에서의 동시성 처리 방식에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/9#issue-2554722581)

- 병렬 처리와 동시 처리의 차이, iOS에서의 멀티코어 활용 방안에 대해 설명해주세요.

9. [암호화와 보안의 기본 개념, iOS 앱 보안을 위한 방안에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/10#issue-2554722676)

- 대칭키 암호화와 비대칭키 암호화의 차이에 대해 설명해주세요.
- 해시 함수의 개념과 활용 사례에 대해 설명해주세요.

10. [가상 메모리(Virtual Memory)의 개념과 동작 원리에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/11#issue-2554722767)

- 가상 메모리의 필요성과 장점에 대해 설명해주세요.
- 페이징(Paging) 기법의 개념과 동작 원리, 페이지 테이블의 역할에 대해 설명해주세요.
- 세그먼테이션(Segmentation) 기법의 개념과 페이징과의 차이점에 대해 설명해주세요.

11. [iOS 앱의 메모리 사용량 최적화를 위한 방안과 고려 사항에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/12#issue-2554722871)

- 메모리 캐싱 기법(예: NSCache, 이미지 캐싱)의 개념과 iOS에서의 구현 방법을 설명해주세요.
- 대용량 데이터(예: 이미지, 비디오) 처리 시 메모리 최적화 방안(예: lazy loading, 썸네일 활용)에 대해 설명해주세요.

12. [데이터베이스의 종류와 iOS에서 주로 사용되는 데이터베이스에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/13#issue-2554723054)

- iOS에서 사용되는 SQLite, Core Data, Realm 등의 특징과 사용 사례를 설명해주세요.
- 관계형 데이터베이스의 ACID 특성과 트랜잭션의 개념에 대해 설명해주세요.
- iOS에서 데이터베이스 스키마 버전 관리와 마이그레이션을 처리하는 방법을 설명해주세요.

13. [iOS에서 자동 참조 카운팅(ARC)과 가비지 컬렉션(Garbage Collection)의 차이점에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/14#issue-2554723192)

- 가비지 컬렉션의 동작 원리와 장단점에 대해 설명해주세요.
- iOS에서 가비지 컬렉션을 사용하지 않는 이유와 ARC를 선택한 배경에 대해 설명해주세요.

14. [싱글톤 패턴(Singleton Pattern)이란 무엇이며, 어떤 경우에 사용하나요?](https://github.com/ujhong7/iOSDevStudy/issues/15#issue-2554723374)

- 싱글톤 패턴의 장단점은 무엇인가요?
- 싱글톤 객체의 초기화 방법과 접근 방법을 설명해주세요.
- 싱글톤 패턴을 구현할 때 주의할 점은 무엇인가요?
- Swift에서 싱글톤 패턴을 구현할때 멀티스레드에 대해서 어떻게 고려해야하나요?

---











