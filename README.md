# NLP_using_DeepNN_on_Large_dataset
Sentiment analysis on a large dataset
There is a huge database available at http://help.sentiment140.com/for-students/ to be used for sentiment analyses
I ran the code in an iMac. It took 13 hours to create a lexicon, train a model and test it. 
The accuracy is 74%

If you want to download these files and run, here are some suggestions:
Recreational training: If you want to check if the code compiles and have a quick fun to see the response of LSTM, make the following changes to the settings:
in file utils_senti.py, set hm_lines = 100 or 1000 (or any number in between)
in NN_senti.py, set hm_data and hm_test_data = 100 or 1000 (or any number in between)

For learning: If you are moderately interested in testing the system and also learn programming LSTMs, make the following changes to the  settings:
in file utils_senti.py, set hm_lines = 1000 or 50000 (or any number in between)
in NN_senti.py, set hm_data and hm_test_data = 1000 or 50000 (or any number in between)
Th above settings will take a couple hours to a few hours for compilation

For Hardcore enthusiasts: If you are highly interested in becoming an expert in LSTMs, run the files as-is with the original settings
The files will have a day or two for compilation. If you have a faster instance on GCP or AWS, you are in better luck. A good GPU will also help.

I am currently working on getting higher accuracies will different hyper parameters and other changes.
