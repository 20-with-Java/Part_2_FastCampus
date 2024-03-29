### BOJ [1935] 후위 표기식2
> https://www.acmicpc.net/problem/1935

[`후위표기식`](https://ko.wikipedia.org/wiki/%EC%97%AD%ED%8F%B4%EB%9E%80%EB%93%9C_%ED%91%9C%EA%B8%B0%EB%B2%95)은 연산자를 연산 대상의 뒤에 쓰는 연산 표기법입니다. 연산자가 나왔을 때 가장 최근 항 둘을 계산해야하므로 스택을 사용할 수 있습니다.

순자가 알파벳으로 대체되어 들어오기 때문에 한 글자씩 순회하여 처리할 수 있습니다. 식의 결과와 중간 결과의 절댓값이 20억으로 `float` 자료형은 정밀도가 부족해 `double` 자료형을 사용하는 것이 좋습니다. 시간복잡도는 O(표기식 길이)가 됩니다.
