# 🚀 TDD counter
이 프로젝트는 테스트 주도 개발(TDD) 방식을 활용해 개발한 간단한 카운터 앱이다. TDD는 테스트를 먼저 작성하고, 이를 통과할 수 있는 코드를 나중에 작성하는 소프트웨어 개발 프로세스이다. TDD 방식을 통해 코드의 신뢰성을 높이고, 버그를 최소화할 수 있다.

![tdd-counter-demo](https://github.com/user-attachments/assets/a7964368-1c67-4a63-ad3b-f3b4803a215a)



## 🛠 TDD란?
테스트 주도 개발(Test-Driven Development, TDD)은 아래와 같은 3단계로 이루어진 개발 방법론이다.

1. 테스트 작성
- 먼저 원하는 기능이 어떻게 동작해야 하는지에 대한 테스트를 작성한다.
- 초기에는 실제 기능 코드가 없기 때문에 테스트는 실패한다.

2. 코드 작성
- 테스트를 통과하기 위한 최소한의 기능 코드를 작성한다.

3. 리팩토링 
- 테스트가 통과한 후, 코드의 가독성과 유지 보수성을 높이기 위해 코드를 정리(리팩토링)한다.
- 이때 테스트가 여전히 통과하는지 확인한다.

TDD를 통해 작성된 코드는 원하는 대로 동작할 가능성이 높고, 코드의 품질과 안정성을 보장할 수 있다.

## ✨ 주요 기능

1. 🔢 카운터 표시
- 현재 카운터의 값을 화면에 표시한다.
- 카운터는 처음에 0으로 시작한다.

2. ⬜️ 증가 및 감소 버튼
- ➕ 버튼을 누르면 카운터 값이 증가한다.
- ➖ 버튼을 누르면 카운터 값이 감소한다.
  
3. 🟦 on/off 버튼
- on/off 버튼을 누르면 ➕와 ➖ 버튼이 비활성화된다.
     
## 🧪 테스트
- 카운터가 0에서 시작하는지 테스트
- ➕ 버튼을 눌렀을 때 카운터 값이 증가하는지, ➖ 버튼을 눌렀을 때 카운터 값이 감소하는지 테스트
- on/off 버튼을 클릭했을 때, ➕와 ➖ 버튼이 비활성화되는지 테스트
- on/off 버튼의 배경색이 파란색인지 테스트
