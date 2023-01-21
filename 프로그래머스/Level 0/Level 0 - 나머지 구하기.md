## 나머지 구하기

### 문제설명
> 정수 num1, num2가 매개변수로 주어질 때, num1를 num2로 나눈 나머지를 return 하도록 solution 함수를 완성해주세요.

### 제한사항
+ 0 < num1 ≤ 100
+ 0 < num2 ≤ 100

### 플로우차트 순서도
<img width="390" alt="image" src="https://user-images.githubusercontent.com/58936137/213855794-131cfc8e-ec1a-4a0e-863f-51cd8a0be669.png">


### 코드 작성
~~~
class Solution {
    fun solution(num1: Int, num2: Int): Int {
        var num = num1 % num2 
        return num 
    }
}
~~~

### 해결코드
+ 매개변수 num1, num2를 받아 % 나머지 연산을 리턴으로 반환
