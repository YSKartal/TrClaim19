# TrClaim19
This is the first labeled data resource for Turkish check-worthy claim detection. The dataset has the following columns separaed by tab(```\t```):
* tweet
* claim: fact checked claim by experts
* relevance_judgment: relevance of tweet and claim. 0: not relevant, 1: relevant
* check_worthiness: check worthiness of the tweet. 0: not check worthy, 1: check worthy
* graded_check_worthiness: number of total check worthy annotations out of 3.

## TrClaim_v1_0
The original dataset with 2287 annotated tweets.


## TrClaim_v1_1
The original dataset contains duplicate tweets comes from different annotation groups. These duplicate tweets are removed in this version. It contains 2188 annotated tweets.



If you find this work useful in your research, please cite:
```
@inproceedings{kartal-kutlu-2020-trclaim,
    title = "{T}r{C}laim-19: The First Collection for {T}urkish Check-Worthy Claim Detection with Annotator Rationales",
    author = "Kartal, Yavuz Selim  and
      Kutlu, Mucahid",
    booktitle = "Proceedings of the 24th Conference on Computational Natural Language Learning",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.conll-1.31",
    doi = "10.18653/v1/2020.conll-1.31",
    pages = "386--395",
    abstract = "Massive misinformation spread over Internet has many negative impacts on our lives. While spreading a claim is easy, investigating its veracity is hard and time consuming, Therefore, we urgently need systems to help human fact-checkers. However, available data resources to develop effective systems are limited and the vast majority of them is for English. In this work, we introduce TrClaim-19, which is the very first labeled dataset for Turkish check-worthy claims. TrClaim-19 consists of labeled 2287 Turkish tweets with annotator rationales, enabling us to better understand the characteristics of check-worthy claims. The rationales we collected suggest that claims{'} topics and their possible negative impacts are the main factors affecting their check-worthiness.",
}
```
