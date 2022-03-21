Exercises inspired by [Natural Language Processing with Transformers, by Tunstall, von Werra and Wolf](https://www.oreilly.com/library/view/natural-language-processing/9781098103231/).
Also see their [official notebook repository](https://github.com/nlp-with-transformers/notebooks).

Contents:

# Chapter 2

## [Text Classification Fine Tuning](./notebooks/ch2-classification-fine-tuning.ipynb)

This is the fine-tuning section of [Chapter 2 - Text Classification](https://github.com/nlp-with-transformers/notebooks/blob/main/02_classification.ipynb).
I found the text notebook wouldn't run in Kaggle on a P100, so this is a cut down version that trains the fine-tuned classifier which will run in Kaggle.

To run in Kaggle:

* Click the Open in Kaggle link: [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/EdwardJRoss/nlp_transformers_exercises/blob/master/notebooks/ch2-classification-fine-tuning.ipynb)
* In the notebook settings select "Accelerator > GPU", as per screenshot below
* Run the cells of the notebook

![Selecting GPU Accelerator in Kaggle](/resources/kaggle_select_gpu.png)


## [Fine Tuning IMDB Classifier](./notebooks/ch2-classification-imdb.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/EdwardJRoss/nlp_transformers_exercises/blob/master/notebooks/ch2-classification-imdb.ipynb)

This is a variation of classifying on the IMDB dataset from [Learning Word Vectors for Sentiment Analysis](https://aclanthology.org/P11-1015/), for which there are [good benchmarks](https://paperswithcode.com/sota/text-classification-on-imdb).


