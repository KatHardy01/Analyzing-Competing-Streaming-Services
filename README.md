# Competing Streaming Services 
This project is a part of the [Virtual Data Bootcamp at Vanderbilt University](https://bootcamps.vanderbilt.edu) with EdX. 

## Project Objective
The purpose of this project is to visualize the data of five different streaming services (Amazon Prime Video, Apple TV, Hulu, HBO Max, and Netflix) to determined which streaming service has the highest IMDB rating. This will determine which service has the most popular movie titles, which attributes to its success. This project aims to provide an exploratory data analysis and data visualization techiques using various datasets by leveraging skills learned in Python, Jupyter, Matplotlib, and Pandas.

### Partners
* Kat Hardy & Madison Mihle 

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling

### Technologies
* Python
* Pandas, Jupyter 
* Matplotlib
* Seaborn
* Plotly 

## Introduction 
What is the appeal of streaming services? What makes the 'best' streaming service, and how do we know? Within the past decade, streaming services have been on the rise, replacing traditional cable and DVD systems within households. They offer consumers a convenient, affordable way to access a vast library of content at anytime and any place. Most can be accessed on laptops, tabets, and smartphones as well as standard Smart TV. Nowadays the average person cannot watch their favorite movies or TV shows without a streaming service subscription. Companies like Netflix, HBO, and Amazon are leading the digital meadia consumption and were the reason for fostering the rise of streaming services. In 2023, the streaming service indistry was valued at $554.33 billion, and it is predicted that in 2024, the revenue is expect to be triple that (source:[_Duarte, F_ (2024)](https://explodingtopics.com/blog/video-streaming-stats). Now, many streaming services have their own 'original content' that provides the suscriber with exclusive access. In 2023, U.S. audiences streamed over 21 million years' worth of video and 133 billion minutes of original content (source: [_Nielsen, Nielsen_(2024)](https://www.nielsen.com/insights/2024/streaming-unwrapped-streaming-viewership-goes-to-the-library-in-2023/#:~:text=In%202023%2C%20U.S.%20audiences%20streamed,binge%20throughout%20much%20of%202023.). 

Many analysts predict that the industry _will_ continue to trend upwards in the upcoming years. However, the higher prices, lack of content, and recent 'ads' have caused users to become disenchanted. So what does the future hold, and how can we help these companies maintain subscribers?  

## Questions to Ask
* Which streaming service has the most content? Why? Is this a positve or negative when looking at a streaming service? 
* Which streaming service has the highest IMDB rating. Which streaming service has the lowest? 
* What are the most popular movies and tv shows of the highest rated streaming service? What are the most popular titles of each? 
* How can we improve the lowest rated streaming service? What are the future aspects we can look at regarding demographic information and membership anaylsis? 

## Project Description

### Part 1: Obtaining Data 
In this section, we took various datasets that were similar in information. Datasets for Amazon, Apple, Hulu, HBO Max, and Netflix were pulled from Kaggle [OctopusTeam](https://www.kaggle.com/octopusteam). (Note: also sourced below). They were analyzed, cleaned, and organized into new CSV files. 

### Part 2: Streaming Service Analysis 
After datasets were loaded and previewed, analysis was performed. 

    2.1: New columns were created to identify and categorize each _'streaming service'_ name within the DataFrames. All DataFrames were combined into a single DataFrame (_all_data_). 
    
    2.2: Content type by streaming service (i.e., Movie vs TV Shows) was determined. The data was plotted using a bar plot to visualize and determined which streaming service had the most content within their library. 
    
    2.3: The IMDB rating was established and determined for each streaming service. It was determined which streaming service had the highest average IMDB rating. A pie chart was used to visualize the five streaming services. 

### Part 3: HBO Max Data Analysis and Visualization 
After determining that HBO Max was the most popular streaming service in regards to the highest IMDB rating, we then took the data given and analyzed it further. 

    3.1: A statistical summary was taken to determine the IMDB rating for HBO max.
    
    3.2: Data visualization was performed using Matplotlub and Seaborn. Here, we looked at the number of movie and tv shows, the top 10 movies and TV shows, and the most popular genres to better understand why HBO Max out-performed the other streaming services.

### Part 4: Data Visualization of the Least Popular Streaming Service 
Lastly, we took the least popular streaming service based on the data obtained and analyzed it further. This was done to determined how we could possibly help improve the streaming service and see why it did so poorly in regards to IMDB rating. 

NOTE: Amazon Prime was considered the least popular streaming service based on the data obtained. However, there was not enough data available to us to properly analyze in order to determine how to improve the streaming service. Netflix was the second least popular in ratings. 

    4.1: A new [CSV file](https://www.kaggle.com/datasets/arnavsmayan/netflix-userbase-dataset) was uploaded, cleaned, and analyzed. It was already pretty organized so we did not have to do much. 

    4.2: The data was reviewed to determine how Netflix can improve in the future and what aspects to look for:
        Demographic information: gender, age, location by country, and devices used

        Membership analysis: subscription type and user length


### Results 

Part 2: Streaming Service Analysis 
* 

Part 3 

### Challenges 
Through data analysis and visualization, we were able to see this clearly and determine such. Some challenges we faced during this was the amount of data we could pull online and the content avilable. We were not able to find any data for Amazon Prime, which was the lowest rated streaming service, so we had to use Netflix which came in second lowest. We also wished to analyze HBO more, but there was little free data avilable to us. 


(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modelling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)


## Conclusion


## Datasets Used: 
- [Amazon Prime Video](https://www.kaggle.com/datasets/octopusteam/full-amazon-prime-dataset)
- [Apple TV](https://www.kaggle.com/datasets/octopusteam/full-apple-tv-dataset)
- [Hulu](https://www.kaggle.com/datasets/octopusteam/full-hulu-dataset)
- [HBO Max](https://www.kaggle.com/datasets/octopusteam/full-hbo-max-dataset)
- [Netflix](https://www.kaggle.com/datasets/octopusteam/full-netflix-dataset)
- [Netflix Userbase](https://www.kaggle.com/datasets/arnavsmayan/netflix-userbase-dataset)

## Featured Notebooks/Analysis
* [Amazon Prime Notebook](https://github.com/KatHardy01/Project-1/blob/main/Amazon_Prime_data/Amazon%20Prime%20Dataset.ipynb)
* [Apple TV Notebook](https://github.com/KatHardy01/Project-1/blob/main/Apple_data/Apple%20dataset.ipynb)
* [Hulu Notebook](https://github.com/KatHardy01/Project-1/blob/main/Hulu_data/Hulu%20Dataset.ipynb)
* [HBO Max Notebook](https://github.com/KatHardy01/Project-1/blob/main/HBO_data/HBO%20dataset.ipynb)
* [Netflix](https://github.com/KatHardy01/Project-1/blob/main/Hulu_data/Hulu%20Dataset.ipynb)
* [Master Analysis]()
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


## Slideshow Presentation Link
* [Competing Streaming Services Slidedeck](https://docs.google.com/presentation/d/1dDlaAHCHg8Mvsx-IGkSL6iZ6WL2cq6LK_y2lsOxYR3g/edit?usp=sharing)

## Contact









