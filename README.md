# Estimation-of-COVID-19-Transmission-Risk
Real-time Screen Analysis using Object and Scene Detection(2020.12.)

# 내용
COVID-19의 확산과 지속으로 외출에 대한 불안은 증가하고 있다. 이에 국내 마스크 착용 의무화 지침이
진행되고 있지만, 장소별 위험 정도는 알 수 없다. 이를 해결하기 위해 본 프로젝트는 질병 관리청에서 제시한
방역 수칙을 기준으로 특정 장소의 COVID-19 전파 위험도 측정을 진행한다. 전파 위험도를 측정하기 위
한 세 가지 기준은 공간 개폐 여부, 마스크 착용 상태, 군중 밀집도이다. 세 가지 기준에 대한 데이터로
YOLO 모델과 이미지 분류 모델을 학습시키고 Deep Learning 알고리즘을 적용하여 값을 산출한다. 결과적
으로 장소의 정보를 수집하여 COVID-19 전파 위험도 평가를 수행하고 CCTV와 같은 Live Feed 영상에 적
용해 실시간으로 알려 예방할 수 있도록 기대한다.

# 환경 설정
1. install YOLO v4 following https://github.com/augmentedstartups/YOLOv4-Tutorials
2. Download CUDNN DLLs (cudnn64_8.dll) from [Nvidia](https://developer.nvidia.com/rdp/cudnn-archive)
3. download [Weights](https://drive.google.com/file/d/1PTlUjXHEavLScCeZcZjbW_oldgi6EJg6/view?usp=sharing)
4. run 'Social_Distance_avg_run' 

# 실행 화면
![s](https://user-images.githubusercontent.com/59173164/102960993-9a9d3580-4526-11eb-9a62-8421a4aef3ef.PNG)
![다운로드](https://user-images.githubusercontent.com/59173164/111056091-aeba5880-84bf-11eb-91d0-566255ab9d27.gif)


# Reference
1. https://github.com/augmentedstartups/YOLOv4-Tutorials
2. https://github.com/VictorLin000/YOLOv3_mask_detect

# Member
- 최성원([worldbrighteststar](https://github.com/worldbrighteststar))
- 공재호([asebn1](https://github.com/asebn1))
- 이민호([yeemh](https://github.com/yeemh))
- 이승민([effectivemadness](https://github.com/effectivemadness))
- 지호진([sj59228](https://github.com/sj59228))

