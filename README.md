# 스터디 과정 소개
삼성전자에서 상시SW 코딩테스트를 진행하며 A형(or A+)을 취득하면 B형(pro등급) 시험을 볼 수 있는 기회가 생긴다. Pro등급에서는 C/C++/JAVA(파이썬은 응시 불가능하다) malloc.h를 제외한 라이브러리 사용이 불가능하다. 자료구조를 구현하고 응용하는 것이 Pro등급을 취득하는데 핵심이다.

# 진행 사항
각 주차마다 해당하는 문제 폴더들이 있다. 문제를 풀고 알고리즘이나 자료구조와 본인의 이름을 붙여 git에 push하면 된다.
ex) 1주차)Hash_Jiyoung.cpp, 2주차)Hash_unionfind_Jiyoung.cpp

# 기본으로 구현할줄 알아야 되는 자료구조
시험보면서 필요한 최소한의 기초 지식은 다음과 같다.
1. 스택
2. 큐
3. 소트(quick, merge, heap)
4. 트라이
5. 유니온파인드
6. 이분탐색

# 핵심
* 해시(정적리스트 사용)
>Pro등급의 핵심은 속도이다. A형과 다르게 B형부터는 절대평가에서 상대평가로 바뀌기 때문에 속도를 빠르게 하는게 굉장히 중요하다. 그렇기 때문에 정적리스트를 활용하여 미리 정적으로 배열을 선언해놓는게 malloc를 사용하는 것보다 5배이상 빠르다.

# 각 주차별 문제
PRO형은 자료구조를 복잡하고 많이 쓰는 문제를 직접 만들거나 풀어보는게 가장 중요하다. 문제를 풀면서 주의할 점은 1시간안에 최적의 설계를 하고 코드로 들어가는게 중요하다.
무작정 설계없이 코드부터 작성하는 것은 엄청난 실력자가 아니면 불가능하다. B형에서는 시간복잡도를 고려할 필요는 없고 O(N^2)처럼 무식하게 설계만 안하면 된다.
어째든 1시간 내에 설계를 끝내고 2시간동안 설계한대로 코드를 짜고 나머지 1시간을 테스트케이스를 맞춰보면서 디버깅하는 것이 가장 이상적이다.

   1주차) : DB 문제

   2주차) : 도서 추천 서비스 문제

   3주차) : 엑셀 문제

# 문제 추천
1) [홍준이의 사전놀이](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV_6pTXqsXUDFAWS&) : 해시나 트라이로 풀 수 있으며 B형 문제처럼 구성되있고 STL을 사용하면 제출이 되지 않는다.
2) [카드 정렬하기](https://www.acmicpc.net/problem/1715) : STL 사용없이 힙을 직접 구현해본다.
3) [생태학](https://www.acmicpc.net/problem/4358) : 해시나 트라이로 풀 수 있으며 해시로 풀면 정렬까지 해야된다.
4) [듣보잡](https://www.acmicpc.net/problem/1764) : 해시나 트라이로 푼다.
5) [블록부품맞추기](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV4szU-qXKYDFAUf) : C형 예제라 그런지 많이 어렵다. 비트마스크, 큐, 해시 등 다양한 방법으로 풀 수 있으며 해시가 가장 빠르다.
6) [친구 네트워크](https://www.acmicpc.net/problem/4195) : 해시 + 유니온파인드 응용
7) [문자열 잘라내기](https://www.acmicpc.net/problem/2866) : 해시 + 이분탐색 응용
8) [수 찾기](https://www.acmicpc.net/problem/1920) : 해시 or 이분탐색
9) [회사에 있는 사람](https://www.acmicpc.net/problem/7785) : 해시나 트라이로 푼다.
10) [(카카오 3차)자동완성](https://programmers.co.kr/learn/courses/30/lessons/17685) : 단순 트라이 구현
