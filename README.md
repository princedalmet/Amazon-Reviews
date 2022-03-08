
# Project Title

Amazon-Reviews Mobile phone Reviews

![2](https://user-images.githubusercontent.com/99526815/157258194-2d6b9f03-4d1e-4587-881e-0f50fc4a5e45.PNG)
             
             Fig: 1 Shows different Sentiment 


## Motivation

Why some brands are so popular and why some brands are not doing well based, on review trying to under why some popular brands makes the difference and some other brands fall back.

## Sentiment Analysis of Mobile Phones reviews Using NLTK

Using this sentiment analysis I want to show that why some major brands are leading and some brands are not doing well. Based on review people try to convey a message that some brands are lacking based on their performance, feature as well as quality.


## Deployment

Importing libraries

Python

Jupyter notebook (label: good first issue)

Jupyter interactive notebook

Pandas (label: good first issue)
Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data. Frame objects, statistical functions, and much more.

numpy (label: good first issue)

    pip install numpy

It is the core library for scientific computing, which contains a powerful n-dimensional array object.

Scikit-learn is a machine learning library for Python.

    pip install scikit-learn

NLTK(Natural Language Toolkit)
The Natural Language Toolkit, or more commonly NLTK, is a suite of libraries and programs for symbolic and statistical natural language processing (NLP) for English written in the Python programming language.

    pip install nltk





## Running the tests

Reading csv File.
Since File was available on kaggle.
There are 4410 phone models in this data set.
There are 385 brands in this data set.

![3](https://user-images.githubusercontent.com/99526815/157258409-99e88dd9-81eb-4581-85b1-8a301eb2fa36.PNG)
        
        Fig: 2 Different types of Phone Company in the list 



## Cleaning data by removing rows having null values

General Description of data

![4](https://user-images.githubusercontent.com/99526815/157258441-6be2e537-e696-4793-8ac4-84bc3aa22aac.PNG)
   
      Fig: 3 Shows Min max Description 

Top 10 brands in the data set sorted on the basis of sum of Ratings.

![5](https://user-images.githubusercontent.com/99526815/157258473-d5d25cc9-2a9c-4dd5-9c91-4f7cf101dc51.PNG)
   
      Fig: 4 Shows Top Brands 

Correlation between price & rating

![6](https://user-images.githubusercontent.com/99526815/157258507-d3fe54c7-7fc4-49b6-b7b2-af6148309a57.PNG)
   
     Fig: 5 Shows different Price and Rating

Correlation between Price and Review Votes

![7](https://user-images.githubusercontent.com/99526815/157258543-4907c161-4d3c-4580-b853-0b83a72c2222.PNG)
    
      Fig: 6 Shows different Price and Review 

Correlation between Rating and Review Votes

![8](https://user-images.githubusercontent.com/99526815/157258600-9b275c01-5024-43f9-9ca7-fd1510c2180e.PNG)
   
      Fig: 7 Shows different Rating and Review

It is observed that Rating has a NEGATIVE CORRELATION with Review Votes = -0.046526

![9](https://user-images.githubusercontent.com/99526815/157258658-f2fed09a-8adc-4603-9cbe-cc64df93a7d9.PNG)
   
       Fig: 8 Shows different Rating 

It is observed that Rating has a POSITIVE CORRELATION with Price = 0.073948

![10](https://user-images.githubusercontent.com/99526815/157258691-677dfd37-3113-4776-b2be-20bf9fa9319a.PNG)
   
       Fig: 9 Shows different Rating of Positive

![11](https://user-images.githubusercontent.com/99526815/157258721-0bd4e403-5174-4530-b036-ddd5c6ac1381.PNG)
![12](https://user-images.githubusercontent.com/99526815/157258762-5a11aa9d-883a-46e7-860c-58f6ef0c8db6.PNG)    
   
       Fig: 10 Shows different item  

  
## NLTK function to find sentiment value and sentiment



![13](https://user-images.githubusercontent.com/99526815/157258790-bb57afe2-6594-4145-ba56-5e4aa6e3eea7.PNG)   
![14](https://user-images.githubusercontent.com/99526815/157258838-3e8d1f84-4cc1-49e3-923a-2596d7251241.PNG)   
![15](https://user-images.githubusercontent.com/99526815/157258877-4c80a9a5-402a-464a-b0a1-a7bf425d1337.PNG)  
    
       Fig: 11 Shows different Top brands Reviews 

![16](https://user-images.githubusercontent.com/99526815/157258924-12b177c8-7a4c-4262-9e1f-fc03fac070ff.PNG)
   
      Fig: 12 Shows different Sentiments 

![17](https://user-images.githubusercontent.com/99526815/157258957-eb1a9598-7003-4f79-b723-b8938cc93cba.PNG)
    
       Fig: 13 Shows different Accuracy 

![18](https://user-images.githubusercontent.com/99526815/157258985-215d552e-69c3-4a37-9dda-c42338aafec2.PNG)
   
       Fig: 14 Shows different intensity 


Observation: Sentiment variation is concentrated towards positivity

![19](https://user-images.githubusercontent.com/99526815/157259012-3fa613ad-3f71-4293-8e01-a75692d1f543.PNG)
    
       Fig: 15 Shows different sentiment based on positivity 

![20](https://user-images.githubusercontent.com/99526815/157259555-0c71537a-50ee-4b7a-a3fe-612e01ef8b7b.PNG)
   
       Fig: 16 Shows Bestselling Brands 

![21](https://user-images.githubusercontent.com/99526815/157259591-5493b90c-0c35-48b5-a22a-267c70a7457c.PNG)
   
       Fig: 17 Shows different product name and sentiment value 

![22](https://user-images.githubusercontent.com/99526815/157261945-7c2306d9-5067-43a9-80af-4e0c04326fe3.PNG)

      Fig: 18 Shows different Values 
  
Sentiment Analysis for Top 5 brands

![23](https://user-images.githubusercontent.com/99526815/157259821-0ff8529b-42d1-46a9-99cd-15d42b1653ea.PNG)
![24](https://user-images.githubusercontent.com/99526815/157259777-19238dd3-f299-42b5-b98a-d493b9891a56.PNG)
    
      Fig: 19 Shows different Sentiment  

Observation :

1. Sentiment concentration towards positivity decreases as we move from top to lower brands.
2. Population towards negativity and neutrality keeps on increasing as we move downwards.¶
