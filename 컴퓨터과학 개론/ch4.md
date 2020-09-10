# 자료구조 (2)

## 트리 용어 정의

비선형 자료구조
* Node
* Branch(Edge)
* Rioot
* Degree
* Level
* Leaf node
* internal node
* ancestor node
* descendant node
* sub tree
* forest

## 이진 트리

binary tree

### 순회 연산
* DLR(ROOT-LEFT-RIGHT) 전위 순회 preorder
* LDR(LEFT-ROOT-RIGHT) 중위 순회 inorder
* LRD(LEFT-RIGHT-ROOT) 후위 순회 postorder

### 포화 이진 트리
full binary tree

### 완전 이진 트리
complete binary tree

### 경사 이진 트리
skewed binary tree

## 그래프
Vertex, Edge
`G = (V, E)`
인접한다(adjacent) : 정점 간의 관계
부수되었다(incident) : 정점과 간선 간의 관계
사이클(cycle) : 
단순 사이클(simple cycle) : 
두 정점이 서로 연결됨
그래프가 서로 연결됨
강하게 연결 됨
약하게 연결 됨
### 방향 그래프
directed graph, digraph
* 진입 차수
* 진출 차수

### 무방향 그래프
undirected graph


## 그래프의 표현

인접 행렬
인접 리스트

### 그래프의 탐색

### DepthFS 깊이 우선 탐색
### BreadthFS 너비 우선 탐색