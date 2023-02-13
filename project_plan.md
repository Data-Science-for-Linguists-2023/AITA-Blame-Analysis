# Project Plan


## Title: Analyzing Blame Shifting on AITA

### Summary
[Am I the Asshole](https://www.reddit.com/r/AmItheAsshole/) (AITA) is a subreddit where users describe a life situation and other users decide on whether or not they were the problem in the situation. The community has a standard structure in which writers convey information such as their age and gender, the age and gender of other parties in the story, and the chronology of the story itself. The community then decides if You're the Asshole (YTA), you're Not the Asshole (NTA), there's No Asshole in this story (NAH), or Everyone Sucks Here in this story (ESH).


This project intends to analyze posts on AITA to consider the methods used to persuade readers to your perspective on a story or move blame toward someone else by creating a corpus from this subreddit. In theory, I believe that people are mostly capable of seeing through blame-shifting tactics and therefore the most egregious stories will still be labelled as "YTA" despite strong efforts to convince otherwise. As part of the analysis, I also intend to attempt to create a model that tries to tag inputted posts based on how the community has categorized posts in the corpus.

### Data
The data would wild data be pulled from this subreddit. The data would likely be stored in a CSV containing information such as the link to the original post, the username, the age and gender of the user, the post itself, and whether the user was flagged as "the Asshole" or "not the Asshole". Pulling the data itself might be simple, but would likely require me to do some manual cleaning and pruning of more difficult posts. Although no public corpus exists for this subreddit, I have found a [paper](https://cs230.stanford.edu/projects_spring_2020/reports/38963762.pdf) exploring similar goals to my project which may be valuable in learning how to achieve my goal.

### Analysis
There are a few goals to this project thus far. Firstly, I want to establish what the typical demographic of this subreddit is through who posts submissions to the subreddit. This will give an idea of what communities' speech behaviors I am analyzing in this project, and will also reflect on potential moral trends within the demographic who votes on the posts. In the same vein, I want to consider the age/gender of other participants in the stories and consider whether there are any trends in sympathy from the community based on that information.

Secondly, after sorting the corpus based on the decisions of the AITA community, I want to look for trends in writing within each category. This will likely culminate through comparing word frequencies from each category. My goal here is to consider how people argue for themselves or shift blame away from themselves despite potential wrongdoing. Other posisble metrics for this is the frequency of passive voice or frequency of each person of pronoun as the subject of a sentence.

Thirdly, I would like to use machine learning to attempt to categorize potential posts by how the AITA community has previously voted. I believe that, in practice, the contexts of these posts are so varied that it will be difficult to draw any firm conclusions, but I would still like to attempt to discover any trends and behaviors that people utilize regardless of universality.

### Presentation
I would like to learn more about how to visualize data and find ways to clearly express potential correlations between age/gender and likelihood to be deemed at fault. Also, in practice, I recognize that the name of the central community of this project is dubious to consistently say within a classroom setting and likely need to find more gracious ways to allude to it.