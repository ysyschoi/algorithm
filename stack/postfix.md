# 후위 postfix

보통 수학에서 사용하는 중위표기식  
 컴퓨터에서는 순차 처리 하기 때문에
연산 순서를 고려하기 힘들다.
-> 후위 표기식으로 만들기

식은 1~9의 숫자와, + - \* / ( )로 이루어져있다.

후위 표기식이란?
연산자가 나오면, 그 앞의 두 숫자를 연산처리해주는 것이다.

예를 들어서
3 + 5 * 2 / (7-2)
5*2 먼저 해주고 7-2 빼서 나눠줘야하고 그다음에 3 더해줘야한다.

1.  3 5 2 \* 7 2 - / +
2.  3 10 5 / +
3.  3 2 +
4.  5

중위식을 후위식으로 바꾸는 것도 스택 필요
후위식 연산하는 것도 스택 필요하다.!!