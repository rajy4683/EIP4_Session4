# EIP4_Session4
## -------------------------------------------------------------
## #########Model details##########    
    Model Used: ResNet38v2 (n=4 and version=2)
    Total params: 1,123,914
    Trainable params: 1,116,970
    Non-trainable params: 6,944
    
    Tweaked LR strategy to use reducing LR starting at Epoch 20 instead of Epoch 80
    
### #### Assignment4B_resnet_9016.ipynb     
    1. Keras model with image augmentation flag enabled
    2. Max Accuracy = 90.17% 
    3. Added GradCam

### #### Assignment4B_resnet_9019_CutOut.ipynb    
    1. Keras Model with Cutout function from 
    2. Accuracy = 90.19% 
    3. Cutout code embedded from https://github.com/yu4u/cutout-random-erasing 
   
