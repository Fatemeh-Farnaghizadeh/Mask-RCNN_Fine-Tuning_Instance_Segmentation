# Fine-Tuning Mask R-CNN for Instance Segmentation on NDD20 Dataset

This repository contains code for fine-tuning the Mask R-CNN model for instance segmentation on the NDD20 dataset. It also includes a notebook that explains how to create instance-based masks from annotations in `.json` format.

![Example Output](mask_RCNN.png)

![Example Output](mask_Rcnn_mask.png)


## Dataset

The NDD20 dataset is available on my Kaggle account. You can download it by following this [link](https://www.kaggle.com/datasets/fatemehfarnaghizadeh/ndd20-instance-based-mask).

Masks are created using the provided [Mask_Creation Notebook](Mask_Creation.ipynb).

## Getting Started

To get started with this project, follow these steps:

### Clone the Repository

```bash
git https://github.com/Fatemeh-Farnaghizadeh/Mask-RCNN_Fine-Tuning_Instance_Segmentation.git
cd Mask_RCNN_Finetuning
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt 
```
### Training

For the complete data loading and training process, refer to the [Mask_RCNN_Finetuning Notebook](Mask_RCNN_Finetuning.ipynb).

## Kaggle Notebook

I have also created a Kaggle notebook related to this repository. You can check it out [here](https://www.kaggle.com/code/fatemehfarnaghizadeh/mask-rcnn-finetuning).