# Programmers_python
## 2021-06-25 금요일 

프로그래머스에서 처음 해봄. 분명 쉬운 것 같은데 아무것도 되지 않는다. 이번 방학 때 파이썬으로 계속 공부해볼 생각이다

:hash_1 // 프로그래머스 

## 2021-06-26 토요일

여기서는 lambda 함수가 많이 사용된다. 이것을 특히 더 잘 알 수 있도록 다음에 관련해서 정보를 적어보겠다

++lambda를 사용할 때는 List나 map을 같이 사용한다. lambda x : x +10 이라고 하면 무명의 함수를 만들어내는 것이다. 앞에 a = 을 붙여주면 def를 통해서 method를 만든 것처럼

똑같이 함수를 생성할 수 있는 것이다. 즉 위의 예시에서는 a(10)을 하면 20이 return 되는 것을 볼 수 있다. *2021-06-29

## 2021-06-28 월요일

이번에 푼 것은 프로그래머스에서 소수 만들기이다. 이 코드를 작성할 때 제일 어려웠던 부분은 combination을 짜는 부분이었다. 결국 import를 해서 combination을 표현했다.

from itertools import combinations 를 이용하였고 사용할 때는 list(combinations(list 이름, 뽑아낼 원소의 개수)) 로 해주면 된다.

## 2021-06-29 화요일

1. 문제 내용은 어렵지 않았다. 두 개의 list가 주어졌을 때 내적을 구하는 것이다. for 구문을 이용해서 각각의 원소끼리 곱해서 총 합을 구해주면 되는 것이다. 하지만 여기에서의 키워드는 zip 이다.

zip(a,b) 를 하면 각 list에서의 같은 자리의 원소끼리 zip이 되는 것을 볼 수 있다. 

2. 가운데 문자 가져오기 

이 부분은 코딩에서 보는 것이 아니라 수학적인 방법으로 해결하는 것이 더 좋은 것 같다. 근데 점수가 1 주는 것을 보니 그냥 쉬운 문제였나보다.

## 2021-07-01 목요일

1. 로또 최고 최하 예상하기 그닥 어렵지 않은 문제였다. 그저 if와 for 만 잘 쓰면 되는 문제

그중에서 내가 가져올 수 있는 method는 count 정도라고 생각한다. 이것도 그다지 어렵지는 않았는데 점수를 11점이나 줬다. 1점 주는 거라 뭔 차이가 있는 거지.

## 2021-07-02 금요일
오늘 또 하루 안합니다.. 뭐하는 아이 였을까

## 2021-07-03 토요일

1. 키패드 누르기

이것은 내가 생각보다 어렵게 생각했다. 분명 무엇인가 필요한 부분이 있을텐데 그것을 못 찾는 것 같은 기분이었다.

하지만 오히려 for 과 if를 이용해서 쉽게 할 수 있고, abs를 이용해 위치를 찾는 것이 다른 사람의 풀이보다 더 나은 것 같다.


## 2021-07-05 월요일

운동복을 도둑 맞았을 때 최대로 많은 학생들이 운동복을 입고 수업을 할 수 있는 경우

이 문제 같은 경우 greedy라고 써있었다. 탐욕 탐색 방법을 뜻한다. 해당 설명은 링크를 걸어두겠다

https://namu.wiki/w/%EA%B7%B8%EB%A6%AC%EB%94%94%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98

하지만 모범 답안으로 적어둔 것은 딱히 greedy algorithm 이라기 보다는 그냥 수학적 관점으로 바라보는 것인 것으로 생각된다.

## 2021-07-06 화요일
십진수를 3진수로 바꿨다가 돌려서 그걸 다시 십진수로 고치기 level1_9

풀 때도 당연히 쉬웠지만 method를 안다면 더욱 쉬운 내용이었음

int(tmp,3) 이게 무엇인지 아는가. tmp가 숫자로 이루어진 str 이라고 하자. 그러면 int(tmp,3)은 tmp를 십진수로 보고 3진수로 나타내주는 method이다.

그리고 지금 나는 하루에 하나씩 하고 있는데 학교에서 올려준건 20일 기준 200개라고 한다. 흠

## 2021-07-07 수요일

숫자 2개 뽑아서 더하기

벌써 수요일이네 생각보다 시간이 엄청 빨리간다. 그래도 나름 잔디 채우기 용으로 꾸준히 하려고 하고 있으니 다행이다.

여기에서 주로 사용한 method 는 from itertools import combinations, set, [x+y for x,y in temp] 등이다. 간단하게 코딩할 때 유용한 method들이다.

이제 2번 반복했으니 계속해서 반복하다보면 조금 더 쉽게 다가갈 수 있을 것 같다.

## 2021-07-08 목요일

실패율 계산하기

그냥 문제푸는 것은 그렇게 어렵지 않았다 하지만 파이썬 특성 상 시간이 좀 걸린다는 것을 간과했다. 

level1_11을 보면 get을 사용하는 것이 나오는 데 다시 확인을 해보겠다. 일단 링크는 관련 링크는 걸어둔다. 

https://wikidocs.net/16

보니 dictionary에 관련된 것이었다.
