Anglicism Counter
=================
The anglicism-counter is a script I have created in order to analyze the frequency of anglicisms in German texts.

Files
-----
 - LICENSE
 - README.md
 - anglicism-counter.py
 - anglicisms.txt (a list of all anglicisms)
 - frequents.txt (a list of the most frequent words in German to minimize false positives)

License
=======
This project is published under the MIT-License, see the file LICENSE for further information

Usage
=====
Copy the text(s) you want to analyze to the folder where the program is located in this format:
```
<text1.txt>
<text2.txt>
<text3.txt>
...
```
Then enter the setname of the texts (in this example "text") when prompted.

The program will then analyze all of the texts and output the total count of lines, blank lines, sentences, words, and anglicisms).
If you see any false positives type them in when asked (only one at the time - separated by enter) or enter "n" to continue.

If you want to you can output the results to a file - simply type "y" (or something else if you want to continue without creating a file
