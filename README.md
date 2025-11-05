# Cauli-NET : Feature Fusion based Deep Dilated Convolution Network and Explainable Intelligence for Defect Identification in Small-Sample Cauliflower Crops
# Problem Description
Pathogen attack is one of the primary concerns for the low quality and productivity of cauliflower, resulting in substantial financial loss. Early disease diagnosis in cauliflower can aid in combating infections and ensure higher-quality production. However, early defect classification of cauliflower is a challenging task due to several physiological and ecological factors, such as complex and heterogeneous backgrounds, structural irregularity, and varying lesion size. The existing deep learning-based methods are limited to either leaves or edible vegetables, which fail to detect cauliflower defect due to complex geometric structures.
# Proposed Study
The proposed method is developed in two phases. First, a novel lightweight VegScratchNet method with an improved ReLU function has captured the deep feature maps of cauliflower vegetation while alleviating the vanishing gradient issue. In the second phase, the parallel fusion of features extracted from VegScratchNet and pre-trained MobileNetv2 is carried out to develop rich feature maps of the cauliflower images. Additionally, the dilated convolution and global average pooling layers enhance the fine-grained feature maps without additional network overhead.
# Results
The defect recognition accuracy of the proposed Cauli-NET method has been validated against the publicly available VegNet dataset. The results affirmed that the proposed method overshadows the existing methods for disease classification in cauliflower heads and leaves.
# Repo Structure
The Cauli-NET method has the following structure:
- `.py files`: `.py` scripts with training, inference, and image processing functions
- `Exemplary Datafiles/`: input data (images are not included due to size constraints) from each class of VegNet dataset
- `Dataset Link/`: Contains the URLs for the public datasets and can be downloaded  [VegNet](https://www.sciencedirect.com/science/article/pii/S2352340922006199).
- `pretrainedmodels/`: weights and configurations of models pre-trained on external datasets

# Install Dependencies
```
!pip install -r requirement.txt
```
