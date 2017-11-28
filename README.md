# PolyFace
PolyFace: Face Recogntion with Pytorch.


### Training Data:
Our Model was trained on the ***cleaned CASIA Dataset (around 450K).***




### Preprocessing: 
MTCNN face detection is used, and then a simple face alignment is applied with the 5 keypoints created by MTCNN.



### Model:
A slightly modified google inception_resnet_v1 is used with input size 160*160.



### Method:
Will be described in upcoming document.



### Performance:
Three training logs are provided. \
Currently, the best performance achieved was **99.583% on LFW data set**. 



### Speed:
With a single Titan X Pascal, it tasks around 36 hours to finish 150,000 steps with batch size 128. 
With a old Titan X, training 150,000 steps takes around 47 hours. 



### Further information: 
We are still preparing our technical document. We will release our code with the technical report.



### Useful Links: 
FaceNet: Face recognition using Tensorflow. \
https://github.com/davidsandberg/facenet

SphereFace: Deep Hypersphere Embedding for Face Recognition, CVPR 2017. \
https://github.com/wy1iu/sphereface



### Contact

Xianbiao Qi: qixianbiao@gmail.com
