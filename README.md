## Open Source Recommender Systems

Most of the non-SaaS recommender systems that are open-source. This may have been because recommender systems are more tailored to clients so not easily made into a product.

The open-source recommender systems are:

1. [PredictionIO](http://prediction.io/) is built on technologies [Apache Spark](https://spark.apache.org/), [Apache HBase](http://hbase.apache.org/) and [Spray](http://spray.io/). It is a machine learning server that can be used to create a recommender system. The source can be located on [github](https://github.com/PredictionIO/PredictionIO) and it looks very active.
1. [Raccoon Recommendation Engine](https://www.npmjs.org/package/raccoon) is an open source Node.js based collaborative filter that uses Redis as a store. It is effectively abandoned.
1. [HapiGER](http://www.hapiger.com/) is an open source Node.js collaborative filtering engine, which can use in-memory, [PostgreSQL](http://www.postgresql.org/) or [rethinkdb](http://rethinkdb.com/). Reasonably active development (when I have time :)
1. [EasyRec](http://easyrec.org/) Java and Rest based recommendations. Abandoned
1. [Mahout](http://mahout.apache.org/) Hadoop/linear algebra based data mining
1. [Seldon](http://www.seldon.io) is a Java based prediction engine built on technologies like [Apache Spark](https://spark.apache.org/). It provides a demo movie recommendations application [here](http://www.seldon.io/movie-demo/).
1. [LensKit](http://lenskit.org/) is a Java based research recommender system designed for small-to-medium scale.
1. [Oryx](https://github.com/OryxProject/oryx) [v2](https://github.com/OryxProject/oryx) a large scale architecture for machine learning and prediction (suggested by [Lorand](https://disqus.com/by/disqus_V9tbLHpUxp/))
1. [RecDB](https://github.com/DataSystemsLab/recdb-postgresql) is a PostgreSQL extension to add recommendation algorithms like collaborative filtering directly into the database.
1. [Crab](https://github.com/muricoca/crab) a python recommender based on the popular packages NumPy, SciPy, matplotlib. The main repository seems to be *abandoned*.
1. [predictor](https://github.com/Pathgather/predictor)is a ruby recommender gem. This uses Jaccard or Sorenson-Dice coefficient to priovide both item centric e.g. "Users that read this book also read ..." and user centric e.g. "You read these 10 books, so you might also like to read ..." recommendations. Looks a bit neglected.
1. [Surprise](http://surpriselib.com) A Python scikit for building, and analyzing (collaborative-filtering) recommender systems. Various algorithms are built-in, with a focus on rating prediction.
1. [LightFM](https://github.com/lyst/lightfm) is an actively-developed Python implementation of a number of collaborative- and content-based learning-to-rank recommender algorithms. Using Cython, it easily scales up to very large datasets on multi-core machines and is used in production at a number of companies, including [Lyst](https://www.lyst.com) and [Catalant](https://gocatalant.com/home).
1. [Rexy](https://github.com/kasramvd/Rexy) is an open-source recommendation system based on a general User-Product-Tag concept and a flexible structure that has been designed to be adaptable with variant data-schema. Rexy is written in Python-3.5 in a highly optimized, Pythonic and comprehensive way that makes it so flexible against the changes. It also used Aerospike as the database engine which is a high speed, scalable, and reliable NoSQL database.
1. [QMF](https://github.com/quora/qmf) is a fast and scalable C++ library for implicit-feedback matrix factorization models.
1. [tensorrec](https://github.com/jfkirk/tensorrec) is a TensorFlow recommendation algorithm and framework in Python.
1. [hermes](https://github.com/lab41/hermes) is a recommendation framework for collaborative-filtering and content-based algorithms in PySpark. Main repository has been *abandoned*.
1. [Spotlight](https://github.com/maciejkula/spotlight) utilizes factorization model and sequence model in the back end for building a basic recommendation system. It's a well-implemented Python framework.
1. [recommenderlab](https://cran.r-project.org/web/packages/recommenderlab/index.html) provides a research infrastructure to test and develop recommender algorithms including UBCF, IBCF, FunkSVD and association rule-based algorithms.
1. [CaseRecommender](https://github.com/caserec/CaseRecommender) is a Python implementation of a number of popular recommendation algorithms. The framework aims to provide a rich set of components from which you can construct a customized recommender system from a set of algorithms.

## Benchmarking Recommender Systems

It is very difficult to benchmark recommender systems, not only because getting good datasets is hard, but different methods and algorithms have different advantages and disadvantages that are difficult to expose.

Here is a list of some benchmarking tools:

1. [TagRec](https://github.com/learning-layers/TagRec) Tag Recommender Benchmarking Framework
1. [RiVaL](http://rival.recommenders.net/) an open source toolkit for recommender system evaluation. Some results are posted [here](http://alans.se/blog/2014/rival/).
1. [Idomaar](http://rf.crowdrec.eu/) is a reference framework for recommender algorithm testing. It is developed in the framework of the [CrowdRec](http://crowdrec.eu) project.

## Media Recommendation Applications

In addition to generic recommender systems, I decided to add a list of applications where recommendations are a core offering, specifically in the domain of media recommendations:

1. [Yeah, Nah](https://github.com/grahamjenson/yeahnah) Movie recommendations app based on [GER](https://github.com/grahamjenson/ger)
1. [Jinni](http://www.jinni.com/) Movie recommendations site
1. [Gyde](http://gyde.tv/) Streaming media recommendations
1. [TasteKid](http://www.tastekid.com/) movies, books, music recommendations. *sent to me by [thelinuxlich](https://github.com/thelinuxlich)*
1. [Gnoosic](http://www.gnoosic.com/) music based on bands. *sent to me by [thelinuxlich](https://github.com/thelinuxlich)*
1. [Pandora](http://www.pandora.com/) music recommendations based on likes and dislikes or songs
1. [Criticker](https://games.criticker.com/ ) Game and movie collaborative recs. *suggested by [ran88dom99](https://github.com/ran88dom99)*
1. [movielens.org](https://movielens.org/) End user movie n book rec by lenskit people. *suggested by [ran88dom99](https://github.com/ran88dom99)*
1. [MAL](https://myanimelist.net/) based [only similar users](http://affinity.animesos.net/)[rec](https://graph.anime.plus/) and [rec](http://www.animerecs.com/)  *suggested by [ran88dom99](https://github.com/ran88dom99)*
1. [NewsPortalUserInteractions](https://www.kaggle.com/gspmoreira/news-portal-user-interactions-by-globocom) A large dataset provided by [globo.com](https://www.globo.com) for news recommendation *suggested by [guedes-joaofelipe](https://github.com/guedes-joaofelipe)*
1. [ContentWise](https://www.contentwise.tv/) UX management solution for digital media entertainment. *suggested by [GiovanniPaoloGibilisco](https://github.com/GiovanniPaoloGibilisco)*

## Books and Class

1. https://www.amazon.com/Practical-Recommender-Systems-Kim-Falk/dp/1617292702/ref=sr_1_1?ie=UTF8&qid=1547871294&sr=8-1&keywords=Practical+Recommender+Systems

Lloyd's fav class https://www.udemy.com/building-recommender-systems-with-machine-learning-and-ai/
