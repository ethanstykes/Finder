# Finder
Algorithm to find the most relevant string from a list 
run find.py
The find.py file is pretty understandable for anyone who knows the basics of python.
You can manipulate the code to find from a text file or a database instead of the list,
or do any manipulation you need. I have set the main algorithm of the search operation
as a different module (finder.py). It can easly modified as a program that can also
display less relevant results.

PS: The program might seem faulty at first because you might feel it isn't working as you
expect it to. It is because you are in control of both the data and the inputs you give.
It hopefully won't last longer. This algorithm takes into consideration a lot of factors
that can affect search, like probability of making a typing mistake (for instance, in 
case you miss a word, you are less likely to miss a noun), relevance and irrelevance 
of stop words while deciding ranking, etc. The optimal solution is made into this simple 
code. However, this search doesn't cover spelling errors (Google is using Application
Specific Integrated Circuits for it!) or learning from previous entries.

Feedbacks/Report an issue: stykesfeedback@gmail.com
