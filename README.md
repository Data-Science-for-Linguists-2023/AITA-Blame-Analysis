# AITA Blame Analysis

Alex Ocampo
AMO104@pitt.edu
04/30/2023

This is a term project for Data Science for Linguistics 2023 at the University of Pittsburgh.

## Project Description


This project analyzes the [Am I the Asshole](https://www.reddit.com/r/AmItheAsshole/) subreddit to question how we pursuade readers and shift blame while telling stories. It focuses on how much agency writers afford themselves and the other parties in their stories.

The data set for this project was generated myself using [PMAW](https://github.com/mattpodolak/pmaw), a wrapper for a third-party Reddit API named [Pushshift](https://reddit-api.readthedocs.io/en/latest/)


## Directory

* **[`final_report.md`](final_report.md): This is my final write-up for this project**
* [`README.md`](README.md): This is this current file which briefly overviews my repo.
* [`LICENSE.md`](LICENSE.md): This is the licensing information for this project. This project is licensed under GNU General Public License v3.0.
* [`class_presentation.pdf`](class_presentation.pdf): This is a slideshow used to supplement a class presentation about my project.
* [`progress_report.md`](progress_report.md): This is a journal used throughout the semester to document major updates to my project.
* [`project_plan.md`](project_plan.md): This is the original pitch for this project from the beginning of the semester.
* [`code`](code): This folder houses the Jupyter Notebooks used to work through my project.
    * [`data_collection_testion.ipynb`](https://github.com/Data-Science-for-Linguists-2023/AITA-Blame-Analysis/blob/main/code/data_collection_testing.ipynb): This houses an initial experiment with PMAW to form my data set
    * [`data_collection.ipynb`](https://github.com/Data-Science-for-Linguists-2023/AITA-Blame-Analysis/blob/main/code/data_collection.ipynb): This maintains the full run through scraping and reorganizing my data set.
    * [`data_analysis.ipynb`](https://github.com/Data-Science-for-Linguists-2023/AITA-Blame-Analysis/blob/main/code/data_analysis.ipynb): This contains the bulk of my project, where I analyze the data set for linguistic features.
    * [`data_analysis_experiments`](https://github.com/Data-Science-for-Linguists-2023/AITA-Blame-Analysis/blob/main/code/data_analysis_experiments.ipynb): This contains attempts to utilize machine learning to explore the data set. The results here are inconclusive.
* [`data`](data): This folder houses the data set develooped from this project. Most of the contents of this folder are ignored on the public repo.
    * [`aita_data_sample.csv`](data/aita_data_sample.csv): This is the results of the initial test run at [`data_collection_test.ipynb`](https://github.com/Data-Science-for-Linguists-2023/AITA-Blame-Analysis/blob/main/code/data_collection_test.ipynb)
    * [`aita_data.csv`](https://github.com/Data-Science-for-Linguists-2023/AITA-Blame-Analysis/blob/main/data/aita_data.csv): This is the final data set gathered from [`data_collection.ipynb`](https://github.com/Data-Science-for-Linguists-2023/AITA-Blame-Analysis/blob/main/code/data_collection.ipynb).
* [`figures`](figures): This folder houses the assets used within my [`final_report.md`](final_report.md).
* [`.gitignore`](.gitignore): This folder serves as housekeeping to omit any unnecessary files from the repository, such as internal saves of my data set.

 
## Visitors log
The guestbook for my project can be found [here](https://github.com/Data-Science-for-Linguists-2023/Class-Lounge/blob/main/guestbooks/alex.md)! Thank you for visiting, and I hope you enjoy :D
