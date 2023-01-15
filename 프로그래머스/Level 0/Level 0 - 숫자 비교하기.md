
## 숫자 비교하기

### 문제설명
> 정수 num1과 num2가 매개변수로 주어집니다. 두 수가 같으면 1 다르면 -1을 retrun하도록 solution 함수를 완성해주세요.

### 제한사항
+ 0 ≤ num1 ≤ 10,000
+ 0 ≤ num2 ≤ 10,000

### 플로우차트 순서도
<img width="459" alt="image" src="https://user-images.githubusercontent.com/58936137/212534946-44bf3c5a-f894-4a89-8176-4cc14a5ae7bd.png">


### 코드 작성
~~~
class Solution {
    fun solution(num1: Int, num2: Int): Int {
        var answer: Int = 0
        if(num1 == num2) answer = 1 else answer = -1 
        
        return answer
    }
}
~~~

### 해결코드
+ 매개변수 num1, num2를 받아 숫자를 비교하여 true 경우 1 false 경우 -1 return 반환

