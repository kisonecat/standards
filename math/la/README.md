
Linear algebra topic identifiers begin
math.la

Following math.la. is one of the following letters, with the stated meaning:

a  application
c  concept (usually an informal statement)
d  definition
e  example
h  exercise  # as in 'homework'
p  proof
t  theorem

The remaining entries use abbreviations for common words, with words
separate by underscore: "_".  Identifiers are all written in lower-case
ASCII.  

If a topic description requires a hyphen or dash (such as "Gram-Schmidt"
or "rank-nullity"), an ASCII dash "-" must be used.  Omit the dash in
the topic identifier.  For example:
id: math.la.t.mat.ranknullity
description: "Rank-nullity theorem."

Avoid making references to R^n, C^n, or F^n, except as examples or
when absolutely necessary.  Instead, specify concepts as either being
expressed in a "coordinate setting" or an "arbitrary setting".
The choice of settings is determined by the prior material: if the
definition of "dimension" does not refer to a coordinate vector space,
but the previous discussion was in the coordinate setting, then consider
the definition to also be in the coordinate setting.

Topic identifiers omit the "s" for a plural, even when the items being
described are plural.  For example:
id: math.la.d.mat.eig
description: "Definition of eigenvalue(s) of a matrix."

Do not put 'quotes' around terms.  For example:
id: d.linsys.consistent
description: "Definition of consistent linear system"
Not  "Definition of 'consistent linear system'"

Available abbreviations are:

arb  arbitrary setting
add  addition
assoc  associative
canon  canonical (or normal) form
charpoly  characteristic polynomial
cn  C^n        # n can be a digit
coeff  coefficient(s)
col  column
commut  commutative
coord  coordinate setting
det  determinant
dim  dimension
eig  eigenvalue(s)
eigvec  eigenvector(s)
eigsp  eigenspace(s)
eqn  equation
equiv  equivalent
exer  exercise
homog  homogeneous
i  infinitely many
inv  inverse
lin  linear
lincomb  linear combination
lindep  linearly dependent
lineqn  linear equation
linindep  linearly independent
linsys  linear system
lintrans  linear transformation
mat  matrix
mult  multiplication
mxn  m-by-n        # m and n can be digits
nonhomog  nonhomogeneous
o  one
op  operation
prod  product
rep  repeat  (when a topic appears formally a second time)
repn  representation
rn  R^n        # n can be a digit
rncn  R^n or C^n      # n can be a digit
rref  reduced row-echelon form
soln  solution
subsp  subspace
sys  system
vec  vector
vsp  vector space
z  zero
zoi  zero, one, or infinitely many

The topic identifiers mention objects before operations or properties, thus
sys.homog  not  homog.sys
mat.inv  not  inv.mat

If an item can be expressed in either a coordinate setting or an arbitrary
setting, then both versions are available, with "coord" or "arb",
respectively, being the last entries in the identifiers.

If a topic occurs in an exercise, put "exer" as the last entry in the identifier.
If a topic is repeated, put "rep" as the last entry in the identifier
the second time it appears.  (For "equiv" theorems, it is optional to repeat
an item after it appears the first time.).

Topic descriptions should start with a capital letter and end with a period
(even if the description is not technically a sentence).  The description should
be sufficiently expansive that the instructor of a typical linear algebra course
can easily discern the meaning.  The writing style should be appropriate for a
footnote in a scholarly publication.

