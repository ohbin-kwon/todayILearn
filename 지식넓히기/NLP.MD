NLP는 언어를 기반으로한 학습 모델을 만드는 과정이다. 아래는 딥러닝을 기반으로한 NLP를 서술한다.

cpu는 dataLoader라는 소프트웨어에 의해, txt, 또는 csv파일의 string을 의미있는 데이터로 만든다.
의미있는 데이터란, gpu를 이용해 학습되는 딥러닝 모델이 받아들일 수 있는 데이터의 형태이다. 이를 텍스트 전처리라고 부른다.
의미있는 데이터는 gpu에 의해 학습되고, 모델파일을 만들어낸다.

NLP가 가능하기 위해서는, NLU가 먼저 필요하다. NLU는 Natual Language Understanding의 약자로, 학습을 통해, 기계가 언어에 대한 해석을 할 수 있도록 NLP의 첫번째 컴포넌트이다. 여러가지 언어들을 대상으로 하고, 인간이 이해하기 쉬운 형태로 한번 더 해석해서 사용자에게 알려주는것을 의미한다.

NLU 모델(C4, T5 등이 대표적)을 기반으로 우리는 NLP를 구현할 수 있다. 예를들어, T5모델을 통해 여러언어를 이해할 수 있는 기반을 마련하고, 프로그래머는 자연어 요약이나, 챗봇 역할을 수행할 수 있도록, 모델을 만들 수 있다.
이렇게 새로만들어진 모델이 수행할 수 있는 역할을 task라고 한다.(요약 task, 챗봇 task)

현재 말한 방법이 정답이라고 할 수는 없지만, 현재 가장 많이 이루어지고 있는 딥러닝 NLP 모델을 만드는 방식이라고 한다.

참조: https://wikidocs.net/21693