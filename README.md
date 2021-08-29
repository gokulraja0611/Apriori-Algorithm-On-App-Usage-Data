# Apriori-Algorithm-On-App-Usage-Data
Apriori Algorithm Intuition:

What are the three essential relations between the support, confidence and lift?

Given two Apps A1 and A2, here are the three essential relations to remember:

Relation between the support and the confidence:
confidence(A1 -> A2) =support(A1,A2)/support(A1)

Relation between the lift and the support:
lift(A1 -> A2) =support(A1,A2)/support(A1)*support(A2)

Relation between the lift and the confidence (consequence of the two previous equations):
lift(A1 -> A2) =confidence(A1 -> A2)/support(A2)
