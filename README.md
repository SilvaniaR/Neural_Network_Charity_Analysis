# Neural_Network_Charity_Analysis
Deep ML

## Overview of the analysis: Explain the purpose of this analysis.
the analysis was conducted to help a foundation predict where to make investments.
Using machine learning and neural networks we used the features in the provided dataset to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: 
### Data Preprocessing
* What variable(s) are considered the target(s) for your model? the targets for this model are if the applicant is successful
* What variable(s) are considered to be the features for your model? some feature of the model are APPLICATION_TYPE,CLASSIFICATION,USE_CASE,ORGANIZATION,STATUS,INCOME_AMT,SPECIAL_CONSIDERATIONS and ASK_AMT.
* What variable(s) are neither targets nor features, and should be removed from the input data? EIN and NAME provide no value added to the model to make a decesion.

* Compiling, Training, and Evaluating the Model
Deep learning: image below
<img width="1437" alt="alphabetcharitydeeplearning" src="https://user-images.githubusercontent.com/93267002/165876067-eeeb46c7-d3e6-4683-84e5-e37ed1aef0b7.png">

Deep learning Optimized: image below
<img width="1421" alt="optimization deeplearning" src="https://user-images.githubusercontent.com/93267002/165876102-2ae14ad9-db15-431d-95a3-61f314d8c124.png">

* How many neurons, layers, and activation functions did you select for your neural network model, and why? For the first deep learning model i chose 8 and 5 neruons with two layers, using relu then sigmoid as output. i wanted to keep simple first to see how the data would train and test. I then made multiple change to the optimized model, i ended up with just 12 and 6 neurons and two layers still be relu activation and sigmoing activation as ouput. 

* Were you able to achieve the target model performance? No stayed at 73%

* What steps did you take to try and increase model performance? I changed layers, neurons, activations, binning outputs and epochs.
 * For the binning I made less bins but that didnt help with accurancy. I then added 4 layers and one of layers had a linear activation. the neuron decreased by two starting the first layer with 16 neurons. I also chnaged the epoch from 100 to 50 and so forth with different layers. That also didnt not change the accurary for training in fact when looking at the training and test scores it looked like it was overfitting.


## Summary: 
Overall the scores between both model are almost the same, I would recomend not deep machine learning but perhaps the SVM or random forest models. These models are much simpler and shorter probably yield the same result or better.
