# Music-Sentiment-Analysis
This is a music sentiment analysis project, it uses the music dataset from spotify, the dataset can be found <a href="https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks?select=data.csv">here</a>.

The aim of the project is to determine the mood of the song based on the lyrics. Various components  of  a  song  contribute  to  its  sentiment/mood  in  general.  Some  of  these components  include  lyrics,  tempo,  background  music  etc. The  approach  used  in  this project  is  to  simply  understand  the  pattern  of  words  in  the  song  lyrics  for  different categories for example, Happy Songs and Sad Songs.

Sentiment of a song based on its valence value (Valence describes the positvity of a song, the higher it is the more cheerful a song). Then TF-IDF is used to vectorize the lyrics. Different Machine Learning models such as SVC, KNN, Random Forest, Logistic Regression are generated.
