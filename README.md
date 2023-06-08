# Sign-Detection-Using-Tensor-mediapipeline
I have tried to implement the sign detection projects which detects the 3 signs. It detects the Hello, ILove You , thanks.
Firstly, I have created functions to draw the landmarks on the face using cv2 and mediapipe-hostilic. Then using cv2
I have captured one picture and analysed all marks of left hand right hand face by detecting all the landmarks.

![image](https://github.com/Vignesh142/Sign-Detection-Using-Tensor-mediapipeline/assets/101886482/bf34066e-81af-4364-a9c7-9715670b5c1b)
##### Landmarks drawn detecting face, hands and body
Below is an example frame of the capture
![image](https://github.com/Vignesh142/Sign-Detection-Using-Tensor-mediapipeline/assets/101886482/1e73c45e-bd33-4f34-9913-03e71b1febdf)
#### Collecting training data
Here, I have collected all the samples to test and train. For each sign I have collected 30 samples and for one sample video i have collected
30 frames of images as one.
![image](https://github.com/Vignesh142/Sign-Detection-Using-Tensor-mediapipeline/assets/101886482/a65212d4-5093-4114-9391-5c7628483a6e)

#### Creating Neural Network for training data
Later, I have collecting the multiple frame and made as a video.For training data , I have collected the multiple frames of video for the 3 
signs- hello, iloveyou, and thanks.
Then i have preprocessed the collected data and built an lstm neural network to train the data.

![image](https://github.com/Vignesh142/Sign-Detection-Using-Tensor-mediapipeline/assets/101886482/a3790909-3e46-4ecc-9c59-6fc8cb9d079c)
