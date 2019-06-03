This folder contains the code to train the GP models
******************************************************************

Run 'GP_training_seq.m' to train GP models using Halton sampling scheme

===> it loads 'testing.mat' (pre-generated testing sample set)

===> it saves 'GP.mat' (trained GP model)
, 'training.mat' (training sample set)
,              'errITA.mat' & 'errCAV.mat' (error history)
, 'predict_test.mat' (validation history)
****************************************************************** 

Run 'GP_Validation.m' to check the accuracy of trained GP models
