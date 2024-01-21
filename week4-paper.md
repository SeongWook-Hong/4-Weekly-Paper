# <4주차 위클리 페이퍼>

### ✅ 자바스크립트에서 얕은 복사(Shallow Copy)와 깊은 복사(Deep Copy)에 대해 설명해 주세요.

**얕은 복사**란? <br>
객체를 복사할 때 기존 값과 복사된 값이 같은 참조를 가리키고 있는 것을 말한다.
객체 안에 객체가 있을 경우 한 개의 객체라도 기존 변수의 객체를 참조하고 있다면 이를 얕은 복사라고 한다.


**깊은 복사**란? <br>
깊은 복사된 객체는 객체 안에 객체가 있을 경우에도 원본과의 참조가 완전히 끊어진 객체를 말한다.



### ✅ var, let, const 를 중복 선언 허용, 스코프, 호이스팅 관점에서 서로 비교해 주세요.

||var|let|const|
|------|---|---|---|
|중복 선언|O|X|X|
|스코프|함수 레벨|블록 레벨|블록 레벨|
|호이스팅|O|△|△|

```
△: 호이스팅은 발생하였으나 변수의 선언과 초기화 사이에 일시적으로 변수값을 참조할수 없는 구간인 TDZ(Temporal Dead Zone)에 빠지게 됨
```