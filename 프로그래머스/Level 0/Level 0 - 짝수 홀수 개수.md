
## 짝수 홀수 개수

### 문제설명
> 정수가 담긴 리스트 num_list가 주어질 때, num_list의 원소 중 짝수와 홀수의 개수를 담은 배열을 return 하도록 solution 함수를 완성해보세요.

### 제한사항
+ 1 ≤ num_list의 길이 ≤ 100
+ 0 ≤ num_list의 원소 ≤ 1,000


### 코드 작성
~~~
class Solution {
    fun solution(num_list: IntArray): IntArray {
        return intArrayOf(num_list.count { it % 2 == 0}, num_list.count { it % 2 != 0})
    }
}
~~~

### 해결코드
+ 매개변수 num_list 배열 값을 받아 짝수, 홀수 값을 count() 함수 통해서 리턴으로 반환


