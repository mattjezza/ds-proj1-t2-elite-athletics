# ds-proj1-t2-elite-athletics

**Summary**

This is my submission for Project 1 of Term 2 of Udacity's Data Science Nano Degree project. It uses data sets obtained from Kaggle to answer questions about the performance of elite athletes. Specifically, it addresses the following questions:

1. How have elite runners' performances changed through history?
2. How have Olympic runners' characteristics (height, weight, age, body mass index) changed through history?
3. Is there a relationship between Olympic runners' characteristics and their race performance?

**Files**

Elite_Running_Analysis.ipynb - Jupyter notebook containing all the analysis
Elite_Running_Analysis.html  - HTML export of the Jupyter notebook

**Environment/Packages imported**

This is a Python 3 project using Jupyter notebooks.
pandas
chardet
ftfy
pyplot
pylab
datetime
numpy
math
fuzzywuzzy
fuzzywuzzy
register_matplotlib_converters

The Jupytert notebook uses toc2 from jupyter_contrib_nbextensions and the jupyter_nbextensions_configurator to insert a table of contents into the notebook. These are installed with:

conda install -c conda-forge jupyter_contrib_nbextensions

**Results**
1. Elite athletes' performances have improved over the last 125 years in all running events.
2. For some events, mean values for characteristics have changed over time (sprinters have tended to get heavier, average age of athletes in several events has increased).
3. Each event has a "sweet spot" which is a combination of characteristic values that tend to give good performance in a particular event.
Neverthless, a wide range of athlete characteristics can produce top performances. Weight is the biggest factor in determining athlete performance for an event.

Other factors (such as training techniques, diet) probably have a large impact, but they are not examined in this analysis.

**Deployment**

A non-technical post summarising this work is published on Medium: "Analysing Elite Running Performance with Historical Data" (https://medium.com/@matt_chap/analysing-elite-running-performance-with-historical-data-b9c6bdd9c5d8)

**Acknowledgements and References**

The following have all been used in the preparation of this project.
- Udacity Data Science Nano Degree course materials

*Kaggle data sources*
- https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results/downloads/120-years-of-olympic-history-athletes-and-results.zip/2
- https://www.kaggle.com/jayrav13/olympic-track-field-results/downloads/olympic-track-field-results.zip/1
- https://www.kaggle.com/jguerreiro/running/downloads/running.zip/2

*Reference for ftfy*
- https://ftfy.readthedocs.io/en/latest/

*References for Fuzzy Matching*
- http://jonathansoma.com/lede/algorithms-2017/classes/fuzziness-matplotlib/fuzzing-matching-in-pandas-with-fuzzywuzzy/
- https://www.kaggle.com/rtatman/data-cleaning-challenge-inconsistent-data-entry#Use-fuzzy-matching-to-correct-inconsistent-data-entry
- https://medium.com/@rtjeannier/combining-data-sets-with-fuzzy-matching-17efcb510ab2
- https://github.com/seatgeek/fuzzywuzzy
- https://www.datacamp.com/community/tutorials/fuzzy-string-python
