# Phishing Website Detector

![alt text](https://www.nextadvisor.com/blog/wp-content/uploads/2017/05/bigstock-Phishing-website-92767220.jpg)

### What is Phishing?
Fraudsters send fake emails or set up fake web sites that mimic Yahoo!'s sign-in pages (or the sign-in pages of other trusted companies, such as eBay or PayPal) to trick you into disclosing your user name and password. This practice is sometimes referred to as "phishing" — a play on the word "fishing" — because the fraudster is fishing for your private account information.

### Website Phishing
Phishing websites are created to dupe unsuspecting users into thinking they are on a legitimate site. The criminals will spend a lot of time making the site seem as credible as possible and many sites will appear almost indistinguishable from the real thing.

### Background of Problem Statement :
The goal is to use one or more of the classification algorithms to train a model on the phishing website data set, which calculates the accuracy score on the test data. and to find which model gives the best accuracy score to predict if a website is a phishing website or not.

### About the Dataset
Its a collection of website URLs for 11000+ websites. Each sample has 30 website parameters(features) and a class label(target) identifying it as a phishing website or not (1 or -1).

### Brief Description of the features in data set

● UsingIP (categorical - signed numeric) : { -1,1 } ● LongURL (categorical - signed numeric) : { 1,0,-1 } ● ShortURL (categorical - signed numeric) : { 1,-1 } ● Symbol@ (categorical - signed numeric) : { 1,-1 } ● Redirecting// (categorical - signed numeric) : { -1,1 } ● PrefixSuffix- (categorical - signed numeric) : { -1,1 } ● SubDomains (categorical - signed numeric) : { -1,0,1 } ● HTTPS (categorical - signed numeric) : { -1,1,0 } ● DomainRegLen (categorical - signed numeric) : { -1,1 } ● Favicon (categorical - signed numeric) : { 1,-1 } ● NonStdPort (categorical - signed numeric) : { 1,-1 } ● HTTPSDomainURL (categorical - signed numeric) : { -1,1 } ● RequestURL (categorical - signed numeric) : { 1,-1 } ● AnchorURL (categorical - signed numeric) : { -1,0,1 }

### Link to the Dataset- 
https://www.kaggle.com/eswarchandt/phishing-website-detector

### Installation
Install the latest version of Anaconda for python 3 from this link (https://repo.anaconda.com/archive/) ,once you open the link, you'll find a long list of installers, choose the latest version and download the relevent OS installer and install it.

To download the ipynb file from GitHub-

* Click on Raw
* Then, press ctrl+s to save it as .ipynb
* Open jupyter notebook
* Go to location where you saved .ipynb file
* Open that file and start executing

### Usage

As Website Phishing is a very serious issue, we need to be cautious before we share our personal information with any website for that matter.This project is to develop a model which predicts if a website is a phishing website or not. In this notebook I have implemented three classification algorithms(Logistic Regression, Random Forest Classifier, Neural Networks).From all the models developed , Neural Networks accuracy has highest accuracy that is 100% and followed by Random Forest Classifier and Logistic Regression. So, neural networks would best predict if a website is a phishing website or not.
 

