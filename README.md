Introduction
------------

This test is based on the famous [Hangman Game](http://en.wikipedia.org/wiki/Hangman_(game)).
Your task is to write a program to play Hangman, guessing words from a list of English Words.

### Our Expectations

Through this programming test, you should be able to demonstrate:

* Good understanding of the programming language you use.
* Good programming practices. Code quality and maintainability.
* Apply suitable algorithms to solve problems.
* Creativity.

The Game Flow and Specification
--------------------------------
You can download a list of English Words [here](http://dreamsteep.com/projects/the-english-open-word-list.html), this will be the "dictionary" you are going to work with. The goal is, for any given word randomly chosen from the list, to develop a method with the highest probability to find out what the given word is.

How you will be scored
--------------------------------
80 words will be randomly selected from the words list, with:

20 words: length <= 5 letters

20 words : length <= 8 letters

20 words : length <= 12 letters

20 words : length > 12 letters

And your program will be run againt 10 sets of such words, with the score being the average number of words it guessed with **5 attempts** (if you get the letter right with one guess, it does not count toward the attempts). You can only guess ONE letter with each attempt.

For an example on how to play the game refer to [this gist](https://gist.github.com/JDLeigh10/3029383#file-hangman-rb). Note you will need to install ruby on your computer and supply a dictionary file in order to run this program. Your program will be run against a modified version of this program, in a similar manner, so make sure to provide instructions on how to start your program.

If you have further questions, feel free to contact me. Good luck!