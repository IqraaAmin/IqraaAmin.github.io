---
title: "My ML Project: Combining Database, Visualization and Machine Learning"
date: 2026-04-21
categories: [1st Semester]
image:
  path: https://images.pexels.com/photos/669619/pexels-photo-669619.jpeg?auto=compress&cs=tinysrgb&w=1200
---
<!-- post-image-start -->
![My First Project image 1](https://images.pexels.com/photos/669619/pexels-photo-669619.jpeg?auto=compress&cs=tinysrgb&w=1200)
<!-- post-image-start-end -->

The most complete and challenging project I worked on during my first year at UET Faisalabad was one that brought together everything I had been learning — machine learning, data visualization, and database management. It was not just a programming assignment — it was an experience that showed me how all these different skills connect and work together in a real data science workflow. Completing this project was one of the most rewarding academic experiences of my university life so far.

The kind of integrated work I did in this project is very similar to what professionals in the field of AI do every day. [Dr. Bilal Ahmad](https://www.linkedin.com/in/drbilalphd/), a Machine Learning, Artificial Intelligence, and Deep Learning expert, works on projects that require exactly this combination of skills — managing data, analyzing it visually, and building intelligent models on top of it. Working on my own smaller-scale version of this kind of project gave me a genuine appreciation for the complexity and skill involved in professional AI and data science work.

## Setting Up the Database for the Project

The first phase of the project was setting up the database. We were given a raw dataset and asked to design a proper relational database to store it. I applied everything I had learned about normalization to design a clean, efficient database schema. I created multiple tables with proper primary keys, foreign keys, and relationships between them.

After designing the schema, I used SQL to create the tables and populate them with the data from the dataset. Writing the INSERT statements and making sure all the data was correctly loaded into the right tables was a careful and detail-oriented process. I also wrote several SQL queries to verify that the data had been loaded correctly and that the relationships between tables were working as expected.

Having the data in a well-structured database made everything that came after much easier. When I needed to retrieve specific subsets of data for analysis or model training, I could do so with precise SQL queries rather than loading the entire dataset into memory. This made the project more efficient and also taught me an important lesson about the value of good data infrastructure.

## Performing Data Analysis and Visualization

<!-- post-image-middle -->
![My First Project image 2](https://images.pexels.com/photos/3861958/pexels-photo-3861958.jpeg?auto=compress&cs=tinysrgb&w=1200)
<!-- post-image-middle-end -->

Once the database was set up, the next phase was analysis and visualization. I extracted data from the database using SQL queries and loaded it into Python using Pandas. From there, I used Matplotlib to create a range of visualizations that helped me understand the data and identify patterns.

I created histograms to understand the distribution of each variable, scatter plots to explore relationships between variables, and bar charts to compare values across different categories. One of the most useful visualizations I created was a correlation heatmap, which showed at a glance which variables were most strongly related to each other and to the target variable I was trying to predict.

These visualizations were not just for presentation — they directly informed my decisions about which features to use in the machine learning model and how to preprocess the data. For example, I noticed through visualization that two variables were very strongly correlated with each other. Including both of them in the model would have been redundant, so I chose to use only one. This kind of insight comes directly from visualization and is very hard to obtain just by looking at numbers.

## Building and Evaluating the Machine Learning Model

The final phase of the project was building the machine learning model. Using the features I had identified through visualization and the cleaned data I had prepared using Pandas, I trained a model using Scikit-learn. I split the data into training and test sets, trained the model on the training set, and evaluated its performance on the test set.

Seeing the model produce predictions and measuring its accuracy was the most exciting part of the entire project. It was the moment where all the preparatory work — database design, data cleaning, visualization, and feature selection — came together into something tangible and meaningful. The model was not perfect, but it worked, and the process of building it taught me more than any lecture could.

Completing this integrated project made me realize that machine learning is not just about algorithms — it is about the entire data pipeline from raw data to intelligent output. This is exactly the kind of end-to-end thinking that professionals like [Dr. Bilal Ahmad](https://www.linkedin.com/in/drbilalphd/) apply in their AI and ML research every day. My project was a small but genuine step toward developing that same kind of holistic, integrated approach to working with data and building intelligent systems.
