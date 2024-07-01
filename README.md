Requirements: /n
!pip uninstall segmentation-models -y /n
!pip uninstall tensorflow -y /n
!pip uninstall keras -y /n
!pip uninstall tensorflow-estimator -y /n
!pip uninstall mtcnn -y /n

!pip install -U -q segmentation-models /n
!pip install -q tensorflow==2.2 /n
!pip install -q keras==2.3.1 /n
!pip install -q tensorflow-estimator==2.2 /n
!pip install mtcnn
 
Python version 3.8 /n
TensorFlow 2.2 /n
Tensorflow-estimator 2.2 /n
MTCNN /n
Keras 2.3.1 /n
OpenCV /n

Pre-trained models to be used are saved as models and can be downloaded (unzipped) for implementation.
