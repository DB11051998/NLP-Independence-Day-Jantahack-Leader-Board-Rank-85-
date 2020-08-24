# NLP-Independence-Day-Jantahack-Leader-Board-Rank-85

![Jantahack](https://datahack-prod.s3.ap-south-1.amazonaws.com/__sized__/contest_cover/jantahack_i-day-thumbnail-1200x1200-90.jpg)
## Topic Modeling for Research Articles
Researchers have access to large online archives of scientific articles. As a consequence, finding relevant articles has become more difficult. Tagging or topic modelling provides a way to give token of identification to research articles which facilitates recommendation and search process.

Given the abstract and title for a set of research articles, predict the topics for each article included in the test set. 

Note that a research article can possibly have more than 1 topic. The research article abstracts and titles are sourced from the following 6 topics: 

1. Computer Science

2. Physics

3. Mathematics

4. Statistics

5. Quantitative Biology

6. Quantitative Finance

To Download Dataset:- https://datahack.analyticsvidhya.com/contest/janatahack-independence-day-2020-ml-hackathon/download/train-file

![Leader-Board](https://github.com/DB11051998/NLP-Independence-Day-Jantahack-Leader-Board-Rank-85-/blob/master/Screenshot%20from%202020-08-24%2001-22-50.png?raw=true)

## Approach
we had to classify mutiple classes, so for that intially i used TextCNN approach using GloVe Pretrained embedding model.On tuning and properly preprocessing i achived a score of 79.76 accuracy and was unable increase even after tuning it.Even after doing some Stemmimg i failed to take the score to 80. My next approach was a machine learning approach using TF-IDF Vectorizer for that and using Linear Support Vector Classifier for that and here i got a score of 83. the pre-processing steps were the same.
