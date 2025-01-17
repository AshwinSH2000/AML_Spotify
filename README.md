Applied Machine Learning 

Explanation
- This repo contains all details required for the applied machine learning reports.
- The steps below describe how to use the code and what each file does.

Disclaimer : All files should run assuming the database path has been set up correctly and you are using Jupyter Notebook Python 3. If a file is taking a while to complete running do not be alarmed.

Steps

1) Load the ipynb files into Jupyter Notebook.
2) Download the dataset linked to the Spotify project. 
3) For each individual file please change the directory and path of the dataset to your own path where it is stored. However, if it placed in the same folder as the python notebooks, then no edits are needed. 
4) Run ExploratoryDataAnalysis.ipynb : Load the notebook and execute each cell. This file contains a collection of graphs and analyses to do with the project. 
5) Run SpotifySupervisedLearningWithoutArtist.ipynb : This files contains a list of results with different supervised models using numerical features excluding the artist.
6) Run SpotifySupervisedLearningWithArtist.ipynb : This files contains a list of results with different supervised models using numerical features, including the self calculated artist weight.
7) Run Processing&Results.ipynb : This file contains processing and results of supervised models being tested after applying unsupervised learning techniques along with data cleaning for more accurate results.
