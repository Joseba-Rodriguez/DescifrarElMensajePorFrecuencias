# Cryptanalysis using Frequency Analysis

This Python code aims to perform cryptanalysis through frequency analysis of an encrypted message. The process is carried out in two main stages:

1. Counting the frequency of each letter in the encrypted message.
2. Substituting each letter in the encrypted message with the most common letter in the Spanish language.

The code starts by importing the Counter class from the collections module. Then, the variable `text` is defined with the encrypted message. The Counter function is used to count the frequency of each letter in the encrypted message, and the result is saved in the `letters` variable.

Next, the letters in the encrypted message are replaced with the most common letters in the Spanish language using the replace() function. Each letter in the encrypted message is replaced with the corresponding most common letter in the Spanish language. For example, the letter "X" is replaced with the letter "e" since "e" is the most common letter in the Spanish language.

Finally, the decoded message is printed on the screen.
