# Machine_Learning_with_Python__scikit-learn

머신러닝 툴킷인 scikit-learn을 이용하여 머신러닝을 공부를 정리하는 저장소입니다.

---
> 깃허브에 모든 예제 코드들이 잘 정리 되어있다. Fork도 하고 그를 보며 따라갈 것이다.   
  똑같이 적을 수 있지만 Ctrl+C,V는 하지 않을 것임을 스스로 다짐하며 천천히 써 내려가고자 한다.
  또한, 개념 위주가 아닌 코드 위주로 작성할 것이다. 최근 코딩을 잘 하지 않고 개념 공부만 하고 있는 느낌이 들어서..
  
![image](https://user-images.githubusercontent.com/71332005/234245094-2d4447e1-0d0b-4c49-a7d3-4eb0c618856b.png)   
["(개정판)파이썬 라이브러리를 활용한 머신러닝"](https://github.com/JeJuBOO/introduction_to_ml_with_python)   

## scikit-learn 설치
[scikit-learn](https://scikit-learn.org/stable/)은 ``NumPy``와 ``SciPy``를 사용한다. 그래프를 그리기 위해 ``matplotlib``, 대화식 개발을 위해 ``IPython``과 주피터 노트북도 설치 해야한다.   
따라서 설치하기 위해 주로 ``Anaconda``를 이용한다. (https://www.anaconda.com/download/)

파이썬을 설치하고 아나콘다를 설치했다면 다음과 같은 코드를 이용해 설치 할 수 있다.
```
conda install numpy scipy scikit-learn matplotlib pandas pillow graphviz python-graphviz
```
7장에서 ``ntlk``와 ``spacy``도 사용되기 때문에 설치 해야한다.
```
conda install nltk spacy
```

**pip를 사용한 패키지 설치**
파이썬이 있고 pip를 사용하여 패키지를 설치하기 위해 다음 코드를 사용한다.
```
pip install numpy scipy scikit-learn matplotlib pandas pillow graphviz

pip install nltk spacy
```

