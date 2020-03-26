# Recommendation Engine for Beer Products using Text Analytics

#### AIM OF THE PROJECT


To build a crowd source recommendation engine for beer products using text analytics. There are several products available in the digital market which provides products based on the description or choices provided by the user. 
One such recommendation produces results by “Relevance”. A method of producing such results is to check the reviews of different people and trying to find the similarity and sentiment between the reviews of different products and the user comments and produce the results accordingly. For example you go to a website to search for a new guitar and type in the chatbot “I want good quality English wood Guitar”, the recommendation system will try to see the reviews having English wood and positive sentiments about its quality and produce the results. 
We have tried to build such a recommendation engine for beer products a part of our Text Analytics class in Fall Semester.



#### PROCEDURE: 

-	Scrape the data from www.beeradvocate.com : scraped 25 reviews for 250 different products along with their rating
-	Found out the word frequency count and developed three attributes: Fruity, Rich and Balanced
-	Performed similarity analysis using SpaCy since this package develops vector by considering the context of the word being used in the sentence as well. Performed the similarity analysis between the three products chosen and chose 300 top reviews based on similarity scores 
-	Performed sentiment analysis using VADER and sorted them based on sentiment scores 
-	By considering the sentiment and similarity scores, recommended 3 beer products to the customer 
