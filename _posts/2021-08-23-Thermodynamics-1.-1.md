---
layout: post
title: '해봅시다, 열역학 _ 1. 1'
author: kwanghyuck.jung
comments: true
date: 2021-09-16 17:49
use_math: true
tags: [chemistry, thermodynamics]
---

## 해봅시다, 열역학 _ 1. 1

#### 1. 열역학은 무엇을 다루는가?

열역학에 대해 알아보기 위해서는 우선 열역학에서 무엇을 탐구하고 싶은 것인지 알 필요가 있겠죠.

탐구의 대상이 되는 그 무엇, 열의 출입이 발생하거나 물질의 출입이 발생할 수 있는 관심의 대상.

이것을 '**계**(system)'라고 부릅니다. 계는 항상 물질을 포함합니다. 그리고 뒤의 내용에서 언급하겠지만 계는 계의 상태를 나타내는 몇 가지 변수들로 표현됩니다. 여기에는 부피, 압력, 온도 등이 가능하겠지요. 

계를 둘러싼 나머지 부분을 '**주위**(surroundings)'라고 부릅니다. 

예컨대 물이 담긴 100ml 비커를 계라고 한다면, 그 비커를 주위한 모든 것 (비커를 받치고 있는 책상, 주변의 공기, 방, 우주 등등..)이 주위가 됩니다.

계와 주위를 합친 전체 부분을 **우주**라고 합니다. 정확히 하자면 **열역학적 우주(thermodynamic universe)**입니다. 

![Figure 1](https://user-images.githubusercontent.com/88145508/133581807-ec9e9513-524b-4a8f-8eb8-fec952aedeb9.jpg)

---

#### 2. 계의 세 가지 분류

계는 계의 특성에 따라서 세 가지로 분류될 수 있습니다. **고립계, 열린계, 닫힌계**가 바로 그것입니다. 물질 교환과 에너지 교환이 모두 되지 않는 계는 **고립계**라고 합니다. 반대로 물질 교환과 에너지 교환이 모두 가능한 계는 **열린계**라고 합니다. 한편, 물질 교환은 불가능하지만 에너지 교환은 가능한 계를 **닫힌계**라고 합니다. 예시를 몇 가지 들면서 알아보겠습니다.

Q. 뜨거운 물을 안에 붓고 가만히 올려둔 보온병을 계라고 한다면, 보온병의 보온 효과가 완벽하다는 전제 하에 **닫혀 있는 **보온병은 닫힌계, 열린계, 고립계 중에 무엇일까요?

A. 고립계가 될 것입니다. 보온병은 열 등 에너지 출입이 불가능하고, '닫혀있다'고 했으니까 물질 교환이 안 되겠군요. 따라서 고립계입니다.

Q. 그렇다면 보온 효과가 없는 플라스틱 생수병에 따뜻한 물을 담아놓고 병뚜겅을 막는 뒤 실온에 올려놓는 상황을 가정해봅시다. 생수병을 계라고 한다면, 생수병은 닫힌계, 열린계, 고립계 중에 무엇일까요?

A. 닫힌계가 될 것입니다. 병뚜껑을 닫았으니 물이 병 밖으로 나갈 일은 없으므로 물질 교환은 되지 않는 반면에, 따뜻한 물과 상온의 공기 사이의 열 교환이 일어나면서 둘의 온도가 같아질 때까지 에너지 교환이 발생하겠군요. 따라서 물질 교환이 일어나지 않고 에너지 교환이 발생하는 고립계입니다.

Q. 마지막으로, 실온에 윗부분을 막지 않은 비커에 따뜻한 물을 부은 뒤 1기압이 작용하는 책상에 올려둔 상황을 생각해보겠습니다. 비커를 계라고 한다면, 이 계는 닫힌계, 열린계, 고립계 중에 무엇일까요?

A. 열린계가 될 것입니다. 물은 증발하면서 외부로 빠져나갈 것이고, 따뜻한 물과 실온의 공기가 열에너지를 교환하기에 물질 교환과 에너지 교환이 모두 일어나는군요. 따라서 열린계입니다.

![Figure 2](https://user-images.githubusercontent.com/88145508/133581820-b3195de8-c377-42ac-ab82-e6ee07a7850f.png)

그렇다면 **열역학적 우주는 고립계일까요?**

**네, 고립계가 맞습니다.** 열역학적 우주는 계와 주위를 포함한 전체를 말하기 때문에, 에너지 보존 법칙에 의해 에너지 출입이 없고, 물질의 교환도 없습니다. 따라서 고립계라고 할 수가 있겠네요.

---

#### 3. 계의 성질들과 성질들의 두 가지 분류

앞에서는 열역학의 대상이라고 할 수 있는 '계'를 다뤄보았습니다. 그렇다면 열역학은 '계'의 **무엇**을 다루는 것일까요? 바로 **계의 성질**을 다루는 것입니다. 계의 성질에는 무엇이 있을까요? 물론 다양한 것이 있을 것입니다. 비커에 담긴 물을 계라고 한다면, 온도나 질량, 부피가 가능할 것이고, 유리 상자 안에 차있는 기체가 계라면 압력도 가능하겠군요. 에탄올과 물을 섞은 뒤 담은 비커를 계라고 한다면, 두 용액 간의 조성 비율도 계의 성질이 될 것 같기도 하니.. **계의 성질**이라는 개념은 참 모호해 보이기도 합니다.

하지만 저희가 앞으로 계속 다룰 대상은 **기체**입니다. (특히 이상 기체가 될 것입니다.) **기체**를 계로 생각하는 이유는 단순합니다. 간단히 다룰 수 있고, 기체를 다루는 방정식이 존재하며, 많이 연구가 된 부분이기 때문이죠. 또 기체는 입자들 간의 상호작용이 적어 분석이 액체나 고체에 비해 수월하다는 특징이 있습니다. 그러니 앞으로 '계'라고 한다면 유리 상자 안에 갇혀 있는 기체의 모습을 생각하셔도 무방합니다.



계를 '**기체**'로 잡았으니, 계의 성질로 다음과 같은 것들을 생각해볼 수 있겠네요.

**"에너지, 온도, 부피, 압력, 질량"**

그런데 이 성질들은 다음과 같이 두 가지로 나눌 수 있습니다. 

**"부피, 질량, 에너지" / "온도, 압력"**

기준이 무엇일까요? 질문에 답하기 위해 **"계를 반으로 나누어도 똑같은가?"**를 생각해보시면 좋을 것 같습니다. 기체가 든 유리상자를 반으로 나누어서 왼쪽에 있는 것을 계 A, 오른쪽에 있는 것을 계 B라고 해보겠습니다.

이때, **부피, 질량, 에너지**는 계 A와 계 B가 모두 나누기 전의 전체의 절반만큼이 됩니다. 부피도 절반, 질량도 절반, 에너지도 절반만큼 나눠가질 것입니다.

하지만 **온도와 압력**은 계 A와 B가 그대로일 것입니다. 50도 물과 50도 물을 섞는다고 100도씨 물이 되지 않는 것과 같은 이치입니다.

이때 **부피, 질량, 에너지와 같은 성질을 크기 성질(extensive property)**라 하고, **온도와 압력과 같은 성질을 세기 성질(intensive property)이라고 합니다.**

---

#### 4. 열역학적 상태란 무엇인가?

그러니까 다시 말해, 열역학은 크기 성질과 세기 성질로 구분되는 여러 성질들과 그 변화를 다루는 학문이라고 할 수 있습니다. 이때 변화를 다루기 위해서는, 변화 이전의 **상태**와, 변화 이후의 **상태**가 어떻게 달라진 것인지를 정량적으로 표현할 수 있어야겠죠? 변화 이전의 상태와 변화 이후의 상태를 모르는데, 어떻게 두 상태 사이의 **변화**를 나타낼 수 있겠습니까? 불가능할 것입니다.

따라서 열역학에서는 **어떤 계의 여러 성질들이 시간이 지남에 따라 변하지 않고 유지될 때, 그 계가 하나의 열역학적 상태에 있다**고 정의해줍니다. 그러니까 어떤 기체가 1기압, 1L, 25도씨의 조건을 계속 유지한다고 하면 그 기체는 하나의 열역학적 상태에 있는 게 되는 셈이죠. 

보다 정확하게 말하면, **열역학적 상태(thermodynamic state)란, 계의 성질들이 시간에 따라 변하지 않을 때 그 거시적 조건**을 의미합니다. 그리고 어떤 계가 열역학적 상태에 있다면 크기 성질도 하나로 유지될 것이고, 세기 성질도 하나로 유지될 것입니다. 

이때 크기 성질을 유지하는 요인과 세기 성질을 구분하는 요인은 서로 다릅니다. 

**첫째로, 세기 성질의 경우입니다.** 간단히 내부에 1기압의 공기가 들어있는 주사기가 25도씨의 1기압의 일정한 외부 압력 아래에 있는 경우를 생각해 봅시다. 

![Figure 3](https://user-images.githubusercontent.com/88145508/133581838-52b703be-b8ce-4f70-a83c-20ce15f98a98.png)

그러면 이 주사기의 손잡이가 이동하지 않고 계속 1기압 상태로 유지될 것입니다. 2기압이나 3기압 상태로도 있을 수 있지 않냐고요? **그런 경우 주사기의 손잡이가 주사기의 내부 기압이 1기압이 될 때까지 이동할 것입니다. 그리고 열역학적 상태는 '시간이 지남에 따라 유지되어야 하기 때문에', 변화하는 과정 자체는 열역학적 상태라고 할 수 없습니다.** 따라서 외부 기압이 1기압으로 유지되는 한, 열역학적 상태에서 주사기는 기압이라는 세기 성질의 값으로 오직 '1기압'만을 가질 수 있습니다. 

**즉, 어떤 계의 세기 성질을 결정하는 요인은 '계'가 아니라 '주위'입니다.**



**둘째로, 크기 성질의 경우입니다.** 아까의 예시를 다시 이용해 봅시다. 아까 예시에서 주사기의 부피가 커진 경우를 생각해 보도록 하겠습니다. 주사기의 부피가 달라진다고 해서 열역학적 상태에 놓였을 때의 주사기의 기압은 1기압이 아니게 될까요? 그렇지 않을 것임을 예상할 수 있습니다. 주사기가 아무리 커져도 외부가 1기압이면, 내부는 계속 1기압을 유지하겠지요. 그리고 주사기의 손잡이를 눌러서 내부 기압을 2~3기압으로 만든다고 해도, 다시 기체가 내부 기압이 1기압이 될 때까지 팽창할 것입니다. 이를 바꾸어 생각해 보면, 부피가 달라진다고 해서 상태가 유지되지 않는 건 아니니**크기 성질은 마음대로 놓아도 되는 것이 아닐까요?** 

**네, 맞습니다. 하지만 딱 처음에만 마음대로 할 수 있습니다.** 처음에 주사기가 10ml의 부피로 시작해도 아무런 상관이 없습니다. 하지만 내부가 1기압인 주사기에 '10ml'라는 부피가 부여된 순간, 주사기는 **10ml라는 부피를 유지해야 합니다.** 처음 조건을 정할 때는 문제가 안 되지만, '25도씨, 10ml에서 1기압을 유지하는 주사기'로 시작했다면 중간에 갑자기 '25도씨, 1000ml에서 1기압을 유지하는 주사기'가 될 수는 없습니다. **이렇게 크기 성질은 처음 정한 조건에 의해 통제되는 요인이라고 할 수 있습니다.** 이것을 **제한 조건(constraints)**이라고 합니다. 한 번 정하면 마음대로 바꿀 수 없는 것이죠.



정리하면, 세기 성질은 주위에 의해 유지되고 크기 성질은 제한 조건에 의해 유지된다고 할 수 있습니다.

---

#### 5. 열역학적 과정과 열역학적 평형이란?

앞에 주사기 예시에서 다루었듯이, 압력을 변화시키거나 부피를 조절하며 계의 성질을 바꾸는 이 모든 행위들이 열역학적 과정이 될 것입니다. **즉, 열역학적 과정(thermodynamic process)은 어떤 계의 열역학적 상태를 변화시킵니다.** 이 과정은 압력을 조절하는 것과 같은 물리적 과정일 수도 있지만, 내부에서 어떤 화학 반응이 일어나서 부피, 압력 등등의 성질들이 변화하는 과정일 수도 있습니다. 물리적 과정이든 화학적 과정이든, 모두 열역학적 과정의 하나입니다.

그리고 어떤 계에서 열역학적 과정이 일어난 뒤 계의 성질들이 변하지 않는 **열역학적 상태**에 있을 때, 이 계는 **평형(equilibrium)**에 있다고 말할 수 있습니다. 평형은 열역학적 상태의 하나인 것이지요.

---

#### 6. 가역 과정과 비가역 과정

이때 열역학적 과정은 다시 **가역 과정(reversible process)**과 **비가역 과정(irreversible process)**으로 나뉠 수 있습니다. 간단히 말해 **가역 과정은 과정을 진행하는 데 추가적인 에너지가 필요하지 않은 과정**이고, **비가역 과정은 과정을 진행하는 데 추가적인 에너지가 필요한 과정**입니다. 예컨대 아까의 주사기 예시에서, 주사기의 내부 기압이 1기압인 열역학적 상태를 생각해보겠습니다. 이 상태에서 손잡이를 쭉 당긴 다음 놓아보겠습니다. 그러면 주사기의 내부 압력은 손잡이를 당기면서 작아지다가, 손잡이를 놓으면서 다시 커지고, 이내 과정이 끝날 때쯤에는 다시 1기압이 되어 있겠네요. 과정 중에 같은 온도를 유지했다고 하면 주사기는 과정을 시작하기 전과 후의 동일한 열역학적 상태에 놓여있다고 할 수 있습니다. 이때 저는 손으로 주사기를 잡아당기며 주사기에 '에너지'를 가해주었습니다. 그 에너지는 마찰이나 공기의 난류 등에 의해 소모되었겠지요. 즉, 제가 방금 진행한 이 과정은 에너지를 소모했으므로 비가역 과정입니다.

그렇다면 어떤 과정이 가역 과정일까요? 가역 과정은 실제로는 이상적인 개념입니다. 우리의 실제 세계에는 마찰과 난류 같은 비가역적인 요소들이 항상 존재하기 때문이죠. 하지만 열역학에서는 가역 과정을 가정하여 실제 세계에 대한 수준 높은 이해를 가능하게 합니다. 

가역 과정은 실제로는 존재하지 않는다고 봐야겠지만, 근사적으로 가역 과정이라고 부를 수 있는 경우가 있습니다. 아까 주사기를 잡아당겼다가 놓는 과정을 생각해 봅시다. 이 과정에서 주사기를 아주 조금, **정말 조금** 당겼다면 어떨까요? 근사적으로 에너지를 거의 사용하지 않았다고 보아도 좋지 않을까요? 네, 엄밀히는 아닐지라도 거의 가역 과정이라고 볼 수 있겠네요. 그리고 이런 경우에서는 다시 역으로 돌리기 위해 **아주 약간의 에너지**만 소모하면 되니까, 거의 가역 과정이라고 볼 수 있습니다.

그리고 비가역 과정이 아주 오랜 시간 동안 일어나더라도 가역 과정과 유사하다고 볼 수 있습니다. 만약에 주사기를 당겼다가 놓는 데 1J의 에너지가 필요하다고 해보겠습니다. 이것을 1초 동안 시행했다면, 일률은 1W(와트)가 되겠군요. 근데 이것을 100000초 동안 한다면 어떨까요? 일률은 0.00001W가 될 것입니다. 그렇다면 3초와 4초 사이에 투입되는 변화는 매우 작으니 4초의 상태에서 3초의 상태로 가는 데에는 아주 약간의 에너지만이 필요할 것입니다. 즉, 4초의 상태에서 3초의 상태로 역으로 바뀌기에 충분한 것이죠. 이렇게 아주 오랜 시간 일어나는 비가역 과정도 가역 과정으로 근사할 수 있고, 이런 과정을 이용해 우리는 **가역 과정**이라는, 현실에는 없는 과정을 생각해볼 수 있습니다.

이때 주의해야 할 것은 가역 과정과 비가역 과정 모두 처음과 끝 단계는 열역학적 단계라는 사실입니다. 하지만 중간 과정에서는 성질들이 변하기에 열역학적 상태라고는 할 수 없습니다. 

참고삼아 말하자면, 가역 과정은 연속적인 열역학적 단계들을 통과하며 진행하는 과정이고 비가역 과정은 중간 단계를 평형 열역학 상태를 도식한 표면 위에 그릴 수 없는 과정입니다. 그러나 상태방정식 표면을 아직 다루지 않았기에 지금 설명은 생략하겠습니다. 

---

#### 7. 상태 함수

정말 마지막으로 상태 함수에 대해 언급하면서 글을 끝맺도록 하겠습니다. **상태 함수란, 계의 열역학적 상태에 따라 유일하게 결정되는 함수를 말합니다.** 말이 조금 어렵습니다. 간단히 말해, **처음과 끝이 정해지면 유일하게 결정되는 함수를 말합니다. 즉, 경로에 영향을 받지 않는 것이지요.**

잘 알려진 상태 함수로는 **압력(P), 부피(V), 온도(T), 에너지(E)**가 있습니다. 예컨대 부피라고 한다면, 부피의 처음과 끝 사이의 변화량은 단순히 V2-V1이 될 것입니다. 또 에너지 중에서 엔탈피(H)를 예시로 들어보겠습니다. 예컨대 다음과 같은 반응에서 엔탈피 변화를 A라고 해보겠습니다.

![수식 1](https://latex.codecogs.com/gif.latex?%5Cdpi%7B300%7D%20NO_2%28g%29%20&plus;%20CO%28g%29%20%5Crightarrow%20NO%28g%29%20&plus;%20CO_2%28g%29%2C%20%5CDelta%20H%20%3D%20A)

그런데 이 반응을 다음과 같이 두 단계를 거쳐서 진행할 수도 있을 것입니다. 각각의 엔탈피 변화를 B1, B2라고 해보겠습니다. 

![수식 2](https://latex.codecogs.com/gif.latex?%5Cdpi%7B300%7D%201.%20NO_2%28g%29%20&plus;%20NO_2%28g%29%20%5Crightarrow%20NO%28g%29%20&plus;%20NO_3%28g%29%20%5Cspace%2C%20%5Cspace%20%5CDelta%20H%3D%20B_1%20%5Cnewline%202.%20NO_3%28g%29%20&plus;%20CO%28g%29%20%5Crightarrow%20NO_2%28g%29%20&plus;%20CO_2%28g%29%5Cspace%2C%20%5Cspace%20%5CDelta%20H%3D%20B_2%20%5Cnewline)

여기서 두 경로를 지나갈 때의 에너지 변화량은 초기 상태와 최종 상태가 같으므로, 

![수식 3](https://latex.codecogs.com/gif.latex?%5Cdpi%7B300%7D%20A%20%3D%20B_1%20&plus;%20B_2)

가 될 것입니다.

그런데 이와 반대되는 개념으로 **경로 함수**라는 것이 있습니다. 경로 함수는 중간에 어떤 과정을 거쳤느냐에 따라서 그 값이 달라지게 됩니다. 경로 함수에는 열(Q)와 일(W)이 있습니다. 이것은 P-V 도표를 통해 설명할 수 있는데, 이 내용은 아직 다루지 않았기에 간단히만 다루고 추후에 포스트를 올리도록 하겠습니다. 예시로 다음 그림과 같이 상태 1에서 상태 2로 전환한다고 해봅시다.

![Figure 4](https://user-images.githubusercontent.com/88145508/133581869-d7dc13fc-e4e6-4054-8865-907ccbef5e88.png)

그런데 P-V 도표에서는 어떤 과정이 진행되었을 때 그때 기체가 한 일은 그 과정의 아래 면적(넓이)이라고 할 수 있습니다. 기체가 한 일은 압력과 부피의 곱으로 표현되는데, 부피가 아주 조금 증가할 때의 기체가 한 일을 그 순간에서의 압력과 부피 증가량의 곱으로 근사하는 **적분**이라는 과정을 통해 이를 증명할 수 있습니다. 위의 그림에서는 시작점인 A와 도착점인 B가 같음에도 불구하고, 두 과정에서 기체가 한 일은 달라지겠군요. 경로에 의존하니 이는 상태 함수가 아닌 경로 함수가 되겠습니다.



**그렇다면 상태 함수가 중요한 이유는 무엇일까요?** 바로 어떤 가역 과정을 통하든 처음과 끝만 알고 있다면 에너지, 부피, 압력 등의 여러 성질들의 변화를 쉽게 구할 수 있기 때문입니다. 즉, **가역적 경로를 이용해 처음과 끝에만 의존하는 상태 함수의 변화량을 구할 수 있습니다.** 추후에 실제로 정량적으로 이 값들을 구해볼 것입니다.

---

#### [총 정리]

오늘 다뤄본 내용을 총 정리해보겠습니다.

- **계 : 직접적인 관심의 대상이 되는 부분**

- **주위 : 계와 에너지, 물질을 교환하는 우주의 나머지 부분**

* **열역학적 우주** **: 계와 주위를 모두 포함하는 부분**
* **계는 닫힌계, 열린계, 고립계로 구분할 수 있다.**
* **계는 크기 성질과 세기 성질로 구분되는 여러 성질을 지닌다.**
* **계의 성질들이 변하지 않을 때 계는 하나의 열역학적 상태를 가진다.**
* **세기 성질은 주위에 의해 유지되고 크기 성질은 제한 조건에 의해 유지된다.**
* **열역학적 과정은 어떤 계의 열역학적 상태를 변화시킨다.**
* **열역학적 과정은 추가 에너지를 필요로 하는 비가역 과정과 그렇지 않은 가역 과정으로 나뉜다.**
* **열역학적 함수는 상태 함수과 경로 함수로 나뉘며, 상태 함수는 가역 과정을 통해서 그 변화를 쉽게 구할 수 있다.**

감사합니다. 다음 시간에는 '해봅시다, 열역학 _ 1. 2'로 돌아오겠습니다.

---

###### 출처

- https://chem.libretexts.org/Courses/University_of_British_Columbia/UBC_CHEM_154%3A_Chemistry_for_Engineering/07%3A_Energy_and_Chemistry/7.5%3A_The_First_Law_of_Thermodynamics (Figure 1.)
- https://lawofthermodynamicsinfo.com/what-is-thermodynamic-system/ (Figure 2.)
- 
