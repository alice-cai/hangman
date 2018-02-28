# hangman
This is a word guessing game written in Turing.

The program selects a secret word from a given list that the user must guess by entering one
letter at a time. Each time they guess a letter, they lose 10 of their 100 points. They have the
option of guessing the entire word at any given time by entering "!" instead of a letter, but if
they guess incorrectly, they lose all their remaining points. If they guess correctly, they gain
10 points! If they're stuck, they can also enter "?" to get a word hint, but this will cost them
20 of their points. Once they have no remaining points, they will be forced to guess the entire
word. In any case, they gain 10 extra points if they guess the secret word correctly. At the end
of each game, they are given the option to play again with 100 new points and a new secret word.
