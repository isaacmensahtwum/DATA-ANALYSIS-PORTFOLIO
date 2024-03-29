# Isaac Twum - Data Analysis and Business Intelligence Portfolio

## About
My name is Isaac and I have a background in Mathematics, Economics and an MSc. in Applied Data Analytics. My journey has equipped me with a robust skill set in business intelligence analysis, data analysis, market research, supply chain, quantitative modeling, and other analytical areas. Throughout my academic and professional experiences, I've cultivated a passion for leveraging data to drive informed decision-making and uncover valuable insights. From teaching applied econometrics to conducting predictive analytics, I've honed my ability to source, prepare, analyze, and visualize data effectively. Whether collaborating with a team or working independently, I thrive on the challenge of solving complex problems through data-driven approaches. I'm dedicated to exploring new data analytics tools and techniques, continuously expanding my knowledge base in this dynamic field.
<br >
<br >
Explore my repository for a comprehensive overview of my skills, experiences, and projects in data science, data management, supply chain, and my knowledge of software.

<!-- ## Table of Content
- [About](https://github.com/isaacmensahtwum/DATA-ANALYSIS-PORTFOLIO/edit/main/README.md#about)
- [Portfolio Projects](https://github.com/isaacmensahtwum/DATA-ANALYSIS-PORTFOLIO/edit/main/README.md#portfolio-projects) -->
    
## Portfolio Projects
### 1. Python
- [Sales Analysis for Retail Stores](https://github.com/isaacmensahtwum/Data-Analysis-with-Python/blob/b8e858a11f1dbecaf1543cd31191dbf20dca71c7/Business%20Metrics%20-%20Sales%20Analysis.ipynb)
    **Goal:** To identify product categories whose sales trend over time have declined and identify key reasons for such decline.
    
    **Code:** [Business Metrics-Sales Analysis.ipynb](https://github.com/isaacmensahtwum/Data-Analysis-with-Python/blob/b8e858a11f1dbecaf1543cd31191dbf20dca71c7/Business%20Metrics%20-%20Sales%20Analysis.ipynb)
    
    **Method:** The dataset contains 30 variables including unit price, quantity sold, product categories, and competitor prices. It spans for 2 consecutive years.
                  Data Cleaning and Exploratory Data Analysis and Visualization.<br>
                  
    **Results:** The sales analysis revealed a decrease in revenue for four product categories, bath products, game consoles, cool stuff, and garden tools in 2018 compared to the previous year. Analyzing the competitor prices highlighted higher average prices for bath products, cool products, and garden tools in 2018 compared to their competitors, indicating a potential influence on customer decision-making.<br>
    
    **Libraries:** pandas, numpy, seaborn<br>
    
    **Skills:** data cleaning, data analysis, data visualization.<br>

- [Movie Recommendation System (Machine Learning)](https://github.com/isaacmensahtwum/Data-Analysis-with-Python/blob/b8e858a11f1dbecaf1543cd31191dbf20dca71c7/Movie%20Recommendation%20System.ipynb)
  
    **Goal:** Recommender systems have become integral to various online platforms, providing personalized suggestions to users across a wide range of entities such as products, movies, and services. Examples include Amazon's product recommendations, Netflix's movie suggestions, and YouTube's video recommendations. In this project, my focus is on building a Content-based movie recommendation system using Natural Language Processing (NLP) techniques. By analyzing textual features such as movie descriptions, genres, and titles, I aim to recommend movies that share similar characteristics with specific movies of interest tailored toward user preferences and tastes.
  
    **Code:** [Movie Recommendation System](https://github.com/isaacmensahtwum/Data-Analysis-with-Python/blob/b8e858a11f1dbecaf1543cd31191dbf20dca71c7/Movie%20Recommendation%20System.ipynb)
  
    **Description:** The dataset contains 4803 entries with 20 columns. Movie titles, taglines, genres, overviews and popularity were utilized to generate the recommendation function. Data cleaning and missing values. Basic text pre-processing, feature engineering and document similarity computation were done.
  
    **Results:** The movie recommendation function successfully generates top 5 recommendations for each given movie title in the dataset. For instance, for the movie "Minions", the recommended movies include "Despicable Me 2", "Despicable Me", "Teenage Mutant Ninja Turtles: Out of the Shadows", "Superman", and "Rise of the Guardians". Similarly, for "Interstellar", recommended movies are "Gattaca", "Space Cowboys", "Space Pirate Captain Harlock", "Starship Troopers", and "Final Destination 2". These recommendations are derived from the movie metadata, enabling the system to suggest similar movies based on their textual descriptions.
  
    **Libraries:** nltk, re, pandas, numpy, TfidfVectorizer, cosine_similarity (sklearn feature_extraction)
 
    **Skills:** Natural language processing, Machine learning, unstructured data, predictive modelling.

  
<!-- - [Customer Sentiment Analysis]()
  
    **Goal:**
  
    **Code:**
  
    **Description:**
  
    **Results:**
  
    **Libraries:**
  
    **Skills:** -->
  
### 2. SQL
  - [Customer Churn Analysis for Telecommunication Networks](https://github.com/isaacmensahtwum/Data-Analysis-with-SQL/blob/88f2c590fc918f37ddc50ed3b5270dedf823021d/Customer%20Churn%20SQL%20Query.sql)

    **Goal:** To identify customers who are likely to cancel their subscriptions, thereby allowing for the implementation of proactive measures to encourage customer continued loyalty
  
    **Code:** [Customer Churn Analysis.sql](https://github.com/isaacmensahtwum/Data-Analysis-with-SQL/blob/88f2c590fc918f37ddc50ed3b5270dedf823021d/Customer%20Churn%20SQL%20Query.sql)
  
    **Method:** Did data sourcing and cleaning, had an entity relationship diagram (ERD) to connect the tables in the database, queried 10 business questions, and visualized using Tableau.
  
    **Results:** The telecommunication network should add value to its service by giving incentives and exploring better pricing opportunities. They should give premium tech support for all customers,
                 train their customer support personnel and improve customer feedback. Also, there should be incentives to encourage long-term commitments. it can be offering locked phone discounts to keep                         customers beyond a year. Further, there should be city-specific market insights and customer feedback collection to gain insights into local preferences. [Attached PowerPoint](https://github.com/isaacmensahtwum/Data-Analysis-with-SQL/blob/88f2c590fc918f37ddc50ed3b5270dedf823021d/Customer%20Churn%20PowerPoints.pptx)
  
    **Software:** MySQL server, draw.io, Tableau
  
    **Skills:** Database Management, Data Manipulation Language (DML), Data Query Language(DQL), Data Definition Language(DDL), Entity Relationship Diagram, RDBMS, Presentation


  - [Analysis of COVID-19 with SQL](https://github.com/isaacmensahtwum/Data-Analysis-with-SQL/blob/88f2c590fc918f37ddc50ed3b5270dedf823021d/Analysing%20COVID-19%20with%20SQL.sql)
    
    **Goal:** To analyze the impact of COVID-19 cases globally by infection and death percentage.
    
    **Code:** [Analysis of COVID-19 with SQL.sql](https://github.com/isaacmensahtwum/Data-Analysis-with-SQL/blob/88f2c590fc918f37ddc50ed3b5270dedf823021d/Analysing%20COVID-19%20with%20SQL.sql)
    
    **Method:** Used Oracle software to clean and create Excel tables imported in Tableau. Performed queries like Join, Like, Having, Where and other high queries.
    
    **Results:** Displayed on Tableau Public [here](https://public.tableau.com/app/profile/isaac.mensah.twum/viz/PortfolioProject_16864195247070/Dashboard1)
    
    **Software:** Oracle database and Tableau
    
    **Skills:** Database Management, Data Manipulation Language (DML), Data Query Language(DQL), Data Definition Language(DDL)

          
### 3. Tableau
  - [My Tableau Public Profile](https://public.tableau.com/app/profile/isaac.mensah.twum/vizzes). This link leads to the Tableau visualizations I published.
        
### 4. Power BI
  [Click Here](https://github.com/isaacmensahtwum/Power-BI-and-Excel.git) for all my Power BI projects and Dashborads
  - [Survey of Data Professionals](https://github.com/isaacmensahtwum/Tableau-and-Power-BI/blob/0f36a2ae637e93c26190139d0f05ef42e76f2b65/Data%20Analysis%20with%20PowerBI.pbix).
    I followed a learning platform to create this Dashboard. The goal is to create a dashboard of Job roles and key variables like salaries, countries, gender, and how happy one is with their job.
    The data was from a survey and therefore I used Power BI to clean, create columns, aggregations, etc.

<!-- ### 5. Excel -->

### 6. SAS viya
  - [SAS viya Dashboard](https://github.com/isaacmensahtwum/SAS-viya.git) printed in PDF format.


## Education
- Appalachian State University, North Carolina <br>
  Master of Science in Applied Data Analytics, August 2024
- Eastern Illinois University, Illinois <br>
  Master of Arts in Economics, May 2023
- University of Cape Coast, Ghana <br>
  Bachelor of Arts in Economics and Mathematics, July 2020
  
## Certifications
- [Web Analytics Certification - GA4](https://skillshop.credential.net/f8ebaff6-7d51-4dc1-af38-b96696dc52d4#gs.5pkzay), Google, Jan. 2024
- [Data-Driven Decision Making in SQL](https://www.datacamp.com/completed/statement-of-accomplishment/course/589044df3fc34ec6c9e933d47871bd54e2d0209a),  DataCamp Oct. 2023
- [Analyzing Business Data in SQL](https://www.datacamp.com/completed/statement-of-accomplishment/course/00fbbadb8223afa88e5d3d69a4ec45bd559001da), DataCamp Nov. 2023
- [Microsoft Certified: Azure Fundamentals](https://www.credly.com/earner/earned/badge/394d8952-078b-47d8-b2a4-8637b6b5d0d6), Microsoft (verification code: wXVqW-48Eq) Oct. 2023
- [Using Python to Access Web Data Certificate](https://www.coursera.org/account/accomplishments/verify/SUHZCAZBGZ4C) Coursera, University of Michigan Sept. 2022
- [IBM Data Analysis with Python](https://www.coursera.org/account/accomplishments/verify/LJJKE8M86ASX), IBM May 2022
- [Google Data Analytics Professional](https://www.coursera.org/account/accomplishments/verify/WBPALMQ97GY2), Coursera, Google Apr. 2022
- [Databases and SQL for Data Science with Python](https://www.coursera.org/account/accomplishments/verify/YMNXGWDT8SUM), IBM Mar. 2022
- [R programming](https://www.coursera.org/account/accomplishments/verify/4J2Z3E2HBUER), Coursera, Johns Hopkins University Dec. 2021

## Contact
  - Website: [@IsaacTwum](https://isaacmensahtwum.github.io/DataAnalyst.github.io/)
  - LinkedIn: [@imtwum](https://www.linkedin.com/in/imtwum/)
  - Email: twumisaacmensah@gmail.com



