Schemas of these pickles and/or csvs:
===

``coha_1.pickle``: pandas dataframe (not included on GitHub because it has a restricted license).

* ``word``: not unique
* ``freq``
* ``decade``: 1=1810-1819, 2=1820-1829, ... , 20=2000-2009
* ``nonalpha``: ``True`` if ``word`` contains non-alphanumeric character(``[A-Za-z]``)
* ``length``: number of character in ``word``
* ``pct``: pecentage of ``freq`` / ``freq.sum()``.(Freq is divided into decades, but the sum is not)

``coha_words.pickle``: pandas dataframe of summary data

* ``word``: only words without nonalphanumerics
* ``freq``
* ``length``: number of character in ``word``
* ``decades``: number of decades in which this word appears.

``coha_words_mean_median.pickle``: tuple of weighted mean word length, weighted median word length

``brown.pickle``: pandas dataframe

* ``word``: not unique
* ``freq``
* ``nonalpha``: ``True`` if ``word`` contains non-alphanumeric character(``[A-Za-z]``)
* ``category``: from what part of the Brown corpus the word is found.

``coha_words.pickle``: pandas dataframe of summary data

* ``word``: only words without nonalphanumerics
* ``freq``
* ``length``: number of character in ``word``

``moby_crossword_list.pickle``: python list of words in alphabetical order