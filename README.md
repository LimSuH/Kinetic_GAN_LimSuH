# Kinetic-GAN  
kinetic gan을 이용한 human action generative model을 학습하고 나아가 수어 데이터 생성을 수행하기 위한 repository 입니다.  

### KETI Dataset 적용  
KETI 데이터셋 적용을 위해 graph 코드를 작성하였습니다: graph_keti.py  
해당 코드는 GCN 연산을 위한 그래프 구성을 구하는 코드 입니다.  

</br> 
KETI 데이터의 GCN 연산 과정은 다음과 같습니다.  

![image](https://github.com/Neural-IntLab/Kinetic_GAN_LimSuH/assets/82634312/e8707e0a-86e0-46f5-b9b4-b29aa1fb5e2c)  

다섯 단계에 걸쳐 GCN연산이 진행되며, 양옆으로 이웃한 노드가 연결된 center 노드로 값이 업데이트 됩니다.  
GCN 관련 참고 자료:  
[![Video Label](http://img.youtube.com/vi/YL1jGgcY78U/0.jpg)](https://www.youtube.com/watch?v=YL1jGgcY78U)  

</br>

### KETI 학습


</br> 

### 학습 데이터 및 생성 데이터 확인
NTU, KETI 데이터 각각에 대해 학습을 완료하였으며 원본데이터-학습을 완료한 모델이 생성해낸 합성 데이터를 확인해본 노트북을 업로드 하였습니다.  
각각 NTUtrain.ipynb, KETItrain.ipynb 입니다.  
또한 각 노트북에서 각 생성데이터의 FID 점수를 확인해 보실 수 있습니다.  

NTU가 6점대인것에 비해, KETI는 152인것을 확인하였습니다.  
단순 visualization에서도 NETU가 보다 뛰어난 결과물을 보였습니다.


