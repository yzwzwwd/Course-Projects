## Introduction
This web page mainly introduces my 4 course projects related to different statistical models. All the projects consist of exploratory data analysis, model building and hypothesis testing. The analysis is conducted via R software.  

* ***Effect of Class Size on Student Achievement*** (One-way ANOVA Model)
* ***Further Research on the Effect of Class Size on Student Achievement*** (Two-Way ANOVA Model)
* ***Relationship between a mandatory jail sentence and traffic fatalities*** (Time and Entity Fixed Effects Regression Model)
* ***Bank Marketing Campaign Prediction*** (Logistic Regression Model & Random Forest)
 
### Project 1 & Project 2: Investigating into Factors related to Student Achievement
#### Methodology  
**One-way ANOVA**  
**Two-way ANOVA**  
**Main Effect and Interaction Effect Plot**  
**Causal Statement**
#### Data Set
The data comes from Tennesses Student/Teacher Achievement Ratio study (Project STAR). Within the experiment, enrolled schools are selected randomly and students among the schools are randomly assigned to each class type: small. regular and regular with a teacher's aide. The dataset contains scaled scores for math and reading from kindergarten to 3rd grade.
#### Main Task  
In project 1, our goal is to analyze the distribution of students' math grade among different class types. Here class type is the only factor we care about, thus we choosing one-way ANOVA model to fit the data. 
In project 2, we take both class type and school type into consideration. Two-way ANOVA model holds more assumptions which are in need of checking.
Another important point in both models is to evaluate the feasibility of making corresponding causal statement following the hypothesis test result. 

#### Important Result
<img src="https://github.com/yzwzwwd/Course-Projects/blob/master/1.png?raw=true" width="700" height="400">
<img src="https://github.com/yzwzwwd/Course-Projects/blob/master/2.png?raw=true" width="700" height="400">

### Project 3: Relationship between a mandatory jail sentence and traffic fatalities
#### Methodology  
**Time and Entity Fixed Effects Regression Model**  
**Selection of Covariatest**
#### Data Set
In this project, we use the data set “Fatalities” containing the traffic fatalities data for 48 US states from 1982 to 1988. Certain measures are included in the
data such as minimum legal drinking age, beer tax and percent of young drivers aged 15-24. Variables related to the economic and human environment of each state and each year are also available like the population, unemployment rate and income per capita.
#### Main Task  
Our goal is to analyse the data to find out which of these variables have association with traffic fatalities. Specifically, we want to check whether having a mandatory jail sentence is associated with reduction of traffic fatalities. Also we will check the feasibility of making causal statements. One of the most important tasks here is to select appropriate control variables (covariates) so that the estimation of the main effect of the variable we are interested in is not biased.  

#### Important Result
<img src="https://github.com/yzwzwwd/Course-Projects/blob/master/32.png?raw=true" width="800" height="400">
<img src="https://github.com/yzwzwwd/Course-Projects/blob/master/31.png?raw=true" width="700" height="400">

### Project 4: Bank Marketing Campaign Prediction
#### Methodology  
**Resampling (upsample/downsample/SMOTE)**
**Logistic Regression**  
**Random Forest** & **Parameter Tunning**  
**ROC Curve** & **AUC**
#### Data Set
In this project, we will use the “Bank Marketing Campaign” data set. It contains the variables of bank clients’ information, social and economic context attributes and some others. The dependent variable is “whether the client will subscribe a term deposit or not”.
#### Main Task
We build classification models such as Logistic Regression and Decision Tree to predict the telemarketing call’s results. Finally, we are going to compare all these models
according to different criterion like the precision and sensitivity. With the implementation of this project, banks can better understand what kinds of clients are more likely to subscribe a term deposit, so that they can select a high quality set of potential customers and reduce the phone calls.
#### Important Result
<img src="https://github.com/yzwzwwd/Course-Projects/blob/master/41.png?raw=true" width="800" height="400">
<img src="https://github.com/yzwzwwd/Course-Projects/blob/master/42.png?raw=true" width="700" height="400">




