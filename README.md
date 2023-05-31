# movie-review-sentiment-classifier

First posted in my [Kaggle](https://www.kaggle.com/code/wesleyacheng/movie-review-sentiment-classifier-with-bert/notebook) and hoted on my [HuggingFace](https://huggingface.co/wesleyacheng/movie-review-sentiment-classifier-with-bert).

## Introduction
I was just reading the IMDb reviews of [*The Super Mario Bros. Movie*](https://www.imdb.com/title/tt6718170/), I thought why don't we make a sentiment classifier to categorize movie reviews!

<img width="793" alt="mario-movie-poster" src="https://github.com/wesleyacheng/movie-review-sentiment-classifier-with-bert/assets/15952538/e3ec77d6-4ba6-402f-a657-bab0d952eab4">

Here we will be doing [transfer learning](https://en.wikipedia.org/wiki/Transfer_learning) on BERT [(blog)](https://ai.googleblog.com/2018/11/open-sourcing-bert-state-of-art-pre.html) [(paper)](https://arxiv.org/abs/1810.04805v2) with an [IMDb dataset](https://huggingface.co/datasets/imdb) to make a sentiment classifier for movie reviews.
