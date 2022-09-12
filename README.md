# IMDB-Sentiment-Analysis-with-Neural-Network
* I did sentiment analysis with Stanford University IMDB Dataset. Dataset has 4 different folder they are 'imdb.vocab', 'imdbEr.txt', 'README', 'test', 'train'. I seperate the train and test folder for analysis. Also, I cleaned the data from some html codes and punctuations. After cleaning the data, I converted the woords to numeric by Text Vectorizer.  
* I applied Neural Network with Sequential Model. I used Embedding Layer, Drop out, and Global Average Pooling which is used to speed up to computation and reduce the size. I applied Binary Cross Entropy and Adam optimizer. In this project, Binary Accuracy metric was used to classify the comment positive or negative.   
* After analysis, the model accuracy is 0.91 on the train data, and 0.87 on the test data. Also, I visualize the losses on train data and test data, and accuracy both of them. I see that it is not differ far from between. So, I can say that the model is reliable for analyzing the comment about the movie.
