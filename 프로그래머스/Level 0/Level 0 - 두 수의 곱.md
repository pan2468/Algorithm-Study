
## 두수의 곱

### 문제설명
> 정수 num1과 num2가 주어질 때, num1과 num2의 곱한 결과 값을 return하도록 soltuion 함수를 완성해주세요.

### 제한사항
+ 0 ≤ num1 ≤ 100
+ 0 ≤ num2 ≤ 100

### 플로우차트 순서도
<img width="363" alt="image" src="https://user-images.githubusercontent.com/58936137/212528269-928d3e99-e69b-443c-9069-26018a425640.png">

### 코드 작성
~~~
class Solution {
    fun solution(num1: Int, num2: Int): Int {
        var answer: Int = 0
        answer = num1 * num2
        return answer
    }
}
~~~

### 해결코드
+ 매개변수 num1, num2를 받아 곱한 결과 값을 리턴으로 반환


