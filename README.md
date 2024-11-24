# Quick Guide to Using the `wc` Command in Linux

The `wc` (word count) command in Linux is used to find out the number of lines, words, and bytes contained in a file. It can also be used to count the number of characters and display the length of the longest line in a file.

## Basic Usage of ccwc

To start using this command on your local machine first run:

`export PATH=$PATH:/path/to/executable/directory`

> Add your own directory where the ccwc executable is located

### Example usage

Example 1

> Input
>
> `ccwc test.txt`
>
> Output
>
> `  7145  58164   342190  test.txt`

Example 2

> Input
>
> `ccwc test.txt random.txt oops.txt hello.txt`
>
> Output
>
> `7145  58164   342190  test.txt` > `23    85      938     random.txt` > `11    116     563     oops.txt` > `5     69      445     hello.txt` > `7184  58434   344136  total`

Example 3

> Input
>
> `ccwc -l test.txt random.txt hello.txt`
>
> Output
>
> `7145  test.txt`
> `23    random.txt`
> `5     hello.txt`
> `7173  total`
