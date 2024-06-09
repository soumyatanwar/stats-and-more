# stats-and-more
Learnings and experiments with statistical modeling

## Cookie Problem (and Coin problem)
How to think about Bayes Theorem
1. A way to compute likelihood of a hypothesis, given some data (may be easier to compute this way)
2. A way of updating beliefs, when we see more data

H = Hypothesis
D = Data or observation(s) made/seen
P(H/D) = P(H) * P(D/H) / P(D) 

Bayes Table (organizing calculations and scaling)

P(H) = Priors = Probability of Hypothesis (before data)
P(D/H) = Likelihood of getting data, assuming hypothesis is true (hypothesis event happened)
P(D) = Probability of data being observed regardless of whether hypothesis is true or not

Law of total probability (depending on how many hypothesis)
_Assuming H1, H2,... are mutually exclusive. Only one happens at a time_
P(D) = P(H1)*P(D/H1) + P(H2)*P(D/H2) + ....

<img width="668" alt="image" src="https://github.com/soumyatanwar/stats-and-more/assets/37302163/d34a7cd9-422b-4857-ae48-30af4cdf7d9c">
