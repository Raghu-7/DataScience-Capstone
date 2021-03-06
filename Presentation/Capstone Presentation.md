Next Word Prediction Application
========================================================
author: Raghu
date: April 7, 2019
autosize: true
<img src="logos.png"; float:bottom;"> 

Develop the App model
========================================================

- App involves creating an algorithm for predicting the next word using one or more words as text input

- A large corpus of blog, news and twitter data is created and loaded 

- N-grams are extracted from the corpus and used to build a predictive model 

Algorithm for App
========================================================

- Dataset is cleaned by removing weblinks, twitter handles, punctuations, numbers, symbols, extra whitespaces etc

- Matrices from unigram to quadgram are extracted using RWeka 

- N-gram model with stupid back-off strategy is used

Shiny App interface
========================================================

- A text input box is provided for user to type a word/phrase

- Based on input words the application predicts the next word reactively

- Predicts using the longest, most frequent, matching N-gram

App and resources
========================================================

- Application can be viewed at: https://raghu-7.shinyapps.io/ShinyApp

- Github link for Capstone project files: https://github.com/Raghu-7/DataScience-Capstone

- Milestone Project presentation can be found at: http://rpubs.com/Raghavendra/482870
