# Chapter I

## 1. Classification Predictive Modeling
- Classfication is a predictive modeling problem that involves assigning a class label to each observaton. 
  - Binary Classification Problem: A classificaton predictive modeling problem where all examples belong to one of two classes. 
  - Multiclass Classification Problem: A classification predictve modeling problem where all examples belong to one of three or more classes
- When working on classification predictive modeling problems, we must collect a training dataset, including both the input data and the output data.

## 2. Imbalanced Classification Problems 
An imbalanced classification problem: an example of a classification problem where the distribution of examples across the know classes is not equal. 
- Unbalanced classification: a class distribution that was balanced and is now no longer balanced. 
- Imbalanced classification: a class distribution that is inherently not balanced.  
It is common to describe the imbalance of classes in a dataset in terms of a ratio. For example, an imbalanced binary classification problem with an imbalance of 1 to 100 means that for every one example in one class, there are 100 examples in the other class. 

## 3. Causes of Class Imbalance 
1. Biased data sampling and Measurement Errors -> can be improved by better sampling methods or correcting the measurement error. 
2. A property of the problem domain: the natural occurance or presence of one class may dominate other classes. This may be because the process that generates observations in one class is more expensive in time, cost, computation, or other resources. -> a model is required to learn the difference between the classes.

## 4. Challenge of Imbalanced Classification 
- Slight Imbalance: an imbalanced classification problem where the distribution of examples is uneven by a small amount in the training dataset. 
- Severe Imbalance: an imbalanced classification problem where the distribution of examples is uneven by a large amount in the training dataset (e.g. 1:100 or more)   
A severe imbalance of the classes can be challenging to model and may require the use of specialized techniques.   
The minority class is harder to predict because there are few examples of this class, meaning it is more challenging for a model to learn the characteristics of examples from this class and to differentiate examples from this class from the majority class.   
Most machine learning algorithms for classification predictive models are designed and demonstrated on problems that assume an equal distribution of classes.   
Imbalanced classification is not __solved__. It remains an open problem generally, and practically must be identified and addressed specifically for each training dataset. 

## 5. Examples of Imbalanced Classification
- Fraud Detection
- Claim Prediction
- Default Prediction
- Churn Prediction
- Span Detection
- Anomaly Detection
- Outlier Detection
- Intrusion Detection
- Conversion Prediction   
Notice that most, if not all, of the examples are likely binary classification problems. Notice too that examples from the minority class are rare, extreme, abnormal, or unusual in some way. 

## 6. Summary
- Imbalanced classification is the problem of classification when  there is an unequal distribution of classes in the training dataset.
- The imbalance in the class distribution may vary, but a severe imbalance is more challenging to model and may require specialized techniques. 
- Many real-world classification problems have an imbalanced class distribution such as fraud detection, spam detection, and churn prediction. 

