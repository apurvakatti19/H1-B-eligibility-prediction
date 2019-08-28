# H1-B-eligibility-prediction
This work deals with making a thorough analysis of the intermediate step before the application is picked up and granted the visa. The intermediate process checks the eligibility of the applicant depending on the various parameters and then issues certified or denied as to its status. It also has several other types of statuses such as certified-withdrawn and withdrawn. This is an important problem as there is no clear rules or criteria for rejecting or accepting a petition.

The main dataset is downloaded from Kaggle listed under the name “H-1B Visa Petitions 2017“.It contains 53 features and 624650 records of applicants. Once the data processing was done, the data was divided into training, testing set and validation sets. The data split was 33% testing and 10% validation.

The fully connected layer was used as the data considered is independent of one another and also
does not consist of images. Each model was trained with different parameters for 10-20 epochs. The validation was done on 10% of the data whereas the learning rate was chosen differently for different models. The output layer activation function was Softmax whereas different models different activation functions in different layers. Dropout was used for both visible layers as well as a hidden layer.
