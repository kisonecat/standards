
The directory

linear-algebra/topics

contains a reasonably complete list of topic for an introductory
course in linear algebra.  Example topics:

math.la.d.mat.orthogonal
   Definition of orthogonal matrix.

math.la.t.lin_sys.nonhomog.particular_plus_homog
   The solutions to a nonhomogeneous system of equations are given by a
   particular solution plus the solutions to the homogeneous system.


Comments:

All linear algebra topic identifiers begin
math.la

Following math.la. is one of the following letters, with the stated meaning:

a  application
c  concept
d  definition
t  theorem

The remaining entries use abbreviations for common words, with words
separate by underscore: "_".  Identifiers are all written in lower-case
ASCII.  

If a topic description requires a hyphen or dash (such as "Gram-Schmidt"
or "rank-nullity"), an ASCII dash "-" must be used.  Omit the dash in
the topic identifier.  For example:
math.la.t.ranknullity
    Rank-nullity theorem.

No reference is made to R^n or C^n, instead, we specify concepts as either
being expressed in "coordinates" or "abstract".

Topic identifiers omit the "s" for a plural, even when the items being
described are plural.  For example:
math.la.d.mat.eig
   Definition of eigenvalues of a matrix.

Available abbreviations are:

abs  abstract
col  column
coord  coordinate(s)
det  determinant
dim  dimension
eig  eigenvalue(s)
eqn  equation
homog  homogeneous
inv  inverse
lin  linear
lin_sys  linear_system
lin_trans  linear_transformation
mat  matrix
mult  multiplication
nonhomog  nonhomogeneous
subsp  subspace
sys  system
trans  transpose
vec  vector
vec_sp  vector_space


The topic identifiers mention objects before operations or properties, thus
sys.homog  not  homog.sys
mat.inv  not  inv.mat

But lin_sys is acceptable, because linear systems are commonly cited objects,
and similarly for lin_trans and vec_sp.

If an item can be expressed in either a coordinate setting or an abstract
vector space setting, then both versions should occur, with "coord" or "abs",
respectively, being the last entries in the identifiers.

Topic descriptions should start with a capital letter and end with a period
(even if the description is not technically a sentence).  The description should
be sufficiently expansive that the instructor of a typical linear algebra course
an easily discern the meaning.  The writing style should be appropriate for a
footnote in a scholarly publication.

----------

The directory

linear-algebra/outcomes

contains a reasonably complete list of outcomes for an introductory
course in linear algebra.  Example outcomes:

math.la.o.c.mat.inv
   Compute the inverse of a matrix.
math.la.o.d.mat.inv
   Define the inverse of a matrix.
math.la.o.n.mat.inv.det
   Describe the relationship between the determinant of a matrix and the determinant of its inverse.

All linear algebra outcomes begin with

math.la.o

Following math.la.o is one of the following letters, with the stated meaning:

c  Compute
d  Define
e  Explain
i  Interpret
n  Describe (n = 'narrative')
p  Prove
r  Relate
s  Solve
u  Use

The remaining parts of an outcome identifier follow the same pattern as the topic identifiers.
Implicit in the naming of outcome identifiers is that all outcomes are of the form "verb noun".



