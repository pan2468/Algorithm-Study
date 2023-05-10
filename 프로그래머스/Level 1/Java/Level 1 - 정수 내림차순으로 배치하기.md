
## 핸드폰 번호 가리기

### 문제설명
> 프로그래머스 모바일은 개인정보 보호를 위해 고지서를 보낼 때 고객들의 전화번호의 일부를 가립니다.
전화번호가 문자열 phone_number로 주어졌을 때, 전화번호의 뒷 4자리를 제외한 나머지 숫자를 전부 *으로 가린 문자열을 리턴하는 함수, solution을 완성해주세요.

### 제한사항
+ phone_number는 길이 4 이상, 20이하인 문자열입니다.


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
+ 매개변수 phone_number String 값을 length 통해서 - 4 자르기 
+ substring 메소드를 통해서 시작 값부터 마지막 값까지 출력하여 return 하 


