## 분석창 불러오기
프로그램을 시작하면 약간의 대기시간 이후 초기 창이 뜹니다. 초기 창 가운데 ANALYSIS 버튼을 클릭하여 이미지 처리 소프트웨어를 사용할 수 있습니다.

## 이미지 데이터 불러오기
해당 분석 창 왼쪽 상단의 Inputting Image Data 버튼을 클릭해 로컬 컴퓨터 내의 이미지 파일을 불러올 수 있습니다. 

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


Invert Color 기법을 적용했을 때의 결과는 다음과 같이 나타납니다.

### Preprocessing
이미지 전처리는 원본 이미지를 분석하고 처리하기 위해 최적화하는 과정입니다. 전처리 단계를 통해 이미지 데이터를 더 효과적으로 분석하고, 머신러닝 또는 딥러닝 모델의 성능을 극대화할 수 있습니다.

![Invert Color](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/invert%20color.png)


### Filtering
Median Blur

### Correction
Edge Detection

### Transformation
Pencil Sketch

### Feature Extraction
PCA

### Segmentation
FCN

### Clustering
K-means

### Transfer Learning
EfficientNetB0


### B

## 파라미터 설정
Invert Color 같은 메소드의 경우에는 불러온 이미지를 정해진 수식을 적용하여 처리된 이미지를 보여줍니다. 그러나 Edge Detection과 같이 사용자로 부터 파라미터를 직접 입력 받아 세밀하게 기법을 컨트롤하여 새로운 이미지를 얻을 수 있습니다.    

파라미터를 설정할 수 있는 메소드들은 다음과 같습니다.
| Category           | Method                                                                  |
|--------------------|-------------------------------------------------------------------------|
| Filtering           | Smoothening                                                             |
| Correction          | Binary, Edge Detection, Skeleton, Power Law Transformation              |
| Feature Extraction   | PCA                                                                    |





## 적용된 이미지 데이터 불러오기
왼쪽 창의 Updating an Image를 통해 기법이 적용된 이미지를 왼쪽 패널로 옮겨와 기법을 추가로 적용받게 할 수 있습니다. 이를 통해 한 번의 기법을 여러 번 수행할 수 도 있고 각기 다른 기법들을 다양한 순서로 적용해볼 수도 있습니다.


## 이미지 초기화
