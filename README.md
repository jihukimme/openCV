# openCV

## openCV란 무엇인가
    OpenCV는 Open Source Computer Vision의 약자로 영상 처리에 사용할 수 있는 오픈 소스 라이브러리 이다. 
    컴퓨터가 사람의 눈처럼 인식할 수 있게 처리해주는 역할을 하기도 하며, 
    우리가 많이 사용하는 카메라 어플에서도 OpenCV가 사용하기도 한다. 
    (추가로 자율주행자동차에서 자동차의 눈이 되주는 것이 카메라와 OpenCV가 합작해서 해낸 일이다.) 

#### 추가로 openCV가 사용되는 예 
    -공장에서 제품 검사할 때   
    -의료 영상 처리 및 보정 그리고 판단
    -CCTV영상
    -로보틱스

등 다양한 범위에서 사용되고 있다. 

카메라로 찍어서 할 수 있는 모든 일은 OpenCV로 처리할 수 있다. 

여기에 머신 러닝과 A.I를 활용해서 그 활용도를 더욱 넓혀가고 있는 중이다.



## 컴퓨터비전이란 무엇인가
Computer Vision: 카메라로 얻은 일련의 영상들

    카메라가 사진을 찍으면 컴퓨터는 이를 단순한 숫자로 인식한다. 
    오로지 0과 1로 이루어져서 다시 나올 뿐이다.
    컴퓨터는 이러한 숫자의 행렬로 사진 및 여러 형태를 인식한다. 
    그렇다면 우리는 이러한 형태를 가지고 컴퓨터에게 유의미한 정보를 입력해줌으로써 사람이 보는 시선과 최대한 비슷하게 만들어야 하는 것이다. 
    하지만 여기에는 많은 문제가 도사리고 있다. 우리의 시각 정보는 왜곡이 많다. 
    예를 들어 우리가 보는 관점에 따라 사물이 왜곡될 확률이 있다. 다른 왜곡은 빛의 양에 따라 달라지기도 하며 비가 오는 경우에는 더욱 심각해진다. 
    심지어 카메라의 성능에 따라 계속 변한다. 
    전기적 노이즈도 생각해봐야 한다. 
    이러한 왜곡을 이겨내고서 우리는 정확한 이미지 처리가 필요한 것이다. (심지어 카메라는 3D 정보를 2D로 받아들이고 있다.) 

    이 부분에 대한 해결책은 머신러닝 기술로 어느정도 보완하고 있다. 
    혹은 다른 추가적인 데이터를 활용해서, 예를 들어 라이다 센서 혹은 거리 센서를 활용해서 왜곡정보를 올바르게 해석하기 위한 노력을 하고 있다. 
    그리고 OpenCV는 이러한 다양한 문제들을 해결하기 위한 도구를 제공해주는 것을 목표로 한다. 
    지금도 많은 연구가 이루어지고 있으며, 다양한 자료들이 쏟아져 나오고 있다. 

 

OpenCV와 사용할 수 있는 언어로는 C/C++, 파이썬, Java등이 있다. 요새 많이 쓰이는 언어로는 파이썬이 많이 사용되고 있다. 
빅데이터와 머신 러닝에서 강점을 보이고 있기에 파이썬이 많이 쓰인다.
하나의 언어를 제대로 배워두면 다른 언어에 대한 장벽은 높지 않은 편이므로 일단은 파이썬으로 진행하려 한다. 
    



# 아나콘다와 주피터노트북을 활용해 진행



