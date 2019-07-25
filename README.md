# Codefundoo-BlockBuster
Microsoft - Codefundoo++ 

Team BlockBuster - Idea Submission

	Abstract 

The majority of information that a voter gets about a particular candidate is through news and social media. Recently we have seen the huge impact fake/pseudo news can have on the electoral public. Hence the need to authenticate and validate the political news one receives. A combined reputation score (based upon the authenticity of the news/social media propaganda) and a sentiment score based on public sentiment towards the reflection of the news on the candidate, would not only make the decision process of the voter more streamlined but also more transparent and straightforward. Hence we propose a web application, targeting the decision making stage of a voter, during campaign season, that allows users to simultaneously assess the authenticity of the news and in turn aid decision making during the election period.


	Workflow/ Implementation 

Step 1 - User can decide which news article/social media posts to assess for authenticity.
Step 2 - The User votes whether the news is authentic or not.
Step 3 - The article/post is then analyzed for authenticity by means of ML and Bayesian Truth        Serum test (surprisingly popular answer). In this way the news article can be checked for reliability using Crowd Wisdom. 
Step 4 - The user gets a chance to classify the news article based on its sentiment as positive or negative and a score is generated in order to gauge public sentiment towards that news.
Step 5 - ML model then tries to classify it in the sector, (from a total of 15 sectors (such as education, health etc.) that we have taken into account) that news article/post belongs to and which political candidate is being addressed.
Step 6 - The blocks contain the candidate’s details such as name and score of the 15 sectors that we are addressing in this project and the news articles which are authenticated.
Step 7 - Based on the classification by the ML model, score is incremented in that particular sector of that particular candidate’s block.
Step 8 - The updated plots/graphs after incrementation are then generated for each sector so that user can easily visualize the competency of the candidates for that particular sector.

This will help voters to choose a candidate based on the sector he wishes to prioritize/see improvement in his area/constituency. In this way, the government can also understand what are the local demands of a constituency and can plan to work on that/add it in their agenda in the near future. It becomes a two-way information sharing and in turn increases transparency and effectiveness of the voting system.

 
	Flowchart of idea 

 IPFS ----->  NEWS/Social media posts  -----> Crowd Wisdom (Analysis and segregation using ML and Bayesian Truth Serum Test)----->         Public Blockchain -----> User can now compare different candidates.
                                                                                         
                                                                                                              
	Technologies Used 

Front End - Web Application for Users

Back End - 	 1) CIVIC API - In order to avoid multiple identities of users.
             2) Blockchain workbench from Azure.
             3) IPFS - to store data in a distributed database.


	Scalability and Feasibility 

The following idea can be used on any platform and can be scaled to include any social media site. The more platforms get integrated, the more thorough this process and analysis becomes. By use of the distributed web, the number of nodes that can be supported is very high, which improves scalability. 


	Benefits 

Such an approach has several benefits in making the decision process easier and more comprehensive for the public. This makes the reporting of news more transparent, traceable and immutable by applying blockchain technology as a decision helper. 


Thank you.
