# Finding optimal number of topics with tmtoolKit in topic modeling with LDA

The script reads Pac Man's Wikipedia page and does topic modeling to it with to different metrics from tmtoolkit library. Mimno (2011) algorithm finds 18 topics and Cao Juan (2009) algorithm finds 17 topics. In total from the Wikipedia is used 18 sections.

These latent topics are different in Mimno's algorithm than in Wikipedia's sections, though.

The script creates "corpus_data" folder into the current directory the script is at (if it doesn't exist) and writes there on separate files the sentences that are used in txt format.

I hope this notebook helps people to work with tmtoolkit! ;-)

https://tmtoolkit.readthedocs.io/en/latest/