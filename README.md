# Indian Elections 2019

India, the largest democracy in the world, hosted its general election in 2019. For the second consecutive time, Indians chose Mr. Narendra Modi as its national leader. The Modi government, known for its overt Hindutva ideology, recently passed a bill callled the Citizenship Act 2019. The bill regulaste the citizenship of illegal migrants based on their religion and threatens the citizenship of Muslim minorities in India. Most of the citizens who voted for the BJP government did so because it was led by Mr. Narendra Modi. In doing so, voters ignored the credentials of the candidates they chose for their constituencies. In this project, we look at the competency of the candidates who represented the BJP in the 2019 general elections and how they fair in comparison to their peers. We also run few machine learning algorithms to predict the winning candidates of the election and notice which factors contribute the most towards the predictions. 

Read the <a href = "https://medium.com/@tanwarkml/how-the-largest-democracy-in-the-world-voted-in-2019-2edb23f79a4e">article</a> for full story.

#### Project Summary

One of the objectives was to compare the winning polical party - Bharatiya Janata Party or BJP - with its peers. In the exploratory analysis, I found that BJP's candidates have more criminal cases and have lower education qualification as compared to other political parties who won majority of the seats. For all politcal parties, the gender ratio was skeweed towards men although there were some exceptions. Average age and representation of minorities were also almost similar across all politcal parties. The next step could be to look for statistical significance on different variables. 

To predict the winners, I used three classification algorithms - logistic regression, knn, and decision tree. The data was split into train and test with test data size 30%. Decision tree has the highest accuracy on the test set - 83%

#### Files used

LS_2.0.csv: The data file which will be used for the project. The dataset was created by Prakrut Chauhan and is also available <a href = "https://www.kaggle.com/prakrutchauhan/indian-candidates-for-general-election-2019">here</a>. The dataset was collected from myneta.info and <a href = "https://eci.gov.in/">Election Commision of India</a>. More description can be found at the kaggle link shared above

Project 1 - Indian Elections.ipynb: Jupyter notebook for the project.

README.md: Documentation file

mytree.dot: Text file for graphical representation of the decision tree

#### Installations required

<a href = "https://numpy.org/"> numpy </a>, <a href = "https://pandas.pydata.org/">pandas </a>, <a href = "https://matplotlib.org/">matplotlib</a>, <a href = "https://scikit-learn.org/stable/">sklearn </a>, and <a href = "https://www.graphviz.org/">graphviz</a>


#### Acknowledgments
As described above, original dataset can be found <a href = "https://www.kaggle.com/prakrutchauhan/indian-candidates-for-general-election-2019">here</a>. If you do like the project, please give a shotout to Prakrut Chauhan too!
Some visusalizatio code used in the notebook was inspired by <a href="https://chrisalbon.com/">. It's an amazing resource for machine learning so do check it out.
