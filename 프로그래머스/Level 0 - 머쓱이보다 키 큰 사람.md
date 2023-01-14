## 머쓱이보다 키 큰 사람

### 문제설명
> 머쓱이는 학교에서 키 순으로 줄을 설 때 몇 번째로 서야 하는지 궁금해졌습니다.
> 머쓱이네 반 친구들의 키가 담긴 정수 배열 array와 머쓱이의 키 height가 매개변수로 주어질 때, 머쓱이보다 키 큰 사람 수를 return 하도록 solution 함수를 완성해보세요.


### 제한사항
+ 1 ≤ array의 길이 ≤ 100
+ 1 ≤ height ≤ 200
+ 1 ≤ array의 원소 ≤ 200


### 플로우 차트 순서도 
<img width="493" alt="image" src="https://user-images.githubusercontent.com/58936137/212462333-e591b575-6e02-4db7-bd06-96cbfd4dfd1f.png">


### 해결 코드
+ count() 메소드를 사용하여 매개변수에 주어진 array 보다 작은 값을 조건에 만족하여 리턴으로 반환
