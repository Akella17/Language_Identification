# Language_Identification

This project is a Character-level LSTM model for language identification over DSLCC-v2.0 dataset. Both 3 layer and 1 layer LSTM networks perform similarly on the test set achieving an accuracy of about 60%. The accuracy further increases by increasing the context (sample text size) for the LSTM.

## DSLCC-v2.0
The training set contains 18,000 sentences for each language. The dev set contains 2,000 sentences for each language. All sentences are encoding in latin script UTF-8. The dataaset consists of 13 languages and an extra category which contains samples from varous languages (effectively 14 categories). 
