The results of our code are stored in this folder.

Prediction drug-target interaction matrix for each cross validation is stored in 'NeoDTI_pred*.npy'. Higher scores correspond to higher probabilties of binding.
Test mask matrix for each cross validation is stored in 'NeoDTI_mask*.npy'. 1 means the corresponding drug-target pair is treated as a test example in this cross validation.

Suppose there are M virus proteins and N human proteins in our dataset.
The above matrices will have M+N columns, where the first M columns correspond to the virus proteins and the rest correspond to the human proteins.

