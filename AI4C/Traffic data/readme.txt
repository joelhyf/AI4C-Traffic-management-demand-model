ChanceModel.h5 is the pretrained NN model using all training data.
ChanceModel_14.h5 is the pretrained NN model using the last 14 days of demands in training data.

Please insert the training.csv in this folder, 
then run the AI4C_PreProc.py and AI4C_LocProfile.py to cunstruct the location profile data,
then you will be able to test the NN model.
To train a new NN model, please run the AI4C_GenTrain12.py, then AI4C_NN.py,
after the location profile data has been created.
