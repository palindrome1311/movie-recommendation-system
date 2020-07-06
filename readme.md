

# Movie Recommendation System

A **recommender system** or a **recommendation system** (sometimes replacing “system” with a synonym such as platform or engine) is a subclass of information filtering system that seeks to predict the “rating” or “preference” a user would give to an item

and putting in a simple language “*a recommendation system suggest anything relevant based on the used interest*” 

## Installation 

Use the Package manager [pip](https://pip.pypa.io/en/stable/)  to install various dependencies .

```bash
pip install pandas 
pip numpy as np
pip seaborn as sns
pip install scipy 
pip install ast
pip install sklearn
pip install nltk
pip install surprise
```

## Importing Dependencies

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats
from ast import literal_eval
from sklearn.feature_extraction.text import TfidfVectorizer, CountVectorizer
from sklearn.metrics.pairwise import linear_kernel, cosine_similarity
from nltk.stem.snowball import SnowballStemmer
from nltk.stem.wordnet import WordNetLemmatizer
from nltk.corpus import wordnet
from surprise import Reader, Dataset, SVD, evaluate
```

## Content Based Filtering



![](C:\Users\Nirav\Desktop\ml stanford\highly elastic demand curve - Google Search_files\cbf.png)

*The idea behind* **Content-based (cognitive filtering)** *recommendation system is to recommend an item based on a comparison between the content of the items and a user profile.In simple words,I may get recommendation for a movie based on the description of other movies.*

## Team

* Naman Mittal

* Neerav Jain

* Niti Mangwani

  

