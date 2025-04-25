This project uses IBM SPSS, a powerful data analytics tool, to analyze user behavior and predict addiction levels based on various factors.

Project Title: Social Media Addiction Analysis and Prediction

Objective: The aim of this project is to analyze social media usage patterns and predict addiction levels using machine learning algorithms. This is achieved by categorizing user behavior and identifying key factors that contribute to social media addiction.

Workflow Overview: The project is divided into two main segments, each focusing on different stages of the analysis:

Left Segment: Exploratory Data Analysis & Clustering Data Input: A dataset containing 43 fields related to social media usage is imported.

Preprocessing: Fields are filtered and relevant ones are selected. The variable AddictionLevel is defined to represent the degree of addiction.

Data Typing: Variables are assigned appropriate types (categorical, continuous).

Clustering Techniques: K-Means Clustering and TwoStep Clustering are applied to identify user groups based on social media behavior.

Classification Models: CART (Classification and Regression Trees) is used to classify users into different addiction levels.

Visualization: Outputs from clustering and classification are visualized and analyzed.

Right Segment: Prediction Model Development Refined Dataset: A reduced dataset with 13 selected fields is used for model training.

Preprocessing: Data is typed and partitioned into training and testing sets.

Decision Tree Algorithm (CHAID): CHAID models are developed to predict the AddictionLevel based on the input features.

Prediction: The model outputs addiction levels and helps identify user IDs at risk.

Evaluation: Model outputs are analyzed to assess prediction accuracy and feature importance. Gender-based insights and other demographic patterns are explored.

Tools & Techniques Used: IBM SPSS Modeler (or similar visual analytics tool) K-Means Clustering TwoStep Clustering CART & CHAID Decision Trees Data Partitioning Exploratory Analysis and Visualization
