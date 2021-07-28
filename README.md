# Capstone_3

## Proposal 1: SAT/ACT style grammar question generation
I want to create an automatic question generator for comma, subject/verb agreement, and prepositional phrase grammar questions. I think this can be done using GANs or Autoencoders with BERT/other current NLP models. I know this is ambitious and I really want to try it. The questions will be pulled from SAT/ACT tests that are publically available and I have had access to in the past as a tutor. If there aren't enough (I believe there are ~2k that I have access to across all question types, but that is likely ~400-500 per question type) I can write more questions that match the style and are approximately what I'd be trying to generate anyways. If this is approved please let me know ASAP because I'm going to start writing questions once I know.

## Proposal 2: ActionMLBoyz
The patreon podcast ActionBoyz has about 220 episodes. I want to generate new cold opens (first ~5 min of each episode) based on the mp3 files available to me as a subscriber by generating scripts for the three hosts. If possible I would want to also try to do voice replication to have them read generated scripts, but primarily this would be another NLP chatbot type thing. Some free episodes are on the "High and Mighty" feed on whatever podcast app you want to look at, here is one for Batman Returns: https://open.spotify.com/episode/0E9G4TvVg2x9EDwwfzMAb2?si=0798cc0b1be94e7f

Not sure how feasible this is. I would be happy to talk about it if you think it's in the realm of a good idea.


## Proposal 3: Smiros Pictures (working title)
Going back to the IMDb and TMDb datasets, I want to create both a recommender based on info I had in capstone 1 as well as NLP analysis of reviews/descriptions (also for what movies to watch for people who have already seen a whole lot of movies) and do time series analysis on top of the financial analysis I did in capstone 1. The primary goal for the financial analysis end would be to project future trends in subgenres of Horror, Sci-Fi, and Comedy/see if I can make an argument for more movies like Barb & Star go to Vista Del Mar

## Proposal 4: Furniture recommender
Because I think 1 and 2 are pretty ambitious and you said 3 might be too small for capstone 3 this is an idea that I'm not as excited about but think could be good. Webscrape images/descriptions of a bunch of different furniture from Ikea, CB2, Pottery Barn, Restoration Hardware, West Elm, Crate and Barrel, Macy's, etc and build a recommender that does item/item recommendation and make a Flask app, maybe hosted on an EC2 instance, to give pictures/links based on uploaded images/a poll of what do you like from a group of them, idk.
