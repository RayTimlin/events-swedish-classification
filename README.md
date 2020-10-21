# events-swedish-classification
The use of Swedish BERT deep learning method to train and classify multilabel data.  
The primarly labelling method is MultiLabelClassificationModel by https://simpletransformers.ai/

There arent many examples of Swedish datasets which are pre-labeled so thanks to https://www.citypolarna.se/ and Johan Broddfelt for allowing me to publish data.

The data (csv format) is quite raw and needs to be cleaned before eventual use into one-hot-encoding method.

<b> Part 1 </b> of the notebook is about cleaning, selecting and preparing the data for use.
Only categories which had more than 1000 incidents were used. Incidents with less than 5 words were excluded.

<b> Part 2 </b> of the notebook relates to the training, evaluating and validatiing the model.
The result is 78% LRAP after 4 epochs. Could easily be increased if further incidents with a low word count are excluded and more epochs run (4).




