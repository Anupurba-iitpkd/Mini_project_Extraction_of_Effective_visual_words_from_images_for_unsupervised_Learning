# Mini_project_Extraction_of_Effective_visual_words_from_images_for_unsupervised_Learning
Visual words were extracted from images using SIFT, ORB and FAST feature descriptors for unsupervised learning tasks. 

Open CV version required : 4.4.0 and above (for executing SIFT)
other dependencies : Numpy, Pandas, Sklearn, Sklearn Image, Scipy, Matplotlib

Colab notebook is divided into the following sections : All the sections can be executed independently. 

Part 1 : Bag of Visual Words Algorithm : 
1. Feature Extraction : Image segmentation and feature extraction using SIFT, ORB and FAST
2. Visual Word Creation : BoVW algorithm is implemented here.
3. Quantization of feature space.

Part 2: Image interpretation and visualizations

Part 3: Application to LDA based Topic Model and Interpretation of the results : 
1. Evaluation of LDA results, Forming the mappings.

Part 4: Classification Results:
1. Supervised classification : Naive approach
2. Supervised Classification : using topic modelling results and naive bayes classifier
3. uneupervised clustering : using Topic modelling results and K means clustering.
