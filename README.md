# Cleaning-Cornell-Movie-Corpus-dataset
This repository contains the steps of cleaning Cornell Movie corpus. the procedure which is given here can be applied to any kind of document data as well for texts cleaning.
Cornell movie corpus data set which contains more than 600 movies containing thousands of conversations between lots of characters. when you doownload this corpus it comes with different form of texts. the goal here is to clean the movies_lines and movie_lines for better use in training of some Deep natural language processing models such as seq2seq model. later we will compare both uncleaned and cleaned lines&conversations after preprocessing.

DATA PREPROCESSING STEPS:
1. Importing the libraries
2. Importing the dataset
3. Creating a dictionary that maps each line and its id
4. Creating a list of all of the conversations 
5. Getting separately the questions and the answers
6. Doing a first cleaning of the texts
7. Cleaning the questions
8. Cleaning the answers
9. Filtering out the questions and answers that are too short or too long
10. Creating a dictionary that maps each word to its number of occurrences
11. Creating two dictionaries that map the questions words and the answers words to a unique integer
12. Adding the last tokens to these two dictionaries
13. Creating the inverse dictionary of the answerswords2int dictionary
14. Adding the End Of String token to the end of every answer
15. Translating all the questions and the answers into integers and Replacing all the words that were filtered out by <OUT>
16. Sorting questions and answers by the length of questions.
  
  compare uncleaned data and cleaned one
