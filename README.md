# Quick Guide to Using the `wc` Command in Linux

The `wc` (word count) command in Linux is used to find out the number of lines, words, and bytes contained in a file. It can also be used to count the number of characters and display the length of the longest line in a file.

Run `man wc` in your terminal for explanation and example usage

## Basic Usage of ccwc

To start using this command on your local machine first run:

`export PATH=$PATH:/path/to/executable/directory`

> Add your own directory where the ccwc executable is located

### Upgrades

My wc clone is still incomplete

1. cannot take in standard input when no files are specified
2. Issues with the way output is printed in terminal
3. Cannot take in a '-L' argument that finds the lines with the most bytes
