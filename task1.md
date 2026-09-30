
# Lab Exercise — Task 1: Prolog Unification

2 ?- house = house .
true.

3 ?- house = abc .
false.

4 ?- edge(a,b) = edge(C,b). 
C = a.

5 ?- edge(a,d) = edge(C,B).
C = a,
B = d.

6 ?- edge(C,B) = edge(a,d).
C = a,
B = d.

7 ?- edge(A,f(g,h)) = edge(a,B). 
A = a,
B = f(g, h).

8 ?- edge(A,A) = edge(b,c). 
false.

9 ?- edge(A,A) = edge(b,b).
A = b.

10 ?- A = B , B = f .
A = B, B = f.

11 ?- A = B , B = f , A = e .
false.

12 ?- 