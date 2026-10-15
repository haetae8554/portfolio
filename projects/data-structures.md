# C++ 자료구조 학습

[전체 프로젝트로 돌아가기](../README.md)

수업 과제에서 제공된 저장소를 fork한 학습 프로젝트입니다. 아래 내용은 저장소에서 확인한 파일·함수 구성으로, 모든 코드를 독자 작성했다는 의미는 아닙니다. 제공 코드와 추가 구현의 차이 및 실행 결과는 별도 정리가 필요합니다.

<a id="graph"></a>

## 그래프 표현과 알고리즘

[내 저장소](https://github.com/haetae8554/2025_Kwangwoon_DS_Project_3) · [fork 원본](https://github.com/KimTaegwan03/2025_Kwangwoon_DS_Project_3)

**학습 주제:** 서로 다른 그래프 표현과 탐색·경로 알고리즘을 C++로 다루기.

- `ListGraph`와 `MatrixGraph`: 인접 리스트와 인접 행렬 표현
- `GraphMethod.cpp`: BFS, DFS, Kruskal, Dijkstra, Bellmanford, FLOYD, Centrality 함수
- `Manager`와 명령 파일: 입력 명령과 알고리즘 실행 흐름

포트폴리오를 보완할 때는 하나의 그래프를 두 표현으로 처리하는 예제, 최단 경로 알고리즘의 적용 조건, 직접 추가한 코드의 커밋과 테스트 결과를 정리합니다.

<a id="trees"></a>

## B+ Tree · Heap · Selection Tree

[내 저장소](https://github.com/haetae8554/2025_Kwangwoon_DS_Project_2) · [fork 원본](https://github.com/evejaeyong/2025_Kwangwoon_DS_Project_2)

**학습 주제:** 목적이 다른 자료구조를 연결해 데이터를 관리하기.

- `BpTree.cpp`: 삽입, 데이터·인덱스 노드 분할, 범위 검색, 노드 해제 함수
- `EmployeeHeap`: Heap 관련 구현 파일
- `SelectionTree`: Selection Tree 관련 구현 파일
- `Manager`: 입력 명령 처리와 자료구조 연결

포트폴리오를 보완할 때는 노드 분할 전후 그림, 범위 검색 예시, 자료구조 선택 이유와 직접 작성한 부분을 정리합니다. 이번 정리에서는 실행·메모리 검사 결과를 새로 측정하지 않았습니다.
