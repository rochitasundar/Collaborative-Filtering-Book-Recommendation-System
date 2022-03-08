### Book Recommendation Project

Recommendation Systems are one of the largest application areas of Machine Learning. They enable tailoring personalized content for users, thereby generating revenue for businesses

There are 2 main types of personalized recommendation systems:

#### Content based filtering
Recommendations are based on user's past likes/ dislikes & item feature space. The system makes recommendations which are similar to items the user has liked in the past. Items are considered similar based on item's features such as author, publisher, genre etc

#### Collaborative based filtering
Recommendations are based solely on user's past likes/ dislikes & how other users have rated other items. The system does not take into consideration an item's features like author, publisher, genre etc nor a user's features like age, gender, location etc. These take either a memory based approach or a model based approach

#### (1)Memory based approach: 
Utilizes entire user-item rating information to calculate similarity scores between items or users for making recommendations. These are further either of 2 types:

 - __User based__: Two users are considered similar, if they rate items in a similar manner. An item is recommended to a user, if another user i.e., similar to the user in question has liked the item

 - __Item based__: Two items are considered similar, if users rate them in a similar manner. An item is recommended to a user, that is similar to the items the user has rated in the past

#### (2)Model based approach: 
Utilizes user-item rating information to build a model & the model (not the entire dataset) is thereafter used for making recommendations. This approach is preferred in instances where time & scalability are a concern

This project aims to build a recommendation system based on collaborative filtering & will tackle an example of both memory based & model based algorithm


### Datasource:
This project will use the 'Book-Crossing dataset' collected by Cai-Nicolas Ziegler 
(http://www2.informatik.uni-freiburg.de/~cziegler/BX/)

The dataset consists of 3 different tables:

- 'BX-Users': 278,858 records
- 'BX-Books': 271,379 records
- 'BX-Book-Ratings' : 1,149,780 records
