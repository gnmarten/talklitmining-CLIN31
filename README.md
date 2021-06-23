# TalkLitMining - CLIN31

Project Website: [link](https://www.talklitmining.ugent.be)

<!-- Add buttons here -->

![GitHub release](https://img.shields.io/badge/release-1.0.0-orange)
![GitHub last commit](https://img.shields.io/github/last-commit/gnmarten/talklitmining-CLIN31)
![GitHub issues](https://img.shields.io/github/issues-raw/gnmarten/talklitmining-CLIN31)
![GitHub pull requests](https://img.shields.io/github/issues-pr/gnmarten/talklitmining-CLIN31)

<!-- Describe your project in brief -->

### Evaluation of literature by professional and layperson critics: A digital and literary sociological analysis of evaluative talk of literature through the prism of literary prizes (2007-2017) ###

![Banner](https://www.talklitmining.ugent.be/wp-content/uploads/2021/06/vlcsnap-error192_statements.png)


The project aims to answer questions such as: What are the criteria for telling ‘good’ from ‘bad’ literature used by both professional and layperson critics? What role does the attribution of societal engagement play in the judgment of contemporary literature? What are the differences between academic prizes and literary prizes that draw on audience participation?

In the current version of this code, we analyze tweets in German, and train classifiers to predict categories and sentiment associated with keywords and aspects in the tweets. 

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

