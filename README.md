# Pneumonia-Image-Recognition
## Introduction
We are a group of data scientists attempting to predict pneumonia based on X-ray scans. We hope that the charity Stop Pneumonia will adopt our model and deploy it to assist doctors and help reduce misdiagnosis of pneumonia. This will in turn improve treatment and health outcomes.

## Buisness Understanding
Pneumonia is a bacterial, viral or fungal infection of the lungs. It is very serious condition where the air sacs fill with liquid. This disease acounts for 14% of all deaths of children under 5 years old.
Pneumonia is an infectious disease with a high mortality rate.  It claimed 2.5 million lives in 2019, including 672,000 children under the age of five.
That’s one person dying every 13 seconds. This data underscores a critical need to effectively diagnose patients as early as possible for effective intervention and treatment strategies.

## Data Description
The data was aquired from Mendeley. The data contained over 5000 images of pneumonia of children aged 1-5. The images were screened prior to inclusion and poor quality xrays were removed. The images showed anterior and postior xrays of the chest cavity.
The data was organized into train and test sets.
https://data.mendeley.com/datasets/rscbjbr9sj/3
## Modeling
We used a convolutional neural network (CNN) model to create predictions based on the X-rays of patient's lungs. We iterated through many different activation functions including relu, softmax, and tanx, with different amounts of hidden nodes to optimize our model. Our best model used the 'relu' activation function.

## Model Evaluation
We evaluated our models based on accuracy and recall metrics.
Our model was somewhat prone to overfitting, but the relu model minimized overfitting while giving us higher metrics.

![image](https://user-images.githubusercontent.com/92397941/148302752-99096f53-9432-4e46-b34d-5f9c3ea2196a.png)
![image](https://user-images.githubusercontent.com/92397941/148302911-85978ed1-e540-49ff-880f-53413e8a504a.png)

Here we display a model where the loss function between the train and testing sets are minimized, and makes predictions against unseen data with 87.2% accuracy. While these results are consistent, the data scientists working on this project are limited by their PC's computing power. Future work would increase the image sizes for greater resolution and therefore more accurate predictions. Additionally, having a larger data set would also benefit the model to perform with greater accuracy. Having an accuracy rate that is as high as possible is ideal for high stakes predictive models such as this.

## Conclusion
If adopted our model will Stop Pneumonia's charity to reduce the occurance of false negatives in pnemonia diagnosis and improve health outcomes. With greater computional power and more data, this model can be further optimized to increase its accuracy.
We also recommend increasing funding to charities fighting Pneumonia.
Finally, efforts should be in place to continue pursuing technological solutions to misdiagnosis issues.

## Presentation
https://github.com/meowkaiser/Pneumonia-Image-Recognition/blob/main/Slides.pdf

```
├── README.md                               <- The top-level README for reviewers of this project
├── Pneumonia_Imaging_tanh_models.ipynb     <- Tanu was our first model, but not effective
├── Pneumonia_Imaging_softmax_model.ipynb   <- Softmax was an improvement
├── RELU Model.ipynb                        <- RELU was our best model
├── Final_model_validation.ipynb            <- Concise summary of the project with all data science steps
├── Slides.pdf                              <- PDF version of project presentation
├── Data                                    <- Both sourced externally and generated from code, includes exploratory notebooks
└── Images                                  <- Both sourced externally and generated from code
```  
