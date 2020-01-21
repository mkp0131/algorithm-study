## 문제 설명
1. 문자열 s에 나타나는 문자를 큰것부터 작은 순으로 정렬해 새로운 문자열을 리턴하는 함수, solution을 완성해주세요.
2. s는 영문 대소문자로만 구성되어 있으며, 대문자는 소문자보다 작은 것으로 간주합니다.
3. 제한 사항: str은 길이 1 이상인 문자열입니다.

### 입출력 예

s | return
|---|:---:|
"Zbcdefg" | "gfedcbZ"

```javascript
function solution(s) {
	var result = s.split('').sort().reverse().join('');
	return result;
}

var _result = solution('Zbcdefg');

console.log('', _result);
```
### 메모
1. sort(): 문자를 비교하는경우 유니코드의 값이 작은 순대로 배열을한다. 문자가 여러개일경우 순차적으로 비교하여 적용.
2. 예) 'az', 'ab' 경우 앞의 문자 'a'를 먼저 비교하고 뒤에 'z' 와 'b' 를 비교한다.


#### 참고사이트
> https://programmers.co.kr/learn/courses/30/lessons/12917

<hr/>

## 문제 설명
1. 마라톤에 참여한 선수들의 이름이 담긴 배열 participant와 완주한 선수들의 이름이 담긴 배열 completion이 주어질 때
2. 완주하지 못한 선수의 이름을 return 하도록 solution 함수를 작성해주세요

### 입출력 예

participant | completion | return
|---|:---:|---|
[leo, kiki, eden] | [eden, kiki] | leo
[marina, josipa, nikola, vinko, filipa] | [josipa, filipa, marina, nikola] | vinko
[mislav, stanko, mislav, ana] | [stanko, ana, mislav] | mislav

```javascript

```
### 메모



#### 참고사이트
> https://programmers.co.kr/learn/courses/30/lessons/42576


