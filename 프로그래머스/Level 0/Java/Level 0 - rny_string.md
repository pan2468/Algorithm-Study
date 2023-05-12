
## rny_string

### 문제설명
> 'm'과 "rn"이 모양이 비슷하게 생긴 점을 활용해 문자열에 장난을 하려고 합니다. 
문자열 rny_string이 주어질 때, rny_string의 모든 'm'을 "rn"으로 바꾼 문자열을 return 하는 solution 함수를 작성해 주세요.

### 제한사항
+ 1 ≤ rny_string의 길이 ≤ 100
+ rny_string은 영소문자로만 이루어져 있습니다.


### 코드 작성
~~~
class Solution {
    public String solution(String rny_string) {
        return rny_string.replace("m","rn").toString();
    }
}
~~~

### 해결코드
+ replace() 메소드 사용해서 문자열 변경 후 toString() 통해서 리턴

