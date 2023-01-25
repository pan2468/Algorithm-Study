
## 가장 큰 수 찿기

### 문제설명
> 정수 배열 array가 매개변수로 주어질 때, 가장 큰 수와 그 수의 인덱스를 담은 배열을 return 하도록 solution 함수를 완성해보세요.

### 제한사항
+ 1 ≤ array의 길이 ≤ 100
+ 0 ≤ array 원소 ≤ 1,000
+ array에 중복된 숫자는 없습니다.


### 코드 작성
~~~
class Solution {
    fun solution(array: IntArray): IntArray {       
        return intArrayOf(array.maxOf{ it }, array.indexOf(array.maxOf{ it }) )
    }
}
~~~

### 해결코드
+ array 배열 값을 받아 가장 큰 값 maxOf() 함수와, 몇번째 인덱스 인지 위치를 찿기 위해서 indexOf() 함수 사용하여 리턴으로 반환


