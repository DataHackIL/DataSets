DataSets by `DataHack <http://datahack-il.com/>`_
####################

A curated list of cool open datasets to use in machine learning driven projects.

Brought to you by `DataHack <http://datahack-il.com/>`_, a data-driven hackathon. You can also find us on `Facebook <https://www.facebook.com/datahackil/>`_, `Meeutp <https://www.meetup.com/DataHack>`_, `Twitter <https://twitter.com/DataHackIL/>`_ and join `our monthly newsletter <http://us12.campaign-archive2.com/home/?u=de6927f58980fe1c8f3b78cf7&id=d70a19b217>`_. 

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

**Description:** A constantly updated dataset of *every* comment posted on reddit since the site's inception in 2005, totallin at more than 1.7 *billion* comments. You can read about the origin of the dataset `here <https://www.reddit.com/r/datasets/comments/3bxlg7/i_have_every_publicly_available_reddit_comment/>`_, and about the way it is stored in Google BigQuery `here <https://www.reddit.com/r/bigquery/comments/3cej2b/17_billion_reddit_comments_loaded_on_bigquery/>`_.

**Link:** https://bigquery.cloud.google.com/dataset/fh-bigquery:reddit_comments

**Project ideas:** 

- What makes a reddit comment popular (i.e. get a high score)? Find correlation to time posted and content: Do late comments still have a chance to be popular? Do short comments fair better than long ones? Are there any specific words or terms that boost a post's score?
- Generate an average, or a popular, reddit comment given a reddit link and the comments already posted on its thread.
- Find correlation between real world events and reddit comments: What events do the reddit community respond to more? What types of events elicit a quick bu short response and what types bring about a long response continuing for days or weeks?
