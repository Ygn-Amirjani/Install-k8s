# ArvanCloud-Project

The whole project of ArvanCloud's take-home assignment.

in this project, we used kubernetes to manage our containers. 

Here we have a very simple application in which producer generates messages over epoch timestamp in ms and the consumer transforms it to RFC 33339.

this messages put to a messaging system.

we also used a monitor `Prometheus and grafana` to monitor all servers and all containers.

### How did I solve this problem?
I'm an Algorithm enthusiast! And one of the main algorithms for solving big problems is `Divide  & conquer`; So I decided to break this problem into smaller subproblems, solve them, and finally merge them on the main problem.

Here is the way of my thinking and how I broke the problem:

1) Understand the whole problem and find the relations between given data.
2) A high level thinking of the needed system design.
3) Think about trade-offs that I should make about each path. (I truly believe in William Kennedy's famous quote: `Nothing is free! Everything has cost!`)

Now the implementing part starts with baby steps:

