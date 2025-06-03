# Breast-Cancer-Detection-
Overview
This project leverages deep learning techniques to detect breast cancer from mammogram images. The goal is to enhance early diagnosis and reduce mortality rates by providing reliable, AI-assisted interpretation of mammograms.

1. Problem Significance
Breast cancer is the second leading cause of cancer-related deaths among women.

Early detection can identify tumors up to 3 years before they are clinically palpable.

AI systems have demonstrated the ability to match or exceed human expert performance in interpreting mammograms, offering enhanced diagnostic support.

2. Dataset
The dataset includes mammography images resized to 224×224×3 dimensions and supports two main classification tasks:

a. Breast Density Classification (4 Classes)
Class	Description	Prevalence
A	Almost entirely fatty	10%
B	Scattered fibroglandular density	40%
C	Heterogeneously dense	40%
D	Extremely dense	10%

b. Tumor Classification (2 Classes)
Benign: Noncancerous tumors

Malignant: Cancerous tumors

3. Technical Approach
a. Image Preprocessing
Enhanced image sharpness and contrast to clarify features in blurry mammograms.

b. Deep Learning Models
Designed and trained separate models for:

Breast density classification

Tumor classification (benign vs. malignant)

c. Performance
Achieved accuracy comparable to expert radiologists.

Reduced false negatives, especially in challenging cases involving dense breast tissue.

4. Deployment
Platform
Deployed as a Gradio web application for interactive usage.

Features
Image upload functionality

Real-time prediction with class probabilities

Interactive cropping tool to focus on regions of interest

Clear visualization of diagnostic results


5. Clinical Impact
This system acts as a decision support tool for radiologists by offering:

24/7 availability

Consistent diagnostic performance, unaffected by fatigue

Reduction in false negatives

Enhanced assistance in dense breast tissue cases, which are typically harder to interpret

🔍 Conclusion: This project highlights how deep learning can complement (not replace) radiologists, ensuring faster, more consistent, and more accurate breast cancer detection.
