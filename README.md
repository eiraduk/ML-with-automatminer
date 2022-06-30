# ML-with-automatminer

using a new package called Automatminer (to automate some of the tasks you should perform with matminer)


it helps to import dataset and perform the model without manual tunning
decorate the dataset using ML features
Select features which are best for ML

in this dataset we don't have formula, volume ,...
we need to split the dataframe into 2 parts. one is for training and other is for testing

our test_df4 will only have composition only
automatminer will now add the features automatically

preset we used is express_single to give general performance. 
sinngle means means we are not doing the automatic machine learning part, we are going to train as single pipeline

automatminer selected the best featulizer that provided a good performance
it generated all the features 
it did data cleaning process by itself
it did also feature reduction
it will add the other features and predict the "yield strength predict" wich was our target

pprint was used for pretty print dictionary
