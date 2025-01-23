# Course_Evaluation_Prediction_and_Analysis
Work done with two teammates as part of the Data Mining Course at the Lebanese American University

# Problem Selection
In light of the time context of this assignment, the approaching end of the semester and finals period is the moment universities and educational institutions send their students course evaluation forms to assess their feedback and experience from the courses they have taken within the semester.

Student’s answers from course evaluations yield crucial insights on receptivity to teaching practices, quality of learning, and performance of professors. Thus, in this project, we decided to apply several machine learning models on a data set comprised of students’ course evaluation answers, compiled over the span of 5 years from the University of Queensland, Australia. Our first goal is to predict students’ overall course rating based on the different available features, while our second goal is to understand the relationship between the features and the response variable, by determining what factors influence student’s rating and thus the perceived quality of learning the most and by what extent.

While our analysis and results are adequate for Queensland University and its students, to a certain extent, the results of this work can be extended to other institutions to tailor the educational experience of their students to their needs and refine the strategies of course delivery for an enhanced student performance and quality of teaching at the university.

# Methodoly
The work includes the following steps:
* Data collection
* Data Preprocessing
* Descriptive Exploratory Analysis
* Feature Engineering and Feature Selection
* Model Development and Evaluation
  - Tree Based Methods
  - SVM with different kernels
  - Principle Component Analysis
  - KMeans and Hierarchal Clustering


# Concludion
In this report, we used a dataset of course evaluations compiled over multiple years from the University of Queensland, Australia. Touching upon the goals identified earlier in the problem selection, our findings were as follows:

SVM Model with radial kernel, gamma of 0.001, and cost of 10 resulted in the best prediction model when compared to different tree models.

The factors involved in the class environment and teaching method are much more relevant to the overall course rating compared to more objective factors like the class size, campus, gender, etc.

Future work includes collecting more data about the details of the learning environment like activities, projects, and other coursework that will help us identify which of these components resulted in factors such as clear understanding, intellectually simulating.. etc which were related to higher ratings.
