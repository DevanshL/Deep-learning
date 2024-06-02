# Swin Transformer: A Hierarchical Vision Transformer

This repository contains the implementation of the Swin Transformer, a state-of-the-art vision transformer architecture for computer vision tasks. The Swin Transformer is a variant of the Vision Transformer (ViT) model, designed to efficiently capture local and global dependencies through a hierarchical structure and shifted window partitioning.

## Files

- `swin-transformer.ipynb`: A Jupyter Notebook containing the implementation of the Swin Transformer architecture and training/evaluation code.
- `swin-transformer_pretrained.ipynb`: A Jupyter Notebook with code for loading and using pre-trained Swin Transformer models.

## Dataset

The dataset used for training and evaluating the Swin Transformer models can be found at the following Google Drive link:

![Dataset Google Drive Link](https://drive.google.com/drive/folders/19dRMuuGBtguy2JAtmF7JxEE2Mnq241iy)

Please download the dataset and update the appropriate paths in the Jupyter Notebooks.

## Architecture

The Swin Transformer architecture follows a hierarchical design, combining local and global attention mechanisms through window partitioning and shifted window partitioning. The architecture diagram is shown below:

![Swin Transformer Architecture]([https://example.com/swin-transformer-architecture.png](https://github.com/DevanshL/Deep-learning/blob/main/Swin%20Transformer/image/swin-transformer.png))


## Usage

1. Clone the repository or download the files.
2. Install the required packages specified in the `requirements.txt` file.
3. Download the dataset from the provided Google Drive link.
4. Open the `swin-transformer.ipynb` or `swin-transformer_pretrained.ipynb` notebook and follow the instructions to train or evaluate the models, respectively.

## Requirements

The required packages for this project are listed in the `requirements.txt` file, which can be found at the following path:

https://github.com/DevanshL/Deep-learning/blob/main/Swin%20Transformer/requirements.txt

You can install the packages using the following command:

```
pip install -r requirements.txt
```

## References

- [Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030)

