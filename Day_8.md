# frequentist definition of probability
The frequentist definition of probability is based on the idea that probability is the long-run relative frequency of an event occurring in repeated independent trials or experiments. In other words, the probability of an event is defined as the proportion of times the event occurs in a large number of trials, assuming the trials are independent and identically distributed.

Mathematically, if we have a random experiment and an event 
A, the frequentist probability of 
A, denoted 
P(A), is defined as:

P(A)= 
lim
n→∞

Number of times A occurs in n trials/n
​
 
Where:

n is the number of trials,
The limit is taken as the number of trials goes to infinity.


# Law of Large Numbers 
 Law of Large Numbers (LLN) is a fundamental concept in probability and statistics that describes how the average of a large number of independent, identically distributed (i.i.d.) random variables tends to get closer to the expected value as the number of trials increases. In other words, the more times you repeat an experiment, the closer the observed average will be to the true theoretical average (or expected value) of the underlying probability distribution.

# Sample Space (S)
The sample space is the set of all possible outcomes of a random experiment. It encompasses everything that can possibly happen in that experiment.

# Events
An event is any subset of the sample space. An event can consist of a single outcome or multiple outcomes from the sample space. In simple terms, an event is the occurrence of one or more outcomes from the sample space.

# Probability of an Event
The probability of an event is a measure of how likely the event is to occur. It is defined as the ratio of the number of favorable outcomes to the total number of possible outcomes in the sample space.

Mathematical Formula:
𝑃
(
𝐴
)
=
Number of favorable outcomes for event A/
Total number of outcomes in the sample space.

# Independent Events
Independent events are events where the occurrence of one event does not affect the probability of the occurrence of the other event. In other words, the outcome of one event has no impact on the outcome of the other.

Mathematical Definition: Two events 
𝐴 and 
𝐵 are independent if:

P(A∩B)=P(A)⋅P(B) 

# Dependent Events
Dependent events are events where the occurrence of one event does affect the probability of the occurrence of another event. In other words, the outcome of one event changes the likelihood of the other event happening.

Mathematical Definition: Two events 
𝐴 and 
𝐵 are dependent if:

P(A∩B)!
=P(A)⋅P(B)

# Joint Probability
Joint probability refers to the probability of two (or more) events occurring together. It gives the likelihood that two events, say 

A and 
B, will both happen simultaneously.  

# Marginal Probability
Marginal probability refers to the probability of an event occurring, regardless of the outcome of another event. It is called "marginal" because it can be found by summing or integrating the joint probabilities over the possible values of the other event (hence "marginalizing" over the other event).

# Conditional Probability
Conditional probability refers to the probability of an event occurring given that another event has already occurred. It describes how the probability of an event 
𝐴 changes when we know that another event 
𝐵 has happened. 

# Bayes' Theorem
Bayes' Theorem is a fundamental concept in probability theory and statistics that provides a way to update the probability of an event based on new evidence or information.
Bayes' Theorem Formula
The general form of Bayes' Theorem is:

P(A∣B)= 
P(B)
P(B∣A)⋅P(A) 

Where:

P(A∣B) is the posterior probability: the probability of event 

A occurring given that event 
B has occurred.

P(B∣A) is the likelihood: the probability of event 
B occurring given that event 
A has occurred.

P(A) is the prior probability: the initial probability of event 
A occurring, before considering the new evidence.

P(B) is the marginal probability or normalizing constant: the total probability of event 
B occurring, considering all possible events that could lead to 
B.
​
# Diff. between conditional probability and Bayes theorem

* Conditional probability  
P(A∣B) is the probability of event 
A given event 
B. It’s used when you already know that event 
B has occurred and you want to find out how it affects the probability of event 
A.
* Bayes' Theorem is a way to update the probability of a hypothesis 
A given new evidence 
B. It applies conditional probability in a broader context to calculate the posterior probability by considering the prior knowledge and the likelihood of observing the new evidence.

In short, Bayes' Theorem is a method to compute conditional probability when you have new data, and conditional probability is one of the building blocks that make Bayes' Theorem work.

# ​Quantitative Uncertainty
Measures how much uncertainty exists about an event. More uncertainty → more information.

# Entropy	
The average uncertainty or information content of a random variable; a measure of unpredictability.

# Entropy Curve
Shows how entropy changes as the probability distribution of outcomes becomes more or less certain.

# Cross-Entropy	
Measures the difference between two probability distributions, quantifying the inefficiency of assuming 
Q bar when the true distribution is 
P bar.
