# Chest_XRay_Example
The repo contains example notebooks for Chest XRay Transfer Learning Example contained in draft AI Frontiers Paper 'Deep Learning and its Application for Healthcare Delivery in Low-Middle Income Countries'


Each classifier is trained with a balanced set of Pneumonia and Normal image, leading to a naive prediction with 50% accuracy.  Models are trained using distinct Train, Validation and Test datasets:
 - Train:  Used for actual model training
 - Valid:  Used for model selection and hyperparameter tuning
 - Test:  Used to evaluate final result

## Notebooks:
-  Pneumonia_RESNET18_50_224.ipynb
-  Pneumonia_RESNET18_100_224.ipynb
-  Pneumonia_RESNET18_200_224.ipynb
-  Pneumonia_RESNET18_300_224.ipynb
-  Pneumonia_RESNET18_1000_224.ipynb



## Supporting Software:
- fastai_addons.py
- fastai_helpers.py
- helpers.py
- pneumonia_loaders.py
- pneumonia_new_loader.py
- 'Generate Resized Images.ipynb'


## Dependencies
- [fast.ai Framework](https://docs.fast.ai/)
- Chest X-ray dataset is available on [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia ) and [Mendeley](https://data.mendeley.com/datasets/rscbjbr9sj/3)
