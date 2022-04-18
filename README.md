# CNN을 이용한 코로나19 흉부 X선 이미지 분석

2021-2 일반화 선형모형 수업의 기말 프로젝트로 진행한 내용으로, CNN 주요 모델인 Alexnet, VGG, GoogLenet, Resnet 4가지 방법론의 논문을 읽고 각 모델의 구조와 차이점을 이해하였다.
실제 이미지 데이터 분석에 적용하여 성능을 비교하였다.

<br/> <br> 
## Reference Paper Reveiw
<br/> <br>

## Data Description
코로나19 확진자, 폐렴 환자, 정상인 세 그룹의 흉부 X선 이미지 데이터로, train set 251개, test set 66개로 이루어져있다.
<br>
:link: 데이터 출처 : https://www.kaggle.com/pranavraikokte/covid19-image-dataset
<br/> <br>

## Model Comparison
||**Alexnet**|**VGG19**|**GoogLenet**|**Resnet18**|
|:-----:|:-----:|:-----:|:-----:|:-----:|
|Depth|8|19|22|18|
|time|4.71m|5.61m|4.61m|4.79m|
|test acc|**0.803**|**0.833**|**0.894**|**0.909**|
