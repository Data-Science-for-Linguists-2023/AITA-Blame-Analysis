# Progress Report

## 02/13/2023

* I've created the repository and filled out the necessary files
* Begun looking into using the Reddit API to create my corpus

## 1st Progress Report - 02/24/2023

I've begun the process of utilizing [PRAW](https://praw.readthedocs.io/en/latest/index.html) and [PMAW](https://github.com/mattpodolak/pmaw) to scrape data from [r/AmITheAsshole](https://www.reddit.com/r/AmItheAsshole/). I've discovered that it's difficult to use PRAW, the Python wrapper for the built-in Reddit API, alone for my needs. This is because the built-in Reddit API does not allow you to query posts past a certain duration of time (I'm still unsure what that duration is), and only lets you scrape 1,000 posts at a time. Because I'm only using one subreddit for this project, that does not give a satisfactory number of posts to use.
Luckily, there's a third-party API called the Pushshift API, which has the Python wrapper PMAW, which allows you to scrape all archived posts for a given subreddit. However, I came across a new problem: apparently, the Pushshift API is undergoing a migration and does not have access to any data from before November 2022 ([source](https://github.com/mattpodolak/pmaw/issues/57)). Still, AITA is a popular subreddit, so there is still a large amount of data available, but going forward it might be important to consider how small of a sliver temporally into the trends of speaking patterns people are exhibiting.
Lastly, it seems that limiting the amount of posts you are scraping is currently broken. If you set your limit above 1,000 posts, PMAW will just scrape everything available. As such, I am yet to have a successful run of scraping all of my data at once, and am doing it in batches in a notebook I currently have set to be ignored. I have a notebook that has a sample of the process available at "code/data_collection_testing.ipynb"

As for sharing plans, all of the data I use for this project should hypothetically already be available for people to view, so I think it would be safe to have my corpus publicly accessible. However, I might consider omitting the usernames of the posters. Although many people use a throwaway/temporary account to post to this subreddit, I am unsure whether publicizing the usernames in this corpus could result in some harm.
