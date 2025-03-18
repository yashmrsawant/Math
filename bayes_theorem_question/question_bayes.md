## Probability Question (Bayes' Theorem)

Two bags, A and B, contain balls of two different colors:
	•	Bag A: 3 red and 4 black balls.
	•	Bag B: 5 red and 6 black balls.

A bag is selected at random, and a ball is drawn from it. Given that the drawn ball is red, what is the probability that it was taken from Bag B?



Experiment: Choose a bag A or bag B randomly (equally likely) and draw a ball out of it.

Solution:

Suppose we perform the experiment 1000 times i.e. we repeat the same experiment of choosing a bag A or B and taking a ball out of it 1000 times.

Out of 1000 times, about 495 times we chose bag A and 505 times we chose bag B (as we equally like choose bag A or bag B in each experiment)

In those bag A trials : 495 times => We get red ball about 212 times, and 283 times black ball
In those bag B trials : 505 times => We get red ball about 229 times, and 276 times black ball

Now we know focusing on that experiments in which we get red ball i.e. either bag A trials with 212 times red ball trials or bag B trials with 229 times trials, because it is given in the question that red ball was drawn from the bag, so we know either bag A red ball trials is there (which is 212 times) or bag B red ball trials is there (which is 229 times). 

Probability that red ball is from bag B is basically $(229/(229+212)) \approx \frac{35}{68}$
