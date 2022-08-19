# Dropped Object Angle Detection

### Abstract:

Container salvaging is becoming common in maritime industry, and we are more interested in recycling containers from the sea. Often, containers are often loaded with either valuable or harmful substances and must be retrieved. Therefore, there is motivation for model tests and numerical calculations on container models falling into water. 3D-printed container models, representing different loading conditions, have been dropped into the towing tank at the University of New Orleans (UNO). Videos of these dropped containers are analyzed to classify the initial angle of the container dropped into water. The containers were dropped 57 times at 0°, 45°, and 90° angles into the tank. Preprocessing tasks are conducted on the videos to prepare for model training. The two-phase angle classification approach uses a pre-trained ResNet50 model, trained on ImageNet, as a feature extractor to produce latent features to train a gated recurrent unit (GRU) model for classifying the entry angle of the dropped object. Initial results have shown it is possible for a model to classify the angles of dropped objects into water with up to 95% accuracy. Furthermore, the data obtained from these small-scale experiments will be integrated into the existing DROBS project. 

### Find:

In this repository find the collection of trimmed videos used to generate our final dataset. These videos can be modified further with the AuglyVideoAugmentation ipynb file to generate the full training, testing, and validation datasets. Finally, find the Res50GRUVideoAngleClassification to see our feature extraction and gru training processes. The files were designed for use in Google Colab.


### Links:

We also supply the viewable links in Colab for quick analysis.

https://colab.research.google.com/drive/1ldsOflqxEFOUH3bz8Qqm30aUPECKfaN8?usp=sharing

https://colab.research.google.com/drive/1m2FS2gXheLas7T66QCSYrwW-X3JasKPT?usp=sharing
