# Youtube_Polarization
This is originally born out of a class assignment, but I decided to take it further, since polarization through social media is a publicly relevant issue. 

In the project I request Video Info via API on a politically relevant search term, do basic analytics and then do network analysis of the recommended videos.

Further goals are: Training a model to categorize videos in political dimensions: Left, Right; Populist, Informative and so on.
Final goal is to investigate the Hypothesis, that polarizing content tends to be more often recommended, independent of popularity.

# Introduction
Several people in the US have already analyzed Youtube's potential to direct towards polarized topics with its search results and recommendations.

This is just one example: https://www.theguardian.com/technology/2018/feb/02/youtube-algorithm-election-clinton-trump-guillaume-chaslot

In this project, I attempt to analyze the debate on the Migration-Compact, which was largely held online on facebook and twitter, but also on Youtube. Thereby, the following questions come up:

1) Was the debate noticable on Youtube (Postings, Likes, Comments Views etc.)?

2) What were the main keywords in the debate?

3) Did each side in this debate get the same amount of attention?

4) Does Youtube equally recommend other videos, or are recommendations largely reduced to a few videos?

While I progressed with the project, additional questions came up, which mainly concern the Youtube Search Algorithm:

5) What kinds of videos are recommended?

6) Following long queues of videos, recommendations and so forth - what topic am I likely to end up at?

Since the demand for answering each question largely varies, I have split the project into three parts, ordered by demand. The third part is only slightly working, which is why I consider part 1 and 2 as the turned in project. The third part is more of an outlook on what I would do next.

Part 1 considers Question 1 to 3, where I use the Youtube API to extract IDs and details about results, if I would enter the search term 'Migrationspakt'.

Part 2 considers Question 4, where I look for recommended videos and compare them, regarding their in-degree-centrality.

Part 3 considers Question 5 and 6, where I have actually built a working function to retreive data of the recommended video IDs, paired with their degree centrality in one dataset. Furthermore I present an attempt to recursively iterate through lists of recommendations multiple times. Unfortunately, the API kicked me out due to quota overlow. Otherwise, this might have worked.

Suggestions are welcome.
