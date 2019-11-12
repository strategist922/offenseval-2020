# [OffensEval 2020](https://sites.google.com/site/offensevalsharedtask/)

## Models
- currently have binary logistic regression for subtask a
    - only evaluates on accuracy. Should include recall, precision, and f1 too
    - try taking average of 5ish classifiers
- try most common label as another baseline

## Datasets  

### [OLID - Offensive language identification dataset](https://arxiv.org/abs/1902.09666)
- Official semeval dataset
- Twitter comments
- So far only the trial data has been released ~ 14,000 entries
- 3 levels for offensive
  - Level A: Offensive vs non Offensive
  - Level B: Targeted insult vs untargeted 
  - Level C: Target identification (individual, group or other)
- Paper also compares a few baseline evaluation methods
- Says CNN does best

### [Kaggle Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview)
- Wikipedia Comments labeled by humans as toxic
- Toxic comments are identified by type
  - toxic
  - severe_toxic
  - obscene
  - threat
  - insult
  - identity_hate
- ~ 150K data points for training and ~160K for testing
- [Student blog on project](https://nycdatascience.com/blog/student-works/toxic-comment-classification-challenge-a-kaggle-competition/)
  - They did a logistic regression and got really good results.
  - Also explain how they got features from data and some choices they made to make the regression work.

