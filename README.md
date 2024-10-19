## Data Mining Mini Project 2
## by Harsh Siroya

This project Answers a few quesitons based on Movie Summaries

### Questions Addressed:
1. **Most Common Genre of Movies:** Determine the most common genre of movies and calculate the total and mean box office revenue for each genre.
2. **Correlation Between Actor Age and Box Office Revenue:** Investigate if there is a correlation between actor age and box office revenue. Identify the most common age of actors in the dataset and analyze the total box office revenue for each movie a specific actor has acted in to identify successful actors.
3. **Total Revenue per Year:** Analyze the trend of box office revenue over the years to determine if the revenue is increasing or decreasing.
4. **Similar Movies in the Dataset:** Identify which movies are similar to others in the dataset to assist viewers in finding movies they may like, similar to a recommendation system.



### Reasoning and Implications behind the Questions:
1. **Most Common Genre of Movies:**
   - **Reasoning:** Determining the most common genre of movies provides valuable insights into audience preferences and market trends. By understanding which genres are most prevalent, filmmakers can tailor their content to cater to the demands of the target audience.
   - **Implications:** Calculating the total and mean box office revenue for each genre allows filmmakers to assess the revenue-generating potential of different genres. Genres with higher average box office revenue may indicate greater audience interest and profitability, guiding investment decisions and resource allocation in movie production.

2. **Correlation Between Actor Age and Box Office Revenue:**
   - **Reasoning:** Investigating the correlation between actor age and box office revenue helps unravel the influence of actor demographics on movie success. Understanding whether there is a correlation can inform casting decisions and marketing strategies, as certain age demographics may resonate more strongly with target audiences.
   - **Implications:** Identifying the most common age of actors in the dataset provides valuable demographic insights for filmmakers. Analyzing the total box office revenue for each movie a specific actor has acted in enables the identification of successful actors, facilitating the selection of talent with a proven track record of box office success.

3. **Total Revenue per Year:**
   - **Reasoning:** Analyzing the trend of box office revenue over the years offers valuable insights into the overall trajectory of the movie industry. Understanding whether revenue is increasing, decreasing, or fluctuating over time can help stakeholders anticipate future opportunities and challenges.
   - **Implications:** A rising trend in box office revenue suggests a growing market and increased consumer spending on movies, presenting opportunities for industry expansion and investment. Conversely, a declining trend may signal market saturation or changing consumer preferences, prompting stakeholders to adapt their strategies accordingly.

4. **Similar Movies in the Dataset:**
   - **Reasoning:** Identifying similar movies in the dataset serves as a recommendation system, helping viewers discover new content based on their preferences. By clustering movies with similar plot summaries, viewers can find movies they are likely to enjoy, enhancing their overall viewing experience.
   - **Implications:** Offering personalized movie recommendations based on similarity enables platforms to engage viewers and increase user satisfaction. By facilitating content discovery and improving user experience, stakeholders can drive audience retention and loyalty, ultimately leading to increased revenue and market competitiveness.


### Code Overview:
The Jupyter notebook for this data mining mini project provides a comprehensive analysis of the movie dataset using Python and various libraries. Here's a breakdown of the key sections:

1. **Data Loading and Exploration:** The code begins by loading the movie metadata, character metadata, plot summaries, name clusters, and TV tropes clusters from separate files into Pandas DataFrames. It then performs exploratory data analysis to understand the structure, content, and quality of the data.

2. **Genre Analysis:** Utilizing the movie metadata, the code identifies the most common genres of movies in the dataset. It calculates both the total and mean box office revenue for each genre and visualizes the results using bar plots.

3. **Actor Analysis:** The code investigates the correlation between actor age and box office revenue by analyzing the distribution of actor ages and their respective movie revenues. It also identifies the most successful actors in the dataset based on their total box office revenue and the number of movies they have appeared in.

4. **Revenue Trend Analysis:** A time-series analysis is conducted to understand the trend of box office revenue over the years. This helps in identifying whether the revenue is increasing, decreasing, or fluctuating over time.

5. **Text Analysis for Similar Movies:** Using the plot summaries of movies, the code applies text analysis techniques to cluster similar movies together. This allows viewers to discover movies with similar plots, akin to a recommendation system.

6. **Visualization:** Throughout the analysis, various visualizations such as bar plots, joint plots, and time-series plots are utilized to present the findings in an interpretable manner.

7. **Insights and Interpretations:** The code provides insightful interpretations of the analysis results, offering valuable insights for movie directors, actors, and industry stakeholders to make informed decisions.



### Data Overview:
- The dataset contains information about movies, including movie metadata, character metadata, and plot summaries and also the name clusters and the tvtropes.clusters.

- Movie Metadata: Stored in a Pandas DataFrame with columns such as Wikipedia Movie ID, Freebase Movie ID, Movie Name, Movie Release Date, Movie Box Office Revenue, Movie Runtime, Movie Languages, Movie Countries, and Movie Genres.

- Character Metadata: Also stored in a Pandas DataFrame, includes information like Wikipedia Movie ID, Freebase Movie ID, Movie Release Date, Character Name, Actor Date of Birth (DOB), Actor Gender, Actor Height, Actor Ethnicity, Actor Name, Actor Age at Movie Release, Freebase character map id, Freebase character id, and Freebase actor id.

- Plot Summaries: Contained in a DataFrame with columns for Wikipedia Movie ID and Plot Summary.

- Name Clusters: DataFrame with columns for Name and Cluster ID.

- TV Tropes Clusters: DataFrame with columns for TV Trope and Details.



### Summary Information:
"The data mining mini project offers a comprehensive exploration of a diverse movie dataset, uncovering actionable insights to guide decision-making in the film industry. Through meticulous data loading, exploration, and analysis, the code reveals compelling trends and relationships. Notably, the analysis highlights the dominance of certain movie genres such as drama and comedy, correlating their popularity with box office success. Furthermore, the examination of actor demographics elucidates the significant impact of age on box office revenue, empowering filmmakers to make informed casting decisions. A temporal analysis unveils an upward trend in box office revenue over the years, signaling promising opportunities for industry growth. Leveraging advanced text analysis techniques, the code clusters similar movies based on plot summaries, offering personalized recommendations to enhance viewer engagement. By synthesizing these insights, stakeholders can refine their strategies, optimize performance, and captivate audiences in the dynamic landscape of the movie market."



### Instructions:
1. Clone the repository.
2. Run the provided Python code in a Jupyter notebook environment.
3. Analyze the results to answer the questions posed in the project.

This `readme.md` file provides an overview of the data mining mini project, the questions addressed, the code structure, and instructions for running the analysis.
