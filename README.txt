
The directory

linear-algebra/topics

contains a reasonably complete list of topic for an introductory
course in linear algebra.  

The purpose of the list is for tagging educational resources in order to
facilitate the discovery of useful material.

Example topics:

math.la.d.mat.orthogonal
   Definition of orthogonal matrix.

math.la.t.linsys.nonhomog.particular_plus_homog
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

No reference is made to R^n or C^n.  Instead, we specify concepts as either
being expressed in a "coordinate" vector space or an "abstract" vector space.

Topic identifiers omit the "s" for a plural, even when the items being
described are plural.  For example:
math.la.d.mat.eig
   Definition of eigenvalues of a matrix.

Available abbreviations are:

abs  abstract vector space
add  addition
charpoly  characteristic polynomial
coeff  coefficient
col  column
coord  coordinate vector space
det  determinant
dim  dimension
eig  eigenvalue(s)
eigvec  eigenvector(s)
eigsp  eigenspace(s)
eqn  equation
equiv  equivalent
homog  homogeneous
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
nonhomog  nonhomogeneous
op  operation
prod  product
repn  representation
soln  solution
subsp  subspace
sys  system
vec  vector
vsp  vector space
z  zero

The topic identifiers mention objects before operations or properties, thus
sys.homog  not  homog.sys
mat.inv  not  inv.mat

But linsys is acceptable, because linear systems are commonly cited objects,
and similarly for lintrans.

If an item can be expressed in either a coordinate setting or an abstract
vector space setting, then both versions should occur, with "coord" or "abs",
respectively, being the last entries in the identifiers.

Topic descriptions should start with a capital letter and end with a period
(even if the description is not technically a sentence).  The description should
be sufficiently expansive that the instructor of a typical linear algebra course
can easily discern the meaning.  The writing style should be appropriate for a
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

a  Apply
b  Describe
c  Compute (or Calculate)
d  Define
e  Explain
f  Formulate
g  Recognize
i  Interpret
l  List
m  Determine
n  Understand
o  Perform
p  Prove
q  Qualitatively describe
r  Relate
s  Solve
t  Translate
u  Use
v  Provide
w  Write
y  Identify
z  Analyze

(May wish to add these:  Discuss, State, Understand, Demonstrate, Find,
but only 4 letters remain.  "Understand" is problematic, because it is
not directly testable.)

The remaining parts of an outcome identifier follow the same pattern as the topic identifiers.
Implicit in the naming of outcome identifiers is that all outcomes are of the form "verb noun".

The description of an outcome must start with the corresponding word above.

