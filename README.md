# CSE3042-JComp
This repository contains the code and other requirements for Alzheimer's Prediction using Quantum Neural Networks

## Abstract
This project explores the transformative potential of Quantum Support Vector Machines (QSVM) in the domain of Alzheimer's disease prediction, leveraging the unique properties of quantum computing. The study investigates the efficacy of QSVM in comparison to classical algorithms, showcasing the advantages derived from quantum parallelism, superposition, and entanglement. Through extensive evaluations, our research highlights the robust performance of QSVM in feature extraction and dimensionality reduction, crucial aspects in neurodegenerative disease prediction. The model's interpretability, achieved through quantum explainability tools, addresses concerns related to the transparency of quantum algorithms. While presenting promising results, we acknowledge challenges such as hardware dependency and sensitivity to noise. This work contributes to the growing intersection of quantum computing and healthcare analytics, pointing toward a future where quantum algorithms play a pivotal role in advancing predictive models for Alzheimer's disease and similar medical applications.

## Materials and Methods
#### 1. Data
In this project, we used public brain MRI data from **Alzheimers Disease Neuroimaging Initiative (ADNI)** Study. ADNI is an ongoing, multicenter cohort study, started from 2004. It focuses on understanding the diagnostic and predictive value of Alzheimers disease specific biomarkers. The ADNI study has three phases: ADNI1, ADNI-GO, and ADNI2. Both ADNI1 and ADNI2 recruited new AD patients and normal control as research participants. Our data included a total of 4854 structure MRI scans in Axial view, with 1124 AD cases, 1140 MCI cases and 2590 normal controls.

#### 2. Image preprocessing
The MRI images obtained from the ADNI dataset were pre-processed prior to being fed to the CNN model for feature extraction. Input shape of the images was set to be (224,224) akin to VGG-16s input layer.  The MRI images are then converted to grayscale for simplification, consistency, and enhanced interpretability. Grayscale representation reduces the image to a single intensity channel, facilitating the implementation of image processing algorithms with reduced computational complexity. Grayscale images also provide improved contrast, making them suitable for visualizing specific anatomical details or abnormalities. Min-Max normalization is also applied to scale pixel values between 0 and 1, ensure consistent scale and mitigate intensity variations.

#### 3. Proposed Methodology
