# 문제 분석
- 이차원 배열 moves가 매개변수로 주어지고 격자의 상태가 담긴 2차원 배열 board
- 크레인을 모두 작동시킨 후 터트려져 사라진 인형의 개수를 return
- moves는 열 정보
- 처음엔 1열이니까 1열에서 처음으로 0이 아닌 것을 stack에 push, 그리고 해당 정보를 0으로 바꾼다.
- stack에 같은 것이 2개 쌓이면 2개를 스택에서 빼고 터진 인형에 2를 추가한다. 
    
# 배열 순회할 때 
- for (const item of items) <= 이런 방식으로 순회
