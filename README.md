# NewsTopicClassification
Text classification using BBC dataset from Kaggle <br />
It takes in texts as inputs and classifies the topic of the inputs (e.g. Entertainment, Sports, Business, Politics, tech) <br />

# Results<br />
**BBC NEWS DATA (ACCURACY)** <br />

RNN | GRU | LSTM | BiGRU with Focal loss | BERT
------------ | ------------- | ------------ | ------------- | ------------- 
46.2 | 83.9 | 79.8 | 96.7 | **98.6** 

**BBC NEWS DATA (INFERENCE TIME (ms))** <br />

RNN | GRU | LSTM | BiGRU with Focal loss | BERT
------------ | ------------- | ------------ | ------------- | ------------- 
**4.33** | 4.80 | 4.66 | 7.95 | 195.90 
