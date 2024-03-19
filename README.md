# GlioScanAnalyzer

# Description
GlioScanAnalyzer is an innovative automated pipeline designed to streamline the analysis of brain tumor MRI scans, with a specific focus on glioblastoma (glio) tumors. This project leverages the power of deep learning and machine learning to segment tumors in MRI scans and predict tumor growth over time. By integrating a U-Net architecture for tumor segmentation with an RNN component for temporal analysis, GlioScanAnalyzer provides a comprehensive tool for clinicians and researchers to analyze brain tumors and predict their growth.

![image](https://github.com/thespongeenthusiast/GlioScanAnalyzer/assets/163718946/616064d0-30c9-4b89-9773-1c0f9987cd4b)

# Background
Glioblastoma is one of the most aggressive and lethal types of brain tumors, with a high mortality rate. Traditional methods of tumor analysis and growth prediction often require significant time and expertise, making it challenging for clinicians to monitor the progression of these tumors effectively. GlioScanAnalyzer addresses this challenge by automating the process of tumor analysis, from MRI data acquisition to tumor segmentation, registration, and growth prediction.

The project utilizes the BraTS-Reg dataset, which includes registered MRI scans of brain tumors, to train the U-Net model for tumor segmentation and the RNN model for tumor growth prediction. By processing the registered MRI scans, GlioScanAnalyzer can analyze changes in tumor size or volume over time, providing valuable insights into the progression of glioblastoma tumors.

# Features
Tumor Segmentation: Utilizes a U-Net architecture to accurately segment glioblastoma tumors in MRI scans, providing a clear and precise representation of tumor locations.
Tumor Growth Prediction: Employs an RNN component to analyze the changes in tumor size or volume across registered MRI scans, predicting future growth based on the current and past tumor sizes.
Automated Analysis: Automates the entire pipeline, from data preprocessing to tumor segmentation and growth prediction, simplifying the analysis process and making it more accessible to clinicians and researchers.
Predictive Capabilities: Provides insights into the progression of glioblastoma tumors, which can inform treatment planning and monitoring, potentially improving patient outcomes.
Usage
To use GlioScanAnalyzer, follow these steps:

Data Preparation: Obtain the BraTS-Reg dataset and preprocess the MRI scans as required.
Tumor Segmentation: Train the U-Net model on the dataset to segment tumors in MRI scans.
Tumor Growth Prediction: Train the RNN model on the segmented tumor regions to predict tumor growth over time.
Automated Pipeline: Utilize the automated pipeline to analyze new MRI scans and predict tumor growth.
Contribution
We welcome contributions from the community. If you have suggestions for improvements or wish to contribute to the project, please feel free to submit a pull request or open an issue.
