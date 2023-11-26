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
- **Content Dataset:** [Google Scraped Image Dataset](https://www.kaggle.com/datasets/duttadebadri/image-classification/)
- **Style Dataset:** [Best Artworks of All Time](https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time/)

### Pretrained Weights
Download the weights and update the link in the jupyter notebook in the "Hyper Parameters" section.  
- **VGG19 Encoder:** [Encoder](insert_link_here)
- **VGG19 Decoder:** [Decoder](insert_link_here)

### Trained Weights
Download the weights and update the link in the jupyter notebook in the "Hyper Parameters" section.  
- **Trained Model Weights:** [model11](insert_link_here) (Content Loss Weight: 1.0, Style Loss Weight: 1.0)

## How to Run

Execute the code cells in the provided Jupyter Notebook. Ensure that the required datasets and weights are available. Adjust hyperparameters as needed.
You can customize hyperparameters in the notebook. Change them at the top of the notebook under the "Hyper Parameters" section.
## References

- [Learning Linear Transformations for Fast Arbitrary Style Transfer](https://arxiv.org/abs/1808.04537) by [Li, Xueting and Liu, Sifei and Kautz, Jan and Yang, Ming-Hsuan]

- [Neural Style Transfer](https://medium.com/ai-techsystems/neural-style-transfer-742dca137976)
