# DFS & BFS

## 자구 기초 : 스택 & 큐
- 스택 : 파이썬 기본리스트 사용
- 큐 : deque 모듈 사용
```
from collections import deque
q = deque()

q.append(1)
q.append(2)
q.append(3)
q.popleft()
```

## 재귀함수
=> 종료조건 명시해줄것!!!  

## 그래프표현
array vs linked list 소스코드 참고.  

## DFS & BFS
![그래프](./그래프.png)
- DFS : 1 2 7 6 8 3 4 5 with Stack & 재귀
- BFS : 1 2 3 8 7 4 5 6 with Queue
- 구현준비물 : 그래프, 방문리스트, 함수
- 많이 풀면서 익숙해지자!