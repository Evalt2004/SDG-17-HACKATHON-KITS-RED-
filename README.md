                                              # SDG-17-HACKATHON-KITS-RED
                     This Repository Contains the work Summary And Work done in the SDG-17 Hakathon
![image](https://user-images.githubusercontent.com/116806974/223617391-70febe0d-98ca-4600-85da-126bc23bc888.png)
Name : Evalt David R

URK22CS1200

<img width="473" alt="image" src="https://user-images.githubusercontent.com/116806974/223620847-f7ffe30a-bfee-43c5-9eb2-824c95ff2a9c.png">

Session 1 - Introducing Pandas Objects

Colab Link Provided to Learn. - https://colab.research.google.com/drive/1avlURUdoWar4CtDAJQJScDSIre8H-Ad1?usp=sharing  

COLLAB Worked on: https://colab.research.google.com/drive/1p471oC-aOPRSTpn8WZoW8JD0_mBWGlG6#scrollTo=wKd7YVbWmLxQ
<img width="1032" alt="image" src="https://user-images.githubusercontent.com/116806974/223619198-ff78514f-145b-47a3-a4a0-1d1ed60871df.png">

Datasets provided for session 1

toyota.csv

https://drive.google.com/file/d/1M_xRNd4XVOyQQtp4uwIjAIT8x3kmTcxs/view

Emp_EDA.Csv

https://drive.google.com/file/d/1d87-xe9ErDjdUfu17PvZ3xWba7HzrxdQ/view?usp=drive_web&authuser=0

Emp.visu.csv

https://drive.google.com/file/d/1HztMWEM_aFJ-9LttLv6hbh4SiD4I--55/view?usp=drive_web&authuser=0

Assessment - 1( Session 1)
Using the Titanic_visu.csv file plot the following graphs and state your inference from each of them:

1. Draw a bar chart with Embarked and its count (use different colors for each team)
2. Draw a comparative bar chart for Fare and New_Fare against each person (first 15
persons)
3. Draw a horizontal bar chart for Embarked and Fare
4. Draw a stacked bar chart for Fare and New_Fare against the person (first 10 persons)
5. Draw a pie chart with Passenger class and its count
6. Draw the dot plot between person and age (first 15 persons)
7. Draw the line plot between Age and Concession. Observe the trend line.
8. Draw the scatter plot between Fare and New_Fare. Observe the correlation
9. Draw the scatter plot between Age and Fare. Observe the correlation
10. Draw the box plot to show the statistical summary of Age column and verify with
describe()
11. Draw the histogram plot for Concession column
12. Draw the histogram plot for Concession column with bin value and PDF


Data Set provided (Titanic_visu.xlsv)

https://drive.google.com/file/d/10Wp8p9bFLjXihyoRIbxhf0hT1FjazyZF/view?usp=drive_web&authuser=0

COLAB LINK WORKED ON :

https://colab.research.google.com/drive/1TMhilYBJo--cP7jR6qCVX4ZxzaRip7Xg






<img width="306" alt="image" src="https://user-images.githubusercontent.com/116806974/223621003-e97a20c5-971c-4b0f-b4aa-b1586a8c3652.png">

TOPIC 1 

<img width="236" alt="image" src="https://user-images.githubusercontent.com/116806974/223622635-f4c8a915-90e9-42cf-90b5-1c3be013d626.png">


Regression analysis is a statistical technique used to model the relationship between variables. In coding, there are many libraries and frameworks that can be used to perform regression analysis, including:

Python: NumPy, Pandas, Scikit-learn, Statsmodels, TensorFlow, Keras, PyTorch
R: lm(), glm(), ggplot2, caret, randomForest, h2o.ai, dplyr
Matlab: Regression Learner App, fitlm(), regress(), ridge()


import numpy as np


EXAMPLE

x = np.random.rand(100)
y = 2*x + 1 + np.random.randn(100)*0.2

A = np.vstack([x, np.ones(len(x))]).T
m, c = np.linalg.lstsq(A, y, rcond=None)[0]

print("Slope = {}, Intercept = {}".format(m, c))

..



Colab Link Given:

https://colab.research.google.com/drive/1gJYSL24754yS0R2zc1I2ddv4ijalaPmp?usp=sharing

Dataset Provided:

https://drive.google.com/file/d/1Qs7SkmkiOkrP1OY13KoNHLqOXspptnR1/view?usp=drive_web&authuser=0

Colab Link Worked on:

https://colab.research.google.com/drive/1JcJw7kXCL-sAU7sn9iwh4k-wKfqwZTEC

TOPIC 2

![image](https://user-images.githubusercontent.com/116806974/223622480-49405ff2-05fc-460f-94a3-90ca7ad88c96.png)


KNN and K-Means:


KNN (K-Nearest Neighbors) and K-Means are two popular machine learning algorithms used for classification and clustering tasks, respectively.

KNN is a classification algorithm that works by finding the k nearest data points to a given test data point and assigning it the label of the majority class among those k nearest neighbors. The value of k is a hyperparameter that can be tuned to optimize performance. Here's an example of how to use the KNeighborsClassifier class from Scikit-learn to perform KNN classification:


from sklearn.neighbors import KNeighborsClassifier
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split

iris = load_iris()
X, y = iris.data, iris.target

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.3, random_state=42)


knn = KNeighborsClassifier(n_neighbors=5)


knn.fit(X_train, y_train)

accuracy = knn.score(X_test, y_test)

print("Accuracy: {:.2f}%".format(accuracy * 100))


..


Colab Link Given:

https://colab.research.google.com/drive/1jBEASoTv_udmTQlffJgk_vmIv3xM9Lrm?usp=sharing

Dataset Provided:

Cancer.csv

https://drive.google.com/file/d/1mFET-UxBqJMfhbDHk0gyv0UMgtLhPppd/view?usp=drive_web&authuser=0

Mall_Customer.csv

https://drive.google.com/file/d/1hGiPV12IwMYEK8W-xJMmEkaY2t85_72w/view?usp=drive_web&authuser=0

COLAB LINK WORKED ON:

https://colab.research.google.com/drive/1jk0Mqp--V8icGRiHlnsMRMgYxH-Q3bS6



TOPIC 3


Performance Metrics:


Colab link Given:

https://colab.research.google.com/drive/1w2fzfAI_YVUJ6QCZVtTLxIlffd9xYB5-?usp=sharing


Dataset provided

Income.data.csv

https://drive.google.com/file/d/1wcHMQQUq44ZzE0Idz1Ck03GMQYrKHix4/view?usp=drive_web&authuser=0


Colab link Worked ON:

https://colab.research.google.com/drive/1nqEvOPYD0QNxS8af8kkdMJ-I1KMQre0w


Assessment - 2

![image](https://user-images.githubusercontent.com/116806974/223623667-d3741eb6-3bee-4d27-9c0b-f0fc18b76e1f.png)


Group - 2:
Develop the linear regression model for the heart disease dataset using the scikit-learn
a. Divide the data into training (75%) and testing set (25%)
b. Analyse the impact of smoking to the heart disease and display the intercept and
regression coefficients
c. Predict the y value (y’) for the testing set (x)
d. Analyse the performance metrics with the actual value (y) and predicted values (y’)


Dataset Provided:

Heart.data.csv

https://drive.google.com/file/d/1Tt-6dyNQH-bwD8ksEoG55IHXnsgl5zoY/view?usp=drive_web&authuser=0


COLLAB LINK Worked ON:

https://colab.research.google.com/drive/1NQArcRRFOTa328j8UYZ6mGdlBoPGWqUa


<img width="191" alt="image" src="https://user-images.githubusercontent.com/116806974/223624765-8999761b-409f-4f24-8ebc-8ae116c4e21d.png">


![image](https://user-images.githubusercontent.com/116806974/223686614-48a181ee-3a1f-467f-9797-e0cf9274c7e6.png)

SESSION 1 

IDEAS , MOTIVATIONS SHARED BY PRATISHKA MORE CEO & FOUNDER AT SUSTAINABILITY 101

LINKEDIN - https://www.linkedin.com/in/pratikshamore18

SESSION 2 - HANDS ON WORK SESSION

ANALYZING THE DATA 

https://colab.research.google.com/drive/1jVEmkVVHS2NwzRDE7Je2mUfeIP4fwAkf#scrollTo=__4ICy6SmTqJ

DATA SET CHART 

https://colab.research.google.com/drive/1j8AvNehsSmFykF4W-WQkjazs2Cw_5wXB#scrollTo=L3WUrstLnCtz

PERFORMANCE MATRIX

https://colab.research.google.com/drive/1nqEvOPYD0QNxS8af8kkdMJ-I1KMQre0w#scrollTo=7CjFR_udosXO


Datasets Used

HALElifeExpectancyAtBirth.csv


HALeWHOregionLifeExpectancyAtBirth.csv


lifeExpectancyAtBirth.csv


NOTE.txt


WHOregionLifeExpectancyAtBirth.csv


Mainly Used

ofHaleInLifeExpectancy.csv














