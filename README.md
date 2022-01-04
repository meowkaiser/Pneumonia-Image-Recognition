# Pneumonia-Image-Recognition
## Introduction
We are a group of data scientists attempting to predict pneumonia based on xray scans.

## Buisness Understanding
Pneumonia is an infection of one or both of the lungs caused by bacteria, viruses, or fungi. It is a serious infection in which the air sacs fill with pus and other liquid. Lobar pneumonia affects one or more sections (lobes) of the lungs.
Pneumonia accounts for 14% of all deaths of children under 5 years old, killing 740 180 children in 2019
The cost of antibiotic treatment for all children with pneumonia in 66 of the countdown to 2015 countries for maternal, newborn and child survival is estimated at around US$ 109 million per year. The price includes the antibiotics and diagnostics for pneumonia management.
treat pneumonia focusing on making sure that every sick child has access to the right kind of care -- either from a community-based health worker, or in a health facility if the disease is severe -- and can get the antibiotics and oxygen they need to get well;
Pneumonia is the world’s biggest infectious killer of adults and children – claiming 2.5 million lives, including 672,000 children under five, in 2019.
That’s one person dying every 13 seconds.
Our goal is to create an image detection system that minimizes error is diagnoses of Pneumonia. We hope this will in turn reduce morbidity and mortality for people effected with the condition.

## Data Description
The data contains more than 5000 images of pneumonia of viral and bacterial pneumonia of and children 1-5 in Guangzhou Women and Children’s Medical Center, Guangzhou.
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

## Modeling
We used a CNN model to create predictions based on the xray's of patients lungs. We iterated through many different activation functions and different amounts of hidden nodes to optimize our model.

## Model Evaluation
We evaluated based on the recall metric.
Our model was somewhat prone to overfitting and we had an inconsistant loss function.
Adopt Our Model. 
Increase funding to charities fighting Pneumonia.
Continue pursuing technological solution to problems.

## Conclusion
