# Hangman_game
Finding a probabilistic graphical model of the popular game 'Hangman' using a large corpus of words. Project completed as part of homework 1 of CSE 250A of UCSD, CSE, Fall 2022. 

# Brief Description: 
Based on a probabilistic graphical model of the game 'Hangman' (for 5-letter words) we create a program where the best letter is predicted by the computer to be put in a given set of 5 boxes (some can be blank and the rest can be filled). The predictions are based on the occurrences of letters from a list of 5-letter words (including names and proper nouns) and their counts from a large corpus of Wall Street Journal articles (roughly three million sentences). 

For a detailed description of the model and a sample solution, please refer to the file 'Hangman_game.pdf'

# Files : 
1. hw1 word counts 05.txt: text file having a large corpus of 5-letter words based on which predictions will be made in the game.
2. part a.ipynb: Solves part a of the question which asks for printing the most and the least frequent words from the corpus.
3. part bc.ipynb: Code for the actual hangman game, based on part b of the question given in 'Hangman_game.pdf'.
4. Hangman_game.pdf: The detailed problem statement, with questions forming each part of the problem. A sample solution is also given.


# Execution :
Execute the parts that you want to solve from the given jupyter notebooks. You may have to run part a before running part bc. 
