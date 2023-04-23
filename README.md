# Online News Popularity
### Predict The Number Of Shares In Social Networks

**Author:** Hazal Aydin
***

### Business Problem

Mashable is a global, multi-platform media and entertainment company. With the increase focus of the organisation on the online channels, the marketing team wants to understand what resonates with their readers and what drives them to share the Mashable articles with their own network.

Basically Mashable wants to understand what works for them, what not - and can we predict if an article will become viral.

### Data

The dataset I used came from the online articles published by  www.mashable.com between Jan 2013  and Jan 2015.
It contains 58 features that about the articles, as well as the total number of shares they received. 

These features include metadata information (title, keywords etc.), sentiment analysis statistics (rate of positive words, text subjectivity, title polarity etc.), SEO features (number of internal and external shares etc.), and some other features around the article (number of images, videos, the day it’s published, the content channel it belongs to etc.).

### Methods

- Used descriptive statistics and visualizations.
- Took an iterative and train-test split approach to the regression model. 
- Used both OLS model from statsmodels and LinearRegression from sklearn.
- Used plots to visualise the relationships between the variables and behaviours of the residuals.

### Conclusions

After 4 iterations, I created a model that is a good fit - meaning that I can validate my model on the training dataset. However, the model can only explain 10.8% of the observed data. This result shows that the dataset is limited to predict the future share behaviour. That's why I used the model more in an explanatory way.

### Recommendations

- Sticking to average keyword tags are better than choosing high ranked keywords is a better strategy - perhaps high ranked keywords have more competitive environment.
- Opinion pieces that are  strongly worded gets more shares. I recommend having opinion pieces more often.
- The shorter titles are better than the longer ones.
- I recommend having more external links than the internal links.
- Articles published on Mondays and Weekends have higher chance to become viral.
- Finally, I recommend publishing less articles in entertainment, business and world channels.

### Limitations & Next Steps

The biggest limitation and the challenge of this study was the dataset itself. It does a good job to identify some of the important features but is limited to fully explain the dynamics behind the Mashable's readers'article sharing behaviour. Looking at the features in the dataset, it lacks external factors and the group behaviours of individuals. We know that the relevancy of the articles to the current topic and trends, and whether or not someone influencial shares the article impacts its total shares. For the next studies, the dataset needs new featueres to reflects these.

### For More Information

For More Information Please review our full analysis in my jupyter notebook or my presentation.

For any additional questions, please contact Hazal Aydin at h.aydinhazal@gmail.com

Repository Structure 
├── README.md                               <- The top-level README for reviewers of this project 
├── student.ipynb                           <- Narrative documentation of analysis in Jupyter notebook 
├── Online_News_Popularity_Notebook         <- PDF version of the jupyter notebook 
├── Online_News_Popularity.pdf              <- PDF version of project presentation 
└── data                                    <- Sourced externally
