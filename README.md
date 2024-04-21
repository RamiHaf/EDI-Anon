# Explainability-Driven Incremental Image Anonymization

Privacy regulations require that images depicting humans be anonymized before they are publicly released or shared for secondary use. However, current image anonymization methods significantly degrade the analytical utility of the protected images. This paper addresses the challenge of balancing privacy protection and utility preservation in image anonymization. We propose a general disclosure risk-aware anonymization framework that leverages explainability techniques to target identity-revealing features within the images. Contrary to conventional methods, which uniformly perturb all image pixels, our proposal focuses on perturbing the pixels that contribute the most to disclosure. Moreover, pixel perturbation is enforced incrementally, and it is driven by the observed residual risk. Our framework is not tied to a specific pixel perturbation mechanism, and is versatile enough to support a wide variety of techniques, including blurring, pixelation, noise-addition and pixel masking. Empirical results show that, even with the simplest perturbation techniques, our approach significantly improves the privacy/utility trade-off compared to conventional as well as advanced state-of-the-art methods.


## The content of the repository

### Iterative file: 
The iterative file contain the code to run the EDI-Anon method with all its diferent variation.

### Simple codes file:
The simple codes file contains the codes to run the simple 'conventional' anonimyzation methods.

### For utility file:
The file for utility conatain the code to evaluate the data sets for the tree utilities which are 'age, race, and gender'.

### Utils file:
The utils file contain some of the codes to help run the EDI-Anon. It contains the code to train the for different model 'FR, age classification, race classification, and gender classification'. In addition to that, it contain the code to reorganize the from the FR classification, into the new folder with the distribution of the three utilities automatically.
