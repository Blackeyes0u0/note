class P : 어떤 문제에 대해서 polynomial time algorithm 이 존재하는 그문제는 p

non -deterministic polynomial time : class NP

"어떤 certificate가 다항시간(Polynomial Time)에 verify할 수 있으면, 그 문제는 클래스 NP에 속합니다."

Polynomial Time Algorithm : n^k형태로 Worst time Complexity가 정의되는 알고리즘 (k는 상수.)

클래스 P : 어떤 문제에대해서 Polynomial Time Algorithm이 존재하면 그 문제는 클래스 P에 속합니다.

클래스 NP : 어떤 certificate가 다항시간(Polynomial Time)에 verify할 수 있으면, 그 문제는 클래스 NP에 속합니다. 또는 그 문제를 해결하는 Non-Deterministic Polynomial Time algorithm이 존재하면, 그 문제는 클래스 NP에 속합니다.
출처: https://zeddios.tistory.com/92?category=682196 [ZeddiOS:티스토리]



# NP -Hard

NP클래스 안에 있는 모든 문제가 어떤 문제(Q)로 reducible하면, 그 문제 Q는 NP-Hard이다. 
출처: https://zeddios.tistory.com/93?category=682196 [ZeddiOS:티스토리]

![image](https://user-images.githubusercontent.com/78690390/175808675-0e66fe78-f586-4367-bb5d-d25bd9f82466.png)
x 가 들어갑니다. x는 p라는문제의 인풋입니다ㅅㄹ
t라는 박스를 만나요 t는 transformation funcitonㅅㄱ
t는 들어온 인풋을 아웃풋하나 주는데 그것이 q의 인풋



# NP-Complete

NP-Hard이면서 NP클래스 안에 있으면 NP-Complete입니다.NP클래스에 속해있으면서, 어떤 기준에 의해 가장 어려운 문제이면 NP-Complete인거죠.
출처: https://zeddios.tistory.com/93?category=682196 [ZeddiOS:티스토리]
