#  Car accident severity - Capstone Project 
![zz](https://user-images.githubusercontent.com/41941627/95646403-0fa1c700-0b03-11eb-94d1-479ff49b8b76.jpg) </br></br>
If you want to see metadata or get more detailed information on the data set, please refer to the link below.</br>
<https://s3.us.cloud-object-storage.appdomain.cloud/cf-courses-data/CognitiveClass/DP0701EN/version-2/Metadata.pdf>
 

 ## Table of content",
1. [Introduction]
2. [Business Problem]
3. [Data]

# 1. Introduction
The total number of vehicles worldwide is increasing every year.</br>
It mean that Car accidents can occur all the time all the way. </br>
However there are some conditions were the probabilities of have an accident arise due multiple variables. 
This report has as purpose develop a model for Seattle government to predict the probabilities of have a car accident and severity, based on different conditions as weather or road conditions. </br></br>
The information was provided by Seattle Police Department form 2004 to 2020. </br></br>
# 2.Business Problem
Identify the conditions that can cause future car accidents in order to alarm the people with anticipation to be aware and drive more carefully.
</br> In an effort to reduce the frequency of car collisions in a community, an alogorithm must be developed to predict the severity of an accdient given the current features.</br></br></br>
It will give us THREE BIG benefits : </br></br>
__1. Save lives as main benefit </br>__</br>
__2. Reduce costs in damage infrastructure</br>__</br>
__3. Reduce cost from police and paramedics to attend each accident__</br></br>

# 3. Data
It comes from Seattle Police Department and recorded by Traffic Records and include Collisions at intersection or mid-block of a segment. The period information is from 2004 to May 2020.</br></br>
The information is organized in a CSV File with 37 attributes and originally 194673 rows. Information is labeled and unbalanced. Additionally a document with the description of each column were given. </br></br> 
Due our information is labeled we know the result for each record, we have select the column __SEVERITYCODE__ as Dependent varible. The possible values are:</br>
</br>
__1 -- Property Damage Only Collision__</br></br>
__2 -- Injury Collision__</br>
The information is unbalanced by the difference in samples for each accident type. In our case there are only two types of accidents. Look at the picture below:</br>
<img width="303" alt="1" src="https://user-images.githubusercontent.com/41941627/95647741-bfc7fd80-0b0c-11eb-9dd7-c8ba765eb74d.png"></br></br>
In it's original form, this data is not fit for analysis. For one, there are many columns that we will not use for this model. Also most of the features are of type object, when they should be numerical type. </br> We must use label encoding to covert the features to our desired data type.</br>



