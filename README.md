# irm

make your script and repository compliant with the principles of reproducibility. 
This means that you have to pay particular attention to the following aspects: 
1) document your code (what is does and how to use it); 

First the code finds all occurances of "De" in the Wikipedia.html file. The Wikipedia.html file is an offline copy of 
https://nl.wikipedia.org/wiki/Rijksuniversiteit_Groningen. Second the code counts all those occurances. Finally the code prints the result.
the shell can be executed by using the command: $ bash word_counter.sh

2) document your GitHub (what isit for? what an external user can find in it? what are the results); 

the code and wikipedia article can be found on https://github.com/rPaleman/irm/. 

There are 239 occurances of the word "de"

3) document your data (how can the data be accessed? are you storing an offline version of the page or not?)

The data is saved on the afforementioned github repository. An offline version of the wikipedia article is used. 
This is in case the original article is changed, making my results non-replicable.
