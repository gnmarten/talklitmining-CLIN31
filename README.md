# TalkLitMining - CLIN31


<!-- Add buttons here -->

![GitHub release](https://img.shields.io/badge/release-1.0.0-orange)
![GitHub last commit](https://img.shields.io/github/last-commit/gnmarten/talklitmining-CLIN31)
![GitHub issues](https://img.shields.io/github/issues-raw/gnmarten/talklitmining-CLIN31)
![GitHub pull requests](https://img.shields.io/github/issues-pr/gnmarten/talklitmining-CLIN31)

<!-- Describe your project in brief -->

### Evaluation of literature by professional and layperson critics: A digital and literary sociological analysis of evaluative talk of literature through the prism of literary prizes (2007-2017) ###

![Banner](https://www.talklitmining.ugent.be/wp-content/uploads/2021/06/vlcsnap-error192_statements.png)

### Context ###

Aspect-based Sentiment Analysis (ABSA) of German-language social media data related to the Ingeborg-Bachmann-Preis and Tage der deutschsprachigen Literatur (TDDL), two German-Language Literature festivals. For more background information, please consult the [project website](http://www.talklitmining.ugent.be.)

### Data Collection ### 

We collected tweets published about the TDDL between 2007 and 2019 using the freely available scraping tool [“OMGOT3”](https://github.com/marquisvictor/Optimized-Modified-GetOldTweets3-OMGOT) and a predefined list of topical hashtags.

The scraping of social media was limited to tweets published about the TDDL between 2007 and 2019 via marquisvictor’s [“OMGOT3”](https://github.com/marquisvictor/Optimized-Modified-GetOldTweets3-OMGOT). All social media data were/are publicly accessible and have been anonymized during pre-processing. The collected data are used for non-commercial, academic purposes only. No information on individual users, apart from their handle and the number of likes and retweets, was collected – in keeping with the social media platform’s API access terms. Academics who wish to replicate our research can collect the data using the provided tweet IDs, which give access to the original tweet content if it is still publicly available. More information on Twitter’s policy and recently expanded access for academic research is to be found [here](https://developer.twitter.com/en/products/twitter-api/academic-research).

Please note that tweets are constantly being created or removed and that some profiles may no longer be public. As a consequence, your collected corpus may differ slightly from ours.

# Installation

Requirements:

* Python 3.6 + 
* pip

Setup: 

* ```git init```

* ```git clone https://github.com/gnmarten/talklitmining-CLIN31```

* ```cd talklitmining-CLIN31```

* ```pip install -r requirements.txt```

# Usage

The repository is structured as followed:

* data/ : This directory contains all the annotated CSVs, and stores all the intermediary files while preprocessing
* preprocessing.ipynb : Contains all the functions and code to download Tweet texts, and setup data for training for the model
* train_and_eval.ipynb : Trains model from scratch and runs evaluation on the test sets

Note: Add Twitter API developer keys, at the top of the file preprocessing.ipynb to get the code running!

# Contacts

Open an issue for bugs or trouble with running the scripts.

For further questions related to the code contact:

* Pranaydeep Singh [(E-Mail)](mailto:pranaydeep.singh@ugent.be)[(Github)](https://github.com/pranaydeeps)
* Lore De Greve [(E-Mail)](mailto:lore.degreve@ugent.be)

# License

[GNU General Public License version 3](https://opensource.org/licenses/GPL-3.0)

