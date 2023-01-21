## 옷 가게 할인 받기 

### 문제설명
> 머쓱이네 옷가게는 10만 원 이상 사면 5%, 30만 원 이상 사면 10%, 50만 원 이상 사면 20%를 할인해줍니다.
구매한 옷의 가격 price가 주어질 때, 지불해야 할 금액을 return 하도록 solution 함수를 완성해보세요.

### 제한사항
+ 10 ≤ price ≤ 1,000,000
+ price는 10원 단위로(1의 자리가 0) 주어집니다.
+ 소수점 이하를 버린 정수를 return합니다.

### 플로우차트 순서도
<img width="555" alt="image" src="https://user-images.githubusercontent.com/58936137/213847679-46f6ff6f-a79e-43ff-ab0a-96921a3080ed.png">


### 코드 작성
~~~
class Solution {
    fun solution(price: Int): Int = if (price >= 500000) {
        (price * 0.8).toInt()
    } else if (price >= 300000) {
        (price * 0.9).toInt()
    } else if (price >= 100000) {
        (price * 0.95).toInt()
    } else {
        price
    }
}
~~~

