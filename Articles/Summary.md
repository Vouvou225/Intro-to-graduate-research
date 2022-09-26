## Clustering performances in the NBA according to players’ anthropometric attributes and playing experience

In this article, they are trying to group players into similar clusters based on anthropometric characteristics and playing experience. After doing so, they will explore the distribution of players within the obtained cluster. The data have been obtained from open-access official NBA record during 2015-2016 regular season. Some criteria have been established to come up with the final data  using a descriptive design. Players with less than 500 minutes a season and 5 minutes or less per game were excluded. Games with score difference equal to or less than 10 points were included which gave a total of 699 regular season balanced games. this method limited the sample to 354 players with 12724 performance records(57% of the total sample). A total of 20 variables considered. A random sub-sample of 20 games were observed by basketball coaches with more than 5 years of experience in basketball performance analysis).  A two-step cluster with log-likelihood as the distances measure and
Schwartz’s Bayesian criterion was carried out to group basketball players into the different groups using experience, weight and height as variables. A descriptive discriminant analysis was conducted to identify which variables best discriminate the previously obtained clusters. Cross-validation analysis evaluated the usefulness of discriminant functions when classifying new data.



## Clustering Professional Basketball Players by Performance by Riki Patel

Coming from www.basketball-reference.com, this article tried to reclassify players from 2016-2017 regular season into groups. Reduction techniques such as t-Distributed Stochastic Neighbor Embedding (t-SNE) and principal component analysis (PCA) employed to visualize player performance in two dimensions then K-means clustering will be employed to find similarities among groups of players on the scatterplot. Riki Patel came up with 18 variables while excluding variables that do not reflect positive player performance such as turnovers, fouls ... He also excluded the player's classic position, the team each player belongs to to minimize its influence on clustering. Focusing on k-means clustering, he used three validation methods to select the best number of clusters:  within-sum-of-squares, the silhouette score, and the gap statistic which led to four groups: "The Paint Protector", "The supporters", "The Shooters", "The Insiders". To conclude, he used visual representations and linear regression to determine the relationship between clusters and nba team success.



## Clustering performance in the European Basketball according to players’ characteristics and contextual variables

This articles focuses on identifying differences in the game performance profiles of basketball players in Euroleague and European national championships; and to analyse the influence of player-related (e.g. age or court-position) and contextual variables (e.g. distance travelled or game break) in players’ game-related statistics. To do so, the article used two step cluster to identtify different performance player profiles and discriminant analysis to analyze differences within those playing profiles.  A one-way ANOVA was used to compare the selected variables into the different clusters obtained. Pairwise comparisons were assessed using the Bonferroni post hoc test. The leave-one-out method of cross-validation was used to evaluate the usefulness of discriminant functions when classifying new data. The variables analyzed were divided into three groups and defined as follows: (i) player-related: players’ age, court-position and minutes played; (ii) contextual variables: distance travelled, between the teams’ headquarters and the city where the games were played (kilometers) and game break, number of rest days between games (days); and (iii) game-related variables: field-goals made and attempted, 3-point made and attempted, free-throws made and attempted, points, offensive rebounds, defensive rebounds, total rebounds, assists, steals, blocks, turnovers, and personal fouls.


## Role revolution: towards a new meaning of positions in basketball

This article focuses on re classifying the five traditional NBA positions into a new set of five roles based on players'charateristics. In other terms, The aim of this paper is to propose a new definition of the positions of basketball players by means of the analysis of their performance statistics with data mining and machine learning tools. The method was applied to NBA players of the 2010-11 NBA regular season. The parameters used in the analysis were points, rebounds, assists, steals, turnovers, fouls and blocks. The result was a set of 13 clusters, corresponding to 13 new positions unveiled in the analysis. The Analysis started by training the 8 players with the highest number of average minutes played per game, for each of the 30 teams. Then the classification procedure which followed three steps: definition of a 7-dimensional SOM trained with the Key Players Training Set; clusterization of the SOM output layer into a proper number of groups by means of a fuzzy clustering algorithm, to take into account the possible presence of players whose statistics’ values suggest a hybrid position; analysis of the clusters’ profiles to detect heterogeneities that allow to define more refined positions within the clusters, resorting to basketball technical considerations.












## A cluster analysis of basketball players for each of the five traditionally defined positions

- goal: group basketball players into similar clusters according to their playing styles(pg,sg,sf,pf,c)
- the data is from the basketball-reference.com website, 2000/2001 to 2015/2016 NBA season except 2011/2012(boycott)
- five man analysis condition: played together at least 21 matches for 240 total min(565 five men lineup for 15 seasons found)
- the player who played more than 25% in a position in a single season were included in that position
- 6040 observations for 72 variables(joined tables on player's name, season, and team name)
- cluster analysis :    PG: 426 players   SG: 490 players  SF: 544 players  PF: 522 players  C: 525 players
- we conducted advanced statistics and shooting statistics
- advanced statistics yielded more efficient results by reducing playing times and teams'effect(which caused mistakes in evaluating the players)
- shooting statistics were selected for a detailed analysis of the offensive characters of the players
- To examine the style of players, we focused on the shooting distance of the field goal attepmts
- the number of clusters were unknown in advance. It was performed with a minimum of 4 clusters and a maximum of 10 groups for each position. They used Internal Validity Indices to determine the optimal number of clusters.
- cluster analysis for PG: "Ball Handler"(high usage and assist); "Floor General"(high assist,efficiency,steals,dribbling); "Shooter"(high shooting 3s, low free throw); "Role Player"(complimentary to the team)
- Cluster analysis for SG position: "Shooter"(high 3s%,high true shooting%,low free throw); "Warrior"(high block and offensive rebound); "Role Player"; "Team Leader"(high usage,high PER)
- Cluster analysis for SF position: "Team Leader"(high usage and high PER); "Shooter"(high 3s%,high true shooting, low FT%); "Warrior";"Role Player".
- Cluster analysis for PF position: "Shooter:; "Big Man"(PER,DRB), "Role Player"; "Team Leader", "Warrior"
- Cluster analysis for C position: "Warrior"; "Shooter"; "Big Man"; "Team Leader"; "Rim Protector"(BLK,high TO); "Role Player"
- metrics used: Adjusted plus-minus (APM), average points differential(APM), and the percentage of clusters on winning teams were analyzed while determining the prominent clusters.
- how players play with each other in basketball is a crucial factor for success


## Similarities
- around same number of variables
- data comes from one regular season
- specific criteria to meet before being considered into final dataset
- exploring data within different clusters to see how it behave



## Differences
 -  descriptive design VS positive player performance (to come up with final dataset)
 -  two step cluster vs validation methods (for clustering)


