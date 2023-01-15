
## 두수의 합

### 문제설명
> 정수 num1과 num2가 주어질 때, num1과 num2의 합을 return하도록 soltuion 함수를 완성해주세요.

### 제한사항
+ -50,000 ≤ num1 ≤ 50,000
+ -50,000 ≤ num2 ≤ 50,000

### 플로우차트 순서도
<img width="383" alt="image" src="https://user-images.githubusercontent.com/58936137/212525916-21afb778-b1e0-45e8-9bc1-cb4428db6faa.png">

### 코드 작성
~~~
class Solution {
    fun solution(num1: Int, num2: Int): Int {
        var answer: Int = -1
        answer = num1 + num2 
        
        return answer
    }
}
~~~

### 해결코드
+ 매개변수 num1, num2를 받아 더하기를 하여 결과 값을 리턴으로 반환

