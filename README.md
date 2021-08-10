# My Time - Breathe, take your time

This is a simple sentiment analysis program which uses various reviews
from yelp, amazon and IMDB to train and test a model before
predicting if a statement is positive or negative. The user can then
insert a statement which would be analysed to see if it was positive or
negative.

There are two ways for the user to input their statement,
either by typing it out or speaking into a microphone. If the script
predicts that the statement was negative, it will ask the user if they
want to relax and a breathing exercise would ensue. The idea behind
this program is a simple app that analyses users mental state or his
emotion at the moment, allows user to speak or type how they feel
about their day and the app would be able to calm or destress the user
through several means, whether it be by listening to calming music or
doing breathing exercises.

### IMPLEMENTATION
- Logistic Regression
- Multinomial Naive-Bayes

**Few Point About The Project**
- IMDB movie reviews, Yelp reviews and reviews
on the Amazon website were used as data
- Train : Test is 0.75 : 0.25
- These accuracies are then compared to see which was
better at predicting one's sentiment, before narrowing it down to
only one algorithm thus leading to good result in analysing the
emotion of the individual and further responding on the basis of
prediction

Snapshots 👇
![accuracy](https://user-images.githubusercontent.com/69981287/128843661-874f4169-0dbd-4303-aa02-5c40d1daba60.png)
![Untitled](https://user-images.githubusercontent.com/69981287/128844066-9e1160ef-c60a-4ac0-986f-fab2bc6a728d.png)
![Untitleda](https://user-images.githubusercontent.com/69981287/128844280-9db97b51-2cdf-412b-b64d-dec32974bde4.png)
