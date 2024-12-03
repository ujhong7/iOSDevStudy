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


1. **Swift에서 옵셔널(Optional)이란 무엇이며, 언제 사용해야 하나요?**
   - 옵셔널 바인딩과 강제 언래핑의 차이점은 무엇인가요?
   - 옵셔널 체이닝의 동작 원리는 무엇이며, 어떻게 사용하나요?
   - 암시적 언래핑 옵셔널(Implicitly Unwrapped Optional)은 어떤 경우에 사용해야 하나요?

2. **iOS 앱의 생명주기(App Life Cycle)에 대해 설명해주세요.**
   - 앱의 각 상태(`Not Running`, `Inactive`, `Active`, `Background`, `Suspended`)에서 가능한 작업은 무엇인가요?
   - 상태 변화에 따라 호출되는 `AppDelegate` 또는 `SceneDelegate` 메서드는 무엇인가요?
   - 백그라운드에서 작업을 완료하기 위한 방법은 어떤 것이 있나요?

3. **Auto Layout을 사용하는 이유와 장점은 무엇인가요?**
   - 제약 조건(Constraints)의 우선순위(Priority)는 어떻게 동작하나요?
   - Intrinsic Content Size란 무엇이며, 어떻게 활용되나요?
   - Ambiguous Layout과 Unsatisfiable Constraints는 무엇이며, 어떻게 해결하나요?

4. **Swift에서 클로저(Closure)란 무엇이며, 어떻게 사용하나요?**
   - 클로저의 캡처(Capture) 기능은 무엇인가요?
   - @escaping 클로저와 non-escaping 클로저의 차이점은 무엇인가요?
   - 트레일링 클로저(Trailing Closure) 문법은 어떤 경우에 유용한가요?

5. **iOS에서 Delegate 패턴은 무엇이며, 어떤 상황에서 사용되나요?**
   - Delegate 패턴과 Notification, KVO의 차이점은 무엇인가요?
   - 프로토콜을 활용한 Delegate 패턴 구현 방법을 설명해주세요.

6. **Swift의 기본 데이터 타입과 컬렉션(Collection) 타입에는 어떤 것들이 있나요?**
   - 값 타입(Value Type)과 참조 타입(Reference Type)의 차이점은 무엇인가요?
   - 구조체(Struct)와 클래스(Class)의 사용 시기는 어떻게 구분하나요?
   - 열거형(Enum)의 원시값(Raw Value)과 연관값(Associated Value)은 무엇인가요?

7. **Xcode에서 디버깅 시 자주 사용하는 기능은 무엇인가요?**
   - 중단점(Breakpoint)의 종류와 활용 방법을 설명해주세요.
   - LLDB 콘솔에서 유용한 명령어는 어떤 것이 있나요?

8. **iOS 앱에서 데이터를 저장하는 방법에는 어떤 것들이 있나요?**
   - `UserDefaults`의 사용 시 주의할 점은 무엇인가요?
   - Keychain은 어떤 데이터를 저장하기에 적합한가요?
   - Core Data와 SQLite의 차이점은 무엇이며, 각각 언제 사용하면 좋나요?

9. **Swift에서 프로토콜(Protocol)이란 무엇이며, 어떻게 활용하나요?**
   - 프로토콜의 요구사항은 무엇인가요?
   - 프로토콜 확장(Protocol Extension)을 사용하는 이유는 무엇인가요?
   - 프로토콜 지향 프로그래밍(Protocol-Oriented Programming)의 장점은 무엇인가요?

10. **Swift의 접근 제어자(Access Control Levels)에 대해 설명해주세요.**
    - `open`과 `public`의 차이점은 무엇인가요?
    - `internal`, `fileprivate`, `private`의 사용 시기는 어떻게 결정하나요?
    - 접근 제어자를 사용하는 이유는 무엇인가요?

11. **iOS 앱에서 네트워크 통신을 하는 방법에는 어떤 것들이 있나요?**
    - `URLSession`의 기본 사용 방법을 설명해주세요.
    - 네트워크 요청 시 에러 처리는 어떻게 하나요?
    - 서드파티 라이브러리(예: Alamofire)를 사용하는 이유는 무엇인가요?

12. **의존성 관리 도구(CocoaPods, Carthage, Swift Package Manager)의 종류와 차이점은 무엇인가요?**
    - 각 도구의 사용 방법과 장단점을 설명해주세요.
    - 의존성 관리를 통해 얻을 수 있는 이점은 무엇인가요?

13. **Swift의 고차 함수(Higher-Order Functions)에 대해 설명해주세요.**
    - `map`과 `flatMap`의 차이점은 무엇인가요?
    - `filter`, `reduce` 함수는 어떤 경우에 사용하나요?
    - `compactMap`은 어떤 역할을 하나요?

14. **Git에서 브랜치(Branch)를 사용하는 이유와 장점은 무엇인가요?**
    - 브랜치를 병합(Merge)하는 방법에는 어떤 것들이 있나요?
    - 브랜치 전략(예: Git Flow, GitHub Flow)에 대해 설명해주세요.
    - 충돌(Conflict)이 발생했을 때 해결 방법은 무엇인가요?

15. **Swift의 에러 처리 방법에 대해 설명해주세요.**
    - `throws`, `try`, `catch` 키워드의 사용 방법은 무엇인가요?
    - 옵셔널을 사용한 에러 처리와 `do-catch`를 사용하는 에러 처리의 차이는 무엇인가요?
    - 에러를 전파하는 방법은 무엇인가요?

16. **메모리 관리에서 강한 참조(Strong Reference)와 약한 참조(Weak Reference)의 차이점은 무엇인가요?**
    - 순환 참조(Retain Cycle)가 발생하는 경우와 해결 방법은 무엇인가요?
    - 클로저에서 `[weak self]`와 `[unowned self]`의 차이는 무엇인가요?

17. **iOS 앱에서 Multi-threading을 구현하는 방법은 무엇인가요?**
    - `DispatchQueue`와 `OperationQueue`의 차이점은 무엇인가요?
    - 동시성 프로그래밍에서 Race Condition을 방지하는 방법은 무엇인가요?
    - 메인 스레드에서 UI 업데이트를 해야 하는 이유는 무엇인가요?

18. **UIKit에서 TableView와 CollectionView의 차이점은 무엇인가요?**
    - 셀(Cell)의 재사용(Reusability)은 어떻게 구현되나요?
    - 동적인 셀 높이(Dynamic Cell Height)를 설정하는 방법은 무엇인가요?
    - CollectionView의 레이아웃을 커스터마이징하는 방법은 무엇인가요?

19. **ARC(Automatic Reference Counting)의 동작 원리는 무엇인가요?**
    - Retain Cycle이 발생하지 않도록 방지하는 방법은 무엇인가요?
    - `deinit` 메서드는 언제 호출되며, 어떤 역할을 하나요?

20. **상속(Inheritance)과 프로토콜(Protocol)의 차이점은 무엇인가요?**
    - 클래스 상속을 사용할 때의 장단점은 무엇인가요?
    - 다중 상속(Multiple Inheritance)이 불가능한 이유는 무엇인가요?
    - 프로토콜 준수(Conformance)를 통해 다형성을 구현하는 방법은 무엇인가요?

21. **사용자 인터페이스(UI) 테스트와 단위(Unit) 테스트의 차이점은 무엇인가요?**
    - XCTest 프레임워크를 사용하여 테스트를 작성하는 방법은 무엇인가요?
    - 테스트 주도 개발(TDD)의 장점은 무엇인가요?
    - 의존성 주입(Dependency Injection)을 활용하여 테스트 가능한 코드를 작성하는 방법은 무엇인가요?

22. **Xcode에서 Instruments를 사용하여 앱의 성능을 분석하는 방법은 무엇인가요?**
    - Time Profiler를 사용하여 성능 이슈를 찾는 방법을 설명해주세요.
    - Allocations Instrument를 사용하여 메모리 누수를 탐지하는 방법은 무엇인가요?
    - Leaks Instrument를 사용하여 메모리 누수를 찾는 방법은 무엇인가요?

23. **Swift의 제네릭(Generic)에 대해 설명해주세요.**
    - 제네릭을 사용하는 이유는 무엇인가요?
    - 제네릭 타입 파라미터와 제약 조건을 설정하는 방법은 무엇인가요?
    - 제네릭을 사용할 때의 장점과 주의할 점은 무엇인가요?

24. **Swift의 클로저와 함수의 차이점은 무엇인가요?**
    - 클로저가 일급 객체(First-Class Citizen)인 이유는 무엇인가요?
    - 함수형 프로그래밍 패러다임에서 클로저가 어떻게 활용되나요?

25. **동시성 프로그래밍에서 동기(Synchronous)와 비동기(Asynchronous)의 차이점은 무엇인가요?**
    - iOS에서 비동기 작업을 처리하는 방법은 무엇인가요?
    - 세마포어(Semaphore)와 뮤텍스(Mutex)의 차이점은 무엇인가요?

26. **GCD(Grand Central Dispatch)의 주요 개념과 사용 방법을 설명해주세요.**
    - 직렬(Serial) 큐와 동시(Concurrent) 큐의 차이는 무엇인가요?
    - 글로벌 큐(Global Queue)와 메인 큐(Main Queue)는 어떻게 다르나요?
    - DispatchWorkItem을 사용하는 방법은 무엇인가요?


































