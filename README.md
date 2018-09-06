# WikiQAar
WIKIQAar is a bilingual English--Arabic Question Answering corpus built on top of WIKIQA.
In order to build WIKIQAar, we independently produced two (sub-)corpora. On the question side, we produced a parallel corpus by translating the questions into Arabic. We applied two automatic machine translators and crowdsourced the selection of the best one to be incorporated into the corpus. On the reference side, we produced a comparable corpus by retrieving the Arabic edition of the corresponding Wikipedia articles. In order to identify the exact answers, we applied a supervised model to find out which text fragment in the Arabic article corresponded to the answer in English (hence composing yet another parallel collection). 

We make this dataset publicly available for the community to explore models such as cross-language question answering and answer triggering across languages; i.e. deciding if an answer exists in the same language as the question and ---if not--- searching in the other language.
# List of files
WIKIQAar is organised in the same way as WIKIQA English.

The dataset comes in four files: 

* WikiQAar.tsv: contains all data

* WikiQAar-train.tsv, WikiQAar-dev.tsv, WikiQAar-test.tsv: train/dev/test split of WikiQAar.tsv as in WIKIQA English.

Together with the WIKIQAar corpus, two other test sets are available: 

* WikiQAQuestionsCorpusAr-En.tsv: a collection of 3047 English questions translated into Arabic via machine translation and crowdsourcing.

* WikiQAArticlesCorpusAr-En.tsv: a collection of Wikipedia articles in Arabic and English.
# References
[WIKIQA: A Challenge Dataset for Open-Domain Question Answering]( https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/YangYihMeek_EMNLP-15_WikiQA.pdf)

**Contact:**
abbes.ines@yahoo.com and albarron@hbku.edu.qa
