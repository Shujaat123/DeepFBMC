# DeepFBMC-
FBMC using deep neural network
in dataset folder there is a mat file 

There are 2 variables in the data: input_data  and output_data. Both have dimension 10500 X 24 where we have 7 different scenarios of SNR with 50 samples for each SNR. There are 30 time instants and 24 frequency sub-carriers. The organization is as follows:

first 50 samples for first SNR are in the fist 50 rows 
second 50 samples for second SNR are in the second 50 rows
and so on till 350 rows completed which make first time instant
Then next 350 rows similarly organized for second time instant and so on 
