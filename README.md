# python-codingtest-2023
파이썬 코딩테스트 리포지토리

## 1일차
1. 코딩테스트 소개
2. 코딩테스트 학습
    - [x] 자료구조 - 배열/리스트
    - [x] 구간 합

## 2일차
! 파이썬 파일명에는 '_'만 사용하자.
1. 코딩테스트 학습
    - [x] 구간 합 2
    - 자료구조
        - [x] 연결리스트
        - [x] 스택
        - [x] pythonds 스택

## 3일차
1. 코딩테스트 학습
    - 자료구조
        - [x] 큐
        - [x] pythonds 큐
        - [x] 이진 트리
            - 삭제는 연결리스트 삭제와 유사
        - [x] 그래프

## 4일차
1. 코딩테스트 학습        
    - 자료구조
        - [x] 그래프
        - [x] 재귀호출
        - [x] 정렬

## 5일차
1. 코딩테스트 학습
    - 자료구조 / 알고리즘
        - [x] 정렬
        - [x] 검색
        - [x] 다이나믹 프로그래밍

## 6일차
1. 코딩테스트 학습
    - 자료구조
        - [x] deque

    - 알고리즘
        - [x] 투포인터
        - [x] 슬라이딩윈도우
        - [x] 정렬

```python
# 백준 2750 - 수 정렬하기
N = int(input())
A = [0] * N

for i in range(N):
    A[i] = int(input())

for i in range(N-1):
    for j in range(N-1-i):
        if A[j] > A[j+1]:
            A[j], A[j+1] = A[j+1], A[j]

for i in range(N):
    print(A[i])
```

## 7일차
1. 코딩테스트 학습
    - 자료구조
        - [x] 그래프
        - [x] PrioriyQueue (우선순위 큐)
        - [x] heapq (힙큐)


    - 알고리즘
        - [x] 탐색 - DFS / BFS / 이진탐색
        - [ ] 그리디
        - [ ] 정수론

## 8일차
1. 코딩테스트 학습
    - 자료구조
    - 알고리즘
        - [ ] 정수론
        - [ ] 그래프 활용
        