# Empowering-Investors-Hackathon

#### Team Name  
Beta-L
#### Problem Statement  
Investors face the risk of encountering deceptive investment claims from self-proclaimed influencers on digital platforms, potentially leading to financial losses and reputational harm. These influencers may have vested interests in promoting certain products or earning commissions.

#### Team Leader Email -sriramulu.appana@alumni.ipl.edu.in

## A Brief of the Prototype:


The rise of digital platforms has led to an alarming increase in misleading investment claims. These claims, often made by self-proclaimed influencers, can have serious financial repercussions for unsuspecting investors. Our solution targets this issue by leveraging advanced technologies like Gen Ai and Machine Learning to detect and flag these misleading claims.

We collected the Data  by gathering claim data from a variety of sources. These sources include popular social media platforms such as Facebook, Twitter, Instagram and YouTube.Once we have the data, we use natural language processing techniques to extract relevant information from these claims. We also performed sentiment analysis on user comments to gauge the perceived trustworthiness of influencers. This analysis provides valuable insights into the overall sentiment around the claims being made.

The advanced functionality is achieved by applying machine learning techniques to analyze the claim data and assign credibility scores to both claims and influencers. We considered various features and factors to ensure the accuracy of our credibility scores. These scores enable us to rank influencers based on their credibility, empowering users to make informed decisions.

In addition to the above features, We offer real-time monitoring of influencers' posts and claims. This means immediate identification of potentially misleading content, ensuring that investors are protected in real-time.

To make the insights easily accessible, we've designed an interactive dashboard. The dashboard displays the results of our analysis in a user-friendly way, utilizing graphs, charts, and metrics. This empowers users to quickly assess the credibility of influencers and claims.


 

## Tech Stack: 
  
 Technologies used to Build the prototype
  Programming Language: Python
  Framework for the web crawler: Scrapy,BeautifulSoup
  Library for NLP tasks: NLTK
  Library for ML tasks: Scikit-learn
  Library for Deep Learning Models: TensorFlow
  Framework for the web application: Flask
  User Interface: HTML,CSS
  Data Visualization: Plotly
  Database: MySQL

   
## Step-by-Step Code Execution Instructions:

For data collection,We can run the web_scrapping code to get the data from various social websites and load into Azure sql database.We had  the data collected from various sources stored in the azure blob storage.

##Packages to be Installed:

!pip install pandas mysql-connector-python 
!pip install pytube
Tensorflow.python.keras.models
tensorflow.python.keras.layers

By running the colab notebooks inside the Ml_codes folder.We will get the credibility scores of the influencers.

#clone this repository

https://github.com/samyatitech/betal.git

#create a virtual environment 

Python -m venv [name]

#activate virtual environment 

[name]/Scripts/activate

#installing necessary libraries

pip install Flask 
pip install pandas
pip install plotly
pip install numpy  matplotlib  sklearn tensorflow
pip install nltk

#run the base python file in terminal (or) CMD

python app.py

  
## What I Learned:
   One of the biggest learnings we had while developing the prototype was how to use Gen AI and Machine Learning techniques to analyze and evaluate the credibility of influencers and their claims on digital platforms related to investment or trading in the securities market. We learned how to use libraries such as TensorFlow, NLTK, Scikit-learn, etc. to create and train models that can perform tasks such as sentiment analysis, text classification, text summarization, text generation, etc. We also learned how to use various features that are relevant for assessing the credibility of an influencer or a claim in this domain, such as whether the influencer is registered as an advisor with SEBI, whether they follow SEBI’s registered advisor guidelines, whether they have any action pending from SEBI, whether they disclose any commission or conflict of interest, whether they provide evidence or references for their claim, whether they have a consistent track record of performance, whether they have a large and engaged following, etc. We found this learning very interesting and challenging, as it involved applying domain knowledge and expertise, as well as using state-of-the-art technologies and methods.


