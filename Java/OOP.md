# OOP (Object-Oriented Programming)

### 객체지향 프로그래밍이란?

객체 지향 프로그래밍은 컴퓨터 프로그래밍의 패러다임 중 하나이다. 프로그래밍에서 필요한 데이터를 추상화시켜 상태와 행위를 가진 객체간의 유기적인 상호작용을 통해 로직을 구성하는 방법이다.

객체지향 프로그래밍은 코드의 재사용성이 높고 유연하기 때문에 유지보수가 쉽다 그러므로 대형 프로젝트에 적합한 방법이다.

### 구성요소

- 클래스 - 클래스는 객체를 생성해 주는 틀이라고 할 수 있다. 속성과 행동을 정의해 놓는다.
- 객체 - 클래스를 이용해 인스턴스화 시킨 것으로 실제 메모리에 올라간 상태이다. 객체마다 고유한 속성을 가지며 행위를 수행할 수 있다.
- 메서드, 메시지 - 객체간에 통신을 하거나 객체에 명령을 내리는 메시지라고 할 수 있다.

### 특징

- 추상화
  인터페이스로 공통적인 특성들을 묶어 표현하는 것
  <br>

- 캡슐화
  불필요한 정보를 외부로부터 감추고, 변수와 메소드를 하나로 묶는다. 하여 함수를 통해서 데이터를 접근한다.
  <br>

- 상속
  부모 클래스의 특성을 자식 클래스로 물려주는 것, 캡슐화를 유지하고 클래스의 재사용에 용이
  <br>

- 다형성
  인터페이스로 역할과 구현을 철저히 분리함으로써 언제든 다양한 상황을 만들어 낼 수 있다.

### 설계 5원칙 (SOLID)

이 5원칙을 사용하면 시간이 지나도 유지보수 와 확장이 쉬운 시스템을 만들 때 좋다.

- SRP(Single Responsibility Principle) : 단일 책임 원칙
  한 클래스는 하나의 책임만 가져야 한다.
  <br>

- OCP(Open-Closed Principle) : 개방 폐쇄 원칙
  소프트웨어 요소는 확장에는 열려있고, 변경에는 닫혀있어야 한다.
  <br>

- LSP(Liskov Substitution Principle) : 리스코프 치환 원칙
  프로그램의 객체는 프로그램의 정확성을 깨뜨리지 않으면서 하위 타입의 인스턴스로 바꿀 수 있어야 한다.
  <br>

- ISP(Interface Segregation Principle) : 인터페이스 분리 원칙
  특정 클라이언트를 위한 인터페이스 여러 개가 범용 인터페이스 하나보다 낫다.
  <br>

- DIP(Dependency Inversion Principle) : 의존관계 역전 원칙
  프로그래머는 추상화에 의존해야지 구체화에 의존하면 안된다.