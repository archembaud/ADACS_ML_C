This folder should contain 100 pairs of files designed for testing a previously generated AI as part of the ADACS ML workshop.

However, it's too much data to store (responsibly) with GIT. Therefore, its held in the directory: /fred/oz989/LIGO_DATA/Test_Easy. Please make copies to your local directory as required; don't write your own codes there.

The format of each file is identical to those contained within the Train_Easy folder:
* Each X_LIGO_ file contains 200,000 double precision elements saved in binary format.
* Each Y_LIGO file contains a single double precision element (either 0 or 1), also in binary.

Make sure you perform the same filtering on the test data as used on the training data. Otherwise you're gonna have a bad day.
