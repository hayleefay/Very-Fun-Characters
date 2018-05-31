1) The dataset here was used in the following paper:

Snigdha Chaturvedi, Shashank Srivastava, Hal Daume III and Chris Dyer, Modeling Evolving Relationships Between Characters in Literary Novels. In Proceedings of the Thirtieth AAAI Conference on Artificial Intelligence, February 12-17, 2016, Phoenix, Arizona, USA. Pages 2704–2710.

You can get the bibtex here: http://www.aaai.org/ocs/index.php/AAAI/AAAI16/rt/captureCite/12408/0/BibtexCitationPlugin

2) This is part of the data used in the following paper:

Snigdha Chaturvedi, Mohit Iyyer, Hal Daume III, Unsupervised Learning of Evolving Relationships Between Literary Characters. In Proceedings of the Thirty-First AAAI Conference on Artificial Intelligence, February 4-9, 2017, San Francisco, California, USA. Pages 2704–2710. 

3) The summaries are obtained from the plotoverviews section of sparknotes (http://www.sparknotes.com/sparknotes/). Please do not forget to acknowledge them in your work, if you use this data.

======================================================================
This data constitutes of:

--------------------------------
Summaries
--------------------------------
For raw as well as preprocessed text of the 300 novel summaries, please download the dataset used in AAAI 2017 paper. The data is available at https://sites.google.com/site/snigdhac/academics 

--------------------------------
Sequences
--------------------------------
From the above mentioned 300 novel summaries, we extracted 634 sequences of sentences representing relationships between pairs of characters. The sequences can be downloaded from the dataset used in the AAAI 2017 paper. A subset of these sequences were manually annotated with whether the relationship at any sentence is cooperative or non-cooperative. In our annotation, 'p' represents cooperative relationship and 'n' represents non-cooperative relationship. 50 sequences were fully annotated while 50 were partially annotated (partial annotation means not all sentences in a sequence were annotated). 

The fully annotated sequences can be found at in the subdirectory:
fullyAnnotatedSequences

The partially annotated sequences can be found in the subdirectory:
partiallyAnnotatedSequences

Each file in the above directories contains the text of the annotated sequences, one sentence per line. Each line contains the label, sentence id and text of the sentence separated by ':::'. The sentence id corresponds to that in the processed summaries (can be found in the 'processedText' directory of the dataset used for AAAI 2017 paper). The sentence text is space separated tokens of the sentence. The tokens are also appended with charId of the token using an underscore. The charId= -1 if the token doesn't represent a character. Note that charIds are automatic labels from the 'processedText' directory. 

The features extracted by our system for each of the 634 sequences are present in the subdirectory named "features". They include 33 content related features. 

--------------------------------
Notes
--------------------------------

The results reported in Section 4.3 of AAAI 2016 paper are on the fully annotated set.

Duplication: The sequences that are annotated here are a subset of the sequences used in AAAI 2017 paper, and so they appear in both datasets.
