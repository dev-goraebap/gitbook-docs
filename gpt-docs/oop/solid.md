---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# SOLID 원칙

SOLID 원칙은 객체지향 프로그래밍과 설계에서 좋은 코드 구조와 유지 보수성을 촉진하기 위한 다섯 가지 기본 원칙의 첫 글자를 따서 만든 약어입니다. 이 원칙들은 로버트 C. 마틴(Robert C. Martin)이 제안하였으며, 각 원칙은 소프트웨어 엔지니어가 더 깔끔하고 확장 가능하며 유연한 시스템을 개발할 수 있도록 돕습니다.

1. **S: Single Responsibility Principle (단일 책임 원칙)**
   * 하나의 클래스는 하나의 책임만 가져야 합니다. 이 원칙에 따르면, 클래스가 변경되어야 하는 이유는 오직 하나여야 합니다. 이렇게 하면 클래스가 과도하게 커지는 것을 방지하고, 시스템의 각 부분이 잘 정의된 역할을 갖게 도와줍니다.
2. **O: Open/Closed Principle (개방-폐쇄 원칙)**
   * 소프트웨어 엔티티(클래스, 모듈, 함수 등)는 확장에 대해 열려있어야 하며, 수정에 대해서는 닫혀 있어야 합니다. 즉, 기존의 코드를 변경하지 않고도 시스템의 기능을 확장할 수 있어야 합니다. 이는 추상화와 상속을 사용하여 구현할 수 있습니다.
3. **L: Liskov Substitution Principle (리스코프 치환 원칙)**
   * 프로그램의 객체는 그 서브 타입의 인스턴스로 대체할 수 있어야 하며, 이로 인해 프로그램의 정확성을 저해해서는 안 됩니다. 즉, 서브 클래스는 언제나 그들의 기반 클래스로 교체 가능해야 합니다.
4. **I: Interface Segregation Principle (인터페이스 분리 원칙)**
   * 한 클래스는 자신이 사용하지 않는 인터페이스는 구현하지 않아야 합니다. 큰 단일 인터페이스보다는, 구체적인 여러 개의 인터페이스가 더 낫습니다. 이 원칙은 특정 클라이언트를 위한 인터페이스가 여러 일반적인 인터페이스에 의해 오염되지 않도록 합니다.
5. **D: Dependency Inversion Principle (의존관계 역전 원칙)**
   * 고수준 모듈은 저수준 모듈에 의존해서는 안 되며, 둘 다 추상화에 의존해야 합니다. 또한, 추상화는 세부사항에 의존해서는 안 되며, 세부사항은 추상화에 의존해야 합니다. 이 원칙은 시스템의 결합도를 낮추고, 유연성을 향상시킵니다.

이러한 SOLID 원칙들은 객체지향 설계의 품질을 높이는 데 중요한 역할을 하며, 개발자가 보다 견고하고, 유지보수가 용이하며, 확장성 있는 소프트웨어를 설계할 수 있도록 돕습니다.