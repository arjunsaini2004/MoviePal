# Movielens
Built a full-stack content-based movie recommender using TF-IDF and cosine similarity to suggest similar movies based on metadata like genre and plot, with React, Node.js, and Python.



🔍 Project Title: Movie Recommendation System (Full Stack)
📄 Description:
Developed a full-stack web application that recommends movies based on user preferences using collaborative filtering and content-based algorithms. The system allows users to sign up, rate movies, view personalized recommendations, and explore trending films through an interactive UI.

💻 Tech Stack:
Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB / PostgreSQL (any one)

Machine Learning: Python (Pandas, Scikit-learn), Surprise / TMDB API

Authentication: JWT, bcrypt

Deployment: Render / Vercel / Netlify / Heroku

🚀 Key Features:
User registration and login

Personalized movie recommendations

Search functionality with auto-suggestions

Trending & top-rated movie lists (using TMDB API)

Ratings and review system

Responsive design for mobile and desktop



![frontend](https://github.com/user-attachments/assets/a71865a4-2ded-4e0a-85d5-d1d1cf07ad1b)






A recommender system is a subclass of information filtering system that seeks to predict the "rating" or "preference" a user would give to an item. Recommender systems are utilized in a variety of areas including movies, music, news, social tags, and products in general. Recommender systems typically produce a list of recommendations and there are few ways in which it can be done. Two of the most popular ways are – through collaborative filtering or through content-based filtering.

Most internet products we use today are powered by recommender systems. YouTube, Netflix, Amazon, Pinterest, and long list of other internet products all rely on recommender systems to filter millions of contents and make personalized recommendations to their users. Recommender systems are well-studied and proven to provide tremendous values to internet businesses and their consumers.

There are majorly six types of recommender systems which work primarily in the Media and Entertainment industry:

Collaborative Recommender system
Content-based recommender system
Knowledge based recommender system
Hybrid recommender system
Demographic based recommender system
Utility based recommender system
GitHub Logo

Recommender System is a vast concept rooted from a base idea of giving out suggestions to the users. There are wide range of algorithms are used to build a recommender system and the type of recommender system used is mostly dictated by the type of data available. In this project, first three of the above recommender systems were built.

Content based recommender system
This approach utilizes a series of discrete characteristics of an item in order to recommend additional items with similar properties. Content-based filtering methods are based on a description of the item and a profile of the user's preferences. To keep it simple, it will suggest you similar movies based on the movie we give (movie name would be the input) or based on all of the movies watched by a user (user is the input). It extracts features of a item and it can also look at the user's history to make the suggestions.

Collaborative recommender system
Collaborative filtering is based on the assumption that people who agreed in the past will agree in the future, and that they will like similar kinds of items as they liked in the past. The system generates recommendations using only information about rating profiles for different users or items. By locating peer users/items with a rating history similar to the current user or item, they generate recommendations using this neighborhood. This approach builds a model from a user’s past behaviors (items previously purchased or selected and/or numerical ratings given to those items) as well as similar decisions made by other users. This model is then used to predict items (or ratings for items) that the user may have an interest in. Collaborative filtering methods are classified as memory-based and model-based.

Knowledge based recommender systems
These are based on explicit knowledge about the item assortment, user preferences, and recommendation criteria (i.e., which item should be recommended in which context). These systems are applied in scenarios where alternative approaches such as collaborative filtering and content-based filtering cannot be applied. In simple terms, knowledge based recommender system can be used to suggest content/item to a new user or an anonymous user who doesn't have any history.

Hybrid recommender system
This combines more than one of these techniques to resolve one or more problems. This approach can be used to overcome some of the common problems in recommender systems such as cold start and the sparsity problem in collaborative approach, as well as the knowledge engineering bottleneck in knowledge-based approaches. It is proved that hybrid recommender system performs extremely well compared to pure collaborative and content based methods.
