Finegrained Sentiment Data Set, Release 1
========================================
The finegrained sentiment data set contains 294 product reviews from various
online sources manually annotated with sentence-level sentiment by
Oscar Täckström and Ryan McDonald. The data is approximately balanced with
respect to domain (books, dvds, electronics, music, videogames) and overall
review sentiment (positive, negative, neutral).

The data set, annotation guidelines and inter-annotator agreement is described
in more detail in [1] and [2].

The data set can be freely used for any friendly purpose, but please cite [1]
if you use it for any of your publications.

Any comments and suggestions are welcome by e-mail to
Oscar Täckström (oscar@sics.se)!

Downloads
---------
The data set can be downloaded from
https://github.com/oscartackstrom/sentence-sentiment-data

Data format
-----------
The data set is found in the file data/finegrained.txt
The file is in plain unicode (utf-8) text format with *nix line breaks.

Reviews are separated by a blank line.
Each review starts with a header containing document id, domain and star rating:
DOCID
DOMAIN	#STARS

Then follows the sentence-split review content, one sentence per line.
Each line consists of two columns containing the sentence sentiment label and
the actual content of the sentence in raw format, that is without tokenization:
LABEL1	CONTENT1
LABEL2	CONTENT2
...

References
----------
The data set has been used for the following publications (please cite [1]):

[1] Oscar Täckström and Ryan McDonald (2011).
Discovering fine-grained sentiment with latent variable structured prediction models.
European Conference on Information Retrieval (ECIR 2011), Dublin, UK.

[2] Oscar Täckström and Ryan McDonald (2011).
Discovering fine-grained sentiment with latent variable structured prediction models.
Technical Report T2011:02, Swedish Institute of Computer Science (SICS), Kista, Sweden.

[3] Oscar Täckström and Ryan McDonald (2011).
Semi-supervised latent variable models for sentence-level sentiment analysis.
The Association for Computational Linguistics: Human Language Technologies (ACL-HLT), Portland, OR, USA.
