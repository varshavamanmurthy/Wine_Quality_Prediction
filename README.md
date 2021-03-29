# Wine_Quality_Prediction

1.	Abstract:

Wine is one of the most consumed alcoholic beverages in the world. It is renowned not only for its taste, smell, and color but also for its quality, depending on how old or new the wine is. Winemaking can be both interesting and challenging at the same time. Winemakers usually enjoy working in their wineries, sorting the different types of grapes to come up with unique and best quality wines to suit the diverse palate. Hence, choosing wine based on its quality can be a convoluted issue. However, manually tasting all of them and determining the quality can be a time-consuming task. This is where the need for machine learning techniques comes into the picture, mainly for selecting the best quality wine with accuracy. Wine quality can be classified into high or low, good or bad using the machine learning classification approach. Moreover, we can determine the physico-chemical factors which affect the making of good quality wine by using the regression analysis. The goal of this project is to classify and predict the quality of the wine, based on significant feature variables which will be evaluated through the course of our project. We hope that this evaluation will help the winemakers to understand the chemical concentration of the wine to increase its quality to a higher standard. Along with this, the novice wine enthusiasts can also figure out the quality of wine that they are indulging into. This approach can be beneficial to the wine industry as a whole to improve their business. 


2.	Motivation for the project:

Wine making is a complicated process that consists of many steps and chemical composition. Steps like harvesting and crushing are performed manually, but when it comes to fermentation and clarification, we noticed that the right proportion of different ingredients/chemicals are very important, which can further help us in determining the quality of the wine. The entire winemaking process is very time-consuming and needs a lot of iteration, as sometimes the proportions are not accurate. This cost a lot of money and effort. Our inspiration came from knowing the above issue, and we thought about using machine learning algorithms to train the system based on the available data about wine and make suggestions based on that. This will help both manufacturers and the consumers in producing and selecting the good quality wine.


3.	Brief literature survey: 

a. In one of the previous research papers [D Nguyen, Red Wine Quality Prediction Using Regression Modeling and Machine Learning] the authors have used University of California, Irvine wine dataset. Probability plots such as QQ plots have been utilized, which further determines that the need for pre-processing is not necessary. Additionally, Certain three-dimensional plots have been exploited to determine the relationships within independent variables and also the quality of the wine. Furthermore, two models were built, one based on the selection and regularization and the other on multilinear regression for an optimal prediction for the quality of the red wine. The paper focuses on the quality of red wine with the properties like sulfur dioxide, total sulfur dioxide, Density, PH etc.
 
b. The other paper [Chao Ye, Ke Li, and Guo-zhu Jia, A new red wine prediction framework using machine learning] talked about the data set taken from the University of Minho. They used the boosting algorithm, light bgm algorithm, and proposed an MF-DCCA framework. Also, they make use of objective testings like the Cross-correlation Test, Multifractal detrended Cross-correlation Analysis, Rolling Windows Analysis, and Classification Algorithm Analysis. This paper got the results based on the significant tests and classification of the accuracy is achieved through the ml algorithms mentioned.
 
Our background research found that one paper does the classification, and the other paper does the regression analysis. It is observed that the analysis has been done only on the red wine dataset but not on the white wine dataset. Moreover, In the previous papers, there were no comparisons done with red wine to any other wines. We have taken an approach to combine both classification and regression techniques of machine learning to determine the quality of the wine based on the physicochemical properties used by comparing them to find out which model gives the best accuracy model.


4.	Methodology:

The aim of our project is to determine the quality of wine. In our project we plan to take an approach not only to predict the quality of the wine depending on its physicochemical properties but also to determine whether that quality of the wine is “good” or “bad”. To achieve this outcome, we will take the help of several classification and regression algorithms available in the machine learning libraries.
Hence, our project methodology is divided into two sections:
 
      I.       Regression approach
     II.      Classification approach
 
For regression approach: This section of our project will deal with identifying the quality rank of the wine, depending upon the important physicochemical factors present in the wine. We will use the regression technique to predict the quality using:
 
·       Decision Tree Regression
·       Random Forest Regression 
·       Support Vector Machines Regression
 
We will train our model with our training dataset separately using all of the mentioned algorithms and then test the accuracy of the model using our test dataset. We are hopeful to achieve certain accurate predictions of the wine quality once the model is trained with each of these algorithms. As we will be using several algorithms for this prediction, we will come up with a comparative discussion and conclude the most suited regression algorithm for this kind of wine dataset to predict the wine quality if its input feature variables are known.
 
For classification approach: For this section of our project, we will take the help of some popular classification techniques of machine learning in order to identify the wine quality like:
 
·       Logistic regression
·       Naive Bayes classification
·       Decision tree classification
·       Random forest classification
·       Support vector machines classification
 
Here also, we will train our model with our training dataset separately using all of these algorithms and then test the accuracy of the model using our test dataset. We will follow the similar approach taken in regression. We will try to arrive at the most accurate algorithm by a comparative analysis on the accuracy of the above-mentioned algorithms. 
 
Additionally, we will also conduct an experiment to determine the important features which affect the wine quality. We hope to achieve this using feature importance and come up with a list of top physicochemical properties whose levels in the wine determine the quality of the wine effectively. During the course of this project, we might take into consideration some more classification or regression algorithms if we see fit to train our model. At the end of this experiment, we will come up with a result stating which algorithm(s) are best to identify the wine quality and also a list of features determining the wine quality.

5.	Deliverables:

As we will be using different algorithms to classify and predict the quality of wine, our main deliverables will include but not limit to:
1.	Identification of the quality of wine by classifying it as “good” wine or “bad” wine using classification techniques.
2.	Predicting the wine quality based on the important physicochemical properties mentioned in the dataset.
3.	We will also try to present the data of our project through data visualization and other charts to showcase the important features and their correlations with our target variable.
4.	Creation of a comprehensive project report based on the research and expected outcomes from the project.
 
Milestones:

•	Searching and finalizing relevant datasets required for the project.
•	Analyzing the data from the obtained datasets (Kaggle), mainly for data mining.
•	Training and testing our model with the help of machine learning algorithms (as mentioned in the methodology section) to qualify wine as “good” or “bad”, based on the prediction.
•	Comparison of applied machine learning models and procurement of the best model with accurate prediction.
•	Creating a data visualization using our date set to showcase its properties.
•	Creation of a summative project report with relevant references.

6.	Team members and their roles:

i.	Shinjini Gupta
ii.	Sonam Barsainya
iii.	Tejaswini Yegurla
iv.	Varsha Vaman Murthy

Pre-processing of the data is done with collaboration. Each team member will work on two different machine learning algorithms (as mentioned in the methodology section). Finally, data visualization will be done with the help of Tableau and python packages.


7.	Relevant information about our project:

We read multiple research papers as motivation and reference to our project which are stated below.
 
1)	D Nguyen, Red Wine Quality Prediction Using Regression Modeling and Machine Learning https://towardsdatascience.com/red-wine-quality-prediction-using-regression-modeling-and-machine-learning-7a3e2c3e1f46

2)	Chao Ye, Ke Li, and Guo-zhu Jia, A new red wine prediction framework using machine learning https://iopscience.iop.org/article/10.1088/1742-6596/1684/1/012067/meta

3)	S. Kumar, K. Agrawal and N. Mandan, Red Wine Quality Prediction Using Machine Learning Techniques https://ieeexplore.ieee.org/abstract/document/9104095

4)	Paulo Cortez, António Cerdeira, Fernando Almeida, Telmo Matos, José Reis, Modeling wine preferences by data mining from physicochemical properties. https://www.sciencedirect.com/science/article/abs/pii/S0167923609001377



