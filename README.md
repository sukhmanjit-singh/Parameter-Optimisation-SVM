# Parameter-Optimization-SVM
## Sampling Assignment

**Dataset Used:** [Wine Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/)

| Number of Instances:  | 4898 |
|-----------------------|--------|
| Number of Attributes: | 12    |

Two datasets are included, related to red and white vinho verde wine samples, from the north of Portugal. The goal is to model wine quality based on physicochemical tests (see [Cortez et al., 2009], http://www3.dsi.uminho.pt/pcortez/wine/).

## Dataset Characteristics
Multivariate

## Subject Area
Business

## Associated Tasks
Classification, Regression

## Attribute Type
Real


## Attribute Information:

Input variables (based on physicochemical tests):
   1 - fixed acidity
   2 - volatile acidity
   3 - citric acid
   4 - residual sugar
   5 - chlorides
   6 - free sulfur dioxide
   7 - total sulfur dioxide
   8 - density
   9 - pH
   10 - sulphates
   11 - alcohol
Output variable (based on sensory data): 
   12 - quality (score between 0 and 10)

## Tasks Performed
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using randomisation for every sample and report best accuracy and best parameters
6. For the best sample plot the convergence graph


## Results

The best parameters of SVC for the given dataset are:
- Kernel : rbf
- C : 4.967958  
- Gamma : 0.311632   

The above parameter gave a maximum accuracy of 0.6625 .

### Convergence graph  : 

![image](https://user-images.githubusercontent.com/64249407/233207045-30830ff4-e22e-4ed7-935e-8b365f07eb28.png)

<img width="581" alt="Screenshot 2023-04-20 at 3 11 11 AM" src="https://user-images.githubusercontent.com/64249407/233207045-30830ff4-e22e-4ed7-935e-8b365f07eb28.png">



## Submission by :
**Name** : Sukhmanjit Singh
<br>
**Roll No** : 102003484


