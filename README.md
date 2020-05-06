# Recommender-systems-optimization-for-coverage-diversity-and-serendipity
We introduce a framework for optimizing recommender sys-
tems in the presence of constraints on metrics such as coverage, diversity
and serendipity. We consider the setting where there exist several sets
(categories) of items, and each set belongs to or is produced by a dfferent
entity. These items need to be recommended to users. The first problem
we address is the following. Given a set of ratings for each user and each
item, generated through a conventional recommender system algorithm,
our goal is to recommend items to users such that the ratings of items
in the recommendation lists are maximized, subject to maintaining suffi-
cient coverage and diversity for each set of items. That is, items need to
be recommended to a diverse enough set of users (with respect to their
profiles), and each set of items needs to be recommended to a certain
number of users.
The second problem is to maximize the total serendipity of recommended
items subject to guaranteeing a given minimum serendipity for each set
of items. Serendipity can be defined in various ways. Here we define it
through a combination of item popularity and its dierence from items
a user has experienced so far. We show that these problems may be
viewed as assignment problems. We will perform extensive numerical
experiments with real data that verify the findings of our approach.
With this problem, we aim to gain knowledge and experience working
with real datasets and also advance the fundamentals of optimization.
