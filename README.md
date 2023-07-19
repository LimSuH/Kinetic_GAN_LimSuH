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



