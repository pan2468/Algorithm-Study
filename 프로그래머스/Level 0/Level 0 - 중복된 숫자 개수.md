
## 중복된 숫자 개수

### 문제설명
> 정수가 담긴 배열 array와 정수 n이 매개변수로 주어질 때, array와 n이 몇 개 있는 지를 return 하도록 solution 함수를 완성해 보세요.

### 제한사항
+ 1 ≤ array의 길이 ≤ 100
+ 0 ≤ array의 원소 ≤ 1,000
+ 0 ≤ n ≤ 1,000

### 플로우차트 순서도
<img width="350px" src="https://user-images.githubusercontent.com/58936137/212205091-7643233b-d9f9-4b41-bab0-fc97f572f288.png">

### 코드 작성
~~~
class Solution {
    fun solution(array: IntArray, n: Int): Int {
        return array.count{ it == n }
    }
}
~~~

### 해결원인
+ count() 메소드를 사용하여 조건에 만족하는 원소들을 리턴으로 반환
