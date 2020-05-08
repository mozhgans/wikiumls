# WikiUMLS: Aligning UMLS to Wikipedia via Cross-lingual Neural Ranking (still under construction)


# Neurally ranked candidates 

JSON file in the form of cui:[wikiid1, ....] that can be used for manual aligning of cui to wikipedia/wikidata

https://uq-my.sharepoint.com/:u:/g/personal/uqarahi2_uq_edu_au/Ed8ZPUArBKFNqZyhFsE7l0sB2Xop-ZLE1c9HfAljSdwMsg?e=nP2UAC

# Dataset 

gold values cui:wikiid partitioned into trianing, dev, and test collected from wikidata annotated by wikidata contributors

https://uq-my.sharepoint.com/:u:/g/personal/uqarahi2_uq_edu_au/EYbzkYFxraJKrUaEZe-GG4IBHLl05a6d1KQqN-SMXDOJJw?e=TuNrm1

# Test set BERT-style two sentence binary classification (relevant or not)

It contain: cuialias1, cuialias2, ....  \t wikialias1, wikialias2, ....

https://uq-my.sharepoint.com/:u:/g/personal/uqarahi2_uq_edu_au/EdfgcJf31u1IjJ6PGw9ADt0BdIfB_UOtY-4wh50Qy3An-g?e=ACBshg


#Code

Most code is used for preprocessing of the dataset, otherwise, you can use BERT to train the two sentence classification.