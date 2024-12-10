TicTacToe
=========
![image](https://github.com/user-attachments/assets/3b707ff1-7052-4530-b677-9085849d6cc0)

Game()   
초기 상태   
history = [[null, null, null, null, null, null, null, null, null]]   
currentMove = 0   
xIsNext = true   
currentSquares=[null, null, null, null, null, null, null, null, null]   

move는 0부터 시작   
Go to game start버튼을 return   
   
   
4번을 클릭하면 handleClick(4)이 실행   
4번째 칸이 X로 바뀜   
onPlay; handlePlay   
nextHistory에 nextSquares를 복사하여 뒤에 붙임   
History 변경   
currentMove를 1로 변경   
xIsNext값도 최신 currentMove값을 기반으로 false가 됨.   
   
React는 상태 변화(setState)를 통해 자동으로 리렌더링하고, 그에 따라 UI를 업데이트합니다.   

추가로 몇번째 순서에 있는지 표시하고, 승리 조건 버튼을 강조함.
