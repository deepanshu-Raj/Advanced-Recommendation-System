# Advanced Recommendation System

The goal of the Advanced Recommendation System is to improve suggestions.The majority of extant recommendation algorithms are limited to a single area.

To provide cross-domain suggestions, this proposal would use both content-based suggesting and collaborative filtering. It would also make use of the deep learning architecture to incorporate Implicit Feedback and improvise recommendations. Enhancing the quality of recommendations would lead to a smooth user experience and in turn would lead to increase in the user activity on that platform.

#### Implemented Recommendation Systems



1. Single Domain Recommendation System
	- Demographic Recommendation System.
	- Content-Based Recommendation System.
	- Collaborative Filtering Based Recommendation System.
	- Implicit Feedback Based Recommendation System.

2. Single Domain Hybrid Recommendation System
3. Cross Domain Recommendation System

#### Technology:

Python Programming has been used to implement various Recommender Systems. Apart from the scripting, we have used numpy & pandas packages for data pre-processing. Jupyter Notebook has been used to run the scripts module by module. Integration of various Single Domain Recommender System has been done to create Hybrid Recommendation System for Single Domain Applications & Cross-Domain Recommendation System for Multiple Domain Applications. The Scripts can be used as a starter template for a Real-World Recommender System Applications.

#### Challenges:

Few of the major challenges that we faced are:
- **Cold Start :** If a user is new to a domain, there's just not enough information about them, such as their preferences, engagement rate, and so on, thus the basic recommendation system, which works by locating like-minded people, won't operate well.
- **Data Sparsity:** When a user's information (like things rated) is insignificant in comparison to the available data (items in the database), determining the resemblance between like-minded people is challenging.

#### Assumptions:

Key Assumptions that we made while developing this framework are:
- All the Data that we worked on is from MovieLens website, hence we assumed that reviews written and maintained are all authentic, and do replicate a real-world scenario; and not just a manipulation of numbers.
- The Domains generated for the Cross-Domain Recommendation System are each a quarter of the original dataset that we worked on. Hence, we assumed the data had sufficient variance to accommodate 4 domains with specific needs.

#### Results:

<p align="center">
<img src="https://github.com/user-attachments/assets/23fa1a7b-cc61-4d32-a3b9-6c7eedda79e0" width="600" height="300">
</p>
<p align="center">Performance of Collaborative Filtering Based Recommendation System</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/494a2419-11ed-4648-bd44-9acb9136b1b5" width="600" height="300">
</p>
<p align="center">Line Plot of comparison on MAE of various Recommender models</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/1f2f3742-6b53-41a8-baa3-ed4c43598974" width="500" height="300">
</p>
<p align="center">Line Plot of comparison on RMSE of various Recommender models</p>

#### Improvement w.r.t Single Domain Recommendation System (SDRS)

As can be clearly seen, that the Recommendations improve on increasing the data, i.e if data sparsity is dealt with properly; Massive improvements in recommendations can be observed as the MAE drops from 0.93 to 0.79 in Single Domain CF and 0.83 to 0.736 in Cross-Domain (no-bias), with increase of data in target domain from 10% to 100% of the total data.

Similarly, RMSE drops from 1.25 to 1.0 in Single Domain CF and 1.04 to 0.93 in Cross-Domain (no-bias), with an increase of data in target domain from 10% to 100% of the total data. With respect to the accuracy improvement comparison between SDRS & CDRS, average MAE in single domain is 0.78 and Average MAE in Cross Domain is 0.75, hence we can conclude that accuracy of cross domain recommendations is better as compared to that of the single domain recommendations.

#### Authors

- [@Deepanshu Raj](https://github.com/deepanshu-Raj)
- [@Devansh Shukla](https://github.com/devanshjsr)
- [@DharmRaj Maurya](https://github.com/Dharm1999)





