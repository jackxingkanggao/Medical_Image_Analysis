# Medical_Image_Analysis
Design and develop a CNN for malaria imagine analysis, and specific steps include the following:

1. Download the image dataset from NIH (National Library of Medicine) https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#malaria-datasets
2. Divde the dataset into train, validation and test sets
3. Use VGG16 model to extract features from the images
4. Save the extracted features for future exploration
5. Develop a classification model that sits on top of the feature extractor (Transfer Learning)
6. Fit the model with train dataset and validate with validation dataset
7. Evaluate model performance with test set
