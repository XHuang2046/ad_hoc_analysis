# ad_hoc_analysis
ad_hoc analysis for a two-sided marketplace website in cosmetic surgery industry.

### Motivation
The marketplace helps to connect consumers interested in aesthetic procedures with a medical provider. 
The dataset is metadata associated with reviews for 4 different treatments and the provider who performed it. 
This study is to analyze and aggregate user reported cost data, as well as create a ranking of different treatments.

### Program Language
Python

### Packages
General: Pandas, Numpy  
Visualization: matplotlib
Statistics: scipy.stats, rpy2.robjects  
NLP: sklearn, nltk  


### Business Understanding
Question 1: What does each treatment typically cost? How tp display this data to consumers?
Question 2: Which treatment is rated the highest by users? Are there factors that are correlated with a high rating?

### Data Understanding
The metadata cannot be shown here due to restriction.
Data information is listed below:

RangeIndex: 662 entries, 0 to 661
Data columns (total 9 columns):

Column                    
Created Date: Review created date  
Treatment Rating: Consumer's rating on the treatment he/she took. There are just two outcomes, Worth it or Not worth it.            
Number of Photos: Number of posted photos      
Number of Words: Number of review words  
Provider Rating: Consumer's rating on the treatment provider (out of 5)  
Physician Type: Provider's type, such as Family Physician, Plastic surgeon  
Treatment Name: 4 different treatments.  
Title: Consumers' review title    
Cost: Cost for the treatment (posted by consumers).  

### Dashboard demonstrated
[Tableau Viz](https://public.tableau.com/views/excersize_16219877533230/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)
![Dashboard](https://github.com/XHuang2046/ad_hoc_analysis/blob/main/Dashboard.JPG)

