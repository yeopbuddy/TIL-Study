# 문제 사이트
BAEKJOON ONLINE JUDGE


# 문제 요약
1. 문제 난이도 : GOLD 4
2. 알고리즘 분류 : BFS
3. 문제 내용 : 이모티콘 복사, 붙여넣기, 삭제 연산을 통해 최단 시간에 정해진 개수의 이모티콘을 만든다.

# 구현 로직
1. 이모티콘을 복사하는 경우, 붙여넣기 하는 경우, 삭제하는 경우에 대해서 모두 탐색을 기록하며 수행한다.
2. 현재 화면에 같은 개수의 이모티콘이 있고, 클립보드에도 같은 수의 이모티콘이 있는 경우는 탐색하지 않는다(BFS이므로 더 빠른 시간에 이미 탐색함).
3. 정해진 개수의 이모티콘이 만들어진 경우가 바로 최단 시간이므로 출력하고 종료한다.

# 고찰
- 복사/붙여넣기를 하나의 동작으로 정의했다가,, 낭패봤던 문제..
