# 이 작업은 사과 이미지를 분석해 품질 등급을 알려주는 코드입니다.





### 1. Flutter의 camera x 를 이용해 카메라 진입
![1](https://user-images.githubusercontent.com/94780831/175015380-e5bea0b3-f95b-4a5b-ae8e-f775be826363.PNG)


### 2. 사진을 찍거나 미리 다운된 이미지 선택

![2](https://user-images.githubusercontent.com/94780831/175015573-eece241a-3612-46cb-a46f-39022330c555.PNG)


### 3. 사과 품질 이미지 L(특상) M(상) S(보통) 품질을 확인한다. (정확도 90%)
![3](https://user-images.githubusercontent.com/94780831/175015795-cf1ec7a5-2b1a-4552-8d01-4942c8c4f551.PNG)


### tensorflow 에서 직접 제작한 모델을 tflite(tensorflow lite) 모델로 변환 후 flutter 앱에 이식하는 작업이 필요함
- label 값 .txt 파일 및 라벨링 작업이 필요하다.
- 양자화를 통해 정확도의 극 소량 손해를 보지만 용량 감소를 통해 App 더 적합해진다.
