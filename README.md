# Summary

The Hindi-English Code-switching treebank is based on code-switching tweets of Hindi and English multilingual speakers (mostly Indian) on Twitter. The treebank is manually annotated using UD sceheme. The training and evaluations sets were seperately annotated by different annotators using UD v2 and v1 guidelines respectively. The evaluation sets are automatically converted from UD v1 to v2. 
# Requirements

Install [Tweepy](https://github.com/tweepy/tweepy)

Get your Twitter app keys from https://apps.twitter.com/ and put the keys in the ``crawl_tweets.py`` script.


# Crawl Tweets

    python crawl_tweets.py -i merge/tweet_ids_train.txt -a merge/train-annot.json -o qhe_hiencs-ud-train.conllu  #NAACL'18 Dataset
    python crawl_tweets.py -i merge/tweet_ids_dev.txt -a merge/dev-annot.json -o qhe_hiencs-ud-dev.conllu  #EACL'17 dataset
    python crawl_tweets.py -i merge/tweet_ids_test.txt -a merge/test-annot.json -o qhe_hiencs-ud-test.conllu  #EACL'17 dataset


# Acknowledgments

Any publication reporting the work done using this data should cite the following papers:

Irshad Ahmad Bhat, Riyaz Ahmad Bhat, Manish Shrivastava and Dipti Misra Sharma. Universal Dependency Parsing for Hindi-English Code-switching. In Proceedings of the North American Chapter of the Association for Computational Linguistics (NAACL) 2018, New Orleans, USA.


    @inproceedings{bhat2017joining, 
      title={Joining Hands: Exploiting Monolingual Treebanks for Parsing of Code-mixing Data},
      author={Bhat, Irshad and Bhat, Riyaz A and Shrivastava, Manish and Sharma, Dipti},
      booktitle={Proceedings of the 15th Conference of the European Chapter of the Association for Computational Linguistics: Volume 2, Short Papers},
      volume={2},
      pages={324--330},
      year={2017}
    }

Irshad Ahmad Bhat, Riyaz Ahmad Bhat, Manish Shrivastava and Dipti Misra Sharma. Joining Hands: Exploiting Monolingual Treebanks for Parsing of Code-mixing Data. In Proceedings of the European Chapter of the Association of Computational Linguistics (EACL) 2017, Valencia, Spain.

    
    @inproceedings{bhat2018universal,
      title={Universal Dependency Parsing for Hindi-English Code-Switching},
      author={Bhat, Irshad and Bhat, Riyaz A and Shrivastava, Manish and Sharma, Dipti},
      booktitle={Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long Papers)},
      volume={1},
      pages={987--998},
      year={2018}
    }


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.3
License: CC BY-SA 4.0
Includes text: no
Genre: social
Lemmas: converted from manual
UPOS: manual native
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Bhat, Riyaz Ahmad; Bhat, Irshad Ahmad
Contributing: elsewhere
Contact: riyaz.ah.bhat@gmail.com
===============================================================================
</pre>
