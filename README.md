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

# 레벨 0

1. [컴퓨터 시스템에서 CPU, RAM, 저장 장치의 역할과 이들이 어떻게 상호 작용하는지 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/41)
   - CPU와 메모리 간의 데이터 교환은 어떻게 이루어지나요?
   - 버스(Bus)란 무엇이며, 어떤 종류가 있나요?
   - 캐시 메모리의 개념과 역할에 대해 설명해주세요.

2. [캐시의 지역성(Locality) 원리에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/42)
   - CPU 아키텍처의 종류(예: ARM, x86)와 각 특징에 대해 설명해주세요.

3. [iOS 기기에서 사용되는 AP(Application Processor)의 특징과 역할에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/43)

4. [SoC(System on a Chip)의 개념은 무엇인가요?](https://github.com/ujhong7/iOSDevStudy/issues/44)
   - 운영체제의 역할과 iOS의 운영체제 구조에 대해 설명해주세요.

5. [iOS의 샌드박스 구조는 어떻게 동작하나요?](https://github.com/ujhong7/iOSDevStudy/issues/45)
   - 커널(Kernel)의 역할은 무엇인가요?
   - 다중 태스킹(Multitasking)은 어떻게 지원되나요?
   - 프로세스와 스레드의 차이점, 그리고 iOS에서의 프로세스와 스레드 관리 방법에 대해 설명해주세요.

6. [멀티스레딩이 필요한 이유는 무엇인가요?](https://github.com/ujhong7/iOSDevStudy/issues/46)
   - iOS에서 GCD(Grand Central Dispatch)는 어떤 역할을 하나요?
   - 메모리 관리 기법 중 iOS에서 사용되는 방식과 그 특징에 대해 설명해주세요.

7. [자동 참조 카운팅(ARC)은 어떻게 동작하나요?](https://github.com/ujhong7/iOSDevStudy/issues/47)
   - Garbage Collection과의 차이는 무엇인가요?
   - iOS의 샌드박스(Sandbox) 개념과 역할, 그리고 앱 간 데이터 공유 방법에 대해 설명해주세요.

8. [URL 스킴(URL Scheme)을 이용한 앱 간 통신은 어떻게 이루어지나요?](https://github.com/ujhong7/iOSDevStudy/issues/48)
   - 앱 그룹(App Group)을 활용하여 데이터 공유를 하는 방법은 무엇인가요?
   - iOS에서의 메모리 구조와 관리 방식에 대해 자세히 설명해주세요.

9. [힙(Heap)과 스택(Stack)의 차이점은 무엇인가요?](https://github.com/ujhong7/iOSDevStudy/issues/49)
   - 네트워크 프로토콜 스택과 iOS에서의 네트워크 통신 방식에 대해 설명해주세요.

10. [HTTP와 HTTPS의 차이점, 그리고 iOS에서의 보안 통신 방법에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/50)

11. [SSL/TLS의 동작 원리는 무엇인가요?](https://github.com/ujhong7/iOSDevStudy/issues/51)
   - 컴퓨터 네트워킹에서 OSI 7계층 모델에 대해 설명해주세요.

12. [각 계층의 역할과 프로토콜은 무엇인가요?](https://github.com/ujhong7/iOSDevStudy/issues/52)
   - TCP/IP 모델과 OSI 모델의 차이점은 무엇인가요?
   - HTTP 프로토콜의 특징과 HTTP/1.1과 HTTP/2의 차이점을 설명해주세요.

13. [HTTP의 무상태(Stateless) 성질은 무엇이며, 어떻게 극복하나요?](https://github.com/ujhong7/iOSDevStudy/issues/53)
   - HTTP/2에서 추가된 주요 기능은 무엇인가요?
   - HTTP/3에서 추가된 기능은 무엇인가요?
   - TCP와 UDP의 특징과 차이점에 대해 설명해주세요.

14. [연결 지향형 프로토콜과 비연결 지향형 프로토콜은 무엇인가요?](https://github.com/ujhong7/iOSDevStudy/issues/54)
   - TCP의 3-way handshake 과정은 어떻게 이루어지나요?
   - 어떤 상황에서 UDP를 사용하는 것이 적합한가요?

15. [소켓 통신에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/55)

16. [REST API와 iOS에서의 네트워크 요청 및 응답 처리 방법에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/56)
   - iOS에서 URLSession을 사용하여 네트워크 요청을 보내는 방법은 무엇인가요?

17. [REST API에서 HTTP 메서드들의 차이점을 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/57)
   - GET과 POST의 차이점은 무엇인가요?


18. [HTTP 상태 코드에 대해서 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/58)

19. [iOS에서 이미지 파일 포맷(PNG, JPEG 등)과 각 포맷의 특징에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/59)
   - PNG와 JPEG의 차이점은 무엇인가요?

20. [PNG 파일이 어떻게 저장되고 구성되는지 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/60)

21. [iOS에서 메모리 사이즈와 관련된 개념과 고려 사항에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/61)
   - 메모리 정렬(Alignment)이 성능에 미치는 영향은 무엇인가요?

22. [iOS 디바이스의 메모리 제약과 앱 메모리 제한에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/62)
   - 메모리 경고(Memory Warning)가 발생하면 어떤 조치를 취해야 하나요?

23. [알고리즘의 시간 복잡도와 공간 복잡도의 개념, 그리고 빅오 표기법에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/63)
   - O(n)과 O(log n)의 차이는 무엇인가요?

24. [자주 사용되는 정렬 알고리즘(예: 퀵 정렬, 병합 정렬)의 동작 원리와 시간 복잡도를 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/64)

25. [이진 탐색의 원리와 시간 복잡도에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/65)

26. [동적 프로그래밍(Dynamic Programming)의 개념을 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/66)

27. [자료구조의 종류와 iOS 개발에서 자주 사용되는 자료구조에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/67)

28. [배열, 연결 리스트, 스택, 큐의 특징과 iOS에서의 구현 방법을 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/68)

29. [해시 테이블의 개념과 충돌 해결 방법을 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/69)

30. [암호화와 보안의 기본 개념, 그리고 iOS 앱 보안을 위한 방안에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/70)

31. [가상 메모리(Virtual Memory)의 개념과 동작 원리에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/71)

32. [데이터베이스의 종류와 iOS에서 주로 사용되는 데이터베이스에 대해 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/72)

33 [싱글톤 패턴(Singleton Pattern)이란 무엇이며, 어떤 경우에 사용하나요?](https://github.com/ujhong7/iOSDevStudy/issues/73)

34. [Swift에서 싱글톤 패턴을 구현할 때 멀티스레드에 대해서 어떻게 고려해야 하나요?](https://github.com/ujhong7/iOSDevStudy/issues/74)

35. [Array와 List의 차이점이 무엇인지 설명해주세요.](https://github.com/ujhong7/iOSDevStudy/issues/75)

---
# 레벨 1

1. [**Swift에서 옵셔널(Optional)이란 무엇이며, 언제 사용해야 하나요?**](https://github.com/ujhong7/iOSDevStudy/issues/16)
   - 옵셔널 바인딩과 강제 언래핑의 차이점은 무엇인가요?
   - 옵셔널 체이닝의 동작 원리는 무엇이며, 어떻게 사용하나요?
   - 암시적 언래핑 옵셔널(Implicitly Unwrapped Optional)은 어떤 경우에 사용해야 하나요?

2. [**iOS 앱의 생명주기(App Life Cycle)에 대해 설명해주세요.**](https://github.com/ujhong7/iOSDevStudy/issues/17)
   - 앱의 각 상태(`Not Running`, `Inactive`, `Active`, `Background`, `Suspended`)에서 가능한 작업은 무엇인가요?
   - 상태 변화에 따라 호출되는 `AppDelegate` 또는 `SceneDelegate` 메서드는 무엇인가요?
   - 백그라운드에서 작업을 완료하기 위한 방법은 어떤 것이 있나요?

3. [**Auto Layout을 사용하는 이유와 장점은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/18)
   - 제약 조건(Constraints)의 우선순위(Priority)는 어떻게 동작하나요?
   - Intrinsic Content Size란 무엇이며, 어떻게 활용되나요?
   - Ambiguous Layout과 Unsatisfiable Constraints는 무엇이며, 어떻게 해결하나요?

4. [**Swift에서 클로저(Closure)란 무엇이며, 어떻게 사용하나요?**](https://github.com/ujhong7/iOSDevStudy/issues/19)
   - 클로저의 캡처(Capture) 기능은 무엇인가요?
   - @escaping 클로저와 non-escaping 클로저의 차이점은 무엇인가요?
   - 트레일링 클로저(Trailing Closure) 문법은 어떤 경우에 유용한가요?

5. [**iOS에서 Delegate 패턴은 무엇이며, 어떤 상황에서 사용되나요?**](https://github.com/ujhong7/iOSDevStudy/issues/20)
   - Delegate 패턴과 Notification, KVO의 차이점은 무엇인가요?
   - 프로토콜을 활용한 Delegate 패턴 구현 방법을 설명해주세요.

6. [**Swift의 기본 데이터 타입과 컬렉션(Collection) 타입에는 어떤 것들이 있나요?**](https://github.com/ujhong7/iOSDevStudy/issues/21)
   - 값 타입(Value Type)과 참조 타입(Reference Type)의 차이점은 무엇인가요?
   - 구조체(Struct)와 클래스(Class)의 사용 시기는 어떻게 구분하나요?
   - 열거형(Enum)의 원시값(Raw Value)과 연관값(Associated Value)은 무엇인가요?

7. [**Xcode에서 디버깅 시 자주 사용하는 기능은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/24)
   - 중단점(Breakpoint)의 종류와 활용 방법을 설명해주세요.
   - LLDB 콘솔에서 유용한 명령어는 어떤 것이 있나요?

8. [**iOS 앱에서 데이터를 저장하는 방법에는 어떤 것들이 있나요?**](https://github.com/ujhong7/iOSDevStudy/issues/22)
   - `UserDefaults`의 사용 시 주의할 점은 무엇인가요?
   - Keychain은 어떤 데이터를 저장하기에 적합한가요?
   - Core Data와 SQLite의 차이점은 무엇이며, 각각 언제 사용하면 좋나요?

9. [**Swift에서 프로토콜(Protocol)이란 무엇이며, 어떻게 활용하나요?**](https://github.com/ujhong7/iOSDevStudy/issues/23)
   - 프로토콜의 요구사항은 무엇인가요?
   - 프로토콜 확장(Protocol Extension)을 사용하는 이유는 무엇인가요?
   - 프로토콜 지향 프로그래밍(Protocol-Oriented Programming)의 장점은 무엇인가요?

10. [**Swift의 접근 제어자(Access Control Levels)에 대해 설명해주세요.**](https://github.com/ujhong7/iOSDevStudy/issues/25)
    - `open`과 `public`의 차이점은 무엇인가요?
    - `internal`, `fileprivate`, `private`의 사용 시기는 어떻게 결정하나요?
    - 접근 제어자를 사용하는 이유는 무엇인가요?

11. [**iOS 앱에서 네트워크 통신을 하는 방법에는 어떤 것들이 있나요?**](https://github.com/ujhong7/iOSDevStudy/issues/26)
    - `URLSession`의 기본 사용 방법을 설명해주세요.
    - 네트워크 요청 시 에러 처리는 어떻게 하나요?
    - 서드파티 라이브러리(예: Alamofire)를 사용하는 이유는 무엇인가요?

12. [**의존성 관리 도구(CocoaPods, Carthage, Swift Package Manager)의 종류와 차이점은 무엇인가요?**]()
    - 각 도구의 사용 방법과 장단점을 설명해주세요.
    - 의존성 관리를 통해 얻을 수 있는 이점은 무엇인가요?

13. [**Swift의 고차 함수(Higher-Order Functions)에 대해 설명해주세요.**](https://github.com/ujhong7/iOSDevStudy/issues/27)
    - `map`과 `flatMap`의 차이점은 무엇인가요?
    - `filter`, `reduce` 함수는 어떤 경우에 사용하나요?
    - `compactMap`은 어떤 역할을 하나요?

14. [**Git에서 브랜치(Branch)를 사용하는 이유와 장점은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/28)
    - 브랜치를 병합(Merge)하는 방법에는 어떤 것들이 있나요?
    - 브랜치 전략(예: Git Flow, GitHub Flow)에 대해 설명해주세요.
    - 충돌(Conflict)이 발생했을 때 해결 방법은 무엇인가요?

15. [**Swift의 에러 처리 방법에 대해 설명해주세요.**](https://github.com/ujhong7/iOSDevStudy/issues/29)
    - `throws`, `try`, `catch` 키워드의 사용 방법은 무엇인가요?
    - 옵셔널을 사용한 에러 처리와 `do-catch`를 사용하는 에러 처리의 차이는 무엇인가요?
    - 에러를 전파하는 방법은 무엇인가요?

16. [**메모리 관리에서 강한 참조(Strong Reference)와 약한 참조(Weak Reference)의 차이점은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/30)
    - 순환 참조(Retain Cycle)가 발생하는 경우와 해결 방법은 무엇인가요?
    - 클로저에서 `[weak self]`와 `[unowned self]`의 차이는 무엇인가요?

17. [**iOS 앱에서 Multi-threading을 구현하는 방법은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/31)
    - `DispatchQueue`와 `OperationQueue`의 차이점은 무엇인가요?
    - 동시성 프로그래밍에서 Race Condition을 방지하는 방법은 무엇인가요?
    - 메인 스레드에서 UI 업데이트를 해야 하는 이유는 무엇인가요?

18. [**UIKit에서 TableView와 CollectionView의 차이점은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/32)
    - 셀(Cell)의 재사용(Reusability)은 어떻게 구현되나요?
    - 동적인 셀 높이(Dynamic Cell Height)를 설정하는 방법은 무엇인가요?
    - CollectionView의 레이아웃을 커스터마이징하는 방법은 무엇인가요?

19. [**ARC(Automatic Reference Counting)의 동작 원리는 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/33)
    - Retain Cycle이 발생하지 않도록 방지하는 방법은 무엇인가요?
    - `deinit` 메서드는 언제 호출되며, 어떤 역할을 하나요?

20. [**상속(Inheritance)과 프로토콜(Protocol)의 차이점은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/34)
    - 클래스 상속을 사용할 때의 장단점은 무엇인가요?
    - 다중 상속(Multiple Inheritance)이 불가능한 이유는 무엇인가요?
    - 프로토콜 준수(Conformance)를 통해 다형성을 구현하는 방법은 무엇인가요?

21. [**사용자 인터페이스(UI) 테스트와 단위(Unit) 테스트의 차이점은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/35)
    - XCTest 프레임워크를 사용하여 테스트를 작성하는 방법은 무엇인가요?
    - 테스트 주도 개발(TDD)의 장점은 무엇인가요?
    - 의존성 주입(Dependency Injection)을 활용하여 테스트 가능한 코드를 작성하는 방법은 무엇인가요?

22. [**Xcode에서 Instruments를 사용하여 앱의 성능을 분석하는 방법은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/36)
    - Time Profiler를 사용하여 성능 이슈를 찾는 방법을 설명해주세요.
    - Allocations Instrument를 사용하여 메모리 누수를 탐지하는 방법은 무엇인가요?
    - Leaks Instrument를 사용하여 메모리 누수를 찾는 방법은 무엇인가요?

23. [**Swift의 제네릭(Generic)에 대해 설명해주세요.**](https://github.com/ujhong7/iOSDevStudy/issues/37)
    - 제네릭을 사용하는 이유는 무엇인가요?
    - 제네릭 타입 파라미터와 제약 조건을 설정하는 방법은 무엇인가요?
    - 제네릭을 사용할 때의 장점과 주의할 점은 무엇인가요?

24. [**Swift의 클로저와 함수의 차이점은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/38)
    - 클로저가 일급 객체(First-Class Citizen)인 이유는 무엇인가요?
    - 함수형 프로그래밍 패러다임에서 클로저가 어떻게 활용되나요?

25. [**동시성 프로그래밍에서 동기(Synchronous)와 비동기(Asynchronous)의 차이점은 무엇인가요?**](https://github.com/ujhong7/iOSDevStudy/issues/39)
    - iOS에서 비동기 작업을 처리하는 방법은 무엇인가요?
    - 세마포어(Semaphore)와 뮤텍스(Mutex)의 차이점은 무엇인가요?

26. [**GCD(Grand Central Dispatch)의 주요 개념과 사용 방법을 설명해주세요.**](https://github.com/ujhong7/iOSDevStudy/issues/40)
    - 직렬(Serial) 큐와 동시(Concurrent) 큐의 차이는 무엇인가요?
    - 글로벌 큐(Global Queue)와 메인 큐(Main Queue)는 어떻게 다르나요?
    - DispatchWorkItem을 사용하는 방법은 무엇인가요?

---

## 레벨 2

1. Swift의 동시성(Concurrency) 프로그래밍에 대해 설명해주세요.
   - Grand Central Dispatch(GCD)의 주요 개념과 사용 방법을 설명해주세요.
   - OperationQueue와 DispatchQueue의 차이점은 무엇인가요?
   - 동시성 프로그래밍에서 발생할 수 있는 문제(Race Condition, Deadlock 등)와 해결 방법은 무엇인가요?

2. 객체지향 프로그래밍(OOP)의 주요 개념에 대해 설명해주세요.
   - 캡슐화(Encapsulation)와 정보 은닉(Information Hiding)의 차이점은 무엇인가요?
   - 상속(Inheritance)의 장단점은 무엇인가요?
   - 다형성(Polymorphism)을 활용하는 예시를 들어주세요.

3. 프로토콜 지향 프로그래밍(POP)이란 무엇이며, 어떤 장점이 있나요?
   - 프로토콜 확장(Protocol Extension)을 사용하는 이유는 무엇인가요?
   - 프로토콜 컴포지션(Protocol Composition)은 어떤 경우에 사용하나요?
   - 프로토콜과 제네릭(Generic)을 함께 사용하면 어떤 이점이 있나요?

4. iOS 앱의 메모리 관리는 어떻게 이루어지나요?
   - ARC(Automatic Reference Counting)의 동작 원리를 설명해주세요.
   - 강한 참조(Strong Reference)와 약한 참조(Weak Reference)의 차이점은 무엇인가요?
   - 순환 참조(Retain Cycle)가 발생하는 경우와 해결 방법을 설명해주세요.
   - 강한 참조, 약한 참조, 미소유 참조의 차이점을 설명해주세요.

6. Swift의 문자열(String) 다루기와 관련된 주요 기능은 무엇이 있나요?
   - 서브스트링(Substring)과 문자열의 차이점은 무엇인가요?
   - 문자열 보간법(String Interpolation)을 사용하는 방법과 주의 사항을 설명해주세요.
   - 정규식(Regular Expression)을 사용하여 문자열을 다루는 방법을 설명해주세요.

7. Codable 프로토콜은 무엇이며, 어떻게 사용하나요?
   - Encodable과 Decodable 프로토콜의 역할은 무엇인가요?
   - JSON 데이터를 커스텀 객체로 디코딩하는 방법을 설명해주세요.
   - Codable 프로토콜을 채택한 타입에서 인코딩/디코딩 키를 커스터마이징하는 방법은 무엇인가요?

8. iOS 앱에서 의존성 주입(Dependency Injection)은 어떤 목적으로 사용되나요?
   - 의존성 주입의 세 가지 유형(Initializer Injection, Property Injection, Method Injection)을 설명해주세요.
   - 의존성 주입 컨테이너(Dependency Injection Container)란 무엇인가요?
   - 의존성 주입을 사용함으로써 얻을 수 있는 이점은 무엇인가요?

9. 델리게이션 패턴(Delegation Pattern)과 클로저의 차이점은 무엇인가요?
   - 델리게이션 패턴에서 메모리 누수가 발생할 수 있는 경우와 해결 방법을 설명해주세요.
   - 클로저의 캡처 리스트(Capture List)는 어떤 역할을 하나요?
   - 델리게이션 패턴과 클로저를 함께 사용하는 경우의 장단점은 무엇인가요?

10. UIKit에서 테이블 뷰(UITableView)와 컬렉션 뷰(UICollectionView)의 차이점은 무엇인가요?
   - 테이블 뷰와 컬렉션 뷰에서 셀을 재사용하는 이유와 방법을 설명해주세요.
   - 테이블 뷰와 컬렉션 뷰의 데이터 소스(Data Source)와 델리게이트(Delegate)의 역할은 무엇인가요?
   - 컬렉션 뷰에서 사용할 수 있는 레이아웃(Layout)의 종류와 특징을 설명해주세요.

11. iOS 앱 아키텍처 패턴 중 MVC, MVVM, VIP, MVI의 차이점은 무엇인가요?
   - MVC의 장점은 무엇인가요?
   - 각 아키텍처 패턴의 구성 요소와 책임을 설명해주세요.
   - MVVM 패턴에서 Binding은 어떤 역할을 하나요?
   - VIP 패턴에서 Presenter의 역할은 무엇인가요?
   - MVI 패턴에서 Intent의 역할은 무엇인가요?

12. Swift에서 옵셔널(Optional)을 사용할 때 주의할 점은 무엇인가요?
   - 강제 언래핑(Force Unwrapping)을 사용하면 안 되는 이유는 무엇인가요?
   - 옵셔널 바인딩(Optional Binding)과 옵셔널 체이닝(Optional Chaining)의 차이점을 설명해주세요.
   - 암시적 언래핑 옵셔널(Implicitly Unwrapped Optional)은 어떤 경우에 사용하나요?

13. iOS 앱에서 코어 애니메이션(Core Animation)을 사용하는 방법은 무엇인가요?
   - CALayer의 주요 속성과 메서드를 설명해주세요.
   - 애니메이션 그룹(Animation Group)은 어떤 경우에 사용하나요?
   - 키 프레임 애니메이션(Keyframe Animation)과 스프링 애니메이션(Spring Animation)의 차이점은 무엇인가요?

14. Swift에서 프로토콜 지향 프로그래밍(Protocol-Oriented Programming)을 활용하는 방법은 무엇인가요?
   - 프로토콜 확장(Protocol Extension)을 통해 기본 구현을 제공하는 방법을 설명해주세요.
   - 프로토콜 상속(Protocol Inheritance)은 어떤 경우에 사용하나요?
   - 프로토콜 지향 프로그래밍(Protocol-Oriented Programming)에서 제네릭(Generic)을 함께 사용하면 어떤 이점이 있나요?

15. iOS 앱에서 네트워크 요청 시 응답 캐싱(Response Caching)을 하는 방법은 무엇인가요?
   - URLCache는 어떤 역할을 하나요?
   - 응답 캐싱의 장단점은 무엇인가요?
   - 응답 캐싱을 커스터마이징하는 방법을 설명해주세요.

16. Combine 프레임워크란 무엇이며, 어떤 기능을 제공하나요?
   - Publisher와 Subscriber의 역할은 무엇인가요?
   - Operator의 종류와 사용 방법을 설명해주세요.
   - Combine과 RxSwift의 차이점은 무엇인가요?

17. Swift의 제네릭(Generic)에 대해 설명해주세요.
   - 제네릭을 사용하는 이유는 무엇인가요?
   - 제네릭 타입 파라미터(Generic Type Parameter)와 제네릭 타입 제약(Generic Type Constraint)은 무엇인가요?
   - 제네릭을 사용할 때 주의할 점은 무엇인가요?

18. iOS 앱에서 로컬 푸시 알림(Local Push Notification)을 구현하는 방법은 무엇인가요?
   - 로컬 푸시 알림과 원격 푸시 알림(Remote Push Notification)의 차이점은 무엇인가요?
   - 푸시 알림의 콘텐츠(Content)와 트리거(Trigger)는 어떤 역할을 하나요?
   - 사용자가 푸시 알림을 탭했을 때 앱의 동작을 처리하는 방법을 설명해주세요.

19. iOS 앱에서 SwiftUI와 UIKit을 함께 사용하는 방법은 무엇인가요?
   - SwiftUI 뷰에서 UIKit 뷰 컨트롤러를 사용하는 방법을 설명해주세요.
   - UIKit 뷰 컨트롤러에서 SwiftUI 뷰를 호스팅하는 방법은 무엇인가요?
   - SwiftUI와 UIKit을 함께 사용할 때 주의할 점은 무엇인가요?

19. Swift에서 키 경로(Key Path)란 무엇이며, 어떻게 사용하나요?
   - 키 경로 표현식(Key Path Expression)의 문법과 사용 예시를 설명해주세요.
   - 런타임에 키 경로를 사용하여 속성에 접근하는 방법은 무엇인가요?
   - 키 경로와 KVO(Key-Value Observing)의 관계를 설명해주세요.

20. iOS 앱에서 Deep Link와 Universal Link의 차이점은 무엇인가요?
   - Deep Link를 구현하는 방법과 주의 사항을 설명해주세요.
   - Universal Link의 동작 원리와 설정 방법은 무엇인가요?
   - Deep Link와 Universal Link를 함께 사용하는 경우의 장점은 무엇인가요?

21. Swift의 Result 타입과 에러 처리 방식에 대해 설명해주세요.
   - Result 타입을 사용하는 이유와 장점은 무엇인가요?
   - 에러 처리 시 do-catch 문과 Result 타입을 함께 사용하는 방법을 설명해주세요.

22. iOS 앱에서 Thread Sanitizer를 사용하여 동시성 문제를 탐지하고 해결하는 방법을 설명해주세요.

23. Swift의 Sequence와 Collection 프로토콜에 대해 설명해주세요.
   - Sequence와 Collection 프로토콜의 차이점과 요구 사항을 설명해주세요.
   - 사용자 정의 Sequence와 Collection을 구현하는 방법과 사용 예시를 들어주세요.

24. UIKit의 AdaptiveLayout과 Size Classes에 대해 설명해주세요.
   - AdaptiveLayout의 개념과 사용 목적을 설명해주세요.
   - Size Classes를 활용하여 다양한 기기에 적응적인 UI를 구현하는 방법을 예시와 함께 설명해주세요.

25. Swift의 커스텀 연산자(Custom Operator)에 대해 설명해주세요.
   - 커스텀 연산자를 정의하는 방법과 주의 사항은 무엇인가요?
   - 커스텀 연산자를 활용한 코드 가독성 향상 방안을 제시해주세요.

26. Swift의 생성자(Initializer)와 관련된 고급 개념에 대해 설명해주세요.
   - 지정 생성자(Designated Initializer)와 편의 생성자(Convenience Initializer)의 차이점은 무엇인가요?
   - 필수 생성자(Required Initializer)와 실패 가능한 생성자(Failable Initializer)는 어떤 경우에 사용하나요?

27. Combine 프레임워크에서 Scheduler의 역할과 종류에 대해 설명해주세요.
   - Scheduler를 사용하여 작업을 특정 큐(DispatchQueue)에서 실행하는 방법을 설명해주세요.
   - 백그라운드에서 작업을 수행하고 메인 큐에서 UI를 업데이트하는 패턴을 Combine으로 구현하는 방법을 설명해주세요.

28. UIKit의 `UIView`는 클래스 기반으로 구현되어 있지만, SwiftUI에서 `View` 프로토콜을 준수하는 타입은 보통 구조체를 사용합니다. 그 이유는 무엇일까요?
   - `View` 프로토콜을 준수하는 구조체의 주요 특징은 무엇이며, 이는 어떻게 SwiftUI의 성능 및 사용성에 영향을 미치나요?
   - SwiftUI의 `View`가 구조체임에도 불구하고, 상태(state)를 어떻게 관리하고 업데이트하나요?
   - SwiftUI의 구조체 기반 `View` 생성과 업데이트 사이클은 어떻게 UIKit의 클래스 기반 `UIView`와 다른가요?  


---






















