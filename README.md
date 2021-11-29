# Udacity Data Scientist Nanodegree
## Project 1 (Write A Data Science Blog Post)

### Motivation and a summary of the results of the analysis

I chose to analyze Stack Overflow Annual Developer Survey results from 2021 (https://info.stackoverflowsolutions.com/rs/719-EMH-566/images/stack-overflow-developer-survey-2021.zip).
I am a web developer, so I was curious about technology other developers use in the world and some specific countries.

The questions I tried to answer, using this data, are:

1. What programming languages were used the most among all respondents and in different countries?

*JavaScript, HTML/CSS, Python and SQL were used the most. JavaScript is the clear leader.*

2. What operating systems were used the most among all respondents and in different countries?

*Windows is by far the leading operating system. Next, Linux-based and MacOS are used by about the same amount of respondents.*

3. What highest level of education do respondents have? What about some specific countries?

*Almost half of respondents have Bachelor's degree. Next big group, just a little over 20%, have Master's degree.*

4. How well can we predict the age of respondents?
*With just default parameters for the model we could predict the Age with 70.4% accuracy.*


### Project files

survey_results_public.csv - data, survey responses  
survey_results_schema.csv - data schema  
so_survey.ipynb - Jupiter Notebook with data analysis  
so_logo2.png - Stack Overflow logo, used to create a wordcloud  


### Used libraries:
I used Python 3.9 and following libraries:
- pandas
- matplotlib
- collections
- wordcloud
- PIL
- numpy
- scipy
- sklearn
