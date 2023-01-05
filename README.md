# Data Visualization project

This is the Data Visualization project of Valeria Insogna and Cecilia Zagni.

The dataset contains info about results from 17 major international skating events from October 2016 through December 2017.

The project addresses the following questions about the data:
* Do the judges favour compatriot athletes?
* Which athletes present the most difficult elements and how are they ranked? 
* Are elements more important than components in establishing the final ranking?


At the end of each event it oversees, the [International Skating Union](http://www.isu.org/) releases a PDF containing all scores given for each performance which are of public domain. That report is known as a "Protocol," and an example can be [found here](http://www.isuresults.com/results/season1718/gpf1718/gpf2017_protocol.pdf).

You can find the list of those 17 competitions at the following [link](https://github.com/BuzzFeedNews/2018-02-figure-skating-analysis).

## Required Packages

- Python 3.9

Subpackages:
- plotly 
- pandas
- numpy

## Structure

You can find the following files and folders in this repository:

- `data/`: The final data used in the 3 notebooks after preprocessing.
- `img/`: The picture used in the presentation and plots.
- `plots/`: The 3 plots used in the presentation.
- `preprocessing/`: The code used to preprocess the raw data from [this repository](https://github.com/BuzzFeedNews/2018-02-figure-skating-analysis).
- `utils/`: The license of the background picture of the presentation.
- `final_question_1.ipynb`: the notebook addressing the first question.
- `final_question_2.ipynb`: the notebook addressing the second question.
- `final_question_3.ipynb`: the notebook addressing the third question.
- `presentation.pdf`: the presentation of the project in pdf version.
- `presentation.pptx`: the presentation of the project in pdf version.


## Useful links

- [The International Skating Union](http://www.isu.org/).
- [Original dataset and analysis](https://github.com/BuzzFeedNews/2018-02-figure-skating-analysis).
- [Glossary of preprocessing files](https://github.com/BuzzFeedNews/figure-skating-scores).
- [Judging system from Wikipedia](https://en.wikipedia.org/wiki/ISU_Judging_System#:~:text=The%20seven%20elements%20required%20of,spiral%2C%20and%20one%20step%20sequence).
- [ISU Rules for judging system](https://www.isu.org/figure-skating/rules/fsk-judging-system).
- [US scoring system](https://www.usfigureskating.org/about/scoring-system)