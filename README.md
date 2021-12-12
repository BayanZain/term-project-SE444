# term-project-SE444

------ لغتي إشارتي ------

Our project is an Android mobile application that detect the Arabic sign language gestures via the phone camera.
We used a dataset which includes a training images for different 32 letters. These images are trained via a python
code that mainly use the tensorflow: 2.7.0 library. 

For implementing the sign language recognition software, we tried first to use the concept of image classificaton 
via a python code that traint the data and detect the sign language in realtime using the openCV:4.5.3 library, 
which helps in the realtime detection via the labtop camera. This file with the exported model, dataset, and labels file 
are under Iteration 1 folder Under Data Training Code folder. The training code need to be opened with jupyter 
notebook as it has (.ipynb) extenstion. We used VSCode software in implementing the code, and installed the jubyter
extension withing it.

As a second trial, we created an Android mobile application that import the training model and use it in the realtime 
detection. For this iteration, we created another training code that train the images and export the model as tflite 
file. Under iteration 2 there are two folders, which are Data Training Code that includes the python code in 
two versions, as python file (.py) and jupyter file (.ipynb), with the exported model and the dataset. Sign language 
recognition app is the Android application and it needs to have Android Studio installed on the device in order to be 
able to open the project. 
