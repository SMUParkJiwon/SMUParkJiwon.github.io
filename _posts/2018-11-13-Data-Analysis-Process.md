##Data Analysis Process
**Server에서 누적된 데이터와 실시간으로 발생되는 데이터를 병합하여 처리** 

-Python을 통해 데이터를 수집하고, String 연산, 정규표현식 등을 활용하여 csv 파일로 정제

-일반 Desktop에서 다루기 어려운 규모의 Data는 Linux Server를 통해서 Data Handling

-Python의 ggplot, Tableau 등으로 데이터 시각화

![enter image description here](https://i.imgur.com/uBHtLqi.png)

![enter image description here](https://i.imgur.com/4ksSsm8.png)

#Confusion Matrix & F1-Measure

-단순히 정확도 만으로는 데이터 분석의 성능을 올바로 측정하기가 어렵다. 

-데이터 밸런싱을 맞추어야 통계학적으로 설명력Power가 세진다. 

![enter image description here](https://i.imgur.com/fQsdJf0.jpg)

*precision: 정밀도. = Positive predictive value 양성예측도. 예측한 p중 맞춘 p
P = TP/(TP+FP)

*recall:  재현율=민감도 sensitivity. 실제 p중 맞춘 p
R = TP/(TP+FN)

*F-measure: 2*P*R/(P+R)

*Negative: 음성예측도. 예측한 n중 맞춘 n

*predictive value: NPV = TN / (FN+TN)

*error rate:  오분류율. 모든 경우의 수 중에 틀린 것
E = (FP+FN) / ALL
ALL = TP+FP+TN+FN

*accuracy rate: 정분류율 = 정확도. 모든 경우의 수 중에 맞은 것
A = (TP+TN) / ALL

*type 1 error:  p라고 예측했는데 실제는 n인 것. 
예측이 잘못된 것.

*type 2 error:  n이라고 예측했는데 실제는 p인 것. 
예측했어야 하는 것

(타입1에러와 타입2에러 중 타입1에러가 리스크가 훨씬 작다. 타입2에러가 더 심각하다)