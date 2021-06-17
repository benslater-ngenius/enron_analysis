# Enron Anaylsis


### Contents
Exploratory Data Analysis
Pre-process/clean up the data if needed
Basic statistics to help understand the dataset
Explore and present initial insights found from the data
Use visualisation tools to help presentation of the insights
 Find an interesting area to further explore the dataset, e.g., topics modelling and clustering

### Background
In 2000, Enron was one of the largest companies in the United States. By 2002, it had collapsed into bankruptcy due to widespread corporate fraud. In the resulting Federal investigation, there was a significant amount of typically confidential information entered into public record, including tens of thousands of emails and detailed financial data for top executives. In this project, you will play detective, and put your new skills to use by building a person of interest identifier based on financial and email data made public as a result of the Enron scandal. To assist you in your detective work, we've combined this data with a hand-generated list of persons of interest in the fraud case, which means individuals who were indicted, reached a settlement, or plea deal with the government, or testified in exchange for prosecution immunity.


### Summary
A topic modeling tool takes a single text (or corpus) and looks for patterns in the use of words … A topic to the computer is a list of words that occur in statistically meaningful ways.

We plan to find themes of the emails sent by groupoing similar emails into topics and finding the most message sent for that topic. Before we look at the breakdown of the messages, such as time of sending, the distrubition of the people who have sent the messages. The aim is to find split the emails by topics to minimise the amount of human processing needed to find the root cause of the fraud scheme of the Enron company. As 500'000 emails is alot of go through. Tracking the people responsible and the contents of the emails, through the messages sent requires filtering. 

LDA is a topic modelling tool to find grouping of similar words in documents and grouping them up. By transforming the messages into vectors to represent the message and then grouping similar vectors in dimension together. 

We are able to show what similar messages are linked, who sent them and the themes and types of words that will be in them. 

## Dataset

The CSV file of the data can be found at: 
https://www.kaggle.com/wcukierski/enron-email-dataset?select=emails.csv
