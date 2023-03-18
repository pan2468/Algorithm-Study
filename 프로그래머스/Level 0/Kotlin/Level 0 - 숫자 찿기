
## 숫자 찿기

### 문제설명
> 정수 num과 k가 매개변수로 주어질 때, num을 이루는 숫자 중에 k가 있으면 num의 그 숫자가 있는 자리 수를 return하고 없으면 -1을 return 하도록 solution 함수를 완성해보세요.

### 제한사항
+ 0 < num < 1,000,000
+ 0 ≤ k < 10
+ num에 k가 여러 개 있으면 가장 처음 나타나는 자리를 return 합니다.


### 코드 작성
~~~
class Solution {
    fun solution(num: Int, k: Int): Int {
        val result = num.toString().indexOf((k).toString())
        if(result == -1){
            return -1
        }else{
            return result + 1
        }       
    }
}
~~~

### 해결코드
+ 매개변수 num, k 값을 받습니다.
+ num 값을 toString() 문자열 강제 형변환합니다. 
+ k 매개변수 값도 toString() 문자열 강제 형변환합니다.
+ indexOf() 메소드를 통해서 몇번째 위치에 있는지 찿아 if문을 조건문을 통해서 return으로 반환합니다.


