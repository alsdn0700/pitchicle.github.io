---
layout: post
title : '그래서 양자역학이 뭔데? -1편'
author: yeonwoo.bae
comments: true
date: 2021-08-31 17:15
use_math: true
tags: [physics]
image: https://user-images.githubusercontent.com/82321028/131469578-547644f5-a43e-42a0-a84d-ad63ae910ab7.jpeg
---



 32기 배연우



양자역학하면 무엇이 생각나시나요? 슈뢰딩거의 고양이, 양자중첩, 양자얽힘, 양자컴퓨터... 요즘 유튜브라던가 과학 잡지라던가, 많은 곳에서 '양자역학'과 관련된 용어들을 볼 수 있습니다. 그러나 양자역학을 접하다 보면 그런 생각이 들죠.

 "그래서 양자역학이 뭔데?"

 우리의 실생활 속에서 양자역학은 잘만 활용되고 있습니다. 지금 사용하시는 디스플레이도 통신기술에도 양자역학은 사용되고 있을거에요. 그럼에도 불구하고 물리학자들은 여전히 탁자 위에서 양자역학은 무엇인가? 라는 질문에 대해 답하기 위해 골머리를 썩히고 있습니다. 아인슈타인조차 양자역학을 부정하고자 했었죠. 그런 공방을 보고 있자면 '그래, 양자역학이 신기한 것 같긴 해. 이럴 수도 있고 저럴 수도 있다고 하니까. 근데 그걸 그냥 받아들이면 안되나? 왜 아직도 논쟁이 끝나지 않은거지?' 하는 생각이 들지 않나요?

 이 특집 기사에서는 양자역학의 근본적인 문제에 다가가기 위하여 일반적인 교양 서적에서는 접하기 쉽지 않은 내용들을 설명하고자 합니다. 프롤로그에서 코펜하겐 해석과 같이 기본적인 내용에 대해 다루기는 했습니다만, 이미 알고 계신 내용이라면 바로 본문을 읽으셔도 좋아요. 다른 곳에서 쉽게 찾아볼 수 있는 내용 대신, 이 특집에선 EPR, 벨 부등식, HOM dip 현상, 마하젠더 간섭계, Franson 형 비국소적 상관관계에 중점을 두고 이야기를 할 것입니다. 비록 내용은 생소하겠지만 어려운 수학은 사용하지 않을 것입니다. 정성적인 해석에 대한 이야기를 해볼 예정이에요. 수학을 사용하지 않고 양자역학을 이해하는 것은 불가능하겠지만 수학의 벽에 부딪혀 그 신비에 다가가지도 못하는 것 보다는 좋으리라 생각합니다. 그러니 천천히 읽어본다면 이 특집의 끝에서는 양자역학을 향해 어떤 의문을 던지게 될 것이라 기대해봅니다. 이번 편에서는 EPR 역설을 통해 포괄적인 내용을 알아보고 다음 편부터 구체적인 예시를 통해 고찰해 보도록 하겠습니다.

 양자역학을 이야기하기 위해 먼저 고전역학에 대한 이야기를 해보겠습니다. 고전역학은 '결정론적 세계관'을 따릅니다. 예를 들어 볼까요. 자유낙하하는 공을 보았을 때 우리는 그 공의 현재 속도, 가속도, 높이, 공기저항 등의 요소를 알고 있다면 '정확히 n초 뒤에 공이 바닥에 도달할 것이다'라는 예측을 할 수 있고 그것은 정확히 들어맞게 됩니다. 더불어, 우리가 그 공을 관측했든 하지 않았든 공은 정확히 n초 뒤에 땅에 떨어질거에요. 모든 계 내의 요소들은 가속도나 질량과 같이 고정적이며 실재적인 물리값을 가지고 있고 이는 관측과 관계없이 존재한다는 의미이지요.

 여기서는 일단 '현재의 상태를 모두 알고 있다면 미래를 정확히 예측할 수 있다. 모든 상태에 대응하는 실재적인 물리값이 존재하기 때문이다.'라는 것이 결정론적 세계관이라고 이해합시다.

 너무도 당연해보이는 사실입니다. 이러한 결정론적 세계관은 뉴턴역학에서 비롯된 고전역학의 뿌리이며, 우리의 철학 속에도 깊게 자리 잡고 있습니다. 그러나, 이 결정론적 세계관을 산산이 부수어 버리는 역학, 그것이 바로 확률론적 세계관을 기반으로 한 양자역학이었습니다. 양자역학은 불확정성 원리와 코펜하겐 해석을 바탕으로, 관측 전의 물리량들은 오직 확률의 형태로만 존재하며 관측 행위에 의해 파동 함수가 붕괴하여 입자의 형태로 보인다고 말합니다. 어쩌면 이 이론을 아무렇지 않게 받아들일 수 있을지도 모릅니다. 그러나...

 이러한 양자역학을 부정하고자 1935년 아인슈타인과 포돌스키 및 로젠이 EPR 역설을 발표하였습니다. 아인슈타인은 양자역학의 무엇에 의문을 품고 있었을까요?

 아인슈타인의 생각은 1927년 솔베이 회의에 뿌리를 내리고 있었습니다. 당시 회의에서는 파동함수 붕괴와 관련된 해석을 하고 있었는데, 아인슈타인은 전자가 큰 반구 모양의 스크린을 향해 쏘아지는 상황을 제시하였습니다. 양자역학에 따르면 전자의 상태는 파동함수라는 것을 통해 확률적으로 나타나게 됩니다. 그러다가 파동함수가 붕괴하며 한 지점으로 스크린에 나타나게 되죠. 아인슈타인은 이것을 보고 붕괴 순간, 해당 붕괴 지점이 다른 모든 공간을 향해 '붕괴하지 말라'라고 지시한 모양새가 된다고 말했습니다. 그렇습니다, 코펜하겐 해석에 대한 의문점이죠. 어떻게 한 지점에서 일어난 측정이 우주에 연속적으로 분포하는 파동함수를 붕괴시키는 것일까요? 파동함수의 붕괴가 '빛보다 빠르다'라고 양자역학은 말하려는 것일까요? 실재적인 물리량은 오직 측정만으로 이루어지고 그 이전의 물리량은 확률로써만 존재한다는 게 현실이란 뜻일까요?

 이 추상적인 아이디어를 구체화한 것이 "Can Quantum-Mechanical Description of Physical Reality Be Considered Complete?" 제목의 논문, 즉 EPR 역설이었습니다. EPR은 "만약 어떤 식으로든 계를 방해하지 않고 우리가 물리량을 확실히 예측할 수 있다면 그 물리량에 해당하는 실재적 값이 존재한다." 라는 전제를 제시합니다. 코펜하겐 해석과 반대되는 느낌의 전제이지요? 이것은 EPR 기준이라고 불리는데, 이때 고유 상태에 대응하는 고유값은 1의 확률을 갖는데 이것은 EPR 기준에 부합하는 실재적 물리량입니다. 사실 이것은 EPR 기준에 부합하는 유일한 물리량이지요.

 그러나 파동함수는 이러한 확정적 예측이 불가능합니다. 불확정성 원리에 따라 위치와 운동량 혹은 에너지와 시간과 같은 물리량들은 양자 상태에선 동시에 정확한 실재값을 가질 수 없지요. 따라서 저자들은 양자역학의 불완전함을 증명하기 위해서는 그러한 물리량들이 동시에 실재값을 갖는 경우를 보여야 했습니다. 그러나 이것은 쉽게 확립되지 않았기에 저자들은 양자얽힘에 관한 사고실험을 제시했습니다.

 여기서 양자얽힘이란 아직 제대로 정의되지 못한 현상입니다. 어떤 기전인지, 정확히 어떤 상관관계인지는 모르겠지만 특정 상황에서 이 양자 둘은 '어쨌든 얽힘 상태에 있다'라고 설명하는 것이 전부이지요. 양자얽힘이 '일련의 비고전적인 상관관계'라는 추상적인 단어로 정의되는 것은 그 탓입니다.

 다시 EPR에서 제시한 사고실험의 이야기로 돌아가보겠습니다. 이 실험은 서로 공간적으로 멀리 떨어져 있으나 양자 얽힘 상태에 있는 두 양자에 대한 것으로, 이 양자 계의 해밀토니안(전체 에너지)가 0일 때, 한 양자의 운동량이 p인 것으로 확인된다면 다른 양자의 운동량은 -p로 정해질 것이며, 그 위치 또한 얽힘 관계에 있을 것입니다. 이 시점에서 EPR은 두 가지 중요한 이야기를 합니다. 첫째는 계가 분리되었을 때 공간적으로 멀리 떨어져 있는 두 계는 각각 고유한 현실 요소, 즉 실재값을 가질 것이라는 실재성. 둘째는 공간적으로 멀리 떨어져 있는 두 계는 상호작용 할 수 없다는 국소성의 원리였습니다. 자, 양자역학에서는 한 계를 측정하는 순간 전역의 파동함수가 붕괴되어 다른 계의 상태또한 한 지점으로 붕괴하게 됩니다. 그러나 한 계에 대한 관측이라는 행위가 다른 계에 영향을 주는 것은 비국소적인 일로 불가능합니다. 그러나 두 계는 얽힘 상태에 있으므로 두 계의 상태의 합은 일정해야 겠지요. 따라서 만약 얽힘 상태에 있는 한 계에 대한 실재값을 얻을 수 있다면 다른 계의 실재값은 관측 전에 미리 정해져 있어야 한다는 논리입니다. EPR의 내용을 정리하면 다음과 같습니다.

 첫째, EPR 기준은 고유 상태에 해당하는 고유값이 실재 물리적 상태에 의해 결정되는 값임을 보여준다.

 둘째, 공간적으로 분리된 계는 각각 실재 물리적 상태를 갖는다.

 셋째, 계가 공간적으로 분리된 경우, 한 계에 대한 측정 또는 측정의 부재는 다른 계에게 직접적인 영향을 미치지 않는다.

 넷째, 분리된 두 계가 엄격한 상관관계-즉 얽힘 상태에 있을 때 그 물리량은 실재의, 확실한 값을 갖는다. 따라서 실재값을 갖게 하는 데에 측정이라는 행위는 필요치 않다.

 즉 EPR은 얽힘 상태에 있는 두 계는 동시에 명확한 위치와 운동량을 가지고 있으며 이는 양자역학이 불완전함을 증명한다.

 EPR에 더하여 아인슈타인 그 자신의 의견도 있었습니다. 아인슈타인은 분리성 및 지역성을 확인하는 것과 개별 계를 설명하는 것의 완전성 사이의 양립가능성을 탐구하였으며, 둘 중 하나는 가질 수 있지만 둘 다는 가질 수 없다는 결론을 내리게 되었습니다. 한 계가 실재 물리적 상황을 가질 수 있도록 분리성과 지역성을 보장해봅시다. 그러면 측정은 다른 계에게 영향을 끼치지 않겠지요. 그러나 어떤 측정을 수행하느냐에 따라 측정 된 계의 현실은 상당히 다른 모습으로 표현됩니다. 불확정성 원리에 의거, 측정을 수행하는 순서에 따라 결과가 달라진다는 것은 익히 알려져 있었으니까요. 이 경우 엄격한 상관관계, 즉 얽힘이 어떻게 유지되는가에 모순이 발생하며, 분리성 및 지역성, 완전성 사이의 딜레마에 직면하게 됩니다. 아인슈타인은 이 딜레마를 두 개 주장의 양립 불가로 정리하였습니다. '파동함수에 의한 설명은 완전하다'와 '국소성의 원리는 성립한다' 둘 중 하나를 포기해야 한다는 것이죠. 그러나 슈뢰딩거와의 서신 교환 과정에서 아인슈타인은 분리성과 지역성에 대한 가정이 필요치 않음을 깨달았습니다. 그는 그 깨달음을 바탕으로 “crude macroscopic example”을 통해 문제를 설명하리라고 슈뢰딩거에게 보내는 서신에서 밝혔습니다. 그 내용은 다음과 같습니다. 이 계는 화학적으로 불안정한 평형상태의 물질이며, 자연적으로 연소될 수 있는 화약 물질로, 평균 수명은 1년입니다. 원칙적으로 이것은 파동함수적으로 잘 표현될 수 있기는 하나, 요점은 1년 후에 폭발했는가 하지 않았는가 라는 점이겠지요. 이것이 EPR 상황에서의 실제값인데, 고유값-고유상태의 연관성이 유지되는 경우 양자역학의 상태 함수를 통해서는 어떤 결론, 즉 실제값이 얻어지지 않을 것입니다. 이 논쟁은 결어긋남의 도입으로 어느 정도 해결될 수 있습니다. 폭발 가능성 지점과 폭발하지 않는 가능성 지점 사이의 간섭이 환경과의 상호작용으로 사라지고 고유값-고유상태의 연관성을 끊는 것이다-라는 해석이죠. 그러나 이러한 해석은 굉장히 교묘하여, 이 타당성은 아직 논의 중에 있습니다. 이뿐 아니라 아인슈타인과 보어가 논의하면서 나오는 여러 개념들에 대한 정의도 모호한 부분이 많습니다.

 EPR의 결론은 실재값은 관측에 의한 파동함수의 붕괴를 통해 정해진다는 양자역학의 결론과 정반대이지요? EPR만 보면 마치 양자역학이 정말로 틀린 것처럼 보입니다. 그러나 보어 등의 지적과 같이 아인슈타인이 말한 '실재'에 대한 정의가 정확하지 않은 바, EPR에도 허점은 있다는 뜻이겠지요. 아무튼 많은 학자들은 양자역학이 불완전할 수도 있다는 관심을 가졌고, 양자역학의 불완전성은 '우리가 아직 찾지 못한 변수가 있을 것이다'라는 발상 아래 '숨은 변수 이론'을 제창하게 되었습니다. 이 숨은 변수 이론의 중심이 벨 이론이었고요.



![벨 부등식 실험 도식도. 가운데 Source로부터 두 개의 양자가 나오고 그둘이 각각 관측자 a, b에게 간다.](https://user-images.githubusercontent.com/82321028/131468330-ddf5df5c-a11c-4ce1-8f40-a01a29ff9289.png)



벨은 만약 EPR이 희망했던 실재적 물리량을 예측할 수 있는, 즉 결정론적인 완전한 이론이 존재한다면 그것은 추가적인 매개 변수를 포함해야한다고 주장하였습니다. 이러한 변수는 실험에서 직접 도입할 수도 없어 '숨은 변수'라고 불리는데요, 보통은 이 존재를 증명하는 것이 불가능하다고 생각하였습니다. 그러나 벨은 얽힌 두 양자의 상태를 측정하고 그 측정 결과 간의 상관관계를 살펴봄으로써 변수의 존재를 시험하는 방법을 생각해내었습니다. 여기서 벨은 EPR과 같은 가정을 바탕으로, 관측자 a와 b에게 쏘아지는 전자에 대한 실험을 제시합니다. 위의 그림이 그 실험의 모습이라고 할 수 있는데요, 두 전자는 반드시 같은 스핀, 혹은 반드시 다른 스핀으로 나타나는 얽힘 상태에 있다고 해봅시다. (실제로 얽힌 상태에 있는 양자를 만드는 것은 실험적으로 가능합니다. 메커니즘을 알 수 없을 뿐이죠. PPKTP라는 방법에 대해 추후에 설명하겠습니다.) 두 관측자의 관측 각도의 상대값에 따른 관측값과 그 상관관계는 아래 표와 같게 될 것입니다. 여기서 상관관계는 두 스핀의 일치상태를 나타내는 말이라고 보아도 좋습니다.

![관측자 간 관계에 따른 상관관계의 값과 그 평균에 대한 표. ](https://user-images.githubusercontent.com/82321028/131468547-b06ca7ec-457e-41dd-b4d9-0f44f532212a.png)



반평행 상태에서는 언제나 스핀이 같게 측정되어 상관관계는 무조건 1로 나타나게 되고 평균도 당연히 1입니다. 평행할 때는 언제나 반대 스핀이어서 상관관계는 -1이로군요. 직교일 때는 스핀이 절반의 확률로 같게 나오거나 반대로 나옵니다. 따라서 상관관계의 평균은 1과 -1이 상쇄되어 0으로 도출됩니다.

 고전역학과 양자역학은 평균적으로는 같은 결과를 내놓습니다. 여기에 가상의 관측자 c를 추가해보도록 하겠습니다. 그리고 a와 b, a와 c, b와 c의 상관관계 간의 관계를 생각해볼까요? 부등식으로 나타내면 아래와 같으며, 이를 벨 부등식이라 합니다.



![상관관계 부등식. 식 설명은 다음 본문에.](https://user-images.githubusercontent.com/82321028/131468853-75c75e31-2b44-43b1-9bac-6f85d23300ed.png)



C(b,c)가 1의 상관관계를 가질 때, 즉 우항이 최대일 때 부등식이 성립하는지를 보겠습니다. C(a,b)가 -1이고 C(a,c)가 1일때 2가 되어절댓값 안의 수는 최대가 되겠군요. 부등식을 성립합니다. 네, 고전역학적으로 생각한다면 말입니다. 그러나 양자역학적 계산을 거치면 결과는 사뭇 달라집니다. 이에 대한 내용은 양자역학적인 계산과정인데요, 이에 대한 구체적인 내용을 알고 싶으신 분들은 참고문헌 [4]의 본문에서 2번 목차를 참고해주시길 바랍니다. 우리는 일단 결론만 빌려오도록 합시다. 계산 결과, 상관관계의 최댓값은 이상하게도 2√2가 도출됩니다. 2보다 큰, 부등식을 위반하는 결과로군요. 어째서 이런 결과가 나오게 되는 것일까요? 각도에 따른 상관관계의 기댓값을 그래프로 나타내봅시다. 



![각도에 따른 상관관계의 기댓값. 고전역학으로 도출된 결과는 직선형 그래프를 그리고 있고 양자역학으로 도출된 결과는 유선형을 그리고 있다.](https://user-images.githubusercontent.com/82321028/131468967-f3dd9116-39fa-46ac-a0d8-d2dc3b0eaa87.png)





x축은 관측의 상대적 각도, y축은 상관관계입니다. 고전역학과 양자역학 모두180도에 상관관계 1이라는 최댓값을 보이고 0도와 360도에서는 -1의 상관관계를 보이는 개형이군요. 그러나 고전역학이 직선형인데 비해 양자역학은 언덕같은 곡선을 이루고 있습니다.

 두 그래프의 넓이, 달리 말하면 평균은 동일하겠지요. 그러나 1도에서 89도 사이의 값들을 한번 살펴봅시다. 그래프의 개형이 다르며 자연히 상관관계의 최대최솟값도 다르게 되겠군요. 결론적으로 어떤 실험의 결과가 벨 부등식을 만족하면 EPR이 주장하는 바가 옳고, 만족하지 못한다면 양자역학이 옳다는 증거가 되는 것입니다. 벨이 이론을 제시했으니 이제 실험으로 검증할 차례입니다. 벨은 전자에 대한 실험을 제시하였으나 실제 실험들은 대부분 광자를 사용하였는데요, 아래 그림이 그러한 실험들 중 하나입니다.



![벨 부등식 실험. source로부터 두 광자가 튀어나와 각각 하나의 빔스플리터로 들어간다.](https://user-images.githubusercontent.com/82321028/131469133-e427763e-5bc8-4907-b77f-ec8050898f59.png)





앞서 전자를 사용한 실험과 거의 다를바가 없습니다. 이 실험은 전자의 스핀 대신 광자의 편광을 측정한 것이며, 결과는 양자역학의 손을 들어주었습니다. 벨 부등식을 위반한 것이지요.

 이러한 결과는 물리학계에 큰 파문을 일으켰습니다. 물리학자들 중 누구도 파동함수의 붕괴 과정과 그 비국소성을 설명할 수 없었고, 이제껏 너무도 당연히 지켜온 물리량의 실재성이 무너졌으니까요. 이 사건에 대해 학자들은 여러가지 주장을 내놓습니다. 그 중 하나가 지역적 사실주의(local realism)입니다. 모든 사람이 같은 의미로 사용하는 것도 아닌데다가 명확하지 못합니다만, 크라우저와 호른이 쓴 지역 사실적 이론(local realistic theories)와 동의어로 쓰이곤 합니다. 이 사실주의란 것은 "외부 현실이 존재한다고 가정되고, 그들이 누군가에 의해 관찰되든 그렇지 않든 분명한 속성을 가지고 있다고 보는 철학적 견해"입니다. 갑자기 과학 얘기에서 철학으로 넘어간 느낌이군요. 그러나 양자역학은 이제까지의 직관으로는 도저히 이해할 수 없다는 특성 탓에 철학과 깊은 연관을 짓게 되었습니다. 앞의 지역 사실적 이론과 비슷한 맥락에서, 데스파냐트의 사실주의는 "관찰된 현상의 규칙성은 인간 관찰자와 독립되어 존재하는 실재적 물리량들에 의해 야기된다"라고 말합니다. 이러한 철학들은 역시 EPR과 같은 입장으로, 양자역학을 도저히 받아들일 수 없음을 선언하고 있었습니다. 실험적 증명에도 불구하고 말이지요. 

 지금까지 EPR 역설과 벨 부등식에 대해 굉장히 대략적인 내용을 살펴보았습니다. 코펜하겐 해석 등 양자역학의 기본적인 내용들을 보다 깊이 알고 싶으시다면 "양자역학 개론(https://www.cheric.org/files/education/cyberlecture/e201001/e201001-1901.pdf)"을 읽어보시는 것을 추천드립니다. 다음 편에서는 마이켈슨간섭계와 HOM dip 현상에 관한 이야기를 해보도록 하겠습니다.



참고문헌

[1] https://plato.stanford.edu/entries/qt-epr/, “The Einstein-Podolsky-Rosen Argument in Quantum Theory”,Stanford Encyclopedia of Philosophy (2021.01.13.) 

[2] Yehuda B. Band, Yshai Avishai, “Quantum Mechanics with Applications to Nanotechnology and Information Science”, 2013 

[3] https://en.wikipedia.org/wiki/Bell%27s_theorem , “Bell's theorem”, Wikipedia (2021.01.14.) 

[4] https://plato.stanford.edu/entries/bell-theorem/, “Bell’s theorem”, Stanford Encyclopedia of Philosophy (2021.01.14.) 



이미지 출처

[a] https://plato.stanford.edu/entries/bell-theorem/, “Bell’s theorem”, Stanford Encyclopedia of Philosophy (2021.01.14.) 

[b] https://en.wikipedia.org/wiki/Bell%27s_theorem , “Bell's theorem”, Wikipedia (2021.01.14.) 