# Challenge Week 12 Submission Template
Jose Vieitez

#score
80/100

# Reddit Data Challenges

## Challenge 1

![screenshot](http://i.imgur.com/RtqxtrW.png?raw=true)

## Challenge 2

[Explain what's interesting] You can see what tags/ subreddits people post things under, which could be interesting to see the difference in tones between different subthreads.

## Challenge 3

[Explain possible Insights] What leads to rejection; is it tones in certain companies, is it time of post, is it the position of the post relative to other popular/ unpopular posts. 

## Challenge 4

[What it would tell you about the Reddit Community] What is the general tone of the community; for example, how much punctuation, how many positive and negative comments there are.

## Challenge 5

[Link to Code or pasted code]
Create an array where you collect every subreddit name, and store the commenters into it. Then For each subreddit, create an array where you store the name of another subreddit, and the number of common commenters. Then Sort each array by descending number value. Then Sort all the subreddits by the value in the first entry of their array, and take the first 2. 

## Challenge 6

It would remove a large subset of commenters from the set. It is possible there are users who never post popular comments but do so frequently.

## Challenge 7

Yes, it should, as now only popular commenters are considered, which means you are looking at the top 2 subreddits who share the most popular commenters. 


## Challenge 8

It is biased because potentially new users or users who have yet to figure out the community tone may not have the right comment phrasing/ tone to get that many votes.

## Challenge 9

Negative commenters will be removed, which may be a good bias: it is likely you have spammers who post in many subreddits at once, increasing the shared commenter score, but because they will be downvoted, they won't skew the dataset. 

## Challenge 10

You can test the top 2 subreddit rankings before, and after removing all negative comments (only) to show their skewing weight. 

# Yelp and Weather 

## Challenge 1

[Screenshot your query and a result]

## Challenge 2

[Query snippet]
[Answer]

## Challenge 3

grep -o 'Madison' dedupped-1-comment-per-line.json | wc -l
[7156]

## Challenge 4

 grep -o 'Las Vegas' dedupped-1-comment-per-line.json | wc -l
[4503]

## Challenge 5

grep -o 'Phoenix' dedupped-1-comment-per-line.json | wc -l
[19013]

## Challenge 6 [BONUS]

[Code]
[Answer]



