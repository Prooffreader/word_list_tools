``word_list_tools``
===============

Python and pandas tools to perform various analyses on different types of word lists

**Note: This repo was thoroughly resturctured on 2014/09/13, I tried to go through and make sure all the paths were valid, but it's possible some slipped by me.**

Word corpora used:

* COHA, the Corpus of Historical American English from Brigham Young University. 1-grams require a licence to use, so they are not included here; .gitignore has a rule to ignore coha_1*.*. Metadata/summary data is included here.
* Brown corpus, part of python's NLTK
* Europarl: A Parallel Corpus for Statistical Machine Translation, Philipp Koehn, MT Summit 2005 (http://statmt.org/europarl/) [files not included because they are ginormous]

Simple word lists used:

* The Moby list of crossword puzzle words (113,809 words)

Run script first:

* ``initial_data_munge.ipynb`` will make properly formatted python objects of the corpora/lists above

Tools:

* ``letter_frequency``: Simple single letter counts, and comparisons to a standard cryptography text
* ``letter_proximity``: conditional probabilities of each moiety of a bigram; or, the probability that one letter follows or precedes another.
* ``letter_distributions``: graphs of how often a letter is towards the beginning, middle or end of words
* ``letter_distribution_europarl_comparison``: ``letter_distribution`` or multiple languages in Europarl
* ``google_ngrams``: a work in progress
* ``pattern_searches``: various ways to search various word lists by various patterns
* ``stringcmp_py``: scripts to compare strings (e.g. Jaro-Winkler, Levenshtein, Metaphone). From the Australian National University, under a GNU open source license. (The web page I originally downloaded them from in 2013 is no longer online.)

See the readme inside the data_user_pickle_csv for their schemas.

