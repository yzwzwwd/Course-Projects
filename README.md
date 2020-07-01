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
In our project, we use the data set “Fatalities” containing the traffic fatalities data for 48 US states from 1982 to 1988. Certain measures are included in the
data such as minimum legal drinking age, beer tax and percent of young drivers aged 15-24. Variables related to the economic and human environment of each state and each year are also available like the population, unemployment rate and income per capita.
#### Main Task  
Our goal is to analyse the data to find out which of these variables have association with traffic fatalities. Specifically, we want to check whether having a mandatory jail sentence is associated with reduction of traffic fatalities. Also we will check the feasibility of making causal statements. One of the most important tasks here is to select appropriate control variables (covariates) so that the estimation of the main effect of the variable we are interested in is not biased.  

#### Important Result
<img src="https://github.com/yzwzwwd/Course-Projects/blob/master/32.png?raw=true" width="800" height="400">
<img src="https://github.com/yzwzwwd/Course-Projects/blob/master/31.png?raw=true" width="700" height="400">


### Project 4

#### Data Set

```markdown
Syntax highlighted code block

# Project 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```









For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/yzwzwwd/Introduction-of-Zhiwei-Wang-Projects/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
