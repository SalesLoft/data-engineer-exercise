# Salesloft Data Engineer Exercise

Welcome to the Salesloft Data Engineer offline exercise. This offline exercise is intended to simulate real world conditions of what the role of a data engineer looks like at Salesloft. In particular it covers:
* Sourcing, modeling, and transforming data
* Using tools similar to what we use internally at Salesloft
* Generating a meaningful deliverable at the end

## Overall Guidance

* The exercise is due back within 5 days of receipt
    * We are not asking you spend every hour within those 5 days on this project. It is intended to take around 5-7 hours of actual working time. 
* If you don’t finish within those 5 days, send what you have
* If you have questions along the way, don't hesitate to ask 
* There is not a particular answer we are looking for. Rather we wish to see what design decisions you make and how you deal with tradeoffs of those decisions
* You may employ any modeling concepts you wish - feel free to be creative if you imagine that a particular use case or analytical pattern would require it. Just be sure to indicate why you made those decisions. 


## Exercise Details

Stack Overflow is an open community for anyone that writes, reads, or reviews code. It helps members get answers to some of their toughest questions, share knowledge, and find their next dream job. 

In this exercise, we’d like to play the part of a Stack Overflow stakeholder asking a question of their data. 

> What questions are popular and trending, but not being answered? 

To accomplish this - we’d like you to make use of the following tool set. These are either open source or have free trials

* Google Big Query (https://cloud.google.com/bigquery/docs/sandbox)
* dbt (the CLI should be fine for this project, but if you want to deploy it to the cloud feel free 🙂 , https://www.getdbt.com/signup/)
* Github (https://github.com/)
* The publicly available StackOverlow data set (https://cloud.google.com/blog/products/gcp/google-bigquery-public-datasets-now-include-stack-overflow-q-a)
    * You can find an ERD of the overall data set here (https://sedeschema.github.io/)



## Exercise Deliverables

* A dbt project created, developed and tested to a standard you think a data consumer would expect in the time frame allotted. Stored in a public Github repository. 
* A Google BigQuery data set, populated with data from the stack overflow sample data set and modeled with dbt to answer the question posed above. 
* A data model diagram that provides a visual representation of your data model

## Submission Guidelines

* Please respond to your recruiter with the data model diagram and a link to the Github repository. 
