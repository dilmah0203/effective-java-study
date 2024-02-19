# effective-java-study
이펙티브 자바 스터디를 위한 레포지토리입니다.

## 2장. 객체 생성과 파괴
| 아이템 | 자료
:---: | :---:
아이템 1. 생성자 대신 정적 팩터리 메서드를 고려하라 | [dilmah0203](https://github.com/dilmah0203/effective-java-study/blob/main/2%EC%9E%A5/1.%EC%83%9D%EC%84%B1%EC%9E%90_%EB%8C%80%EC%8B%A0_%EC%A0%95%EC%A0%81_%ED%8C%A9%ED%84%B0%EB%A6%AC_%EB%A9%94%EC%84%9C%EB%93%9C%EB%A5%BC_%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.md)
아이템 2. 생성자에 매개변수가 많다면 빌더를 고려하라 | [dilmah0203](https://github.com/dilmah0203/effective-java-study/blob/main/2%EC%9E%A5/2.%EC%83%9D%EC%84%B1%EC%9E%90%EC%97%90_%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EA%B0%80_%EB%A7%8E%EB%8B%A4%EB%A9%B4_%EB%B9%8C%EB%8D%94%EB%A5%BC_%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.md)
아이템 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라 | [dilmah0203](https://github.com/dilmah0203/effective-java-study/blob/main/2%EC%9E%A5/3.private_%EC%83%9D%EC%84%B1%EC%9E%90%EB%82%98_%EC%97%B4%EA%B1%B0_%ED%83%80%EC%9E%85%EC%9C%BC%EB%A1%9C_%EC%8B%B1%EA%B8%80%ED%84%B4%EC%9E%84%EC%9D%84_%EB%B3%B4%EC%A6%9D%ED%95%98%EB%9D%BC.md)
아이템 4. 인스턴스화를 막으려거든 private 생성자를 사용하라 | [shjang1013](https://github.com/dilmah0203/effective-java-study/blob/main/2%EC%9E%A5/4.%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4%ED%99%94%EB%A5%BC_%EB%A7%89%EC%9C%BC%EB%A0%A4%EA%B1%B0%EB%93%A0_private_%EC%83%9D%EC%84%B1%EC%9E%90%EB%A5%BC_%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)
아이템 5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라 | [shjang1013](https://github.com/dilmah0203/effective-java-study/blob/main/2%EC%9E%A5/5.%EC%9E%90%EC%9B%90%EC%9D%84_%EC%A7%81%EC%A0%91_%EB%AA%85%EC%8B%9C%ED%95%98%EC%A7%80_%EB%A7%90%EA%B3%A0_%EC%9D%98%EC%A1%B4_%EA%B0%9D%EC%B2%B4_%EC%A3%BC%EC%9E%85%EC%9D%84_%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)
아이템 6. 불필요한 객체 생성을 피하라 | [shjang1013](https://github.com/dilmah0203/effective-java-study/blob/main/2%EC%9E%A5/6.%EB%B6%88%ED%95%84%EC%9A%94%ED%95%9C_%EA%B0%9D%EC%B2%B4_%EC%83%9D%EC%84%B1%EC%9D%84_%ED%94%BC%ED%95%98%EB%9D%BC.md)
아이템 7. 다 쓴 객체 참조를 해제하라| [hwibaski](https://github.com/dilmah0203/effective-java-study/blob/main/2%EC%9E%A5/7.%EB%8B%A4_%EC%93%B4_%EA%B0%9D%EC%B2%B4_%EC%B0%B8%EC%A1%B0%EB%A5%BC_%ED%95%B4%EC%A0%9C%ED%95%98%EB%9D%BC.md)
아이템 8. finalizer와 cleaner 사용을 피하라 | [hwibaski](https://github.com/dilmah0203/effective-java-study/blob/main/2%EC%9E%A5/8.finalizer%EC%99%80%20cleaner%20%EC%82%AC%EC%9A%A9%EC%9D%84%20%ED%94%BC%ED%95%98%EB%9D%BC.md)
아이템 9. try-finally보다는 try-with-resources를 사용하라 | [hwibaski](https://github.com/dilmah0203/effective-java-study/blob/main/2%EC%9E%A5/9.try-with-resource%EB%A5%BC_%EC%82%AC%EC%9A%A9%ED%95%98%EC%9E%90.md)

## 3장. 모든 객체의 공통 메서드
| 아이템 | 자료
:---: | :---:
아이템 10. equals는 일반 규약을 지켜 재정의하라 | [jexnjeux](https://github.com/dilmah0203/effective-java-study/blob/main/3%EC%9E%A5/10.%20equals%EB%8A%94_%EC%9D%BC%EB%B0%98_%EA%B7%9C%EC%95%BD%EC%9D%84_%EC%A7%80%EC%BC%9C_%EC%9E%AC%EC%A0%95%EC%9D%98%ED%95%98%EB%9D%BC.md)
아이템 11. equals를 재정의하려거든 hashCode도 재정의하라 | [jexnjeux](https://github.com/dilmah0203/effective-java-study/blob/main/3%EC%9E%A5/11.%20equals%EB%A5%BC_%EC%9E%AC%EC%A0%95%EC%9D%98%ED%95%98%EB%A0%A4%EA%B1%B0%EB%93%A0_hashCode%EB%8F%84_%EC%9E%AC%EC%A0%95%EC%9D%98%ED%95%98%EB%9D%BC.md)
아이템 12. toString을 항상 재정의하라 | [jexnjeux](https://github.com/dilmah0203/effective-java-study/blob/main/3%EC%9E%A5/12.%20toSting%EC%9D%84_%ED%95%AD%EC%83%81_%EC%9E%AC%EC%A0%95%EC%9D%98%ED%95%98%EB%9D%BC.md)
아이템 13. clone 재정의는 주의해서 진행하라 | [dilmah0203](https://github.com/dilmah0203/effective-java-study/blob/main/3%EC%9E%A5/13.clone%20%EC%9E%AC%EC%A0%95%EC%9D%98%EB%8A%94%20%EC%A3%BC%EC%9D%98%ED%95%B4%EC%84%9C%20%EC%A7%84%ED%96%89%ED%95%98%EB%9D%BC.md)
아이템 14. Comparable을 구현할지 고려하라 | [dilmah0203](https://github.com/dilmah0203/effective-java-study/blob/main/3%EC%9E%A5/14.Comparable%EC%9D%84%20%EA%B5%AC%ED%98%84%ED%95%A0%EC%A7%80%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.md)

## 4장. 클래스와 인터페이스
| 아이템 | 자료
:---: | :---:
아이템 15. 클래스와 멤버의 접근 권한을 최소화하라 | [dilmah0203](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/15.%ED%81%B4%EB%9E%98%EC%8A%A4%EC%99%80%20%EB%A9%A4%EB%B2%84%EC%9D%98%20%EC%A0%91%EA%B7%BC%20%EA%B6%8C%ED%95%9C%EC%9D%84%20%EC%B5%9C%EC%86%8C%ED%99%94%ED%95%98%EB%9D%BC.md)
아이템 16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라 | [shjang1013](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/16.%20public_%ED%81%B4%EB%9E%98%EC%8A%A4%EC%97%90%EC%84%9C%EB%8A%94_public_%ED%95%84%EB%93%9C%EA%B0%80_%EC%95%84%EB%8B%8C_%EC%A0%91%EA%B7%BC%EC%9E%90_%EB%A9%94%EC%84%9C%EB%93%9C%EB%A5%BC_%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)
아이템 17. 변경 가능성을 최소화하라 | [shjang1013](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/17.%20%EB%B3%80%EA%B2%BD_%EA%B0%80%EB%8A%A5%EC%84%B1%EC%9D%84_%EC%B5%9C%EC%86%8C%ED%99%94%ED%95%98%EB%9D%BC.md)
아이템 18. 상속보다는 컴포지션을 사용하라 | [shjang1013](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/18.%20%EC%83%81%EC%86%8D%EB%B3%B4%EB%8B%A4%EB%8A%94_%EC%BB%B4%ED%8F%AC%EC%A7%80%EC%85%98%EC%9D%84_%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)
아이템 19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라. | [jexnjeux](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/19.%20%EC%83%81%EC%86%8D%EC%9D%84%20%EA%B3%A0%EB%A0%A4%ED%95%B4%20%EC%84%A4%EA%B3%84%ED%95%98%EA%B3%A0%20%EB%AC%B8%EC%84%9C%ED%99%94%ED%95%98%EB%9D%BC.md)
아이템 20. 추상 클래스보다는 인터페이스를 우선하라 |[jexnjeux](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/20.%20%EC%B6%94%EC%83%81%20%ED%81%B4%EB%9E%98%EC%8A%A4%EB%B3%B4%EB%8B%A4%EB%8A%94%20%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EB%A5%BC%20%EC%9A%B0%EC%84%A0%ED%95%98%EB%9D%BC.md)
아이템 21. 인터페이스는 구현하는 쪽을 생각해 설계하라 |[jexnjeux](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/21.%20%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EB%8A%94%20%EA%B5%AC%ED%98%84%ED%95%98%EB%8A%94%20%EC%AA%BD%EC%9D%84%20%EC%83%9D%EA%B0%81%ED%95%B4%20%EC%84%A4%EA%B3%84%ED%95%98%EB%9D%BC.md)
아이템 22. 인터페이스는 타입을 정의하는 용도로만 사용하라 | [dilmah0203](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/22.%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EB%8A%94%20%ED%83%80%EC%9E%85%EC%9D%84%20%EC%A0%95%EC%9D%98%ED%95%98%EB%8A%94%20%EC%9A%A9%EB%8F%84%EB%A1%9C%EB%A7%8C%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)
아이템 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라 | [dilmah0203](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/23.%ED%83%9C%EA%B7%B8%20%EB%8B%AC%EB%A6%B0%20%ED%81%B4%EB%9E%98%EC%8A%A4%EB%B3%B4%EB%8B%A4%EB%8A%94%20%ED%81%B4%EB%9E%98%EC%8A%A4%20%EA%B3%84%EC%B8%B5%EA%B5%AC%EC%A1%B0%EB%A5%BC%20%ED%99%9C%EC%9A%A9%ED%95%98%EB%9D%BC.md)
아이템 24. 멤버 클래스는 되도록 static으로 만들라 | [dilmah0203](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/24.%EB%A9%A4%EB%B2%84%20%ED%81%B4%EB%9E%98%EC%8A%A4%EB%8A%94%20%EB%90%98%EB%8F%84%EB%A1%9D%20static%EC%9C%BC%EB%A1%9C%20%EB%A7%8C%EB%93%A4%EB%9D%BC.md)
아이템 25. 톱레벨 클래스는 한 파일에 하나만 담으라 | [shjang1013](https://github.com/dilmah0203/effective-java-study/blob/main/4%EC%9E%A5/25.%20%ED%86%B1%EB%A0%88%EB%B2%A8_%ED%81%B4%EB%9E%98%EC%8A%A4%EB%8A%94_%ED%95%9C_%ED%8C%8C%EC%9D%BC%EC%97%90_%ED%95%98%EB%82%98%EB%A7%8C_%EB%8B%B4%EC%9C%BC%EB%9D%BC.md)

## 5장. 제네릭
| 아이템 | 자료
:---: | :---:
아이템 26. 로 타입은 사용하지 말라 | [shjang1013](https://github.com/dilmah0203/effective-java-study/blob/main/5%EC%9E%A5/26.%20%EB%A1%9C_%ED%83%80%EC%9E%85%EC%9D%80_%EC%82%AC%EC%9A%A9%ED%95%98%EC%A7%80_%EB%A7%90%EB%9D%BC.md)
아이템 27. 비검사 경고를 제거하라 | [shjang1013](https://github.com/dilmah0203/effective-java-study/blob/main/5%EC%9E%A5/27.%20%EB%B9%84%EA%B2%80%EC%82%AC_%EA%B2%BD%EA%B3%A0%EB%A5%BC_%EC%A0%9C%EA%B1%B0%ED%95%98%EB%9D%BC.md)
아이템 28. 배열보다는 리스트를 사용하라 | [dilmah0203](https://github.com/dilmah0203/effective-java-study/blob/main/5%EC%9E%A5/28.%20%EB%B0%B0%EC%97%B4%EB%B3%B4%EB%8B%A4%EB%8A%94%20%EB%A6%AC%EC%8A%A4%ED%8A%B8%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)
아이템 29. 이왕이면 제네릭 타입으로 만들라 | []()
아이템 30. 이왕이면 제네릭 메서드로 만들라 | 
아이템 31. 한정적 와일드카드를 사용해 API 유연성을 높이라 | 
아이템 32. 제네릭과 가변인수를 함께 쓸 때는 신중하라 |  
아이템 33. 타입 안전 이종 컨테이너를 고려하라 | 

## 6장. 열거 타입과 애너테이션
| 아이템 | 자료
:---: | :---:
아이템 34. int 상수 대신 열거 타입을 사용하라 |
아이템 35. ordinal 메서드 대신 인스턴스 필드를 사용하라 | 
아이템 36. 비트 필드 대신 EnumSet을 사용하라 |
아이템 37. ordinal 인덱싱 대신 EnumMap을 사용하라 | 
아이템 38. 확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라 | 
아이템 39. 명명 패턴보다 애너테이션을 사용하라 | 
아이템 40. @Override 애너테이션을 일관되게 사용하라 | 
아이템 41. 정의하려는 것이 타입이라면 마커 인터페이스를 사용하라 | 

## 7장. 람다와 스트림
| 아이템 | 자료
:---: | :---:
아이템 42. 익명 클래스보다는 람다를 사용하라 | 
아이템 43. 람다보다는 메서드 참조를 사용하라 | 
아이템 44. 표준 함수형 인터페이스를 사용하라 | 
아이템 45. 스트림은 주의해서 사용하라 | 
아이템 46. 스트림에서는 부작용 없는 함수를 사용하라 | 
아이템 47. 반환 타입으로는 스트림보다 컬렉션이 낫다 | 
아이템 48. 스트림 병렬화는 주의해서 적용하라 |

## 8장. 메서드
| 아이템 | 자료
:---: | :---:
아이템 49. 매개변수가 유효한지 검사하라 |
아이템 50. 적시에 방어적 복사본을 만들라 | 
아이템 51. 메서드 시그니처를 신중히 설계하라 |
아이템 52. 다중정의는 신중히 사용하라 |
아이템 53. 가변인수는 신중히 사용하라 | 
아이템 54. null이 아닌, 빈 컬렉션이나 배열을 반환하라 | 
아이템 55. 옵셔널 반환은 신중히 하라 | 
아이템 56. 공개된 API 요소에는 항상 문서화 주석을 작성하라 | 

## 9장. 일반적인 프로그래밍 원칙
| 아이템 | 자료
:---: | :---:
아이템 57. 지역변수의 범위를 최소화하라 |
아이템 58. 전통적인 for 문보다는 for-each 문을 사용하라 |
아이템 59. 라이브러리를 익히고 사용하라 | 
아이템 60. 정확한 답이 필요하다면 float와 double은 피하라 | 
아이템 61. 박싱된 기본 타입보다는 기본 타입을 사용하라 |
아이템 62. 다른 타입이 적절하다면 문자열 사용을 피하라 | 
아이템 63. 문자열 연결은 느리니 주의하라 | 
아이템 64. 객체는 인터페이스를 사용해 참조하라 | 
아이템 65. 리플렉션보다는 인터페이스를 사용하라 | 
아이템 66. 네이티브 메서드는 신중히 사용하라 |
아이템 67. 최적화는 신중히 하라 |
아이템 68. 일반적으로 통용되는 명명 규칙을 따르라 | 

## 10장. 예외
| 아이템 | 자료
:---: | :---:
아이템 69. 예외는 진짜 예외 상황에만 사용하라 |
아이템 70. 복구할 수 있는 상황에는 검사 예외를, 프로그래밍 오류에는 런타임 예외를 사용하라 |
아이템 71. 필요 없는 검사 예외 사용은 피하라 |
아이템 72. 표준 예외를 사용하라 |
아이템 73. 추상화 수준에 맞는 예외를 던지라 | 
아이템 74. 메서드가 던지는 모든 예외를 문서화하라 |
아이템 75. 예외의 상세 메시지에 실패 관련 정보를 담으라 |
아이템 76. 가능한 한 실패 원자적으로 만들라 |
아이템 77. 예외를 무시하지 말라 |

## 11장. 동시성
| 아이템 | 자료
:---: | :---:
아이템 78. 공유 중인 가변 데이터는 동기화해 사용하라 | 
아이템 79. 과도한 동기화는 피하라 |
아이템 80. 스레드보다는 실행자, 태스크, 스트림을 애용하라 | 
아이템 81. wait와 notify보다는 동시성 유틸리티를 애용하라 | 
아이템 82. 스레드 안전성 수준을 문서화하라 |
아이템 83. 지연 초기화는 신중히 사용하라 |
아이템 84. 프로그램의 동작을 스레드 스케줄러에 기대지 말라 |

## 12장. 직렬화
| 아이템 | 자료
:---: | :---:
아이템 85. 자바 직렬화의 대안을 찾으라 | 
아이템 86. Serializable을 구현할지는 신중히 결정하라 |
아이템 87. 커스텀 직렬화 형태를 고려해보라 | 
아이템 88. readObject 메서드는 방어적으로 작성하라 | 
아이템 89. 인스턴스 수를 통제해야 한다면 readResolve보다는 열거 타입을 사용하라 | 
아이템 90. 직렬화된 인스턴스 대신 직렬화 프록시 사용을 검토하라 |
