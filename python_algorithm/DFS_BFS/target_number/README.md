# 문제 설명
- n개의 음이 아닌 정수가 있습니다. 이 수를 적절히 더하거나 빼서 타겟 넘버를 만들려고 합니다. 예를 들어 [1, 1, 1, 1, 1]로 숫자 3을 만들려면 다음 다섯 방법을 쓸 수 있습니다.

- 사용할 수 있는 숫자가 담긴 배열 numbers, 타겟 넘버 target이 매개변수로 주어질 때 숫자를 적절히 더하고 빼서 타겟 넘버를 만드는 방법의 수를 return 하도록 solution 함수를 작성해주세요.

# 문제 분석

1. 숫자를 적절히 더하고 뺀다. -> +, - 밖에 없음
2. 다음수를 더해야 하는지 빼야 하는지를 정한다. => 더한 값과 뺀 값을 모두 탐색한다.
3. 더한 수를 다음 dfs에 넣어준다.

# 파이썬에서의 전역변수 사용
- 전역으로 선언한 이후에 일반 함수내에서 사용하고 싶다면 global 키워드를 사용해 전역변수임을 명시해 준다.
- dfs의 핵심은 끝까지 들어간다, 모든 곳을 탐색한다, 이렇게 두가지 이다.
- 처음 문제를 만났을 때, 어떤 문제인지를 파악하고 문제를 풀 수 있도록 하자.