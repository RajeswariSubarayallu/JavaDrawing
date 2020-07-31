# JavaDrawing
An android application used to recognize gesture recognition of handwritten digits and operator to perform simple arithmetic calculations.
<br>
<br>
Activity_main.xml: File determining the app layout
<br>
<br>
<img src="https://github.com/rajeswari-s/im/blob/master/layout.png">
<br>
<h2>Example<h2>
<br>
<h3>Addition operator</h3>
<br>
<img src="https://github.com/rajeswari-s/im/blob/master/image.png">
<br>
<h3>Contour Drawing and Segmentation</h3>
<br>
<img src="https://github.com/rajeswari-s/im/blob/master/ImageSeg.jpg">
<br>
Segmented images:
<img src="https://github.com/rajeswari-s/im/blob/master/Image1.jpg">
<img src="https://github.com/rajeswari-s/im/blob/master/Image2.jpg">
<img src="https://github.com/rajeswari-s/im/blob/master/Image3.jpg">
<img src="https://github.com/rajeswari-s/im/blob/master/Image4.jpg">
<br>
These images then passed onto the classification module to predict and atlast calculation operations were made and finally we get the results.
<br>
TensorFlow Lite inference is used to execute TensorFlow Lite model on-device to make predictions bases on input data.
<br>
data.pb is a combined dataset model for digits and operator and has a total classes of 14.
<br>
0 to 9 -> 10 classes
<br>
10 -> +
<br>
11 -> -
<br>
12 -> *
<br>
13 -> /
