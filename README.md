# TDI-12-days

Day 1:

UNIX

http://www.ee.surrey.ac.uk/Teaching/Unix/

GIT

https://git-scm.com/book/en/v2/Getting-Started-Git-Basics

https://try.github.io/levels/1/challenges/1

https://git-scm.com/download/gui/linux

https://try.github.io/levels/1/challenges/1

http://learngitbranching.js.org/


Day 2:

PYTHON

google
https://developers.google.com/edu/python/

codeacademy

http://www.siafoo.net/article/52

Project Euler
https://projecteuler.net/archives

Day 3:

Scientific Computation

https://www.youtube.com/watch?v=oYTs9HwFGbY

https://github.com/Shane-Neeley/Brightwork

http://www.labri.fr/perso/nrougier/teaching/numpy.100/

Day 4:

Matplotlib - plotting - Bokeh

https://github.com/mwaskom/seaborn

http://matplotlib.org/users/pyplot_tutorial.html

http://www.scipy-lectures.org/intro/matplotlib/matplotlib.html

http://bokeh.pydata.org/en/latest/docs/gallery.html

http://bokeh.pydata.org/en/latest/docs/user_guide/notebook.html

Day 5:

PANDAS

https://github.com/lemonbalm/pandas-exercises

https://www.youtube.com/watch?v=w26x-z-BdWQ

https://www.youtube.com/watch?v=oYTs9HwFGbY

Day 6:

SQL

http://sqlzoo.net/wiki/SQL_Tutorial

https://community.modeanalytics.com/sql/tutorial/introduction-to-sql/

Day 7:

Day 7: Regular Expressions and jQuery

A common job is to extract data and structure from messy text or HTML documents.

For parsing semi-regular text, you should use regular expressions. There's a great interactive online tutorial that teaches you how to use them. Regular expressions have been implemented via the re library in Python.

If you want to select items from HTML, you should learn to use jQuery selectors. W3 school has a single-page interactive tutorial to teach you the basics (there's really not that much to it!). jQuery selectors are implemented in Python in a library called Beautiful Soup. It is more robust to malformed HTML (as compared to other libraries like lxml, although it is slower).

https://regexone.com/

https://docs.python.org/2/library/re.html

http://www.w3schools.com/jquery/jquery_selectors.asp

https://www.crummy.com/software/BeautifulSoup/bs4/doc/

http://lxml.de/

Day 8: Flask and Basic Websites

The power of the web comes from building dynamic websites (also known as a "web server"). Your final project will require a basic website to display the results. These usually consist of three main parts:

    A database to store the data
    A middle layer of code that handles the "business logic" of the website
    HTML which is rendered to the user

Amongst the number of "frameworks" for building web servers, Python Flask is probably the simplest to learn.

Milestone Project: Clone the Flask Demo repository and create your own Flask app on Heroku that accepts a stock ticker input from the user and plots closing price data for the last month. The Quandle WIKI dataset provides this data for free, and you can use Python's Requests library along with simplejson to access it in Python via API. You can analyze the data using pandas and plot using Bokeh. By the end you should have some kind of interactive visualization viewable from the Internet.

Heroku is a popular cloud application platform, and their documentation is a great resource for understanding how to deploy a simple (free!) server using git.

For more information about Flask, here is a good starting point, especially the links in the "Starting Off" section. This tutorial has great step-by-step explanations.

Note: By default, Flask prohibits connections from external machines. If you wish to run Flask from your DO server but access it from your local machine via your web browser, you must replace the command app.run() with app.run(host='0.0.0.0') in your main program.

When you finish, you should end up with a project that looks like this. To submit, click the link on your dashboard.


The list of links:

https://github.com/thedataincubator/flask-demo

https://www.quandl.com/data/WIKI

http://simplejson.readthedocs.io/en/latest/

http://www.python-requests.org/en/latest/

https://devcenter.heroku.com/

https://realpython.com/blog/python/python-web-applications-with-flask-part-i/

https://github.com/bev-a-tron/MyFlaskTutorial

http://lemurian.herokuapp.com/index


Day 9: Probability Fundamentals - I

At this point, you should learn or brush up on the basics of stats. We'll talk about the more advanced and practical hands-on topics during the bootcamp. The best book on this is Ross, which is conveniently available online. It's written for probabilists but, as a data scientists, you only really need to understand a subset.

You should understand the basics about distributions (mean, median, standard deviation, variance) and a few slightly more advanced concepts like (Chapter 3):

    Independence
    Conditional Probability
    Conditional Expectation
    Bayes Rule

It's also important to understand these discrete distributions (Chapter 4):

    Binomial Distribution (distribution about flipping coins)
    Geometric Distribution (how long you have to flip a coin before seeing heads)
    Poisson Distribution (as a 'counting distribution')

Action Item: The best way to check whether you understand these concepts is to solve Self-Test Problems 3.1, 3.9, 3.14, 3.22, and 3.29 (pp. 114–116), as well as 4.3, 4.9, 4.14, 4.16, 4.19, and 4.22 (pp. 183–185).


zalsiary.kau.edu.sa/Files/0009120/Files/119387_A_First_Course_in_Probability_8th_Edition.pdf


Attention: The problems here and in the next section are exactly the kinds of questions that tend to come up in 'stats' job interviews for data science and quant positions. So this is good practice for finding a job. Keep two things in mind:

    Math is not a spectator sport! Glancing over problems doesn't mean you know how to solve them. Force yourself to solve them to make sure you know how.
    If you really understand things, these problems should not take you more than 5 minutes each (and most of them 2 minutes at most). Get a timer (find one online or use the one on your cell phone) and time yourself as you solve them.


Day 10: Probability Fundamentals - II

It's important to understand these common continuous distributions (Chapter 5):

    Normal Distribution (additivity, relationship to the Central Limit Theorem)
    Exponential Distribution (and the memoryless property)

Finally, these theorems are worth understanding (Chapter 8):

    Quantiles
    Central Limit Theorem
    Strong Law of Large Numbers

You should be able to give the difference between Strong Law and Central Limit Theorem.

Action Item: The best way to check whether you understand these concepts is to solve Self-Test Problems 5.8, 5.11, 5.13, 5.17, and 5.18 (pp. 230–231), in addition to 8.5, 8.6, 8.7, 8.11, and 8.13 (pp. 415–416).

Day 11: Basic Algorithms and Data Structures - I

Algorithms and data structures are important foundational knowledge for programming. There are a lot of 'dumb' ways to do things. These are the 'smart' ways to do them that will save you a lot of time on the job.

There's a great interactive Python-based tutorial available online. From Basic Data Structures, understand:

    Stacks
    Queues
    Deques
    Lists

From Sorting and Searching, understand:

    Hash Tables
    The Bubble Sort
    The Selection Sort
    The Insertion Sort
    The Shell Sort
    The Merge Sort
    The Quick Sort

Action Item: To test your knowledge, make sure you can answer the first five exercises for Basic Data Structures and Sorting and Searching.
http://www.interactivepython.org/courselib/static/pythonds/index.html

http://www.interactivepython.org/courselib/static/pythonds/BasicDS/toctree.html

http://www.interactivepython.org/courselib/static/pythonds/SortSearch/toctree.html

http://interactivepython.org/courselib/static/pythonds/BasicDS/ProgrammingExercises.html

http://interactivepython.org/courselib/static/pythonds/SortSearch/ProgrammingExercises.html
Day 12: Basic Algorithms and Data Structures - II

From Trees and Tree Algorithms, understand:

    Binary Trees
    Priority Queues with Binary Heaps
    Binary Search Trees

From Graphs and Graph Algorithms, understand:

    Breadth First Search
    Depth First Search
    Shortest Path

And, of course, you should already know Recursion and Dynamic Programming (brush up if you don't already).

Action Item: To test your knowledge, make sure you can answer the first five exercises for Recursion, Trees and Tree Algorithms, and Graphs and Graph Algorithms.
LINKS:
http://interactivepython.org/courselib/static/pythonds/Trees/toctree.html
http://interactivepython.org/courselib/static/pythonds/Graphs/toctree.html
http://interactivepython.org/courselib/static/pythonds/Recursion/toctree.html

http://interactivepython.org/runestone/static/pythonds/Recursion/pythondsProgrammingExercises.html

http://interactivepython.org/runestone/static/pythonds/Trees/ProgrammingExercises.html

http://interactivepython.org/runestone/static/pythonds/Graphs/ProgrammingExercises.html


and after that...

D3.js
A tutorial on how to make a bar chart in D3 from scratch
http://bost.ocks.org/mike/bar/

A book on Interactive Data Visualization using D3.
http://alignedleft.com/tutorials/d3/

Demos and associated source codes for a variety of D3 visualizations.
http://flowingdata.com/tag/d3/


Unicode and Character Sets
The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets
http://www.joelonsoftware.com/articles/Unicode.html

And a nice follow up...
http://kunststube.net/encoding












