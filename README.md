# xray-pneumonia-detection

For this project, Kaggle data set with chest X-ray images of healthy patients and patients with pneumonia is used (https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia). The goal is to correctly detect pneumonia based on an X-ray image. '

The possible models are:
- Convolutional Neural Network
- Pretrained Image Classification networks like VGG, ResNet, Inception
- Vision Transformers ([Dosovitskiy et al., 2020](https://arxiv.org/abs/2010.11929))
- Siamese Networks

## Results

| Model | Training accuracy (%) | Test accuracy (%) |
| --- | :---: | :---: |
| Custom ConvNet | 97 | 94 |
| Fine-tuned Inception | 93 | 91 |
| Fine-tuned Vision Transformer | | 84 |


### TODO

Possible fixes:
- Change image size in data loading
- Change imag size in preprocessing
- Gather more data for normal class

