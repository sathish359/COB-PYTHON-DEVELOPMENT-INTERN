# COB-PYTHON-DEVELOPMENT-INTERN

This Python program reads a text file, identifies all unique words, and counts how many times each unique word appears in the file. Here's a summary of its key components and functionality:

1) It defines a function get_unique_word_counts(file_location) to process the file and determine unique word occurrences.
2) Inside the function, it initializes an empty dictionary word_counts to store the word counts.
3) It opens and reads the specified file line by line.
4) For each line, it splits the line into words and processes each word.
5) Words are transformed to lowercase and stripped of any punctuation.
6) It checks whether the word is already in the word_counts dictionary.
    1. If the word exists, its count is incremented.
    2. If the word is new, it's added to the dictionary with a count of 1.
7) The program handles exceptions for file not found and other general exceptions, providing appropriate error messages.
8) It returns the word_counts dictionary with unique word occurrences.
9) In the main part of the program (if __name__ == "__main__"), it specifies the file name to process (python.txt).
10) It calls the get_unique_word_counts function with the specified file name.
11) It checks whether the result is a string (error message) or a dictionary (word occurrences).
    1. If it's a string, an error message is printed.
    2. If it's a dictionary, it prints the unique words and their occurrences.

The program effectively reads a text file, processes its content, and provides a count of each unique word found in the file.
