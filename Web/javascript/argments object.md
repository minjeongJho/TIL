# arguments 객체

함수의 인수의 개수를 정의하지 않고, 배열과 유사한 형태로 인수를 저장하는 객체.

배열과 같이 arguments[0]에 첫번째 값이 저장, 다음 값은 arguments[1]에 저장된다.

또한, 전달받은 인수의 개수를 arguments.length에 저장한다.

예시
```javascript
function addNum(){
    var sum = 0;
    for(var i = 0; i < arguments.length; i++){
        sum += arguments[i];
    }
    return sum;
}

addNum();           // 0
addNum(1);          // 1
addNum(1, 2);       // 3
addNum(1, 2, 3);    // 6
```
#
출처

http://tcpschool.com/javascript/js_function_parameterArgument
