# Recommendation_Engine_Food_Delivery

**DATA: https://drive.google.com/file/d/12eRooA9jz2ZuFWypTuEJKrBlyU6F3aJ3/view?usp=sharing**

The objective of this report is to discuss the process of rebuilding the recommendation engine of Glovo’s restaurant delivery. Since data was not publicly available for Glovo, I decided to use Yelp review dataset due to the similarity in nature of the two companies. Data was further transformed to match the business specificity of Glovo. The current shortcomings of Glovo Recommendation Engine are low serendipity & low novelty, lack of personalization and long tail distribution of review. Thus, a new **Cascade Hybrid Model** was built by ensemble **Context Sensitive, Location-Based, Knowledge Based, Popularity, Random and Item Based Collaborative Filtering recommender**. Each algorithm feeds on the refined recommendations of the previous algorithm to provide the most relevant list of recommendations.

<img width="927" alt="Screen Shot 2019-04-04 at 15 44 04" src="https://user-images.githubusercontent.com/44138106/55560476-8ed56400-56f0-11e9-8c97-e5c329123ec8.png">


