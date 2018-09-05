# disaster_summarizer_TWEB_2018
This directory contains relevant codes from the paper "Extracting and Summarizing Situational Information from the Twitter 
Social Media during Disasters".
This repository contains following set of codes.

Preprocessing & Fragmentation
------------------------------

This directory contains codes to remove noises from tweets, perform lemmatization, fragmentation etc. After fragmentation the files will go to classification phase to detect situational and non-situational tweet fragments.

Classification
--------------

This directory contains codes which are used to classify tweets (tweet-fragments) into situational and non-situational label. After this stage situational tweets are passed to the summarizer.

Summarization
--------------

This directory contains codes which extracts content words from tweets and summarize the information.

This directory contains two summarization codes

1. COWTS: COntent Word based Tweet Summarization proposed in CIKM'15. [Koustav Rudra, Subham Ghosh, Niloy Ganguly, Pawan Goyal, and Saptarshi Ghosh. 2015. Extracting Situational Information from Microblogs during Disaster Events: a Classification-Summarization Approach. In Proceedings of the 24th ACM International on Conference on Information and Knowledge Management (CIKM '15). ACM, New York, NY, USA, 583-592. DOI: https://doi.org/10.1145/2806416.2806485 ]

2. SEMCOWTS: SEMantic relation based COntent Word Tweet Summarization published in this paper. This is an extension of COWTS. [Koustav Rudra, Niloy Ganguly, Pawan Goyal, and Saptarshi Ghosh. 2018. Extracting and Summarizing Situational Information from the Twitter Social Media during Disasters. ACM Trans. Web 12, 3, Article 17 (July 2018), 35 pages. DOI: https://doi.org/10.1145/3178541]

Summarization codes and readmes are there for both the methods. Individual directories contain details about how to run those codes. If you use any of them kindly cite appropriate version.

Frequently changing information
--------------------------------

This directory contains code which captures frequently changing numerical information such as how many people killed, injured, trapped or stranded in different locations and how it varies over time.

Note: Each of the directories contains separate README files containing instructions about how to run the code.
