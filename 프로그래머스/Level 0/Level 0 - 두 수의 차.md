
## 두수의 차

### 문제설명
> 정수 num1과 num2가 주어질 때, num1과 num2의 뺀 값을 return하도록 soltuion 함수를 완성해주세요.

### 제한사항
+ -50000 ≤ num1 ≤ 50000
+ -50000 ≤ num2 ≤ 50000

### 코드 작성
~~~
class Solution {
    fun solution(num1: Int, num2: Int): Int {
        var answer: Int = 0
        answer = num1 - num2
        return answer
    }
}
~~~

### 해결코드
+ 매개변수 num1, num2를 받아 값을 빼서 결과 값을 리턴으로 반환

