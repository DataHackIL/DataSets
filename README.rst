DataSets by `DataHack <http://datahack-il.com/>`_
#################################################

A curated list of cool open datasets and APIs to use in machine learning driven projects.

Brought to you by `DataHack <http://datahack-il.com/>`_, a data-driven hackathon. You can also find us on `Facebook <https://www.facebook.com/datahackil/>`_, `Meeutp <https://www.meetup.com/DataHack>`_, `Twitter <https://twitter.com/DataHackIL/>`_ and join `our monthly newsletter <https://mailchi.mp/2c67d69eb667/datahack-newsletter>`_. 

The list starts with unique Israeli open public datasets, from governmental organizations and other public instituitions, collected and maintained by `The Public Knowledge Workshop <http://www.hasadna.org.il/en/>`_ - one of `DataHack <http://datahack-il.com/>`_'s major partners. We then continue the list with open datasets and APIs from a variety of sources.

This list is open, and contributions are both welcomed and encouraged. To contribute to the list, simply edit this ``README.rst`` file to add an entry in the existing format and create a pull request. To keep in line with the designation of this list as an inspiration for machine learning driven projects (in hackathons and in general), please make sure to include a short description of the dataset, a link where the data is available and a few project suggestions. Additions to existing entries are also welcomed.

|

.. contents:: **Open datasets:**

.. section-numbering:

|


Open Israeli Municipal Budgets 🏘
=================================

**Description:** Open local budget is a project under The Public Knowledge Workshop aimed at making local authorities budgets accessible to the public. While the project is at beta, many budgets are already online (some in a more accessible format than others) and browsable, though only a single budget can be viewed at a time, in the `project's home page <http://www.omuni.org/>`_. Being in beta means that there is plenty of room for improvement - this is where you can come in! 

**Link:** https://drive.google.com/drive/folders/0B9KCjEIdzJZUSUF2NVRaNW9JYTg?sort=7&direction=d

**Project ideas:** 

- How can we compare between budgets of different municipalities or of the same municipality but in different years? And how can such a comparison be visualized?
- Given a budget can we understand how it is invested geographically/demographically? Moreover, can we derive how a given municipality invests the money it got from taxes/arnona in proportion to the amount payed by each region in the city?
- Generalize the above two ideas into a tool that is able to take complex queries and produce meaningful results (not necesarily visualized).


Israeli Knesset members' Facebook posts and comments 🏛
=======================================================

**Description:** We provide a unique dataset of facebook comments to statuses published by Israeli MKs during 2015-2016. In total there are about 5 million such comments, out of which 1,600 are labeled according to the sentiment of the comment's text. A great challenge is to use the 1,600 labeled comments, in order to find the sentiment of all the comments. In the linked folder you'll find the labeled data, some information about the labels, and the unlabeled data. This dataset was collected by the team of `Kikar Hamedina <https://kikar.org/>`_, and they will be more than happy to help. 

**Link:** https://drive.google.com/drive/folders/0Bz-MJkSVg93LaXRFRkdJckYtV0E

**Project ideas:** 

- What type of posts and subjects elicit the most responses?
- How to different Knesset Members differ in the way they communicate with their audience? Think of ways to visualize the difference in frequency, content, amount of feedback and other interesting parameters.
- Are Knesset Members' posts a place of discussion and communication with our representatives? Do they respond to questions? Do later posts refer to their followers' reactions, questions and concerns?


PRO-ACT: Pooled Resource Open-Access ALS Clinical Trials Database 🔬
====================================================================

**Description:** Amyotrophic lateral sclerosis (ALS) is a specific disease that causes the death of neurons which control voluntary muscles. The cause is not known in 90% to 95% of cases. No cure for ALS is known. The `PRO-ACT initiative <https://nctu.partners.org/ProAct/>`_ provides users with easy access to

- Over 10,700 fully de-identified clinical ALS patient records.
- Placebo and treatment-arm data from 23 Phase II/III clinical trials.
- Demographic, lab, medical and family history, and other data elements.
- More than 10 million longitudinally collected data points.

**Link:** https://nctu.partners.org/ProAct/Data/Index

**Project ideas:** 

- *Cause:* The cause of ALS is not known in 90% to 95% of cases, and besides a genetic cause in a small percentage of the cases various environmental factors are suspected. This dataset can be used to investigate the statistical significance of various suggested causes and suggest possible new ones.
- *Diagnosis:* Dignosis of ALS is challenging, and is based on a person's signs and symptoms with testing done to rule out other potential causes. Using the dataset to suggest statistical significance of the connnection of different symptoms and suggesting possible new ones can be extremely valuable to improve diagnosis of ALS.
- *Identify meaningful subgroups:* `The ALS Stratification Challenge <https://www.synapse.org/#!Synapse:syn2873386/wiki/>`_ utilizes the PRO-ACT database, as well as data from the Irish National ALS register and The Piemonte and Valle d'Aosta Register for ALS. It asks solvers to identify meaningful sub-groups of ALS patients. Challenge information and solutions are available on the `Challenge website <https://www.synapse.org/#!Synapse:syn2873386/wiki/>`_ on Sage Bionetwork's Synapse Platform.



The Beit Hatfutsot's family tree database 🌳
============================================

**Description:** The Beit Hatfutsot's `family tree database <https://dbs.bh.org.il>`_ contains over 10,000 family trees encompassing over five million people. The database contains names, professions, births, family ties and numerous other details. The database can be queried through an `API server <https://api.dbs.bh.org.il/v1/docs>`_. 

**Link:** https://api.dbs.bh.org.il/v1/docs

**Project ideas:** 

- Build an automatic tool guessing a person origin based on his family name.
- Visualize the movements of Jewish communities and people through regions and countries over the ages.


Pokéapi - The Pokémon RESTful API ✊
====================================

**Description:** Pokémon started out as a Japanese card game and became a worldwide phenomenom. The link is to a public API providing access to all the information about all Pokémons, throughout all existing (seven) generations + including berries! 

**Link:** http://pokeapi.co

**Project ideas:** 

- A bot that you could compete against.
- A bot that could help you train your Pokémons.

**Additional resources:** 

- `Pokédex Python module <https://github.com/veekun/pokedex>`_ - The name says it all.
- `The Pokédex <https://pokemondb.net/pokedex>`_ - A website holding all information about Pokémon, they have no public API (as far as we could tell), but you can scrape it for info.


Reddit comments 💬
==================

**Description:** A constantly updated dataset of *every* comment posted on reddit since the site's inception in 2005, totalling at more than 1.7 *billion* comments. You can read about the origin of the dataset `here <https://www.reddit.com/r/datasets/comments/3bxlg7/i_have_every_publicly_available_reddit_comment/>`_, and about the way it is stored in Google BigQuery `here <https://www.reddit.com/r/bigquery/comments/3cej2b/17_billion_reddit_comments_loaded_on_bigquery/>`_.

**Link:** https://bigquery.cloud.google.com/dataset/fh-bigquery:reddit_comments

**Project ideas:** 

- What makes a reddit comment popular (i.e. get a high score)? Find correlation to time posted and content: Do late comments still have a chance to be popular? Do short comments fair better than long ones? Are there any specific words or terms that boost a post's score?
- Automatically generate an average, or a popular, reddit comment given a reddit link and the comments already posted on its thread.
- Find correlation between real world events and reddit comments: What events do the reddit community respond to more? What types of events elicit a quick but short response and what types bring about a long response continuing for days or weeks?
-  Find communities and sub-communities, discover leaders or trend-setter within them and visualize how they are formed.


Stack Exchange 🔷
==================

**Description:** Starting in Stack-Overflow, the Stack-Exchange network is a collection of Q&A websites, each dealing with a different topic - from porgramming to home improvement. These vast knowledge bases, some containing over a few millions of answers, are available to download in XML format. 

**Link:** https://archive.org/details/stackexchange 

**Project ideas:** 

- How many questions are unique? We believe that most questions have been answered before (in some form or another) so why not develop an automated answering system?
- Could we teach a machine to code based on answers from Stack-Overflow?
- Is there similarity between different sites relating to similar topics? For instance, do questions asked around Latin-based languages have a similar answer?


The GDELT Project 🗞
====================

**Description:** `The GDELT Project <http://www.gdeltproject.org>`_ monitors the world's broadcast, print, and web news from around the world and identifies people, locations, organizations, emotions and more. This dataset has been used to analyze international relations, monitor the war on Ebola, create influence networks of powerful individuals and examining the implications of the Arab Spring. 

**Data format:** CSV files containing columns for: date, actors, tone, location, source and more.

**Links:** 

- http://data.gdeltproject.org/events/index.html
- http://data.gdeltproject.org/gkg/index.html
- Using Google BigQuery: http://googlecloudplatform.blogspot.co.il/2014/05/worlds-largest-event-dataset-now-publicly-available-in-google-bigquery.html


**Project ideas:** 

- Coverage and tone towards Israel around the world.
- Predict the next protest, disease outbreak or election’s winner.
- Show relations between business people, media personalities and government officials.


Enron emails 📨
===============

**Description:** Enron was a U.S. energy-trading and utilities company that housed one of the biggest accounting frauds in history. Enron's executives employed accounting practices that falsely inflated the company's revenues, which, at the height of the scandal, made the firm become the seventh largest corporation in the United States. Once the fraud came to light, the company quickly unraveled and filed for Chapter 11 bankruptcy on Dec. 2, 2001. The dataset contains ~200,000 email messages from ~150 users, mostly senior management of Enron.

**Data format:** The zip file contains a folder for each employee. Each of these folders is divided into ‘inbox’, ‘sent’, ‘all documents’ and more. The subfolders contain text files with the raw email data.

**Links:** 

- *Overview:* http://www.cs.cmu.edu/~enron/ 
- *Download:* http://www.cs.cmu.edu/~enron/enron_mail_20150507.tgz

**Project ideas:** 

- Find words and phrases that shorten the response time to an email.
- Determine the importance and urgency of a given email.
- Extract a list of tasks from a given email.


U.S. Prisoners ⛓️
=================

**Description:** The National Corrections Reporting Program (NCRP) compiles offender-level data on admissions and releases from state and federal prisons and post-confinement community supervision. The data are used to monitor the nation's correctional population and address specific policy questions related to recidivism, prisoner reentry, and trends in demographic characteristics of the incarcerated and community supervision populations.

**Links:** 

- *Data:* http://www.icpsr.umich.edu/icpsrweb/NACJD/studies/36404
- *A related NYT article:* https://www.nytimes.com/2016/09/02/upshot/new-geography-of-prisons.html

**Project ideas:** 

- Create a good model for predicting trends in the characteristics of the incarcerated and community supervision populations.
- Predict how likey is a person to be incarcerated during his life time by his Facebook/LinkedIn profile.
- Find likely causes to prisoner reentry and possible ways to improve prisoner rehabilitation.


GitHub Repositories 🐱
======================

**Description:**  Github is an online git repository hosting service, holding projects such as Node.JS, Microsoft VisualStudio and Google’s TensorFlow. GitHub is the largest code repository in the world with over 11M users and 29M repositories.

**Data format:** GoogleBigQuery, containing all data + language specific data.

**Data:** https://github.com/blog/1112-data-at-github

**Project ideas:** 

- How likely it is for a programmer who wrote in X to write in Y?
- Is there a correlation between active users in GitHub to active users in other networks such as StackOverflow?
- Find impactful commits (those that caused, for example, a surge of forking)


The New York Times Articles 📰
==============================

**Description:** The New York Times is one of the most wide read newspapers around the world. It has articles about world and local news, opinions, and various other topics. Using these APIs you can access any article since 1851, books, comments and many more. Bare in mind that the access is with a key which is restricted. In the articles API, for examples, you are restricted to 10 calls per second, and 10,000 per day. The restrictions are specified `here <http://developer.nytimes.com/apps/register>`_.

**Data format:** The access to the data is by a web based API - you send a GET request and get back a json with the data. Here are some `examples <http://developer.nytimes.com/docs/read/article_search_api_v2#examples>`_ (there are examples for all of the available APIs). There is also a GUI `API console <http://developer.nytimes.com/io-docs>`_.

**Overview:** http://developer.nytimes.com/docs

**Project ideas:** 

- Identify the topics a reporter usually writes on, and predict the writer of an article by it's content, or even who will cover some specific event.
- Compare coverage with factual data: do similar events get the same coverage?
