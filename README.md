#Python implementation of a Genetic Algorithm

AI - Simple Genetic Algorithm (GA) to solve a card problem

A Python implementation of the code shown in Sacha Barber [article](http://www.codeproject.com/Articles/16286/AI-Simple-Genetic-Algorithm-GA-to-solve-a-card-pro)

## Purpose

You have 10 cards numbered 1 to 10
You have to divide them into two piles so that:
 - The sum of the first pile is as close as possible to 36.
 - And the product of all in the second pile is as close as possible to 360.

Well, all that is being done is the following :

Loop through the population member's genes
 - If the current gene being looked at has a value of 0, the gene is for the sum pile (pile 0), so add to the running calculation
 - If the current gene being looked at has a value of 1, the gene is for the product pile (pile 1), so add to the running calculation
 - Calculate the overall error for this population member. If this member's geneotype has an overall error of 0.0, then the problem domain has been solved
