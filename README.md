# BreastCancer-CNN
Abstract—Breast cancer is the second leading cause of death from cancer in women around the world. 
The CAD system utilizing machine learning and deep learning techniques facilitates the early detection of breast cancers. 
However, few recent studies focused on utilizing multiple feature extractors to compare and analyze the performances of various architectures. 
This paper analyzes the performances of architectures which are combinations of different feature extractors and classifiers in breast cancer diagnosis. 
- We collected histopathological breast cancer images from the BreakHis dataset. 
- The normalized data were converted to one-hot encoding for training, validating, and testing. 
- We used VGG-16, VGG-19, Xception, ResNet50, Inception-V3, and Inception-Resnet-V2 to extract features. 
- Fully connected layer (FCL), logistic regression (LR), and SVM were employed to classify breast cancers on the BreaKHis dataset. <br/>

### Result
With the cyclical learning rate (CLR) policy, the ResNet50-SVM model obtained the optimal accuracy rate of 93.9% on eight-classification. 
The result shows that our proposed method could diagnose breast cancer with high accuracy.
