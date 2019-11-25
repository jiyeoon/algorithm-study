---
layout: default
---

모든 경우에 있어서 항상 우월한 성능을 보이는 자료구조와 알고리즘은 없다. 그래서 자료구조와 알고리즘을 분석하고 평가할 수 있어야 한다.


## 알고리즘이란?

> Algorithm is a series of contained steps which you follow in order to achieve some goal, or to produce some output.

알고리즘은 어떤 목적을 달성하거나 결과물을 만들어내기 위해 거쳐야 하는 일련의 과정들을 의미



## 알고리즘 성능 분석의 주된 요소

1. 공간 복잡도 (Space Complexity) : 알고리즘에 사용되는 메모리 공간의 총량
2. 시간 복잡도 (Time Complexity) : 알고리즘에 사용되는 연산 횟수의 총량

=> 즉,  공간 복잡도는 메모리 사용량에 대한 분석 결과이고 시간 복잡도는 속도에 대한 분석 결과이다.

---

## Big-O 표기란?

> Big-O notation is a way of converting the overall steps of an algorithm into algebraic terms, then excluding lower order constants and coefficients that don't have that big an impact on the overall complexity of the problem.


## 대표적인 시간 복잡도

1. O(1) : 상수 시간 - 입력값 n이 주어졌을 때, 알고리즘이 문제를 해결하는데 오직 한 단계만 거침.
2. O(log n) : 로그 시간 - 입력값 n이 주어졌을 때, 문제를 해결하는데 필요한 단계들이 연산마다 특정 요인에 의해 줄어듭니다.
3. O(n) : 직선적 시간 - 문제를 해결하기 위한 단계의 수와 입력값 n이 1:1 관계를 가집니다.
4. O(n^2) : 2차 시간 - 지수를 해결하기 위한 단계의 수는 입력값 n의 제곱
5. O(C^n) : 지수 시간 - 문제를 해결하기 위한 단계의 수는 주어진 상수값 C의 n제곱 입니다.


### Reference

[https://joshuajangblog.wordpress.com/2016/09/21/time_complexity_big_o_in_easy_explanation/](https://joshuajangblog.wordpress.com/2016/09/21/time_complexity_big_o_in_easy_explanation/)