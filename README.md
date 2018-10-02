# Conversational Analysis - Topics Over Time Using The Santa Barbara Corpus of Spoken American English

The motivation of this project is to examine how conversations flow over time, through the lens of topic composition. This project analyzes the Santa Barbara Corpus of Spoken American English (SBCSAE) and models topic composition over time for the conversations in the corpus.

## Getting Started With This Project

Before running through the notebooks, make sure to download the SBCSAE from the webpage here: http://www.linguistics.ucsb.edu/research/santa-barbara-corpus

Direct download link: http://www.linguistics.ucsb.edu/sites/secure.lsit.ucsb.edu.ling.d7/files/sitefiles/research/SBC/SBCorpus.zip

After downloading the corpus, unzip the downloaded file. You can ignore the TRN folder and `.trn` transcript files - we will focus on the `.cha` files and thus will only use the folder containing those conversation transcript file formats. Note that you may need to rename the folder containing these files from the folder I've specified in the `import_data.ipynb` notebook.

## Setup

Ensure that Python version 3.6+ is downloaded, along with the following libraries:
- Pandas
- Numpy
- PyLangAcq
  * See more information here: http://pylangacq.org/download.html
  * Can be downloaded via pip: `pip install -U pylangacq`
- MatPlotLib
- NLTK
- Scikit-learn

## To-do:
- Expand `README.md` including (and not limited to):
  * Setup section (versions, environment setup)
  * Introduction section
  * Link to future blog post
  * Link to existing presentation
  * License information
- Expand exploratory data analysis section
- Refactor `import_data.ipynb` to save data as a `.csv`
- Refactor majority of `NLP_&_modeling.ipynb` including (and not limited to):
  * Topic words output
  * `convo_topics` function: split into sensible modules
  * Plots of topic composition over time

## Notes

This project was initially undertaken far the Metis Data Science bootcamp program by Jeremy Brown.
