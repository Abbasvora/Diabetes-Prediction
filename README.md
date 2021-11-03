# Diabetes

## Tools Used

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sikit Learn

## Dataset

The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.

![Screenshot (269)](/assets/Screenshot%20(269).png)

During EDA we get to know that patients with high amount of Glucose have higher chances of beeing  Diabetic

![Screenshot (275)](/assets/Screenshot%20(275).png)

![Screenshot (277)](/assets/Screenshot%20(277).png)



## Algorithm

### KNeighborsClassifier

We use Euclidean distance to calculate nearest neighbour and based on smallest distance we can classify their class.

### Support Vector Classifier

SVM seeks the best decision boundary which separates two classes with the highest generalization ability.

Unlike logistic regression, which defines optimality by overall probability, SVM wants the smallest distance between data points and the decision boundary to be as large as possible. In other words, if you imagine the decision boundary as the central line of a street, SVM prefers an 8-line highway rather than a country road. The width of the street is called the margin.

## Result

#### KNeighborsClassifier

Using `n_neighbour= 26` in our model we get an **accuracy of 84.26%**

![Screenshot (270)](/assets/Screenshot%20(270).png)

Confusion Matrix

![Screenshot (272)](/assets/Screenshot%20(272).png)

#### Support Vector Classifier

Using `C=0.03` in our model we get an **accuracy of 77.92%**

![Screenshot (273)](/assets/Screenshot%20(273).png)

Confusion Matrix

![Screenshot (274)](/assets/Screenshot%20(274).png)