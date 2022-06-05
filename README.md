# AHP

Analytic Hierarchy Process 

The Analytic Hierarchy Process (AHP) is a method for organizing and analyzing complex decisions, using math and psychology. It was developed by Thomas L. Saaty in the 1970s and has been refined since then. It contains three parts: the ultimate goal or problem you're trying to solve, all of the possible solutions, called alternatives, and the criteria you will judge the alternatives on. AHP provides a rational framework for a needed decision by quantifying its criteria and alternative options, and for relating those elements to the overall goal.

Stakeholders compare the importance of criteria, two at a time, through pair-wise comparisons. Example, do you care about job benefits or having a short commute more, and by how much more? AHP converts these evaluations into numbers, which can be compared to all of the possible criteria. This quantifying capability distinguishes the AHP from other decision making techniques.

In the final step of the process, numerical priorities are calculated for each of the alternative options. These numbers represent the most desired solutions, based on all users' values.

# Advantages 

The AHP is most useful when finding decisions to complex problems with high stakes. It stands out from other decision-making techniques as it quantifies criteria and options that traditionally are difficult to measure with hard numbers. Rather than prescribing a "correct" decision, AHP helps decision makers find one that best suits their values and their understanding of the problem. (Wikipedia)

Having all stake holders weigh in is important, as various divisions will value criteria differently. For example, when deciding on new software, Sales may be focused on its ease of use, whereas Admin care more about its integrations to other systems. AHP is also different from a regular poll or meeting as it takes out bias from the decision.AHP boosts morale as everyone feels their voices are heard, and they can ultimately understand how a decision is made.

# Calculations 

The basic steps involving AHP are as following.

Define the goal of the decision – what do I want to decide, for what purpose, and what are my alternatives?

Structure the decision problem in a hierarchy – what are the categories and criteria that figure into my decision?

Pairwise comparison of criteria in each category – e.g. blue or green? Which one I prefer, and by how much do I prefer one or the other color?

Calculate the priorities and a consistency index – were my comparisons logical and consistent?

Evaluate alternatives according to the priorities identified – what alternative optimum solution is there to the decision problem?


The pair-wise comparison is used to compare the importance of criteria. It can be carried out with nine-point scale value which includes values 9, 8, 7, 6...., 1/7, 1/8, 1/9, which indicates 9 as extreme preference, 7 as very strong preference, 5 as strong preference and so on down to 1 which represents no preference. Thus, the pair-wise comparison aids to simplify the criteria by evaluating the independent contribution of each criterion with each other. The square matrix is organized for pairwise comparisons of various criteria. The principal eigenvalue and their corresponding eigenvector was developed among the relative importance within the criteria from the comparison matrix. The weights for each element can be generated from the normalized eigenvector. The subjective judgment from AHP were checked via consistency index. The consistency index (CI) is calculated as:

CI = ( λmax - n ) / ( n - 1 )
Where CI = Consitency Index
λmax = maximum eigenvector of the matrix
n = order of the matrix

After comparing CI with random index, Consistency Ratio (CR) can be derived from their ratio. The consistency ratio should be ≤ 0.1 (Saaty, 1990). The pairwise comparison is assumed to be inconsistent if the CR exceeds the threshold, the process has to be reviewed in such case.
