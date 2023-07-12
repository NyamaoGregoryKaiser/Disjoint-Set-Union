# Disjoint-Set-Union
Disjoint Set Union is a data structure that contains elements which point to another element, repeating this process until it reaches the leader, who points to himself.
There are n kingdom.
After every fight between two kingdom, the winner will take the defeated kingdom's resources.
In each fight, the kingdom with more resources will win.

Given the number of kingdoms, their initial resources and the fights,
find the kingdom with the most resources at the end.

Input:
   N M
   AN AN-1 AN-2 ... A1

   P1 Q1
   P2 Q2
   ...
   PN QN
