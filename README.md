# Proposition logic expression evaluator
This is a project made to help me with some homework. It parses an expression from propositional logic, computes truth table and deals with viability and satisifiability.

The whole thing was made in Jupyter using Python. It checks for some basic syntax errors that were present in my homework, fixes them if necessary and builds the truth table.

Furthermore, the program also computes the disjunctive normal form (DNF) of a given expression.
One exercise this program was used to solve is listed below:
```

F,G,H are propositional formulae. Show that the following hold:
• Reduction Laws:
(a)(F⇔G)≡(F⇒G)∧(G⇒F)
(b)(F⇒G)≡(¬F∨G)
• Commutative Laws:
(a)F∨G≡G∨F
(b)F∧G≡G∧F
(c)F⇔G≡G⇔F
• Associative Laws:
(a)(F∨G)∨H≡F∨(G∨H)
(b)(F∧G)∧H≡F∧(G∧H)
(c)(F⇔G)⇔H≡F⇔(G⇔H)
• Distributive Laws:
(a)F∨(G∧H)≡(F∨G)∧(F∨H)
(b)F∧(G∨H)≡(F∧G)∨(F∧H)
(c)(F∨G)⇒H≡(F⇒H)∧(G⇒H)
(d)(F∧G)⇒H≡(F⇒H)∨(G⇒H)
(e)F⇒(G∨H)≡(F⇒G)∨(F⇒H)
(f)F⇒(G∧H)≡(F⇒G)∧(F⇒H)
(g)(F∧G)⇒H≡F⇒(G⇒H)
• Laws of “True” and “False”:
(a)¬⊤≡⊥
(b)¬⊥≡⊤
(c)F∨⊥≡F
(d)F∧⊤≡F
(e)F∨⊤≡⊤
(f)F∧⊥≡⊥
(g)⊥⇒F≡⊤
(h)F⇒⊤≡⊤
• Idempocy rules:
(a)F∧F≡F
(b)F∨F≡F
• Absorbtion Laws:
(a)F∨(F∧G)≡F
(b)F∧(F∨G)≡F
```
