# COB-PYTHON-DEVELOPMENT-INTERN

This Python program reads a text file, identifies all unique words, and counts how many times each unique word appears in the file. Here's a summary of its key components and functionality:

==>It defines a function get_unique_word_counts(file_location) to process the file and determine unique word occurrences.
==>Inside the function, it initializes an empty dictionary word_counts to store the word counts.
==>It opens and reads the specified file line by line.
==>For each line, it splits the line into words and processes each word.
==>Words are transformed to lowercase and stripped of any punctuation.
==>It checks whether the word is already in the word_counts dictionary.
    -->If the word exists, its count is incremented.
    -->If the word is new, it's added to the dictionary with a count of 1.
==>The program handles exceptions for file not found and other general exceptions, providing appropriate error messages.
==>It returns the word_counts dictionary with unique word occurrences.
==>In the main part of the program (if __name__ == "__main__"), it specifies the file name to process (python.txt).
==>It calls the get_unique_word_counts function with the specified file name.
==>It checks whether the result is a string (error message) or a dictionary (word occurrences).
    -->If it's a string, an error message is printed.
    -->If it's a dictionary, it prints the unique words and their occurrences.

The program effectively reads a text file, processes its content, and provides a count of each unique word found in the file.
