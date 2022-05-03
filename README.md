# ML-Classifiers-for-Argumentation-Teaching-Strategies
Machine learning model created for MIT Teaching Systems Lab (TSL)

elk_argumentation_classifiers.ipynb contains code for training, saving, loading, and using the model.
elk_data.csv is the dataset that was used for training the model.
pytorch_model.bin and config.json can be used to load the model so that new data can be labeled.
pytorch_model.bin is too large for github. Here is a link to Google Drive: https://drive.google.com/file/d/1Y5EoXLCC-o3Xh0q9IBgcd7-3jttTsGOc/view?usp=sharing
training_args.bin is used for evaluating the trained model (in case you want to change the evaluation metrics). 

All datasets must contain columns named 'line' and 'role' for the model to work correctly.
These are lines in an ELK transcript and the role of the participant who typed the line ('Student' or 'Teacher') respectively. 
