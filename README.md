# U-Net
Tensorflow implementation of [https://github.com/PacktPublishing/Hands-On-Computer-Vision-with-TensorFlow-2/tree/master/Chapter06] It was trained on the Cityscapes datset.

## Requirements
1. Tensorflow
2. numpy
3. Matplotlib

## Additional Files
1. cityscapes_utils.py: utility functions for the Cityscapes dataset 
2. fcn.py: functional implementation of the FCN-8s architecture 
3. keras_custom_callbacks.py: custom Keras callbacks to monitor the trainings of models 
4. mnist_utils.py: utility functions for the MNIST dataset, using tensorflow-datasets 
5. plot_utils.py: utility functions to display results
6. tf_losses_and_metrics.py: custom losses and metrics to train/evalute CNNs
7. tf_math.py: custom mathematical functions reused in other scripts
8. unet.py: functional implementation of the U-Net architecture



## Cityscapes datasets
1. Need to download gtCoarse, gtFine, LeftImg8bit, LeftImg8bit_blurred (https://www.cityscapes-dataset.com/)
2. Dataset file path
* cityscapesScripts-master
  - datasets
    + cityscapes
      - gtCoarse
      - gtFine
      - leftImg8bit
      - leftImg8bit_blurred

## U-Net architecture
![unet](https://user-images.githubusercontent.com/75243173/168416744-734a14a7-7d66-44ab-9ec7-099ba4e58404.png)
