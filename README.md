# CNN을 이용한 코로나19 흉부 X선 이미지 분석

2021-2 일반화 선형모형 수업의 기말 프로젝트로 진행한 내용이다.
<br> CNN 주요 모델인 Alexnet, VGG, GoogLenet, Resnet 네 가지 방법론의 논문을 읽고 각 모델의 구조와 차이점을 이해하였다.
또한, 실제 이미지 데이터 분석에 적용하여 성능을 비교하였다.

<br/> <br> 

## Reference Paper
:page_with_curl: Alex Krizhevsky, Ilya Sutskever, and Geoff Hinton. 
Imagenet classification with deep convolutional neural networks. 
In Advances in Neural Information Processing Systems 25, p1106–1114, 2012.
<br>:page_with_curl: K. Simonyan and A. Zisserman. Very deep convolutional networks
for large-scale image recognition. In ICLR, 2015.
<br>:page_with_curl: C. Szegedy, W. Liu, Y. Jia, P. Sermanet, S. Reed, D. Anguelov, D. Erhan, V. 
Vanhoucke, and A. Rabinovich. Going deeper with convolutions. In CVPR, 
2014
<br>:page_with_curl: K. He, X. Zhang, S. Ren, and J. Sun. (Microsoft Research) Deep residual 
learning for image recognition. arXiv:1512.03385, 2015.

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
