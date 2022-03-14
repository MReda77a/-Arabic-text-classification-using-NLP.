# MLTask
This task is Arabic text classification using Machine learning and Deep learning for Aims technology.
I've used two models one is NLP andthe other Bert.
The dataset is composed of two columns ids and  dialect.
First i used The  id column  to retrieve the text by a POST request and the request is JSON as a list of strings, and the size of the list is 1000.
Second i used re — Regular expression operations to pre-process the data to remove emojis, users, urls, tags and everything except the arabic words then i dropped the id column.
For Machine learning i tokenizer texts to matrix then encoding the dialect column.
For buliding the model i defined f1 metric which is consists of  true positives, possible_positives, predicted_positives, precision, recall and f1_val.
For Deep learning embeding vectors for few sample statements, Get embeding vectors for few sample words 
finally building Bert Model
