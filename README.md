###### Phishing Website detector

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