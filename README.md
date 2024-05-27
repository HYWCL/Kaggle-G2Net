<div align="center">
<h2> Kaggle - G2Net Detecting Continuous Gravitational Waves </h2>
</div>

<p align="center"><img src="https://imagine.gsfc.nasa.gov/Images/science/gwaves_still.jpg"/></p>

## 대회 설명
<img src="https://github.com/HYWCL/Kaggle---Contrail/assets/86766552/25484a71-9268-4024-a82e-fb197fd6d085" width="250" height="250"/>
<img src="https://github.com/HYWCL/Kaggle---Contrail/assets/86766552/94d8cf71-a5c5-4187-9cdf-f5d8bd224077" width="250" height="250"/>
<img src="https://github.com/HYWCL/Kaggle---Contrail/assets/86766552/1902d658-0bf6-4b33-9f70-9757f2c1a694" width="250" height="250"/>

왼쪽부터 순서대로 Image인 False Color Image, Mask인 Ground Truth Contrail Mask이며 마지막은 Image위에 Mask를 겹친 것입니다. <br>
Semantic Segmentation을 기반으로 모델을 구축하고 훈련 데이터로 False Color Image를 넣어 Ground Truth Contrail Mask를 찾는 게 목표인 대회입니다.

## 코드 설명
 - contrail-unet-train.ipynb (Pytorch - Unet을 이용한 훈련)
 - contrail-unet2-infer.ipynb (Pytorch - Unet을 이용한 추론)
 - contrails-dataset-ash-color.ipynb (데이터 전처리)
 - gr-icrgw-training-with-4-folds.ipynb (PytorchLightning - Unet을 이용한 훈련)
 - gr-icrgw-inference-4-folds.ipynb (PytorchLightning - Unet을 이용한 추론)

## 대회 결과
![1](https://github.com/HYWCL/Kaggle---Contrail/assets/86766552/61c4edb7-58b3-40ba-b444-635a735e816b)
