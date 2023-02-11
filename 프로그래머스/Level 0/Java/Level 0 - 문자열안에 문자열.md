
## 두수의 곱

### 문제설명
> 문자열 str1, str2가 매개변수로 주어집니다. str1 안에 str2가 있다면 1을 없다면 2를 return하도록 solution 함수를 완성해주세요.

### 제한사항
+ 1 ≤ str1의 길이 ≤ 100
+ 1 ≤ str2의 길이 ≤ 100
+ 문자열은 알파벳 대문자, 소문자, 숫자로 구성되어 있


### 코드 작성
~~~
class Solution {
    public int solution(String str1, String str2) {
        int answer = 0;
        if(str1.contains(str2)){
            answer = 1;
        }else{
            answer = 2;
        }
        
        return answer;
    }
}
~~~

### 해결코드
+ 매개변수 str2 변수가 값이 str1 문자열 안에 있는지 확인하기 위해 contains() 메소드 사용


