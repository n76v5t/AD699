java c
AD699: Data Mining for Business Analytics 
Spring 2019 
30APR 
Quiz #3 
Version: ECHO 
You have one hour to complete this quiz.  You may use a calculator, along with your book and/or notes, but may not use a smartphone or anything else with Internet connectivity.For any multiple choice question, you are not being asked to choose the “best” from among four possibilities; instead,  there  are  three  wrong  answers,  and  one  right  answer. Any multiple choice question must be answered with one completely clear answer choice. 
For any free response questions, show your work.  Rounding is completely okay (and showing your work helps me to see what you did).
Do not pass a calculator or any other material to any student during the quiz. If you do this, the quiz will end immediately for you and for the other student. 
Free response questions that ask for multiple pieces of info will be scored in a binary fashion (1 or 0 points). There are three versions of this quiz, but all contain the same content.The data science team at Target recently studied a series of consumer transactions at one of the company’s retail locations in Massachusetts.   Here is a list of the items purchased in a series of 15 recent transactions.  One row represents one consumer’s purchases at the register in one visit.
1.    Oatmeal, Butter
2.   Nintendo Switch, Nintendo Switch Case, Super Mario Odyssey
3.   Gatorade, Oatmeal, Butter, Cheerios, Milk, Tennis Racquet
4.    Dell Laptop, Wrigley’s Chewing Gum
5.   Oatmeal, Gatorade, Cheerios, Milk, Laundry Detergent
6.   Super Mario Odyssey, Red Sox Hat, Blue Jeans
7.    Oatmeal, Frozen Waffles, Butter
8.   Pepsi, Frozen Waffles, Red Sox Hat
9.   Butter, Frozen Waffles, Cheerios, Bread
10.  Nintendo Switch, Nintendo Switch Case
11.   Dell Laptop, Nintendo Switch Case
12.  Gatorade, Bread, Butter, Milk, Frozen Waffles
13.  Red Sox Hat, Blue Jeans, Oatmeal, Butter
14.  Milk, Butter
15.  Gatorade, Red Sox Hat
1.   What is the support for {Milk, Frozen Waffles}?
2.   What is the confidence for IF {Oatmeal} THEN {Gatorade}?
3.    What is the confidence for IF {Milk} THEN {Cheerios}?
4.    What is the lift ratio for IF {Red Sox Hat} THEN {Gatorade}?
5.   What is the lift ratio for IF {Cheerios} THEN {Milk} ?6.  The table below shows categorical values -- a 1 in a particular cell indicates that the store carries in the item in stock, whereas a 0 indicates that the item is not stocked by that store.  Given the information contained in the table below, what is the Jacquard coefficient between Fall River and Ipswich?AD699 Sporting Goods Store Store ID Tennis Racquets Sunscreen Basketball Hoops Boogie Boards Hawaiian Shirts Easton 1 0 1 0 1 Fall River 1 1 1 1 1 Groton 1 0 0 1 0 Hull 0 1 1 1 1 Ipswich 1 1 1 1 0 
7.        Take a look at the dendrogram shown below, which depicts an agglomerative hierarchical clustering  model.   At a distance of 9, how many clusters are there in this model?

8.     Can a stopword list ever be modified?
a.   While a user cannot change a stopword list, he or she can bring in different packages with the library() function in R -- these packages may contain different stopwords for a particular language.
b.   No -- it is important that a user never modify a stopword list, because stopwords are carefully chosen in order to reduce the risk of “data collisions.”   (this  refers to the risk that a stopword may appear on multiple users’ lists, but be meant in a different context across the lists).
c.   Yes, it can.  In some professions, or some instances, particular words might  be  so  common  that  they  don’t  have  value  for  text  mining purposes -- such words can be added to a stopword list.
d.   No.  A stopword list can’t be modified.  Stopword lists are subject to copyright  protections  as  part  of the  agreement  that  enables  R  to function as an open-source programming language.
9. ** To answer this question, a little bit of domain knowledge is required -- you just need to kno代 写AD699: Data Mining for Business AnalyticsWeb
代做程序编程语言w that Boston is south of Cambridge ** 
You recently overhead a conversation on the Green Line.“Excuse me, excuse me,” someone asked a guy wearing a backwards Red Sox cap.  “I’m from  out  of town  and  I  have  a  question  for  you  --  how  far  away  is  Boston  from Cambridge?”
The guy in the Red Sox hat said, “Sure, no problem.  They’re about 10 miles apart.”
“Don’t be a wiseguy,” the tourist responded.  I maybe from somewhere else, but I know that’s not true.”The Bostonian answered with this: “Well, you never told me how you wanted to define the distance metric.   I was  using the southernmost point in Boston (Hyde Park) and giving you the distance to the northernmost point in Cambridge (Alewife).   So if you don’t like the way I answer your questions, here’s an idea -- stop asking me.”
What method did the Bostonian use to measure the distance here?
a.   Complete linkage
b.   Average linkage
c.   Ward’s Method
d.   Single linkage
10. Screenshots of two rules are shown here  -- first, the rule IF {Wu-Tang Clan} THEN {Dr.Dre}, and second, IF {Dr.Dre} THEN {Wu-Tang Clan}.

Based solely off of the information shown in these two rules, which of the following can be concluded:
a.   The support for Dr. Dre must be greater than the support for Wu-Tang Clan.
b.   The support for Dr. Dre and the support for Wu-Tang Clan must be equal.
c.   The support for Wu-Tang Clan must be greater than the support for Dr. Dre.
d.   None of the statements shown here can be concluded with the information provided by these two rules.11.  The metric “average within-cluster sum of squared differences” (wss) is sometimes used to evaluate the effectiveness of clusters.   In  an ideal clustering situation, how should  wss  compare  with  the  total squared distances from the mean for all of the variables in the entire dataset?
a.   The smaller the ratio of wss to total squared distances, the better.
b.   The larger the ratio of wss to total squared distances, the better.
c.   The ideal ratio of wss to total squared distances is 2; anything larger suggests that the model has been overfit to the data, and anything smaller suggests that the clusters are unreliable.
d.   If the data has been normalized, then we should expect to see a high ratio of wss to total squared distances; if the data has not yet been normalized,  though,  we  should  expect  this  ratio  to  be  somewhat smaller.
12. Is it possible to conduct social network analysis without the use of social media data?
a.   Yes,  but  only when the analysis itself is based on social media.   In other words, information could come from the Twitter API, and then could be analyzed in any format (but its original source should still be social media).
b.   No, because there is no reliable system that has been developed that can analyze social network data without having a robust data source (such as Twitter or LinkedIn Application Programming Interfaces).
c.   Yes.   Social  network analysis has been conducted since long before the invention or use of social media.
d.   No, because there isn’t any format that has been developed yet that would  let  people  store,  process,  and  disseminate  social  network analysis without being able to express the results in terms of social media connections.
13.  For  the  graph shown below, which shows an undirected network, list the three people with the highest betweenness scores, in order:

a)    (highest)
b)    (2nd-highest)
c)    (3rd-highest)
14.  What is the density of the social network depicted in the image on Question 13?
15.  Based on the graphic shown in Question 13, which of the following statements is an accurate statement about the social network that it shows?
a.   This network is a clique, but not a connected network.
b.   This network is a connected network, but not a clique.
c.   This network is neither a clique nor a connected network.
d.   This network is both a clique and a connected network.

         
加QQ：99515681  WX：codinghelp
