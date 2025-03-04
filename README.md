## 분석창 불러오기
프로그램을 시작하면 약간의 대기시간 이후 초기 창이 뜹니다. 초기 창 가운데 ANALYSIS 버튼을 클릭하여 이미지 처리 소프트웨어를 사용할 수 있습니다.
![init](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/initial%20screen.png)
![analysis](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/analysis%20screen.png)

## 이미지 데이터 불러오기
해당 분석 창 왼쪽 상단의 Inputting Image Data 버튼을 클릭해 로컬 컴퓨터 내의 이미지 파일을 불러올 수 있습니다. 
![input](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/input%20road%20image.png)

## 원하는 기법 적용
분석 창 왼쪽의 ? 내의 메소드를 불러온 이미지에 적용할 수 있습니다.
사용가능한 메소드는 아래와 같습니다.
| Category           | Method                                                                                     |
|--------------------|--------------------------------------------------------------------------------------------|
| Preprocessing       | Grayscale, Invert Color, Red Attribute, Green Attribute, Blue Attribute                   |
| Filtering           | Average Blur, Gaussian Blur, Median Blur, Bilateral Blur, Sharpening, Smoothening        |
| Correction          | Binary, Edge Detection, Skeleton, Power Law Transformation, Contrast Enhancement         |
| Transformation      | Pencil Sketch, Color Pencil Sketch, Cartoonify, Watercolor, Emboss                       |
| Feature Extraction  | SIFT, PCA, Gabor                                                                          |
| Segmentation        | FCN, DLAB                                                                                |
| Clustering          | K-means, Mean Shift Clustering                                                            |
| Transfer Learning   | VGG16, ResNet50, EfficientNetB0, DenseNet121, MobileNetV2, InceptionV3, Xception       |


### Preprocessing
이미지 전처리는 원본 이미지를 분석하고 처리하기 위해 최적화하는 과정입니다. 전처리 단계를 통해 이미지 데이터를 더 효과적으로 분석하고, 머신러닝 또는 딥러닝 모델의 성능을 극대화할 수 있습니다.Invert Color는 각 픽셀의 색상을 그 반대 색상으로 변환하는 전처리 방법입니다.

![Invert Color](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/invert%20color.png)


### Filtering
필터링은 이미지를 변형하거나 개선하기 위해 특정한 수학적 연산을 적용하는 과정입니다. 필터링의 주요 목적은 노이즈 제거, 경계 강조, 또는 이미지의 특정 특징을 추출하는 것입니다
Median Blur는 이미지에서 노이즈를 제거하기 위한 비선형 필터링 기법입니다. 이 방법은 각 픽셀을 주변 픽셀의 중간값(median)으로 대체하여 이미지를 부드럽게 만듭니다.

![Median Blur](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/Median%20Blur.png)


### Correction
Correction은 이미지의 품질을 향상시키기 위해 다양한 결함이나 왜곡을 수정하는 과정을 의미합니다. 
Power Law Transformation은 이미지의 밝기를 조정하기 위해 사용하는 비선형 변환 기법입니다. 이 기법은 주로 이미지의 대비를 조정하거나 특정 효과를 주기 위해 사용됩니다.

![Power Law Transformation](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/Power%20Law%20Transformation.png)


### Transformation
이미지 처리 기법 중 Transformation은 이미지의 픽셀 값을 변환하거나 조작하여 새로운 이미지를 생성하는 과정을 의미합니다. 이 기법은 이미지의 특성을 변경하거나 향상시키기 위해 사용됩니다.
Pencil Sketch는 원본 이미지를 연필로 그린 듯한 효과를 주는 변환 기법입니다. 

![Pencil Sketch](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/Pencil%20Sketch.png)


### Feature Extraction
Feature Extraction은 이미지 처리에서 중요한 단계로, 이미지 내에서 의미 있는 정보나 패턴을 식별하고 이를 수치적 형태로 표현하는 과정입니다. 
PCA는 고차원 데이터를 저차원으로 축소하는 기법으로, 이미지 처리에서도 널리 사용됩니다

![PCA](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/PCA(20).png)


### Segmentation
(Segmentation)은 이미지를 여러 개의 의미 있는 영역으로 나누는 과정입니다. 이 기법은 이미지 내에서 특정 객체나 영역을 식별하고 분석하기 위해 사용됩니다. 
FCN(fully convolutional network)은 주로 이미지 분할(Segmentation) 작업에 사용되는 딥러닝 모델입니다.

![FCN](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/FCN.png)


### Clustering
이미지 데이터를 활용한 클러스터링은 이미지의 특징을 기반으로 유사한 이미지를 그룹화하는 기법입니다. 이 과정을 통해 데이터의 구조를 이해하고, 비슷한 특성을 가진 이미지를 식별할 수 있습니다. 
K-means 클러스터링은 주어진 이미지의 색상이나 특징을 기반으로 K개의 클러스터로 나누는 데 사용됩니다.

![K-means](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/K-means.png)


### Transfer Learning
전이 학습(Transfer Learning)은 이미 학습된 모델을 새로운 작업에 적용하는 기법으로, 이미지 데이터를 처리하는 데 매우 유용합니다. 
EfficientNetB0는 Google에서 개발한 EfficientNet 모델 시리즈의 첫 번째 모델로, 이미지 분류 작업에 최적화된 신경망 아키텍처입니다. 

![EfficientNetB0](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/EfficientNetB0.png)


## 파라미터 설정
Invert Color 같은 메소드의 경우에는 불러온 이미지를 정해진 수식을 적용하여 처리된 이미지를 보여줍니다. 그러나 Edge Detection과 같이 사용자로 부터 파라미터를 직접 입력 받아 세밀하게 기법을 컨트롤하여 새로운 이미지를 얻을 수 있습니다.    

Edge Detection 같은 경우, Low threshold와 High threshold를 직접 설정할 수 있습니다.
![parameter](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/hyperparameter%20setting.png)

파라미터를 설정할 수 있는 메소드들은 다음과 같습니다.
| Category           | Method                                                                  |
|--------------------|-------------------------------------------------------------------------|
| Filtering           | Smoothening                                                             |
| Correction          | Binary, Edge Detection, Skeleton, Power Law Transformation              |
| Feature Extraction   | PCA                                                                    |





## 적용된 이미지 데이터 불러오기
왼쪽 창의 Updating an Image를 통해 기법이 적용된 이미지를 왼쪽 패널로 옮겨와 기법을 추가로 적용받게 할 수 있습니다. 이를 통해 한 번의 기법을 여러 번 수행할 수 도 있고 각기 다른 기법들을 다양한 순서로 적용해볼 수도 있습니다.

### Invert Color를 2번 적용하였을 경우
Invert Color 를 2번 적용하면 원본 이미지와 같게 됩니다.

![update](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/invert%20color%20update.png)
![x2](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/invert%20color%20x2.png)


### 서로 다른 기법을 적용한 경우
sharpening 이후 edge detection을 하면 이미지의 경계와 윤곽선이 더욱 뚜렷하게 나타나게 됩니다
![sharpening](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/sharpening.png)
![sharpening and edge detetection](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/sharpening%20and%20edge%20detection.png)

## 이미지 초기화
Clear Panels 버튼을 통해 패널 위의 이미지들을 모두 초기화할 수 있습니다.
