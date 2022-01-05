# Pneumonia-Image-Recognition
## Introduction
We are a group of data scientists attempting to predict pneumonia based on xray scans. We hope that the charity Stop Pneumonia will adopt our model and deploy it to reduce misdiagnosis of pneumonia. This will in turn improve treatment and therein health outcomes.

## Buisness Understanding
Pneumonia is a bacterial, viral or fungal infection of the lungs. It is very serious where the air sacs fill with liquid. This disease acounts for 14% of all deaths of children under 5 years old.
Pneumonia is the biggest infectious killer.  It claimed 2.5 million lives, including 672,000 children under five, in 2019.
That’s one person dying every 13 seconds.

## Data Description
The data was aquired from Mendeley. The data contained over 5000 images of pneumonia of children aged 1-5. The images were screened prior to inclusion and poor quality xrays were removed. The images showed anterior and postior xrays of the chest cavity.
The data was organized into train and test sets.
https://data.mendeley.com/datasets/rscbjbr9sj/3
## Modeling
We used a CNN model to create predictions based on the xray's of patients lungs. We iterated through many different activation functions, including relu and tanx, and different amounts of hidden nodes to optimize our model. Our best model used a soft max activation function.

## Model Evaluation
We evaluated based on the recall metric.
Our model was somewhat prone to overfitting.
![image](https://user-images.githubusercontent.com/92397941/148302752-99096f53-9432-4e46-b34d-5f9c3ea2196a.png)


## Conclusion
If adopted our model will Stop Pneumonia's charity to reduce the occurance of false negatives in pnemonia diagnosis and improve health outcomes.
Increase funding to charities fighting Pneumonia.
Continue pursuing technological solution to problems.

```
├── README.md                           <- The top-level README for reviewers of this project
├── notebook.ipynb                      <- Concise summary of the project with all data science steps
├── Slides.pdf                          <- PDF version of project presentation
├── Data                                <- Both sourced externally and generated from code, includes exploratory notebooks
└── Images                              <- Both sourced externally and generated from code
```  
