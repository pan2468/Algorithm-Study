## 길이에 따른 연산

### 문제설명
> 정수가 담긴 리스트 num_list가 주어질 때, 리스트의 길이가 11 이상이면 리스트에 있는 모든 원소의 합을 10 이하이면 모든 원소의 곱을 return하도록 solution 함수를 완성해주세요.

### 제한사항
+ 2 ≤ num_list의 길이 ≤ 20
+ 1 ≤ num_list의 원소 ≤ 9


### 코드 작성
~~~
class Solution {
    public int solution(int[] num_list) {
        int answer = 1;

        for (int i=0; i<num_list.length; i++) {
            if (num_list.length >= 11) {
                answer += num_list[i];
            } else {
                answer *= num_list[i];
            }
        }

        if (num_list.length >= 11) answer--;

        return answer;
    }
}
~~~

### 해결코드
+ num_list 매개변수 값을 받아 길이가 10이하 일경우 answer 변수 통해서 곱하기
