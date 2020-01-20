# Music Generation with HMMs and RNNs

## Research Objectives

* compare the Hidden Markov Models probabilistic approaches with deep learning approach towards music composition. Models we used: 
    1. Simple HMM
    2. Two-layered HMM
    3. Two-layered Autoregressive HMM
    4. Deep Markov Model
    5. Long Short-term Memory Networks
* compared and evaluated the music generated by different models based on their originality,musicality, and temporal structure. 

## Dataset

The dataset we used throughout our research is 
[JSB chorales](http://www-etud.iro.umontreal.ca/~boulanni/icml2012), which contains the entire corpus of 382 fourpart harmonized chorales by J. S. Bach. The data are already formatted as pianoroll matrices to directly feed into LSTM and deep Markov models.

## Jupyter Notebooks
* [HMM_music.ipynb](https://github.com/the-yanqi/DS3001-timeseries/blob/master/HMM_music.ipynb): Generate music with HMM variants, and produce evaluation metrics.
* [dmm_colab.ipynb](https://github.com/the-yanqi/DS3001-timeseries/blob/master/dmm_colab.ipynb): Generate music with deep Markov model. Need to be run on google colab
* [Bach_Music_Generation_LSTM.ipynb](https://github.com/the-yanqi/DS3001-timeseries/blob/master/Bach_Music_Generation_LSTM.ipynb): Generate music with LSTM networks
* [Evaluation.ipynb](https://github.com/the-yanqi/DS3001-timeseries/blob/master/Evaluation.ipynb): Create Metrics Visualization
* [helper_function.ipynb](https://github.com/the-yanqi/DS3001-timeseries/blob/master/helper_function.ipynb): Functions to help preprocess music data, fit Markov models and generate new music.

