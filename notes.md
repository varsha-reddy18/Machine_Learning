**Why machine learning**



**Real-life examples:**



1\) E-commerce

2\) social Media

3)Banking

4\) Health care



**what is machine Learning**



Machine Learning is a subset of AI that allows computers to learn patterns from data and make predictions or decisions without being explicitly programmed



**Types of machine learning**



1)Supervised :(labeled) model learns from labeled data(input \& output pairs)



eg: predicting house process based on area, location, and rooms



Use Cases:

\* Spam Detection

\* Fraud Detection

\* Sales Forecasting



2\) Unsupervised : (Unlabeled )The model identifies hidden patterns in unlabeled data



eg: grouping customers into segments based on their behavior



Use Cases:

Customer segmentation

Anomaly Detection

Recommendation Systems



3\) Reinforcement :Reinforcement learning interacts with environment and learn from them based on rewards



Supervised Algorithms are divided into 2 types



classification: where the goal is to predict discrete labels or categories (text)

deals with categorical data



Regression: where the aim is to predict continuous numerical values

deals with numerical data



**what is a model in machine learning?**



A model in machine learning is a mathematical representation of the relationship btw i/p(features) and o/p data(labels)

&nbsp;

y=f(x) in mathematics 



**Components of a Model**



**1.parameters:** values learned during training

--> parameters = learned values



**2. Hyperparameters:** we set before training

the model does not learn them; instead, we choose them

--> hyperparameters = model settings



**3. Model Structure:** This defines how the input are  combined or how the model is built

&nbsp;

linear model

decision tree

neural network

structure = shape/architecture of the model



**How does a model learn?**

A model learn by adjusting its  parameters based on the training data.



**during training:**

bad prediction -> adjust parameters

better prediction -> keep adjusting

finally 



Loss function(Error)

&nbsp;A loss function tells us how wrong the models prediction is

Small loss -> good prediction

Large loss -> bad prediction



Optimization Goal



**Machine Learning Life Cycle**

  

problem framing -> data collection \& preparation -> data splitting(Train/Test)->

modeling(Train) -> Evaluation(Test) -> Deployment



1.Problem Framing(Imp step)



mean:  clearly understand what problem you want to solve using ml



2\. Data Collection \& Preparation



mean : collect and clean data based on the problem definition



activities:

Collect data

Handle missing values

Remove noise \& duplicates

convert data into usable format

good data -> good model



3\. What are Training and Testing Data



Training Data



used to teach the model

model learns slope, intercept, weights, patterns

this is the practice material



Testing Data



Used to evaluate the model

Model has never seen this data before

this is the exam paper



4\. Modeling



choosing the appropriate model



Regression

&nbsp;   Basically, Regression is a statistical approach to find the correlations between variables(dependent and independent)

regression algorithms give you a continuous output





**2 types of regressions**



**1.Simple linear Regression**

one dependent and one independent 

y = mx+c// y=b0+b1x1



How to find the best fit line?

&nbsp;How to improve the model?

&nbsp; \* Normalize

&nbsp; \* remove outlier



**2. Multi Linear Regression**

it is same like simple linear regression the difference is here we use more than one independent variable



y=b0+b1\*x1+b2\*x2+......+bn\*xn







