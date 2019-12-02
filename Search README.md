# MovieMahal
import pandas as pd
import numpy as np

from sklearn.metrics.pairwise import cosine_similarity
from sklearn.feature_extraction.text import CountVectorizer,ENGLISH_STOP_WORDS
from ast import literal_eval
from sklearn.metrics.pairwise import linear_kernel
from matplotlib.pyplot import figure, gca, xlabel, barh, title
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.feature_extraction.stop_words import ENGLISH_STOP_WORDS

from nltk.stem import WordNetLemmatizer


MovieMahal
