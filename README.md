# categorical_foundations

## A book project on categorical foundations of mathematics.

Early undergraduate students often struggle with mathematical formalism. 
The author is under the impression that this is partly due to the fact that students are told to write down proofs as formal as possible, 
while at the same time they are not given a proper axiomatic foundation to work with (naive set theory).

The reason for this lack of foundations is at least two-fold. On the one hand, naive set theory is commonly taught in the first few weeks
of courses on Calculus and/or Linear Algebra. These topics involve a lot of theory in itselves, so naturally not much time can be spent on
set-theoretic foundations. On the other hand, proper axiomatic foundations of mathematics tend to be technically involved and abstract.
Specifically *Zermelo-Fraenkel Set Theory* (ZF) ... while *topos theory* (TT) requires a lot of category theoretic knowledge beforehand.

To the author's surprise, there is a middle ground. Lawvere's *Elementary Theory of the Category of Sets* (ETCS) gives an axiomatic characterization
of the category of sets, which is surprisingly close to the list of things undergraduates are taught under the name naive set theory. To
demonstrate this point we refer to [Leinster](https://arxiv.org/pdf/1212.6543.pdf) for a quick and lovely read.

The book [Sets for Mathematics](https://www.cambridge.org/core/books/sets-for-mathematics) is similar in
spirit to the present book project and is an important source for the latter. It is however different to the latter in that
it is aimed at advanced undergraduates and thus builds on advanced mathematical intuition. This is in harsh contrast to the goals of this
book project:

1. Introduce the category of sets without previous knowledge of
    a) Formal Logic
    b) Category Theory
   by providing a list of axioms taylormade to every-day use (want products of sets, want sets of functions...)
2. Develop elementary mathematics in this formal framework, such as
    - partial orders
    - the arithmetic of natural numbers, prime numbers and the fundamental theorem of arithmetic
    - the real numbers, euclidean geometry?
    - the complex numbers, Euler's identity and the fundamental theorem of algebra
    - groups and their orbits
3. Introduce a bit of category theory, most importantly
    - Categories, Functors, Natural transformations
    - Functor-Categories and Yoneda's Lemma
    - Adjoint Functors
    - Limits and Colimits
    - Monoidal Structures
4. Prove independence results via Topos-Theory:
    - The independence of AC
    - The independence of CH
    - The independence of the Axiom of Infinity
