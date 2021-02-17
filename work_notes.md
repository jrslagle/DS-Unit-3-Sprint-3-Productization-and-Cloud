You should then update work_notes.md each day with the following:

What went well (in the context of working on the assignment) today?
What was particularly interesting or surprising about the topic(s) today?
What was the most challenging part of the work today, and why?

2020.02.09:
John did a PyCharm trick for environment variables in mod 1 at ~1:08:30

2020.02.10:
Made a new repo for my web app and started off with a tiny Hello World flask app:
https://github.com/jrslagle/Who-tweeted-that

2020.02.11:
Followed along in class. Added much of the html and data structure of the app

2020.02.13:
Turned everything off until it ran. Then got Twitter OAuth 1.0 to work.

2020.02.14:
Followed the user data, printing out each step
Read all the data that twitter_api.get_user() returns
Read all the data that twitter_api.get_user().timeline() returns
Looked at my SQLite database in DB Browser
Downloaded some pretrained English models for Spacy

2020.02.15:
Followed along in class.
Added the html for selecting two users
Added the infrastructure for running the ML
Added a page for displaying the results.

2020.02.16:
take a close look at the vector for a tweet
English model = <class 'spacy.lang.en.English'>
Processed tweet = <class 'spacy.tokens.doc.Doc'>
Tweet vector shape = (96,) numbers look like floats normally distributed around zero.
got vectorizing the tweets to work
fixed the bug where the database stores all nulls


make it so tweets are only downloaded and processed if that user is missing
get the /compare page working

is there a way to suggest users?
display how much data you have on each user with a little green square for each 100 tweets.
can I do PCA > 2D Plotly scatterplot? One dot per tweet and 1 color per user?
  can I mouse over the points and read the tweet?
use the object structure for k-means clustering on the tweets. set each centroid to the average vector of that user's tweets. Predict the query text based on distance to each user's centroid.


Follow one of the solutions


