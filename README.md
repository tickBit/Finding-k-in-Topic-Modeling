# Finding optimal number of topics with tmtoolkit in topic modeling with LDA

The notebooks read Pac-Man's Wikipedia page and do topic modeling to it with different metrics from tmtoolkit module.

The script creates "corpus_data" folder into the current directory the script is at (if it doesn't exist) and writes there on separate files the sentences that are used in txt format.

The difference between the two notebooks is, that the second uses as corpus the original data saved to disk insted of tmtoolkit's doc_labels_short_texts.

## Python version needed

At the time of writing, the tmtoolkit needs Python 3.8-Python3.10.

## Some instructions

Install tmtoolkit with lda:

pip install -U "tmtoolkit[recommended,lda]"

..and the lda module

pip install -U lda

..and to make it work with english (it uses spaCy)

python -m tmtoolkit setup en

https://tmtoolkit.readthedocs.io/en/latest/

