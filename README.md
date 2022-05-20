# Python-Wordle-Clone
Python Wordle This is a python implementation of the popular word guessing game  Wordle. It uses a predefined list of words from a dictionary, generates the index for the random word, and removes the word from the word list so that no duplicate word is generated.


# Dependencies
- `words.py` - the module containing the list of words
- `Rich` - used for GUI implementation

# Instructions
The original Wordle game (created by [Josh Wardle](https://powerlanguage.co.uk/)) 
is a simple word guessing game where a player has a maximum of
6 attempts to guess a single 5 letter word. If a letter is in
the word but not in the right spot, the letter has a yellow
background color. If a letter is both in the word **and** in the
right spot then it has a green background color. Otherwise, the 
letter does not have a background color.
