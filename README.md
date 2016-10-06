인공지능수업 과제1

탐색(8-puzzle) 프로그래밍 : DFS(깊이우선탐색)

* input
	- in.txt: 8-puzzle 초기상태 (빈 공간은 0으로)
	- g.txt: 8-puzzle 목표상태 (빈 공간은 0으로)
* Output 
	- 초기상태에서 목표상태에 이르는 중간 과정의 8-puzzle 상태 리스트 또는 목표상태에 도달 불사능한 8-puzzle 상태리스트
	- 8-puzzle 상태에 평가함수 값 포함하여 출력

* * *

1st Try

Stack : linkedList 사용 

puzzle : int[9]

평가함수f : int

---

	