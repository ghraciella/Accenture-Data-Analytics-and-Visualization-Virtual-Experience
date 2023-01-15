# Accenture-Data-Analytics-and-Visualization-Virtual-Experience


Data Analytics, Microsoft PowerBI, Microsoft Excel Python





<p><h2 align="center"><font color="red">  Project Overview </font></h2>

<p> Client: Social Buzz
<p> Client's Industry: Social Media and Content Creation

Social Buzz is a large social media company with the unique idea of emphasizing content on their platform by making users anonymous and tracking user reactions only. There have over 100 ways that users can react to content, spanning beyond the traditional reactions of likes, dislikes, and comments which ensures that trending content, as opposed to individual users, is at the forefront of user feeds. 

Social Buzz has reached over 500 million active users each month over the past 5 years and the amount of data that they create, collect also analyze is huge. Every day over 100,000 pieces of content mostly in an unstructured form, ranging such as text, images, videos and GIFs are posted. 



<p><h2 align="center"><font color="red">  Task </font></h2>

The Project task was to understand the client's business problem based on provided brief and several datasets. The idea was to simulate a project plan with a focus on these task (I had to only focus on the last point for this project):
<ul>
<li>Audit of their big data practices.</li>
<li>Recommendations for a succesful IPO.</li>
<li>Analysis of the top 5 content categories with the largest aggregate popularity.</li>

Basically the business problem to be tackled by me for this project was how to manage and maintain the massive amounts of data and also how too analyze content categories highlighting top 5 categories.






<p><h2 align="center"><font color="red"> Project Process </font></h2>

<li>Project Understanding
        <ul><li>Read the project brief, understood the client's and their business problem at hand.</li> 
            <li>Identified requirements that need to be deliverd for the project</li>
            <li>Identified the task I should focus on as a Data Analyst</li>
            </li>
        </ul>
    </li>
    
   
<li>Data Cleaning and Data Modelling
        <ul> 
            <li>Using Python I checked for Missing values of the 3 most relevant sample datasets, cleaned the data such as removing rows with                      missing values, changing data types, removing columns not relevant to my analysis, merged datasets using left join, extract top 5                   categories using Pandas GroupBy and Aggregation method, saved the data as Excel and CSV files </li>
            <li> Uploaded relatively cleaned and merged data into PowerBi, transformed data further, creating relevant tables, calculated columns                   (for all categories based on the scores, reactions and sentiments) using DAX programming language and changed to correct datatype                     for new columns, I introduced some measures using DAX to help with my insights as well.</li>
            <li>Created Relationships between the new 3 tables I introduced in Model view in PowerBI</li>
        </ul>
    </li>
 

<li>Data Visualization and Insights
        <ul><li>Created a Dashboard with several visualizations in the report view of PowerBI</li> 
        </ul>
        </li>   
 
 
 <li>Presentation to the Client on Forage Platform for Project
        <ul><li>This part of the task required me to make a video presentation of my analysis of the content data, </li> 
            <li>Give a project recap based on the bussiness problem</li>
            <li>Share my Analsysis, Give Insights and also my recommendations.</li></ul>
            </li>
        </ul>
 </li>    


</p>



<p><h2 align="center"><font color="red"> Visualization </font></h2>

For my  Data Visualization to provide insights, I used MIcrosoft Power BI. I created a dashboard in the report view and used some common visualization char types from the visualization pane to help provide some visual insights in understanding the popularity of different categories based on scores, reactions and sentiments.

<img src = "/images/top5socialbuzz.jpg">





<p><h2 align="center"><font color="red"> Analysis and Insights </font></h2>

Based on my analysis of the cleaned dataset, the top 5 categories with aggregate popularity are animals, science, healthy eating, technolgy and food out of 16 unique categories.

The top category: Animal  has a total score of  74,965 with a total of 1,897 reactions , followed by the science category with a total score of 71,168 with a total of  1,796 reactions.  

Based on the top 2 categories indicates that users enjoy more intuitive, verifiable and nature-based contents. 

Also based on the common theme between categories: Food and Healthy living, this indicates users tend to be more active when it comes to what they consume.


This insight could be used to 

<ul>
<li> Create a more contents based on these categories.</li>
<li> Create a recommendation system for users based of these categories.</li>
<li> Collaborate with brands and advertise content based of these categories to users.</li>











