# DeepPhoto Project

This project is part of the course Deep Learning - MSc Data Science for Business - HEC Paris and Ecole Polytechnique

<img src="https://github.com/Miguel-Jiahao-Wang/InstanceSegmentation_NeuralTransfer/blob/master/examples/usecase_deepphoto.png" />

# Team members

Ching-yu Lin

Fernado Perez

Jorgen Lund

Jiahao Wang

Roberta Conard 

# Usecase

Design a mobile application prototype that allows users to do fine-grained image editing in real-time before uploading the social applications on their mobile phones.

# Techniques

We adapted the semantic segmentation technique (RefineNet) to identify the human part in images. Then we use the neural style transfer to transfer the part of image that user selected. For more details, please see the slides.

# Final Result

We finetuned and pruned the RefineNet to our use case.

Our smallest model: LightNet-MobileNet acheived 0.809 mIoU with only 13MB size, which outperforms the off-the-shelf DeepLabV3 (0.806 mIoU, 233MB) in this specific task in terms of the quality, size and inference speed.

<img src="https://github.com/Miguel-Jiahao-Wang/InstanceSegmentation_NeuralTransfer/blob/master/examples/qualitative_evaluation.png" />

# Duration

This project was conducted between 2019-Nov-05 and 2019-Nov-11.

# Reference

The RefineNet model architecture is adapted from https://github.com/ansleliu/LightNet

