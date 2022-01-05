# Movies-ETL
Amazing Prime video is a platform for streaming movies and TV shows on Amazing Prime, the world's largest online retailer. The Amazing Prime video team would like to develop an algorithm to predict which low budget movies being released will become popular so that they can buy the streaming rights at a bargain. To inspire the team, have some fun, and connect with the local coding community, Amazing Prime has decided to sponsor a hackathon. Providing a clean data set of movie data and asking participants to predict the popular pictures. A member of the team has been tasked with creating the datasets for the hackathon. There are two data sources: a scrape of Wikipedia for all movies released since 1990, and rating data from the Movie Land's website. As part of this initiative, employee needs to extract the data from the two sources, transform it into one clean data set, and finally load that data set into a SQL table. 

## Overview of the Project:
Amazing Prime loves the dataset and wants to keep it updated on a daily basis.  For this it needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database. 

Below is the list of deliverables:
Deliverable 1: Write an ETL Function to Read Three Data Files
Deliverable 2: Extract and Transform the Wikipedia Data
Deliverable 3: Extract and Transform the Kaggle data
Deliverable 4: Create the Movie Database

## Results:
### Deliverable 1: Write an ETL Function to Read Three Data Files
Below are the screenshots of outputs in Deliverable 1.
![Deliverable 1 Output 1](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/Deliverable1_Output1.PNG)
![Deliverable 1 Output 2](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/Deliverable1_Output2.PNG)
![Deliverable 1 Output 3](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/Deliverable1_Output3.PNG)
The complete code for Deliverable 1 can be found here [Deliverable 1 Code](https://github.com/Karenjakins/Movies-ETL/blob/main/ETL_function_test.ipynb)

### Deliverable 2: Extract and Transform the Wikipedia Data
Below are the screenshots of outputs in Deliverable 2.
![Deliverable 2 Output 1](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/Deliverable2_Output1.PNG)
![Deliverable 2 Output 2](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/Deliverable2_Output2.PNG)
The complete code for Deliverable 2 can be found here [Deliverable 2 Code](https://github.com/Bhargavi-ng/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)

### Deliverable 3: Extract and Transform the Kaggle data
Below are the screenshots of outputs in Deliverable 3.
![Deliverable 3 Output 1](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/Deliverable3_Output1.PNG)
![Deliverable 3 Output 2](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/Deliverable3_Output2.PNG)
![Deliverable 3 Output 3](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/Deliverable3_Output3.PNG)
The complete code for Deliverable 3 can be found here [Deliverable 3 Code](https://github.com/Bhargavi-ng/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb)

### Deliverable 4: Create the Movie Database
Below are the screenshots of outputs in Deliverable 4.
![Deliverable 4 Output 1](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/Deliverable4_Output1.PNG)
![Deliverable 4 Output 2](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/movies_query.PNG)
![Deliverable 4 Output 3](https://github.com/Karenjakins/Movies-ETL/blob/main/Resources/ratings_query.PNG)
The complete code for Deliverable 4 can be found here [Deliverable 4 Code](https://github.com/Bhargavi-ng/Movies-ETL/blob/main/ETL_create_database.ipynb)