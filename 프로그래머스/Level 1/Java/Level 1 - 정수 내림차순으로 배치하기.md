
## 정수 내림차순으로 배치하기

### 문제설명
> 함수 solution은 정수 n을 매개변수로 입력받습니다. n의 각 자릿수를 큰것부터 작은 순으로 정렬한 새로운 정수를 리턴해주세요. 예를들어 n이 118372면 873211을 리턴하면 됩니다.
### 제한사항
+ n은 1이상 8000000000 이하인 자연수입니다.


### 코드 작성
~~~
import java.util.*;
 
class Solution {
  public long solution(long n) {
        String[] list = String.valueOf(n).split("");
        Arrays.sort(list);
 
        StringBuilder sb = new StringBuilder();
        for (String aList : list) sb.append(aList);
 
        return Long.parseLong(sb.reverse().toString());
  }
}
~~~

### 해결코드
+ long n 값을 매개변수로 받기 
+ String.valueOf() 메소드통해서 문자열 변환 후 split("") 메소드 통해서 공백 제거
+ StringBuilder 통해서 문자열 데이터 담아서 reverse().toString() 역 정렬시키기
+ Long.parseLong() 메소드 통해서 Long 타입으로 변환하기

