# x만큼 간격이 있는 n개의 숫자

## 1. 문제설명
 + 정수 x와 자연수 n을 입력 받아, x부터 시작해 x씩 증가하는 숫자를 n개 지니는 리스트를 리턴
  
## 2. 제한조건
 + x는 -10000000 이상, 10000000 이하인 정수
 + n은 1000 이하인 자연수


## 입출력 예
|x|n|answer|
|------|---|---|
|2|5|[2,4,6,8,10]|
|4|3|[4,8,12]|
|-4|2|[-4,-8]|
  
## 3. 기본코드
```JavaScript
function solution(x, n) {
    var answer = [];
    return answer;
}
```

## 4. 문제풀이
```JavaScript
function solution(x, n) {
    var answer = [];
    for (let i = 1; i < n+1; i++){
        answer.push(x*i);
    }
    return answer;
}
```

- 반복문 for문을 사용하여 풀어본 문제
- i가 0부터 시작하면 안되어서 1부터 시작하는걸로 작성
- n과 같아질때까지 반복하도록 진행

### 참고자료
-
