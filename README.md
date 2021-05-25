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

### Business Understanding
Question 1: What does each treatment typically cost? How tp display this data to consumers?
Question 2: Which treatment is rated the highest by users? Are there factors that are correlated with a high rating?

### Data Understanding
The metadata cannot be shown here due to restriction.
Data information is listed below:

RangeIndex: 662 entries, 0 to 661
Data columns (total 9 columns):
 #   Column            Non-Null Count  Dtype         
---  ------            --------------  -----      
 0   Created Date      662 non-null    datetime64[ns] Review created date.
 1   Treatment Rating  662 non-null    object   Consumer's rating on the treatment he/she took. There are just two outcomes, Worth it or Not worth it.           
 2   Number of Photos  662 non-null    int64    Number of posted photos    
 3   Number of Words   662 non-null    int64    Number of review words
 4   Provider Rating   644 non-null    float64  Consumer's rating on the treatment provider (out of 5)
 5   Physician Type    547 non-null    object   Provider's type, such as Family Physician, Plastic surgeon
 6   Treatment Name    662 non-null    object   4 different treatments.
 7   Title             662 non-null    object   Consumers' review title   
 8   Cost              662 non-null    float64  Cost for the treatment (posted by consumers).
