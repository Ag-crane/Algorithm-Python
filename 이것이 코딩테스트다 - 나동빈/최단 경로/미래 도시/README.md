### 미래도시
- 방문 판매원 A는 1번 회사에서 출발, K번 회사를 들려 X번 회사로 가려고 한다.
- 두 회사간 도로가 있다면 1만큼의 시간으로, 양방향으로 이동할 수 있다.
- 회사간 도로 정보가 주어질 때, 최단 거리를 구하는 프로그램을 작성하시오.


---
    입력 조건
        첫째줄 - 회사의 개수 N : 1~100, 경로의 개수 M : 1~100
        둘째줄부터 M+1번째 줄 - 연결된 두 회사의 번호가 공백으로 구분되어 주어진다.
        M+2번째 줄 - X, K : 1~100

    출력 조건
        A가 K번 회사를 거쳐 X번 회사로 가는 최소 이동 시간을 출력한다.
        X번 회사에 도달할 수 없다면 -1을 출력한다.

##### 입력 예시 1
    5 7
    1 2
    1 3
    1 4
    2 4
    3 4
    3 5
    4 5
    4 5
##### 출력 예시 1
    3
##### 입력 예시 2
    4 2
    1 3
    2 4
    3 4
##### 출력 예시 2
    -1    