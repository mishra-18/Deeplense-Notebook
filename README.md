### SSL on Real Dataset

There are Two specific notebooks:

* SSL_dinomodel

   **Weights**: [dino_model_final.pth](https://drive.google.com/file/d/1_pKESS9DmMRUZN8XBuEdoHdW1TQd0Zww/view?usp=sharing)

* dino_model

  **Weights**: [dino_model_test.pth](https://drive.google.com/file/d/1OTw18pRL1SV99ueDcTHL7iFcknNjv3HK/view?usp=sharing)


**Dataset**: [Drive](https://drive.google.com/file/d/1aafE2nDp7S6j59sZcBIzP3FnQxVCmHCx/view)

**Dataset Description**: The Dataset consists of two classes, strong lensing images with lenses and non-lenses in npy format. For non-lensing images, the images start with nl_. These images are from the Hubble Space Telescope. 
Evaluation Metrics: ROC curve (Receiver Operating Characteristic curve) and AUC score (Area Under the ROC Curve). Although the dataset is small and results may not be perfect, the pipeline should be such that with more data, the model could achieve high performance. 

### Multi-Class Classification

weights: [classification_model.pth](https://drive.google.com/file/d/1c9UipjdKYQyznsY2M7FbdvPbb6U_xRox/view?usp=sharing)


**Dataset**: [Drive](https://drive.google.com/file/d/1ZEyNMEO43u3qhJAwJeBZxFBEYc_pVYZQ/view)

**Dataset Description**: The Dataset consists of three classes, strong lensing images with no substructure, subhalo substructure, and vortex substructure. The images have been normalized using min-max normalization, but you are free to use any normalization or data augmentation methods to improve your results.
Evaluation Metrics: ROC curve (Receiver Operating Characteristic curve) and AUC score (Area Under the ROC Curve) 


### Learning Mass of Dark Matter Halo 

Using the provided dataset to implement a regression algorithm to learn the mapping between lensing images and the lensing dark matter halo mass.

**Dataset**: https://drive.google.com/file/d/1hu472ALwGPBcTCXSAM0VoCWmTktg9j-j/view

**Dataset Description**: The data set consists of strong lensing images for cold dark matter with subhalo substructure. For each lensing image the corresponding fraction of mass in dark matter substructure is provided. Evaluation Metrics: MSE (mean squared error)
