## Loading the Analysis Window

When you start the program, after a short wait, the initial window appears. Click the ANALYSIS button in the center of the initial window to use the image processing software.

![init](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/initial%20screen.png)
![analysis](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/analysis%20screen.png)


## Loading Image Data

You can load image files from your local computer by clicking the "Inputting Image Data" button at the top left of the analysis window.

![input](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/input%20road%20image.png)


## Applying Techniques

You can apply methods from the options on the left side of the analysis window to the loaded image. The available methods are as follows:

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
Image preprocessing is the process of optimizing the original image for analysis and processing. Through preprocessing steps, image data can be analyzed more effectively, maximizing the performance of machine learning or deep learning models. Invert Color is a preprocessing method that converts each pixel's color to its opposite color.

![Invert Color](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/invert%20color.png)


### Filtering
Filtering is the process of applying specific mathematical operations to modify or enhance an image. The main purpose of filtering is to remove noise, emphasize edges, or extract specific features of the image. Median Blur is a nonlinear filtering technique used to remove noise from an image. This method replaces each pixel with the median value of the surrounding pixels, smoothing the image.

![Median Blur](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/Median%20Blur.png)


### Correction
Correction refers to the process of fixing various defects or distortions to enhance the quality of an image. Power Law Transformation is a nonlinear transformation technique used to adjust the brightness of an image. This technique is commonly used to adjust contrast or apply specific effects.

![Power Law Transformation](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/Power%20Law%20Transformation.png)


### Transformation
In image processing, Transformation refers to the process of converting or manipulating pixel values to create a new image. This technique is used to change or enhance the characteristics of an image. Pencil Sketch is a transformation technique that gives the original image the effect of being drawn with a pencil.

![Pencil Sketch](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/Pencil%20Sketch.png)


### Feature Extraction
Feature Extraction is an important step in image processing where meaningful information or patterns in an image are identified and represented in numerical form. PCA is a technique that reduces high-dimensional data to lower dimensions and is widely used in image processing.

![PCA](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/PCA(20).png)


### Segmentation
Segmentation is the process of dividing an image into multiple meaningful regions. This technique is used to identify and analyze specific objects or areas within an image. FCN (Fully Convolutional Network) is a deep learning model primarily used for image segmentation tasks.

![FCN](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/FCN.png)


### Clustering
Clustering in image data uses the characteristics of images to group similar images based on their features. This process helps to understand the structure of the data and identify images with similar traits. K-means clustering is used to divide a given image into K clusters based on color or features.

![K-means](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/K-means.png)


### Transfer Learning
Transfer Learning is a technique that applies an already trained model to new tasks, which is very useful for processing image data. EfficientNetB0 is the first model in the EfficientNet series developed by Google, optimized for image classification tasks.

![EfficientNetB0](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/EfficientNetB0.png)


## Setting HyperParameters
For methods like Invert Color, the processed image is displayed by applying a specified formula to the loaded image. However, for methods like Edge Detection, parameters can be directly input by the user to finely control the technique and obtain a new image.

In the case of Edge Detection, you can directly set the Low threshold and High threshold.

![parameter](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/hyperparameter%20setting.png)

The methods that allow parameter settings are as follows:

| Category           | Method                                                                  |
|--------------------|-------------------------------------------------------------------------|
| Filtering           | Smoothening                                                             |
| Correction          | Binary, Edge Detection, Skeleton, Power Law Transformation              |
| Feature Extraction   | PCA                                                                    |





## Loading Processed Image Data
Through "Updating an Image" in the left panel, you can bring the processed image to the left panel for further application of techniques. This allows you to apply a technique multiple times or try different techniques in various orders.

### When Invert Color is Applied Twice

If Invert Color is applied twice, it will return to the original image.

![update](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/invert%20color%20update.png)
![x2](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/invert%20color%20x2.png)


### When Different Techniques are Applied

After applying sharpening followed by edge detection, the edges and contours of the image will appear more distinct.

![sharpening](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/sharpening.png)
![sharpening and edge detetection](https://github.com/CDSSK/Open_Computer_Vision_Software/blob/master/Program%20screen/sharpening%20and%20edge%20detection.png)

## Resetting the Image

You can reset all images on the panel by clicking the "Clear Panels" button.

