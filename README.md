# Genre_From_Subtitles
Can you predict the genre of movie from just 1000 characters of the script?

* Description

Using the provided training data you'll be given a 1000 character sample of a movie script and be asked to predict the genre the movie came from.

* Evaluation criteria

This model is evaluated by accuracy; this is a fairly straightforward measure of correctness, and you can think of it like getting a grade on a multiple choice test. For each record you're trying to answer the question "what is the genre of the movie script this excerpt came from?" and accuracy is simple

accuracy := # of correct answers / # of total answer

* Data Description

There was given a training data file that has three columns:

id: An arbitrary id assigned to a record
text: A 1000 character span randomly sampled from a movie script
genre: The genre of the movie the text came from, from the set {drama, thriller, action, comedy, romance, sci-fi, adventure, horror, other}
