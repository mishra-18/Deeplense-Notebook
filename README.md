This is my repository for the solution to the evaluation tasks in the form of notebooks.



## trained model Weights can be accessed from here

[Classification_modelWeights](https://drive.google.com/file/d/1QPdJI2yWdM47B_j4vULs4ObhGXIRjFZU/view?usp=sharing)

[regression_modelWeights](https://drive.google.com/file/d/1fvR47IPpZGlhsT0P59nuj3WDcrEMZh-u/view?usp=sharing)


## Common Test I. Multi-Class Classification 

(the respective solution notebook can be found [here](https://github.com/sam5658/DeepLense/blob/main/classification.ipynb) )

Task: Build a model for classifying the images into lenses using PyTorch or Keras. Pick the most appropriate approach and discuss your strategy.

Dataset: [dataset.zip - Google Drive](https://drive.google.com/file/d/1B_UZtU4W65ZViTJsLeFfvK-xXCYUhw2A/view)

Dataset Description: The Dataset consists of three classes, strong lensing images with no substructure, subhalo substructure, and vortex substructure. The images have been normalized using min-max normalization, but you are free to use any normalization or data augmentation methods to improve your results.

Evaluation Metrics: ROC curve (Receiver Operating Characteristic curve) and AUC score (Area Under the ROC Curve) 


## Specific Test III. Learning Mass of Dark Matter Halo 

(respective solution notebook can be found [here](https://github.com/sam5658/DeepLense/blob/main/classification.ipynb) )

Task: Using the provided dataset implement a regression algorithm to learn the mapping between lensing images and the lensing dark matter halo mass. You can use the machine learning algorithm of your choice.  Please implement your approach in PyTorch or Keras and discuss your strategy.	

Dataset: https://drive.google.com/file/d/1hu472ALwGPBcTCXSAM0VoCWmTktg9j-j/view

Dataset Description: The data set consists of strong lensing images for cold dark matter with subhalo substructure. For each lensing image the corresponding fraction of mass in dark matter substructure is provided.

Evaluation Metrics: MSE (mean squared error)
