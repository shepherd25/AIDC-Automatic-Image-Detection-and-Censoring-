# AIDC
 automatic image detection and censoring

# Installation
1> Download the files from the repository.
2> Install Anaconda on your computer make a virtual environment (lookup anaconda for more queries) and run the file handgun.py if you are not able to run it the terminal ask you to install the missing packages, use conda install to install the necessary packages.
or
2> conda install -r requirements.txt
also install tensorflow-GPU , conda install tensorflow-gpu = 1.14.0
## Requirements
Python 3.4, TensorFlow 1.3, Keras 2.0.8 and other common packages listed in `requirements.txt`.

## How to run the program
python handgun.py splash --weights=filename or path to the weights(.h5 file) --image=filename or path
eg
python handgun.py splash --weights=D:\mask_rcnn_handgun.h5 --image=pic.jpg

# To train the Model
eg
python handgun.py train --dataset=D:\datasets\handgun --weights=D:\mask_rcnn_coco.h5
# Citation
 ```
 @misc{matterport_maskrcnn_2017,
   title={Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow},
   author={Waleed Abdulla},
   year={2017},
   publisher={Github},
   journal={GitHub repository},
   howpublished={\url{https://github.com/matterport/Mask_RCNN}},
 }
 ```
# version
1.1

# Other elements under development
1> extension for the chrome web browser.
2> Integration of the web scrapper with the extension.
