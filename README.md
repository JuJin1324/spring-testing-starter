# spring-testing-starter

## 단위테스트 관리 규칙
### 불필요한 코드 제거
> **테스트 메서드 안에서 try/catch 블록을 통해서 예외를 처리하지 않는다.**  
> 테스트 메서드 안에서 체크 예외를 처리해야하는 메서드를 호출하는 경우 테스트 메서드 옆에 throws 로 처리한다.  
> 테스트 메서드에 throws 로 처리를 하더라도 테스트 메서드 내의 로직에서 예외 발생 시 JUnit 에서 테스트 실패 및 예외 코드의 trace 로그를
> 표시해준다.  

### 테스트 구성
> 잘 구성된 테스트는 시스템과 상호 작용을 '데이터 준비하기(given)', '시스템과 동작하기(when)', '결과 단언하기(then)' 세 가지
> 관점에서 보여 줍니다.

---

## JUnit 5
### assertion
> TODO

---

## Mockito
### @Mock
> TODO

### @MockBean
> TODO

---

## Spring Rest Docs
### TODO
> TODO

---

## testcontainers
### TODO
> TODO
