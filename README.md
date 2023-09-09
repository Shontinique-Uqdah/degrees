# Degrees of Separation
CS50-AI degrees

This program serves to determine the number of degrees of separation between two actors.
It utilizes BFS (Breadth-First Search) to attempt to pinpoint the shortest path / lowest degrees of separation between two actors.

All code except that which is contained in the shortest path function is not my own work, it is the base project provided by The CS50ai course. I was only responsible for the implementation of the shortest path function.

Sample output:
```
$ python3 degrees.py large
Loading data...
Data loaded.
Name: Emma Watson
Name: Jennifer Lawrence
3 degrees of separation.
1: Emma Watson and Brendan Gleeson starred in Harry Potter and the Order of the Phoenix
2: Brendan Gleeson and Michael Fassbender starred in Trespass Against Us
3: Michael Fassbender and Jennifer Lawrence starred in X-Men: First Class
```
