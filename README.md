# ktrial
All datasets come from kaggle, using kaggle notebook as IDE
## clsf-cd
Dataset: cat-and-dog, for classification.
Network: CNN, with 3 convolutional layers, 3 linear layers. Each layer has function ReLU, while conv has function BatchNorm before and MaxPool after.
Update: Loss function is CrossEntropyLoss, Optimizer is SGD, with learning rate 0.01, momentum 0.9.
Epoch is 10, final Accuracy is 84.1%.

## segbrain-unet
Dataset: Brain MRI Segmentation, for segmentation.
Network: [UNet](https://arxiv.org/pdf/1505.04597.pdf)
Update: Loss function is CrossEntropyLoss, Optimizer is SGD, with learning rate 1e-3, momentum 0.7.
Epoch is 10, final validation loss is 0.0453?
