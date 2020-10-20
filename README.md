**Rules**:

For the programming aspects of this task, you may use any language of your choice.
  
It is up to you to decide when to use someone else's code from a library/open source, and when to write something yourself. In each case, you should determine this based on the context of the overall task.

**Overview**:

The included data.json file is a JSON formatted weighted graph, whose nodes represent the characters from Les Miserables. You can find many visualisations of this graph online, such as here https://mbostock.github.io/protovis/ex/force.html

Each link in the JSON has a direction, and an associated value, indicating the strength of the connection between the two ends of the link.

For this problem, you should interpret the graph to be **undirected**, meaning that each link in the table really represents a bi-directional link between the two ends.

We are interested in various methods of determining the "most important" nodes in the graph.

**Question 1**:

Write a program to compute the weighted degree of each node of the graph, and order the nodes by their weighted degree.  The program should print its output to stdout in the following format

highest scoring node name:          score
second highest scoring node name:   score
.
.
.

**Question 2**:

How do you think the method of question 1 performs as a definition of importancefor the nodes in the graph? (What does it do well? What are its shortcomings?)

**Question 3**:

Based on your answer to question 2, and your own research, determine a better method of assigning an "importance score" to each node in the graph, and write a program to implement it (again printing its output to stdout, in the same format as question 1).  Give a brief description of how the chosen method works, and if it has a name, say what it is.
