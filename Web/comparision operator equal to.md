# 비교 연산자 == 과 ===

### == 는 '값'만 비교 한다.
### === 는 '값'과 '타입'을 비교 한다.

예시를 들면,

```javascript
1 == "1"    // true
1 === "1"   // false
```
이처럼, 숫자, 문자열의 데이터 값만 비교했을 땐 true지만, 타입을 비교했을 땐 false가 나오게 된다.

또한, null 과 undefined의 차이도 여기에서 확인할 수 있다.
```javascript
null == undefined      // true
null === undefined     // false
```
따라서, 엄격하게 비교하기 위해서 === 사용을 권장하고 있다.
#
출처

https://programmers.co.kr/learn/questions/25