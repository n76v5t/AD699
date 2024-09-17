java c
AD699: Data Mining for Business Analytics Spring 2019 
25APR 
Quiz #1 
Version: BRAVO 
You have one hour to complete this quiz.  You may use a calculator, along with your book and/or notes, but may not use a smartphone or anything else with Internet connectivity.
For any multiple choice question, you are not being asked to choose the “best” from among four possibilities; instead, there are three wrong answers, and one right answer.
There are three versions of this quiz, but all contain the same content.The data science team at Target recently studied a series of consumer transactions at one of the company’s retail locations in Massachusetts.  Here is a list of the items purchased in a series of 12 recent transactions.   One row represents one consumer’s purchases at the register in one visit (in other words, the first customer bought only oatmeal).
1.    Oatmeal, Butter
2.   Nintendo Switch, Nintendo Switch Case, Super Mario Odyssey
3.   Gatorade, Butter, Cheerios, Milk, Tennis Racquet
4.   Dell Laptop, Wrigley’s Chewing Gum
5.   Oatmeal, Gatorade, Cheerios, Milk, Laundry Detergent
6.   Super Mario Odyssey, Red Sox Hat, Blue Jeans
7.   Oatmeal, Frozen Waffles
8.   Pepsi, Frozen Waffles, Red Sox Hat
9.   Butter, Frozen Waffles, Cheerios
10. Nintendo Switch, Nintendo Switch Case
11.  Dell Laptop, Nintendo Switch Case
12. Gatorade, Bread, Butter, Milk, Frozen Waffles
1.    What is the support for {Gatorade, Milk}?
2.  What is the confidence for IF {Nintendo Switch} THEN {Nintendo Switch Case, Super Mario Odyssey}?
3.   What is the confidence for IF {Butter} THEN {Milk}?
4.   What is the lift ratio for IF {Frozen Waffles} THEN {Butter}?
5.  What is the lift ratio for IF {Milk} THEN {Cheerios} ?
6.   What would someone generally expect to happen to the number of words in the corpus as a result of the various preprocessing steps in text mining?
a.   Some forms of text preprocessing, such as stemming, add to  the number of words in the corpus, while others reduce the number of words (so the overall impact to the word count cannot be reliably predicted).
b.   This all depends on how stopwords are used. Some groups of stopwords are added to an existing corpus, whereas other groups of stopwords subtract from the existing corpus.
c.   Preprocessing steps such as stemming, stopword removal, and normalization will reduce the total number of unique words that remain in the corpus.
d.   Preprocessing typically adds to the total number of the words in the corpus, since it means that the corpus will have to be held in both a volatile format and in a permanent format.7.    Which of the following statements explains the relationship between cutoff distance and the number of clusters that you would expect to see in an agglomerative hierarchical clustering model?
a.   With a higher cutoff distance, someone building such a model should expect to see the  same number of clusters as with a lower cutoff distance (assuming that single-linkage was used for cluster-to-cluster measurement).
b.   As the cutoff distance used in such a model increases, the number of clusters should be expected to decrease.
c.   As the cutoff distance used in such a model increases, the number of clusters should be expected to increase.
d.   There is no predictable relationship between cutoff distance and the number of clusters in an agglomerative hierarchical clustering model.8.    The table below shows categorical values -- a 1 in a particular cell indicates that the store carries in the item in stock, whereas a 0 indicates that the item is not stocked by that store. Given the information contained in the table below, what is the Jacquard coefficient between Groton and Hull?
AD699 Sporting Goods Store 
Store ID 
Tennis Racquets 
Sunscreen 
Basketball Hoops 
Boogie Boards 
Hawaiian Shirts 
Easton 
0 
0 
1 
0 
1 
Fall River 
1 
1 
1 
1 
1 
Groton 
1 
0 
0 
1 
0 
Hull 
0 
1 
1 
1 
1 
Ipswich 
1 
1 
1 
1 
0 
9.  Which of the following statements about social network analysis is true?
a.   Social network analysis has existed since long before the Internet was developed; however, the Internet has enabled a considerable level of social network analysis in recent years.
b.   Social network analysis was not conducted before the Internet was developed; however, many forms of offline social network analysis are conducted nowadays.
c.   Social network analysis relies on social media data. Although social graphs can be shown in formats that don’t require connectivity to social media platforms, the social media platforms still form. the basis of the analysis.
d.   While social network analysis can be conducted with or without social media data, it is considered unprofessiona代 写AD699: Data Mining for Business Analytics Spring 2019 Quiz #1R
代做程序编程语言l for an analyst to create a social network analysis model without considering at least two unique social media sources (in order to account for the variation among undirected and directed network setups).
10.   Our  textbook describes clustering as a popular “unsupervised learning” task. What does this mean?
a.   With clustering, the analyst typically labels the records first, before running a function such as kmeans() or hclust(). The model can then be used to verify those initial cluster assignments made by the person who studied the data before making the model.
b.   Clustering can be performed by someone who does not closely watch the model performance  and results, whereas some other forms of machine learning (like classification) require the modeler to closely watch, or supervise, the entire process.
c.   When a clustering model is built, the data are not yet labeled; instead, we rely on the model to help us better understand and organize our data.
d.   With some other forms of data mining models, the analyst  must continually monitor the results even after the model has been built, due to changing factors in the surrounding world. Once a clustering model has been created, however, it does not require   any “supervision” in the sense that it does not need any continual adjustments.11.   You recently learned about a network that involves Applied Business Analytics students. All of the connections in the network are undirected. Here  are the connections that exist within that network:
Arlene is connected with Ben and Carlos.
Ben is connected with Arlene and Danny.
Carlos is connected with Arlene and Danny.
Danny is connected with Carlos and Ben. What is the density of this network?
12.  Based on the set of association rules shown here, what is the support for {yogurt} ?  
13. Suppose someone wanted to perform. a simplification step to prepare a document for text mining.  As a result of this step, strings of text such as “200 Sycamore Lane” , “850  Commonwealth  Avenue”  and  “52  Babcock  Road”  are  simply  replaced  with “address.”  What is the name of the step that performs this replacement?
a.   stemming
b.   Stopwords
c.   extraction of meaning
d.   normalization14. After  class  tonight,  you  get  on  the  green  line.   You  see someone working very intently on his laptop, and you think “Wow, that guy is really dedicated to his work.” You notice that the guy on the laptop is building a network graph using R.Another person notices the guy on the laptop, looks over his shoulder, and comments on the network graphic that he sees.  “Your network graph is weak, dog,” he says.  “I can’t  believe  you  didn’t  include edge weight. How can anyone be expected to understand your graph without some representation of edge weight?”The guy on the laptop turned around and said, “I don’t know what edge weight is, and I don’t care.  But hey buddy, no one asked you...so how about you get out of my sight before I have to fight you.”Thankfully,  you  got  off the  T  at Copley, so you didn’t see whether these two guys actually fought.   But why would the person who criticized the guy on the laptop say this?
a.   Without showing the edge weight, the graph would be much harder for an observer to understand -- for example, an observer of such a graph  would  not  be  able  to  determine  the  betweenness  or  the closeness of particular nodes.
b.   If a network graph does not show any depiction of edge weight, it would be hard for an observer of the graph to understand the relative strength of the various edges.
c.   Edge weight would reveal directionality.   In that  sense, the person who criticized the modeler was right (even if he was rude to speak so boldly about another person’s network model on the T).
d.   By showing edge weight, an analyst can make it clear who the most central  member of a large network  is;  without  edge  weight,  the position of the various nodes becomes meaningless.
15. Which of the following is a limitation of the “bag of words” approach in text mining?
a.   A   “bag   of   words”   approach   adds   a   considerable   amount   of computational complexity, compared with an approach that considers each word in the context of the entire sentence.
b.   Typically,  a  tf-idf  is  built  in  a  text  mining  model  so  that  truly important words can be identified from a large corpus of many words. With a bag of words approach,  however,  this  cannot  be  done effectively.
c.   In  spoken  sentences,  the  order  of  the words is important for determining  meaning. With the bag  of words approach, however, word order is ignored.
d.   If  an  analyst  wants  to  build  a  predictive  model  with  text,  a  data partition will be required -- this is incompatible with a “bag of words” treatment of text data.

         
加QQ：99515681  WX：codinghelp
