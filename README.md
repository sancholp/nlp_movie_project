# ML movie tagging project (NLP)

## Training a model to assign tags (genres) to movies based on their plot summary
This project aims to train a model to assign tags to a movie based on its plot synopsis.

In this project, I work on a dataset obtained through scraping the [IMDb](https://www.imdb.com/) website. This dataset contains ~6000 movies' plot synopsis and their corresponding genre tags. Throughout the project, I explore the data and subsequently train various models to assign tags to movies. 

The dataset is interesting as it provides many challenges. Most notably, this is a multi-labelled classification problem. In other words, the tags are mutually exclusive. Furthermore, the dataset is extremely unbalanced. 

## Tools used
* [Scikit-learn](https://scikit-learn.org/stable/)
* [PyTorch](https://pytorch.org/)
* [NLTK](https://www.nltk.org/)
