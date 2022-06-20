# MovieLens Recommender: What to watch next?

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/josumsc/movielens-recommender/blob/master/src/movielens-recommender.ipynb)

Analysis of the data located at [Kaggle MovieLens 100K](https://www.kaggle.com/datasets/rajmehra03/movielens100k?select=ratings.csv) 
and building of a recommender system using PyTorch embeddings to infer the latent factors
of both users and movies.

## Installation of the environment

You can follow up this notebook in your machine by downloading Anaconda and then running the following command in the terminal:
```python
conda env create --file movielens-recommender.yml
```
This should have you prepared to run jupyter notebook in the terminal and then running the mentioned code using that familiar interface.

Please note that I've used a M1 Mac, so the installation might suffer from some problems if you are using a different CPU architecture. In those cases do not hesitate to look up information on the official sources such as PyTorch or PyPi to solve your occasional errors during the installation.

## References

- [Deep Learning for Coders with fastai and PyTorch](www.course.fast.ai)
- [Google - Recommendation Systems - Collaborative Filtering](https://developers.google.com/machine-learning/recommendation/collaborative/basics)
