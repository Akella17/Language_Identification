# Language_Identification

- This project is a Character-level LSTM model for language identification over DSLCC-v2.0 dataset. Both 3 layer and 1 layer LSTM networks perform similarly on the test set achieving an accuracy of about 60%. The accuracy further increases by increasing the context (sample text size) for the LSTM.
- Based on the architecture of Stanford Language Identification Engine(SLIDE) by *Mathur et al., (2017)*.

### Model Architecture

- 1 layer LSTM network : hidden units = 768, batch size = 10, timesteps (context) = 50

![](https://github.com/Akella17/Language_Identification/tree/master/LD/files/1_layer_lstm.png)

- 3 layer LSTM network : hidden units = 768 (each), batch size = 50, timesteps (context) = 30

![](https://github.com/Akella17/Language_Identification/tree/master/LD/files/3_layer_lstm.png)

### Dataset Description
- **DSLCC-v2.0** : The training set contains 18,000 sentences for each language. The dev set contains 2,000 sentences for each language. All sentences are encoding in latin script UTF-8. The dataaset consists of 13 languages and an extra category which contains samples from varous languages (effectively 14 categories). 
