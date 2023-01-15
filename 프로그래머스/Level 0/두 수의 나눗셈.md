
## 두 수의 나눗셈

### 문제설명
> 정수 num1과 num2가 매개변수로 주어질 때, num1을 num2로 나눈 값에 1,000을 곱한 후 정수 부분을 return 하도록 soltuion 함수를 완성해주세요.

### 제한사항
+ 0 < num1 ≤ 100
+ 0 < num2 ≤ 100



### 코드 작성
~~~
class Solution {
    fun solution(num1: Int, num2: Int): Int {
        var answer: Double = num1.toDouble() / num2.toDouble() * 1000
        return answer.toInt()
    }
}
~~~

### 해결코드
+ 매개변수 num1, num2를 받아 값을 나눈 후 1000을 곱하여 toInt() 강제 형변환을 주어 리턴으로 반환 

