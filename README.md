# Artistic-Neural-Style-Transfer

This project focuses on Neural Style Transfer using the VGG19 model. The goal is to combine the content of one image with the style of another to create visually appealing stylized images.


## Prerequisites

- matplotlib  
- pytorch  
- numpy  
- torchvision  
- tqdm
## Resources

### Dataset
For traning download Dataset from given kaggle link. And update link of the dataset in the jupyter notebook in the 'Hyper Parameters' section.  
- **Content Dataset:** [COCO 2017](/kaggle/input/coco-2017-dataset/coco2017/train2017)
- **Style Dataset:** [Best Artworks of All Time](https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time/)

### Pretrained Weights
Download the weights and update the link in the jupyter notebook in the "Hyper Parameters" section.  
- **VGG19 Encoder:** [Encoder](https://drive.google.com/file/d/1JQ1wSsi4QT0O8yGgkoAJS4F0Eb9NCOaU/view?usp=sharing)
- **VGG19 Decoder:** [Decoder](https://drive.google.com/file/d/1lGqgE5CNy4sFJbb-LHAUhofEQ5F0igq7/view?usp=sharing)

### Trained Weights
Download the weights and update the link in the jupyter notebook in the "Hyper Parameters" section.  
- **Trained Model Weights:** [model11](insert_link_here) (Content Loss Weight: 1.0, Style Loss Weight: 1.0)

## How to Run

Execute the code cells in the provided Jupyter Notebook. Ensure that the required datasets and weights are available. Adjust hyperparameters as needed.
You can customize hyperparameters in the notebook. Change them at the top of the notebook under the "Hyper Parameters" section.
Or you can run code on [Kaggle Notebook](https://www.kaggle.com/code/nishantvalvi1504/artistic-neural-style-transfer) 
## References

- [Learning Linear Transformations for Fast Arbitrary Style Transfer](https://arxiv.org/abs/1808.04537) by [Li, Xueting and Liu, Sifei and Kautz, Jan and Yang, Ming-Hsuan]

- [Neural Style Transfer](https://medium.com/ai-techsystems/neural-style-transfer-742dca137976)
