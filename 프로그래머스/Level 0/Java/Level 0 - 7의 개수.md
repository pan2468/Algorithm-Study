
## 7의 개수

### 문제설명
> 머쓱이는 행운의 숫자 7을 가장 좋아합니다. 정수 배열 array가 매개변수로 주어질 때, 7이 총 몇 개 있는지 return 하도록 solution 함수를 완성해보세요.

### 제한사항
+ 1 ≤ array의 길이 ≤ 100
+ 0 ≤ array의 원소 ≤ 100,000


### 코드 작성
~~~
import java.util.*;

class Solution{
    public int solution(int[] array){
       int answer = 0;
       String str = Arrays.toString(array);
       for(int i = 0; i < str.length(); i++){
            if(str.charAt(i) == '7'){
                answer++;
            }
       }
       return answer;
    }
}
~~~

### 해결코드
+ 매개변수 array 배열 값을 Arrays.toString() String 타입 강제 형변환하여 str 변수에 담습니다.
+ for문으로 str변수에 담아져 있는 array 값을 루프로 반복합니다. 
+ charAt() 함수를 사용하여 해당 문자열 7과 같은 값을 비교하여 answer++ 증가시킵니다.  


