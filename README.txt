To run the ipynb files, open them in Google Colab, also adding the below text files to your Google Drive in a folder called 'spamdata':
train_set.txt
train_label.txt
test_set.txt
test_label.txt
In order to use the saved files, ensure the 'use_set' parameter in All Filters.ipynb is set to True.
You will also need to download the database called trec07p.tgz and add it to the 'spamdata' folder.
This can be downloaded from:

https://plg.uwaterloo.ca/cgi-bin/cgiwrap/gvcormac/trec07p.tgz

If you are running this locally the text files should be in the same folder as the python notebook and the trec07p folder should be in a folder called 'Emails'.

LSTM Neural Network.ipynb contains the code for the advanced neural network using the LSTM architecture that was implemented.
All Filters.ipynb contains the rest of the implemented classifiers.
The comments in the All Filters.ipynb file indicate where settings can be changed to run the filter with different parameters.
