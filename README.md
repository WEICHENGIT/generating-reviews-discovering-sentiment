# Sentiment Analysis
#### WEI Chen, Pierre-Yves Casanova

This repository is the implementation of sentiment analysis based on mLSTM model from paper [Generating Reviews and Discovering Sentiment](https://github.com/openai/generating-reviews-discovering-sentiment).

Python Requirements:

    Python 3.5
    Pytorch 0.3.0
    numpy
    pandas
    scikit-learn
    matplotlib
    seaborn
    unidecode
    csv
    json
    nltk

[Sentiment Visualization & Opinion Generation Tool.ipynb](https://github.com/WEICHENGIT/Sentiment-Analysis-PRIM/blob/master/Sentiment%20Visualization%20%26%20Opinion%20Generation%20Tool.ipynb)</br>
This jupyter notebook provides a sentiment analysis API where you can try to visualize the sentiment expresssed in text, also generate opinions according the initial text you customize. It is based on work from [@guillette](https://github.com/guillitte/pytorch-sentiment-neuron) and [@NVIDIA](https://github.com/NVIDIA/sentiment-discovery).

[Baseline test.ipynb](https://github.com/WEICHENGIT/Sentiment-Analysis-PRIM/blob/master/Baseline%20test.ipynb)</br>
This jupyter notebook contains two baseline tests: SentiWordNet, n-gram. We test both baselines on middle scale of dataset IMDb, however they can be applied to any labelled dataset.

[Data preprocessing.ipynb](https://github.com/WEICHENGIT/Sentiment-Analysis-PRIM/blob/master/Data%20preprocessing.ipynb)</br>
This jupyter notebook contains the code for data preprocessing for several popular datasets including [Twitter2016](http://alt.qcri.org/semeval2017/task4/index.php?id=data-and-tools), [OpinMind](https://www.kaggle.com/c/si650winter11/data), [CNN](https://github.com/deepmind/rc-data/), [Bloomberg](https://github.com/philipperemy/financial-news-dataset), [MPQA2.0](http://mpqa.cs.pitt.edu/corpora/mpqa_corpus/mpqa_corpus_2_0/), and [IMDb](http://ai.stanford.edu/~amaas/data/sentiment/). The raw dataset/corpus and the processed ones can be found in the [release](https://github.com/WEICHENGIT/Sentiment-Analysis-PRIM/releases).
