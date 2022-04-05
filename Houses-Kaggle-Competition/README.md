<img src='https://github.com/lewagon/data-images/blob/master/ML/kaggle-batch-challenge.png?raw=true' width=600>

The objective is to **submit online an answer** to the open competition.

Download the datasets in the `data` folder and upgrade sklearn to its latest version

```bash
cd ~/code/<user.github_nickname>/data-challenges/05-ML/07-Ensemble-Methods/Houses-Kaggle-Competition
curl https://wagon-public-datasets.s3.amazonaws.com/houses_train_raw.csv > data/train.csv
curl https://wagon-public-datasets.s3.amazonaws.com/houses_test_raw.csv > data/test.csv
curl https://wagon-public-datasets.s3.amazonaws.com/houses_sample_submission.csv > data/sample_submission.csv
pip install --upgrade pip
pip install --upgrade scikit-learn
```