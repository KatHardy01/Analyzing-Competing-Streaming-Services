# Competing Streaming Services 
This project is a part of the [Virtual Data Bootcamp at Vanderbilt University](https://bootcamps.vanderbilt.edu) with EdX. 

## Project Objective
The purpose of this project is to visualize the data of five different streaming services (Amazon Prime Video, Apple TV, Hulu, HBO Max, and Netflix) to determine which streaming service has the highest IMDB rating. This will determine which service has the most popular movie titles, which is attributed to its success. This project aims to provide an exploratory data analysis and data visualization techniques using various datasets by leveraging skills learned in Python, Jupyter, Matplotlib, and Pandas.

### Partners
* Kat Hardy & Madison Mihle 

### Methods Used
* Descriptive Statistics 
* Correlation Analysis 
* Grouping and Aggregation
* Machine Learning
* Data Visualization

### Technologies
* Visual Studio Code
* Python
* Pandas, Jupyter 
* Matplotlib
* Seaborn
* Plotly 

## Introduction 
What is the appeal of streaming services? What makes the 'best' streaming service, and how do we know? Within the past decade, streaming services have been on the rise, replacing traditional cable and DVD systems within households. They offer consumers a convenient, affordable way to access a vast library of content at any time and any place. Most can be accessed on laptops, tablets, and smartphones, as well as standard Smart TVs. Nowadays, the average person cannot watch their favorite movies or TV shows without a streaming service subscription. Companies like Netflix, HBO, and Amazon are leading the digital media consumption and were the reason for fostering the rise of streaming services. In 2023, the streaming service industry was valued at $554.33 billion, and it is predicted that in 2024, the revenue is expected to be triple that (source: [Duarte, F (2024)](https://explodingtopics.com/blog/video-streaming-stats). Now, many streaming services have their own 'original content' that provides the subscriber with exclusive access. In 2023, U.S. audiences streamed over 21 million years' worth of video and 133 billion minutes of original content (source: [Nielsen, Nielsen (2024)](https://www.nielsen.com/insights/2024/streaming-unwrapped-streaming-viewership-goes-to-the-library-in-2023/#:~:text=In%202023%2C%20U.S.%20audiences%20streamed,binge%20throughout%20much%20of%202023.). 

Many analysts predict that the industry _will_ continue to trend upward in the upcoming years. However, the higher prices, lack of content, and recent 'ads' have caused users to become disenchanted. So, what does the future hold, and how can we help these companies maintain subscribers?  

## Questions to Ask
* Which streaming service has the most content? Why? Is this a positve or a negative when looking at a streaming service? 
* Which streaming service has the highest IMDB rating? Which streaming service has the lowest? 
* What are the most popular movies and TV shows of the highest-rated streaming service? What are the most popular titles of each? 
* How can we improve the lowest-rated streaming service? What are the future aspects we can look at regarding demographic information and membership analysis? 

## Project Description

### Part 1: Obtaining Data 
In this section, we took various datasets that were similar in information. Datasets for Amazon, Apple, Hulu, HBO Max, and Netflix were pulled from Kaggle [OctopusTeam](https://www.kaggle.com/octopusteam). (Note: also sourced below). They were analyzed, cleaned, and organized into new CSV files. 

### Part 2: Streaming Service Analysis 
After datasets were loaded and previewed, analysis was performed. 

    2.1: New columns were created to identify and categorize each 'streaming service' name within the DataFrames. 
    All DataFrames were combined into a single DataFrame (all_data). 
    
    2.2: Content type by streaming service (i.e., Movie vs TV Shows) was determined. The data was plotted using a bar 
    plot to visualize and determine which streaming service had the most content within their library. 
    
    2.3: The IMDB rating was established and determined for each streaming service. 
    It was determined which streaming service had the highest 
    average IMDB rating. A pie chart was used to visualize the five streaming services. 

### Part 3: HBO Max Data Analysis and Visualization 
After determining that HBO Max was the most popular streaming service in regards to the highest IMDB rating, we then took the data given and analyzed it further. 

    3.1: A statistical summary was taken to determine the IMDB rating for HBO Max.
    
    3.2: Data visualization was performed using Matplotlub and Seaborn. Here, we looked at the number of movies and 
    TV shows, the top 10 movies and TV shows, and the 
    most popular genres to better understand why HBO Max 
    out-performed the other streaming services.

### Part 4: Data Visualization of the Least Popular Streaming Service 
Lastly, we took the least popular streaming service based on the data obtained and analyzed it further. This was done to determine how we could possibly help improve the streaming service and see why it did so poorly in regards to IMDB rating. A new [CSV file](https://www.kaggle.com/datasets/arnavsmayan/netflix-userbase-dataset) was used to analyze the data. 

NOTE: Amazon Prime was considered the least popular streaming service based on the data obtained. However, there was not enough data available to us to properly analyze in order to determine how to improve the streaming service. Netflix was the second least popular in ratings. 

    4.1: A new CSV file was uploaded, cleaned, and analyzed. 
    It was already pretty organized, so we did not have to do much. 

    4.2: The data was reviewed to determine how Netflix can improve in the future and what aspects to look for:
       - Demographic information: gender, age, location by country, and devices used.

       - Membership analysis: subscription type and user length.


## Results & Analysis 
#### Part 1: Content Type by Streaming Service: Movies & TV

**Question 1: Which streaming service has the most content? Why? Is this a positive or a negative when looking at a streaming service**

 ![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Content_Type_by_Streaming.png?raw=true)


Based on our findings, Amazon Prime Video had the most content by type on their streaming platform. They superseded the others exponentially with their movie and TV libraries. Why? Well, it can be concluded from the visuals provided that Amazon's catalog of both movies and TV shows is extensive. This is impart because Amazon offers a streaming service through 'Prime Video' when paying for the 'Prime Subscription.' Here, they offer 'Prime Originals' and 'exclusive' movies. Again, these are all included within the subscription. However, they also allow access to other movies and TV shows that can be purchased or rented. 

Is this a positive or a negative? Yes and no. As discussed, most subscribers do not want to have to pay an additional fee to have access to movies when they are already paying for the streaming service. With other streaming services (i.e., Netflix, HBO Max, Hulu), the average subscriber pays for the service, and the content is included. There are no additional costs unless there is a change in plan (basic vs premium). However, with Prime Video, the subscriber is looking at paying for their plan and additional fees when they want to buy or rent a movie or TV show. Again, this adds up over time and can become costly, which can deter the customer. 

A positive to all of this is that all the content is in one place. One can 'subscribe' to other streaming services through Prime Video (i.e., Paramount Plus, PBS, Masterpiece, Showtime, Discovery +, AMC, etc.), and they can even have access to HBO Max content. Altogether, these are separate streaming services that the subscriber would have to pay for and download an app to receive content. Whereas Amazon Prime Video makes it so all the content is within one streaming service.  

**Question 2: Which streaming service has the highest IMDB rating? Which streaming service has the lowest?**

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/IMDB_Average_Rating_by_Streaming_Service.png?raw=true)

Based on the data, HBO Max had the highest overall IMDB rating at 20.9%. There is only a slight margin of difference between the other streaming services. Hulu fell at 20.5%, and Netflix and Apple TV at 20.0%. The lowest IMDB rating was Amazon Prime Video, at 18.6%. Why? Well, earlier, when we looked at each streaming service’s full catalog, Amazon Prime came in first with over 50,000 movies and 7,158 TV shows, while HBO had the least amount with only 5,826 movies and 3,602 TV shows.

What does this tell us? We can conclude that HBO's high average IMDB score suggests that it is succeeding in terms of content quality. This success can be attributed to HBO's focus on producing high-quality, critically acclaimed shows and movies. HBO's strategy of investing in original content with strong storytelling and high production values makes it a clear contender for one of the best streaming services. 

#### Part 2: HBO Max Data Analysis and Visualization 
**Question 3: What are the most popular movies and TV shows of the highest-rated streaming service? What are the most popular titles of each?**

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Top_10_Movie_Genres.png?raw=true)

Based on the data, it can be determined that 'Drama' is the highest-ranking movie genre in HBO's catalog. There is a significant dip in 'Comedy' ranking in second, with 'Documentary' in third. 

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Top_10_TV_Genres.png?raw=true)

Based on the data, it can be determined that 'Documentary' is the highest-ranking TV show genre. In second it's 'Reality-TV' and third is 'Drama'. 

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Names_of_top_10_HBO.png?raw=true) 

When the top ten movies and TV shows were plotted side-by-side, it could be seen that there was little variation in IMDB ranking. The margin of difference between the top 10 movies was 0.5, and for TV shows, it was 0.3. This goes onto show that for all the top 10 movies and TV shows, they were ranked similarly within IMDB scores.

"Shawshank Redemption" was the top-rated movie title for HBO. Then 'Celebrity Habla" and "The Godfather". Also, when looking at the data visualization, most of the top 10 movie titles were popular ones. This continues to prove HBO's strategy of investing and providing high-quality, critically acclaimed movies such as _Harry Potter_, _Lord of the Rings_, and _The Dark Knight_. For TV shows, _Planet Earth II_ came in first for most popular TV shows, with _Band of Brothers_ in close second and _Plant Eart I_ in third. Other popular titles are original HBO TV shows such as _Chernobyl_, _The Sopranos_, and _Game of Thrones_.

#### Part 3: Least Popular Streaming Service  
**Question 4: How can we improve the lowest-rated streaming service? What are the future aspects we can look at regarding demographic information and membership analysis?**

When this question was proposed, we wanted to look at two main factors and minor aspects of them in regard to the data. 1) Demographic Information and 2) Membership Analysis. 

1) Demographic Information: 

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Gender_Distribution_of_Netflix_Users.png?raw=true)

The data shows that 50.3% of females use Netflix, contrasting the 49.7% of male viewers and streamers. Why is that? Well, it can be assumed that with the rise of Reality TV shows and more content originals on Netflix, they favor a female audience. 

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Age_Distribution_of_Netflix_Users.png?raw=true)

The average age is 38 years old. While the minimum age is 27 and the maximum is 51. 

Before visualizing and analyzing the data, we predicted that the average age would be lower (19-21), focusing on 'Collage Age' subscribers. However, the data does make sense given that it correlates to the fact that most young adults in their 20s use streaming services, and most within the age range of 25-35 grew up with the rise of these types of platforms (i.e., Gen Z). They are most likely to spend money on streaming services, whereas the older generation is more loyal to traditional cable and TV. As the nature of technology increases, it can be found that more and more of the older generation use streaming services. 

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Country%20Counts%20NFX.png?raw=true)

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Location_of_Netflix_Users.png?raw=true)

The United States has the most number of Netflix users based on the select data provided. This correlates since Netflix started in the States. The second most popular country is Spane and then Canada. There is a significant dip in users in the UK, Australia, Germany, France, Brazil, Mexico, and Italy. The interactive map using Plotly helps visualize the data more clearly to see the differences in usage based on size. 

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Devices_Used_by_Netflix_Users.png?raw=true)

Based on the data, the laptop is the most popular device used, with the tablet as a close second. It is interesting to note that a Smart TV is last with the number of users in the dataset. Prior to this, we assumed that it would have more since most people watch streaming services on their TVs. Why might that be? Well, it could be assumed that many people prefer to watch shows on a smaller device when they are working, or even if we look at the hypothetical that most children use their parent’s account to stream movies and TV shows. It is portable and on the go for those who travel, work, or are away from their Smart TVs. 

2) Membership Analysis: 

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Netflix_Membership_Length.png?raw=true)

Based on the data, the average membership length is 326 days. When looking at the Wisker plot, it was interpreted that most people cancel their subscription close to a year into their service. Why is that? Well, most subscription services increase their rates around a year into service. Again, the number of streaming services adds up over time, and the average American has found it hard to maintain the added fees and price increases over time. 

According to an article in the New York Times, most subscribers find it frustrating to have several different subscription services. Everything is not always in the same place, so they have to switch back and forth (Source: [Koblin, J. (2024)](https://www.nytimes.com/2024/04/20/business/media/streaming-subscription-jumping.html#:~:text=Now%2C%20with%20a%20pared%2Ddown,are%20making%20me%20do%20this.”). Also the other main factor, especially with Netflix, is that it no longer fits their budget and the price is too expensive. This was seen signifcantly during the crackdown on 'sharing passwords' and having multiple accounts logged in at the same time with Netflix. According to a survey from 2023, a majority of U.S. consumers who have canceled their video streaming subscription did so because of price, which is around one in four respondents, another 13% said there was better content on another platform (Source: [Stroll, J (2024)](https://www.statista.com/statistics/672663/reasons-cancel-streaming-subscriptions/#:~:text=Reasons%20for%20canceling%20video%20streaming%20subscriptions%20in%20the%20U.S.%202023&text=According%20to%20a%20survey%20from,no%20longer%20fit%20their%20budgets.). 

![alt text](https://github.com/KatHardy01/Project-1/blob/main/Images/Netflix_Subscription_Type.png?raw=true)

It is interpreted that the 'Basic' subscription plan is the most popular at 40%, with 'Standard' coming in second at 30.7% and last with 'Premium' at 29.3%. Why is this? Well, again, as mentioned above, cost is one of the main factors. 

We asked ourselves how we could help low rated streaming services improve. Through our analysis, we determined that most streaming platforms need to offer high quality and engaging content (mostly originals) and more high profile and award-winning titles (i.e., _The Godfather_, _Lord of the Rings_, _Marval Saga_, _Avatar_, etc.). This helps ensure viewer approval ratings and also a higher IMDB overall score. Also, catering to various age ranges and genders would be beneficial to the streaming service. This will help pull a wider range of subscribers than just a select handful. 


### Challenges 
Some challenges we faced during this were the amount of data we could pull online and the content available. We were not able to find any actual data for Amazon Prime, which was the lowest-rated streaming service, so we had to use Netflix, which came in second lowest. We also wished to analyze HBO more, but there was little free data available to us. This is why we selected Netflix since we were able to find a CSV file of a section of data from the company. 

## Conclusion
Overall, whether we want to acknowledge it or not, streaming platforms are the future, and they will only continue to grow as technology prospers. This can be a good and bad thing in this day and age as the rapid rate of technology evolution changes what the average human knows. The downside to all of this is that as the demand increases, so does the cost of the service and the availability of titles on each different streaming platform. As seen earlier, not every platform has the same titles, which pushes for the need to enroll in several different streaming services. Lastly, it's not always that more content equals a higher rating, and that can be seen with Amazon. Netflix's issue, however, is most likely due to the crackdown on password sharing and constantly increased costs over time. A deeper analysis of a stock portfolio and quarterly profit will need to be evaluated.  

## Datasets Used: 
- [Amazon Prime Video](https://www.kaggle.com/datasets/octopusteam/full-amazon-prime-dataset)
- [Apple TV](https://www.kaggle.com/datasets/octopusteam/full-apple-tv-dataset)
- [Hulu](https://www.kaggle.com/datasets/octopusteam/full-hulu-dataset)
- [HBO Max](https://www.kaggle.com/datasets/octopusteam/full-hbo-max-dataset)
- [Netflix](https://www.kaggle.com/datasets/octopusteam/full-netflix-dataset)
- [Netflix Userbase](https://www.kaggle.com/datasets/arnavsmayan/netflix-userbase-dataset)

## Featured Notebooks/Analysis
* [Amazon Prime Notebook](https://github.com/KatHardy01/Project-1/blob/main/Notebooks/Cleaned_Files/Amazon%20Prime%20Dataset.ipynb)
* [Apple TV Notebook](https://github.com/KatHardy01/Project-1/blob/main/Notebooks/Cleaned_Files/Apple%20Dataset.ipynb)
* [Hulu Notebook](https://github.com/KatHardy01/Project-1/blob/main/Notebooks/Cleaned_Files/Hulu%20Dataset.ipynb)
* [HBO Max Notebook](https://github.com/KatHardy01/Project-1/blob/main/Notebooks/Cleaned_Files/HBO%20Dataset.ipynb)
* [Netflix](https://github.com/KatHardy01/Project-1/blob/main/Notebooks/Cleaned_Files/Netflix%20Dataset.ipynb)
* [Master Analysis](https://github.com/KatHardy01/Project-1/blob/main/Notebooks/Master%20Analysis.ipynb)


## Slideshow Presentation Link
* [Competing Streaming Services Slidedeck](https://docs.google.com/presentation/d/1R9uEAbSm3jXMbDZ5Hc-CgKV7WD4EyWN2_fCbdLx89-k/edit?usp=sharing)

## Sources Cited 
Duarte. (2024) _Video streaming statistics: Trends and insights_. Exploding Topics. Retrieved January 15, 2025, from https://explodingtopics.com/blog/video-streaming-stats#

Koblin, J. (2024, April 20). _Streaming services are making me do this_. The New York Times. Retrieved January 15, 2025, from https://www.nytimes.com/2024/04/20/business/media/streaming-subscription-jumping.html#:~:text=Now%2C%20with%20a%20pared%2Ddown,are%20making%20me%20do%20this

Nielsen. (2024). _Streaming unwrapped: Streaming viewership goes to the library in 2023_. Nielsen. Retrieved January 14, 2025, from https://www.nielsen.com/insights/2024/streaming-unwrapped-streaming-viewership-goes-to-the-library-in-2023/#:~:text=In%202023%2C%20U.S.%20audiences%20streamed,binge%20throughout%20much%20of%202023.

Stroll. (2023). _Reasons for canceling video streaming subscriptions in the U.S. 2023_. Stastia. Retrieved January 15, 2025, from https://www.statista.com/statistics/672663/reasons-cancel-streaming-subscriptions/#:~:text=Reasons%20for%20canceling%20video%20streaming%20subscriptions%20in%20the%20U.S.%202023&text=According%20to%20a%20survey%20from,no%20longer%20fit%20their%20budgets




