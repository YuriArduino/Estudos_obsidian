https://plato.stanford.edu/entries/category-theory/


_First published Fri Dec 6, 1996; substantive revision Thu Aug 29, 2019_

Category theory has come to occupy a central position in contemporary mathematics and theoretical computer science, and is also applied to mathematical physics. Roughly, it is a general mathematical theory of structures and of systems of structures. As category theory is still evolving, its functions are correspondingly developing, expanding and multiplying. At minimum, it is a powerful language, or conceptual framework, allowing us to see the universal components of a family of structures of a given kind, and how structures of different kinds are interrelated. Category theory is both an interesting object of philosophical study, and a potentially powerful formal tool for philosophical investigations of concepts such as space, system, and even truth. It can be applied to the study of logical systems in which case category theory is called “categorical doctrines” at the syntactic, proof-theoretic, and semantic levels. Category theory even leads to a different theoretical conception of set and, as such, to a possible alternative to the standard set theoretical foundation for mathematics. As such, it raises many issues about mathematical ontology and epistemology. Category theory thus affords philosophers and logicians much to use and reflect upon.

- [1. General Definitions, Examples and Applications](https://plato.stanford.edu/entries/category-theory/#GeneDefiExamAppl)
    - [1.1 Definitions](https://plato.stanford.edu/entries/category-theory/#Defi)
    - [1.2 Examples](https://plato.stanford.edu/entries/category-theory/#Exam)
    - [1.3 Fundamental Concepts of the Theory](https://plato.stanford.edu/entries/category-theory/#FundConcTheo)
- [2. Brief Historical Sketch](https://plato.stanford.edu/entries/category-theory/#BrieHistSket)
- [3. Philosophical Significance](https://plato.stanford.edu/entries/category-theory/#PhilSign)
- [Bibliography](https://plato.stanford.edu/entries/category-theory/#Bib)
- [Academic Tools](https://plato.stanford.edu/entries/category-theory/#Aca)
- [Other Internet Resources](https://plato.stanford.edu/entries/category-theory/#Oth)
- [Related Entries](https://plato.stanford.edu/entries/category-theory/#Rel)

---

## 1. General Definitions, Examples and Applications

### 1.1 Definitions

Categories are algebraic structures with many complementary natures, e.g., geometric, logical, computational, combinatorial, just as groups are many-faceted algebraic structures. Eilenberg & Mac Lane (1945) introduced categories in a purely auxiliary fashion, as preparation for what they called functors and natural transformations. The very definition of a category evolved over time, according to the author’s chosen goals and metamathematical framework. Eilenberg & Mac Lane at first gave a purely abstract definition of a category, along the lines of the axiomatic definition of a group. Others, starting with Grothendieck (1957) and Freyd (1964), elected for reasons of practicality to define categories in set-theoretic terms.

An alternative approach, that of Lawvere (1963, 1966), begins by characterizing the category of categories, and then stipulates that a category is an object of that universe. This approach, under active development by various mathematicians, logicians and mathematical physicists, lead to what are now called “higher-dimensional categories” (Baez 1997, Baez & Dolan 1998a, Batanin 1998, Leinster 2002, Hermida _et al_. 2000, 2001, 2002). The very definition of a category is not without philosophical importance, since one of the objections to category theory as a foundational framework is the claim that since categories are _defined_ as sets, category theory cannot provide a philosophically enlightening foundation for mathematics. We will briefly go over some of these definitions, starting with Eilenberg’s & Mac Lane’s (1945) algebraic definition. However, before going any further, the following definition will be required.

**Definition**: A mapping e will be called an _identity_ if and only if the existence of any product eα or βe implies that eα=α and βe=β

Here is the original definition of a category.

**Definition** (Eilenberg & Mac Lane 1945): A category C is an aggregate Ob of abstract elements, called the _objects_ of C, and abstract elements **Map**, called _mappings_ of the category. The mappings are subject to the following five axioms:

(C1) Given three mappings α1,α2 and α3, the triple product α3(α2α1) is defined if and only if (α3α2)α1 is defined. When either is defined, the associative law

α3(α2α1)=(α3α2)α1

holds. This triple product is written α3α2α1.

(C2) The triple product α3α2α1 is defined whenever both products α3α2 and α2α1 are defined.

(C3) For each mapping α, there is at least one identity e1 such that αe1 is defined, and at least one identity e2 such that e2α is defined.

(C4) The mapping eX corresponding to each object X is an identity.

(C5) For each identity e there is a unique object X of C such that eX=e.

As Eilenberg & Mac Lane promptly remark, objects play a secondary role and could be entirely omitted from the definition. Doing so, however, would make the manipulation of the applications less convenient. It is practically suitable, and perhaps psychologically more simple to think in terms of mappings and objects. The term “aggregate” is used by Eilenberg & Mac Lane themselves, presumably so as to remain neutral with respect to the background set theory one wants to adopt.

Eilenberg & Mac Lane defined categories in 1945 for reasons of rigor. As they note:

> It should be observed first that the whole concept of a category is essentially an auxiliary one; our basic concepts are essentially those of a functor and of natural transformation (…). The idea of a category is required only by the precept that every function should have a definite class as domain and a definite class as range, for the categories are provided as the domains and ranges of functors. Thus one could drop the category concept altogether and adopt an even more intuitive standpoint, in which a functor such as “Hom” is not defined over the category of “all” groups, but for each particular pair of groups which may be given. The standpoint would suffice for applications, inasmuch as none of our developments will involve elaborate constructions on the categories themselves. (1945, chap. 1, par. 6, p. 247)

Things changed in the following ten years, when categories started to be used in algebraic topology and homological algebra. Mac Lane, Buchsbaum, Grothendieck and Heller were considering categories in which the collections of morphisms between two fixed objects have an additional structure. More specifically, given any two objects X and Y of a category C, the _set_ Hom(X,Y) of morphisms from X to Y form an abelian group. Furthermore, for reasons related to the ways homology and cohomology theories are linked, the definition of a category had to satisfy an additional formal property (which we will leave aside for the moment): it had to be self-dual. These requirements lead to the following definition.

**Definition**: A category C can be described as a set Ob, whose members are the objects of C, satisfying the following three conditions:

_Morphism_ : For every pair X,Y of objects, there is a set Hom(X,Y), called the _morphisms_ from X to Y in C. If f is a morphism from X to Y, we write f:X→Y.

_Identity_ : For every object X, there exists a morphism idX in Hom(X,X), called the _identity_ on X.

_Composition_ : For every triple X,Y and Z of objects, there exists a partial binary operation from Hom(X,Y)×Hom(Y,Z) to Hom(X,Z), called the composition of morphisms in C. If f:X→Y and g:Y→Z, the composition of f and g is notated (g∘f):X→Z.

Identity, morphisms, and composition satisfy two axioms:

_Associativity_ : If f:X→Y,g:Y→Z and h:Z→W, then h∘(g∘f)=(h∘g)∘f.

_Identity_ : If f:X→Y, then (idY∘f)=f and (f∘idX)=f.

This is the definition one finds in most textbooks of category theory. As such it explicitly relies on a set theoretical background and language. An alternative, suggested by Lawvere in the early sixties, is to develop an adequate language and background framework for a category of categories. We will not present the formal framework here, for it would take us too far from our main concern, but the basic idea is to define what are called weak n-categories (and weak ω-categories), and what had been called categories would then be called weak 1-categories (and sets would be weak 0-categories). (See, for instance, Baez 1997, Makkai 1998, Leinster 2004, Baez & May 2010, Simpson 2011.)

Also in the sixties, Lambek proposed to look at categories as deductive systems. This begins with the notion of a _graph_, consisting of two classes _Arrows_ and _Objects_, and two mappings between them, s:Arrows→Objects and t:Arrows→Objects, namely the source and the target mappings. The arrows are usually called the “oriented edges” and the objects “nodes” or “vertices”. Following this, a _deductive system_ is a graph with a specified arrow:

(R1) idX:X→X,

and a binary operation on arrows:

(R2) Given f:X→Y and g:Y→Z, the composition of f and g is (g∘f):X→Z.

Of course, the objects of a deductive system are normally thought of as _formulas_, the arrows are thought of as _proofs_ or _deductions_, and operations on arrows are thought of as _rules of inference_. A _category_ is then defined thus:

**Definition** (Lambek): A _category_ is a deductive system in which the following equations hold between proofs: for all f:X→Y,g:Y→Z and h:Z→W,

(E1) f∘idX=f,   idY∘f=f,   h∘(g∘f)=(h∘g)∘f.

Thus, by imposing an adequate equivalence relation upon proofs, any deductive system can be turned into a category. It is therefore legitimate to think of a category as an algebraic encoding of a deductive system. This phenomenon is already well-known to logicians, but probably not to its fullest extent. An example of such an algebraic encoding is the Lindenbaum-Tarski algebra, a Boolean algebra corresponding to classical propositional logic. Since a Boolean algebra is a poset, it is also a category. (Notice also that Boolean algebras with appropriate homomorphisms between them form another useful category in logic.) Thus far we have merely a change of vocabulary. Things become more interesting when first-order and higher-order logics are considered. The Lindenbaum-Tarski algebra for these systems, when properly carried out, yields categories, sometimes called “conceptual categories” or “syntactic categories” (Mac Lane & Moerdijk 1992, Makkai & Reyes 1977, Pitts 2000).

### 1.2 Examples

Almost every known example of a mathematical structure with the appropriate structure-preserving map yields a category.

1. The category _Set_ with objects sets and morphisms the usual functions. There are variants here: one can consider partial functions instead, or injective functions or again surjective functions. In each case, the category thus constructed is different.
2. The category _Top_ with objects topological spaces and morphisms continuous functions. Again, one could restrict morphisms to _open_ continuous functions and obtain a different category.
3. The category _hoTop_ with objects topological spaces and morphisms equivalence classes of homotopic functions. This category is not only important in mathematical practice, it is at the core of algebraic topology, but it is also a fundamental example of a category in which morphisms are _not_ structure preserving functions.
4. The category _Vec_ with objects vector spaces and morphisms linear maps.
5. The category _Diff_ with objects differential manifolds and morphisms smooth maps.
6. The categories _Pord_ and _PoSet_ with objects preorders and posets, respectively, and morphisms monotone functions.
7. The categories _Lat_ and _Bool_ with objects lattices and Boolean algebras, respectively, and morphisms structure preserving homomorphisms, i.e., (⊤,⊥,∧,∨) homomorphisms.
8. The category _Heyt_ with objects Heyting algebras and (⊤,⊥,∧,∨,→) homomorphisms.
9. The category _Mon_ with objects monoids and morphisms monoid homomorphisms.
10. The category _AbGrp_ with objects abelian groups and morphisms group homomorphisms, i.e. (1,×,(−)−1) homomorphisms.
11. The category _Grp_ with objects groups and morphisms group homomorphisms, i.e. (1,×,(−)−1) homomorphisms.
12. The category _Rings_ with objects rings (with unit) and morphisms ring homomorphisms, i.e. (0,1,+,×) homomorphisms.
13. The category _Fields_ with objects fields and morphisms fields homomorphisms, i.e. (0,1,+,×) homomorphisms.
14. Any deductive system T with objects formulae and morphisms proofs.

These examples nicely illustrates how category theory treats the notion of structure in a uniform manner. Note that a category is characterized by its morphisms, and not by its objects. Thus the category of topological spaces with open maps differs from the category of topological spaces with continuous maps — or, more to the point, the categorical properties of the latter differ from those of the former.

We should underline again the fact that not all categories are made of structured sets with structure-preserving maps. Thus any preordered set is a category. For given two elements p,q of a preordered set, there is a morphism f:p→q if and only if p≤q. Hence a preordered set is a category in which there is at most one morphism between any two objects. Any monoid (and thus any group) can be seen as a category: in this case the category has only one object, and its morphisms are the elements of the monoid. Composition of morphisms corresponds to multiplication of monoid elements. That the monoid axioms correspond to the category axioms is easily verified.

Hence the notion of category generalizes those of preorder and monoid. We should also point out that a groupoid has a very simple definition in a categorical context: it is a category in which every morphism is an isomorphism, that is for any morphism f:X→Y, there is a morphism g:Y→X such that f∘g=idY and g∘f=idX.

### 1.3 Fundamental Concepts of the Theory

Category theory unifies mathematical structures in two different ways. First, as we have seen, almost every set theoretically defined mathematical structure with the appropriate notion of homomorphism yields a category. This is a unification provided _within_ a set theoretical environment. Second, and perhaps even more important, once a type of structure has been defined, it is imperative to determine how new structures can be constructed out of the given one. For instance, given two sets A and B, set theory allows us to construct their Cartesian product A×B. It is also imperative to determine how given structures can be decomposed into more elementary substructures. For example, given a finite Abelian group, how can it be decomposed into a product of certain of its subgroups? In both cases, it is necessary to know how structures of a certain kind may combine. The nature of these combinations might appear to be considerably different when looked at from a purely set theoretical perspective.

Category theory reveals that many of these constructions are in fact certain objects in a category having a “universal property”. Indeed, from a categorical point of view, a Cartesian product in set theory, a direct product of groups (Abelian or otherwise), a product of topological spaces, and a conjunction of propositions in a deductive system are all instances of a categorical product characterized by a universal property. Formally, a _product_ of two objects X and Y in a category C is an object Z of C _together_ with two morphisms, called the projections, p:Z→X and q:Z→Y such that—and this is the universal property—for all objects W with morphisms f:W→X and g:W→Y, there is a unique morphism h:W→Z such that p∘h=f and q∘h=g.

Note that we have defined a product for X and Y and not _the_ product for X and Y. Indeed, products and other objects with a universal property are defined only up to a (unique) isomorphism. Thus in category theory, the nature of the elements constituting a certain construction is irrelevant. What matters is the way an object is related to the other objects of the category, that is, the morphisms going in and the morphisms going out, or, put differently, how certain structures can be mapped into a given object and how a given object can map its structure into other structures of the same kind.

Category theory reveals how different kinds of structures are related to one another. For instance, in algebraic topology, topological spaces are related to groups (and modules, rings, etc.) in various ways (such as homology, cohomology, homotopy, K-theory). As noted above, groups with group homomorphisms constitute a category. Eilenberg & Mac Lane invented category theory precisely in order to clarify and compare these connections. What matters are the morphisms between categories, given by functors. Informally, functors are structure-preserving maps between categories. Given two categories C and D, a functor F from C to D sends objects of C to objects of D, and morphisms of C to morphisms of D, in such a way that composition of morphisms in C is preserved, i.e., F(g∘f)=F(g)∘F(f), and identity morphisms are preserved, i.e., F(idX)=idFX. It immediately follows that a functor preserves commutativity of diagrams between categories. Homology, cohomology, homotopy, K-theory are all example of functors.

A more direct example is provided by the power set operation, which yields two functors on the category of sets, depending on how one defines its action on functions. Thus given a set X,℘(X) is the usual set of subsets of X, and given a function f:X→Y,℘(f):℘(X)→℘(Y) takes a subset A of X and maps it to B=f(A), the image of f restricted to A in X. It is easily verified that this defines a functor from the category of sets into itself.

In general, there are many functors between two given categories, and the question of how they are connected suggests itself. For instance, given a category C, there is always the identity functor from C to C which sends every object/morphism of C to itself. In particular, there is the identity functor over the category of sets.

Now, the identity functor is related in a natural manner to the power set functor described above. Indeed, given a set X and its power set ℘(X), there is a function hX which takes an element x of X and sends it to the singleton set {x}, a subset of X, i.e., an element of ℘(X). This function in fact belongs to a family of functions indexed by the objects of the category of sets {hY:Y→℘(X)|Y in Ob(Set)}. Moreover, it satisfies the following commutativity condition: given any function f:X→Y, the identity functor yields the same function Id(f):Id(X)→Id(Y). The commutativity condition thus becomes: hY∘Id(f)=℘(f)∘hX. Thus the family of functions h(-) relates the two functors in a natural manner. Such families of morphisms are called _natural transformations_ between functors. Similarly, natural transformations between models of a theory yield the usual homomorphisms of structures in the traditional set theoretical framework.

The above notions, while important, are not fundamental to category _theory_. The latter heading arguably include the notions of limit/colimit; in turn, these are special cases of what is certainly the cornerstone of category theory, the concept of adjoint functors, first defined by Daniel Kan in 1956 and published in 1958.

Adjoint functors can be thought of as being conceptual inverses. This is probably best illustrated by an example. Let U:Grp→Set be the forgetful functor, that is, the functor that sends to each group G its underlying set of elements U(G), and to a group homomorphism f:G→H the underlying set function U(f):U(G)→U(H). In other words, U forgets about the group structure and forgets the fact that morphisms are group homomorphisms. The categories Grp and Set are certainly not isomorphic, as categories, to one another. (A simple argument runs as follows: the category Grp has a zero object, whereas Set does not.) Thus, we certainly cannot find an inverse, in the usual algebraic sense, to the functor U. But there are many non-isomorphic ways to define a group structure on a given set X, and one might hope that among these constructions at least one is functorial and systematically related to the functor U. What is the conceptual inverse to the operation of forgetting all the group theoretical structure and obtaining a set? It is to construct a group from a set solely on the basis of the concept of group and nothing else, i.e., with no extraneous relation or data. Such a group is constructed “freely”; that is, with no restriction whatsoever except those imposed by the axioms of the theory. In other words, all that is remembered in the process of constructing a group from a given set is the fact that the resulting construction has to be a group. Such a construction exists; it is functorial and it yields what are called _free groups_. In other words, there is a functor F:Set→Grp, which to any set X assigns the free group F(X) on X, and to each function f:X→Y, the group homomorphism F(f):F(X)→F(Y), defined in the obvious manner. The situation can be described thusly: we have two conceptual contexts, a group theoretical context and a set theoretical context, and two functors moving systematically from one context to the other in opposite directions. One of these functors is elementary, namely the forgetful functor U. It is apparently trivial and uninformative. The other functor is mathematically significant and important. The surprising fact is that F is related to U by a simple rule and, in some sense, it arises from U. One of the striking features of adjoint situations is precisely the fact that fundamental mathematical and logical constructions arise out of given and often elementary functors.

The fact that U and F are conceptual inverses expresses itself formally as follows: applying F first and then U does not yield the original set X, but there is a fundamental relationship between X and UF(X). Indeed, there is a function η: X→UF(X), called the _unit of the adjunction_, that simply sends each element of X to itself in UF(X) and this function satisfies the following universal property: given any function g:X→U(G), there is a unique _group homomorphism_ h:F(X)→G such that U(h)∘η=g. In other words, UF(X) is the best possible solution to the problem of inserting elements of X into a group (what is called “insertion of generators” in the mathematical jargon). Composing U and F in the opposite order, we get a morphism ξ:FU(G)→G, called the _counit of the adjunction_, satisfying the following universal property: for any group homomorphism g:F(X)→G, there is a unique function h:X→U(G) such that ξ∘F(h)=g. In other words, FU(G) constitutes the best possible solution to the problem of finding a representation of G as a quotient of a free group. If U and F were simple algebraic inverses to one another, we would have the following identity: UF=ISet and FU=IGrp, where ISet denotes the identity functor on Set and IGrp the identity functor on Grp. As we have indicated, these identities certainly do not hold in this case. However, some identities do hold: they are best expressed with the help of the commutative diagrams:

|   |   |   |
|---|---|---|
|Uη∘U−−−→UFU↘↓U∘ξU||FF∘η−−−→FUF↘↓ξ∘FF|

where the diagonal arrows denote the appropriate identity natural transformations.

This is but one case of a very common situation: every free construction can be described as arising from an appropriate forgetful functor between two adequately chosen categories. The number of mathematical constructions that can be described as adjoints is simply stunning. Although the details of each one of these constructions vary considerably, the fact that they can all be described using the same language illustrates the profound unity of mathematical concepts and mathematical thinking. Before we give more examples, a formal and abstract definition of adjoint functors is in order.

**Definition**: Let F:C→D and G:D→C be functors going in opposite directions. F is a _left adjoint_ to G(G a _right adjoint_ to F), denoted by F⊣G, if there exists natural transformations η:IC→GF and ξ:FG→ID, such that the composites

Gη∘G−−−→GFGG∘ξ−−−→G

and

FF∘η−−−→FGFξ∘F−−−→F

are the identity natural transformations. (For different but equivalent definitions, see Mac Lane 1971 or 1998, chap. IV.)

Here are some of the important facts regarding adjoint functors. Firstly, adjoints are unique up to isomorphism; that is any two left adjoints F and F′ of a functor G are naturally isomorphic. Secondly, the notion of adjointness is formally equivalent to the notion of a universal morphism (or construction) and to that of representable functor. (See, for instance Mac Lane 1998, chap. IV.) Each and every one of these notions exhibit an aspect of a given situation. Thirdly, a left adjoint preserves all the colimits which exist in its domain, and, dually, a right adjoint preserves all the limits which exist in its domain.

We now give some examples of adjoint situations to illustrate the pervasiveness of the notion.

1. Instead of having a forgetful functor going into the category of sets, in some cases only a part of the structure is forgotten. Here are two standard examples:
    - There is an obvious forgetful functor U: **AbGrp** → **AbMon** from the category of abelian groups to the category of abelian monoids: U forgets about the inverse operation. The functor U has a left adjoint F: **AbMon** → **AbGrp** which, given an abelian monoid M, assigns to it the best possible abelian group F(M) such that M can be embedded in F(M) as a submonoid. For instance, if M is N, then F(N) “is” Z, that is, it is isomorphic to Z.
    - Similarly, there is an obvious forgetful functor U:Haus→Top from the category of Hausdorff topological spaces to the category of topological spaces which forgets the Hausdorff condition. Again, there is a functor F:Top→Haus such that F⊣U. Given a topological space X,F(X) yields the best Hausdorff space constructed from X: it is the quotient of X by the closure of the diagonal ¯¯¯¯¯ΔX⊆X×X, which is an equivalence relation. In contrast with the previous example where we had an embedding, this time we get a quotient of the original structure.
2. Consider now the category of _compact_ Hausdorff spaces **kHaus** and the forgetful functor U: **kHaus** →Top, which forgets the compactness property and the separation property. The left adjoint to this U is the Stone-Cech compactification.
3. There is a forgetful functor U:ModR→ **AbGrp** from a category of R-modules to the category of abelian groups, where R is a commutative ring with unit. The functor U forgets the action of R on a group G. The functor U has both a left and a right adjoint. The left adjoint is R⊗−: **AbGrp** →ModR which sends an abelian group G to the tensor product R⊗G and the right adjoint is given by the functor Hom(R,−): **AbGrp** →ModR which assigns to any group G the modules of linear mappings Hom(R,G).
4. The case where the categories C and D are posets deserves special attention here. Adjoint functors in this context are usually called _Galois connections_. Let C be a poset. Consider the diagonal functor Δ:C→C×C, with Δ(X)=⟨X,X⟩ and for f:X→Y,Δ(f)=⟨f,f⟩:⟨X,X⟩→⟨Y,Y⟩. In this case, the left-adjoint to Δ is the coproduct, or the sup, and the right-adjoint to Δ is the product, or the inf. The adjoint situation can be described in the following special form:X∨Y≤ZX≤Z,Y≤Z⇕Z≤X∧YZ≤Y,Z≤X⇕
    
    where the vertical double arrow can be interpreted as rules of inference going in both directions.
    
5. Implication can also be introduced. Consider a functor with a parameter: (−∧X):C→C. It can easily be verified that when C is a poset, the function (−∧X) is order preserving and therefore a functor. A right adjoint to (−∧X) is a functor that yields the largest element of C such that its infimum with X is smaller than Z. This element is sometimes called the relative pseudocomplement of X or, more commonly, the _implication_. It is denoted by _X ⇒ Z_ or by X⊃Z. The adjunction can be presented as follows:Y∧X≤ZY≤X⇒Z⇕
6. The negation operator ¬X can be introduced from the last adjunction. Indeed, let Z be the bottom element ⊥ of the lattice. Then, since Y∧X≤⊥ is always true, it follows that Y≤X⇒⊥ is also always true. But since X⇒⊥≤X is always the case, we get at the numerator that (X⇒⊥∧X)=⊥. Hence, X⇒⊥ is the largest element disjoint from X. We can therefore put ¬X=defX⇒⊥.
7. Limits, colimits, and all the fundamental constructions of category theory can be described as adjoints. Thus, products and coproducts are adjoints, as are equalizers, coequalizers, pullbacks and pushouts, etc. This is one of the reasons adjointness is central to category theory itself: because all the fundamental operations of category theory arise from adjoint situations.
8. An _equivalence of categories_ is a special case of adjointness. Indeed, if in the above triangular identities the arrows η:IC→GF and ξ:FG→ID are natural _isomorphisms_, then the functors F and G constitute an _equivalence_ of categories. In practice, it is the notion of equivalence of categories that matters and not the notion of isomorphism of categories.

It is easy to prove certain facts about these operations directly from the adjunctions. Consider, for instance, implication. Let Z=X. Then we get at the numerator that Y∧X≤X, which is always true in a poset (as is easily verified). Hence, Y≤X⇒X is also true for all Y and this is only possible if X⇒X=⊤, the top element of the lattice. Not only can logical operations be described as adjoints, but they naturally arise as adjoints to basic operations. In fact, adjoints can be used to define various structures, distributive lattices, Heyting algebras, Boolean algebras, etc. (See Wood, 2004.) It should be clear from the simple foregoing example how the formalism of adjointness can be used to give syntactic presentations of various logical theories. Furthermore, and this is a key element, the standard universal and existential quantifiers can be shown to be arising as adjoints to the operation of substitution. Thus, quantifiers are on a par with the other logical operations, in sharp contrast with the other algebraic approaches to logic. (See, for instance Awodey 1996 or Mac Lane & Moerdijk 1992.) More generally, Lawvere showed how syntax and semantics are related by adjoint functors. (See Lawvere 1969b.)

Dualities play an important role in mathematics and they can be described with the help of equivalences between categories. In other words, many important mathematical theorems can be translated as statements about the existence of adjoint functors, sometimes satisfying additional properties. This is sometimes taken as expressing the _conceptual_ content of the theorem. Consider the following fundamental case: let C be the category whose objects are the locally compact abelian groups and the morphisms are the continuous group homomorphisms. Then, the Pontryagin duality theorem amounts to the claim that the category C is equivalent to the category C°, that is, to the opposite category. Of course, the precise statement requires that we describe the functors F:C→C° and G:C° →C and prove that they constitute an equivalence of categories.

Another well known and important duality was discovered by Stone in the thirties and now bears his name. In one direction, an arbitrary Boolean algebra yields a topological space, and in the other direction, from a (compact Hausdorff and totally disconnected) topological space, one obtains a Boolean algebra. Moreover, this correspondence is functorial: any Boolean homomorphism is sent to a continuous map of topological spaces, and, conversely, any continuous map between the spaces is sent to a Boolean homomorphism. In other words, there is an equivalence of categories between the category of Boolean algebras and the dual of the category of Boolean spaces (also called Stone spaces). (See Johnstone 1982 for an excellent introduction and more developments.) The connection between a category of algebraic structures and the opposite of a category of topological structures established by Stone’s theorem constitutes but one example of a general phenomenon that did attract and still attracts a great deal of attention from category theorists. Categorical study of duality theorems is still a very active and significant field, and is largely inspired by Stone’s result. (For recent applications in logic, see, for instance Makkai 1987, Taylor 2000, 2002a, 2002b, Caramello 2011.)

## 2. Brief Historical Sketch

It is difficult to do justice to the short but intricate history of the field. In particular it is not possible to mention all those who have contributed to its rapid development. With this word of caution out of the way, we will look at some of the main historical threads.

Categories, functors, natural transformations, limits and colimits appeared almost out of nowhere in a paper by Eilenberg & Mac Lane (1945) entitled “General Theory of Natural Equivalences.” We say “almost,” because their earlier paper (1942) contains specific functors and natural transformations at work, limited to groups. A desire to clarify and abstract their 1942 results led Eilenberg & Mac Lane to devise category theory. The central notion at the time, as their title indicates, was that of natural transformation. In order to give a general definition of the latter, they defined functor, borrowing the term from Carnap, and in order to define functor, they borrowed the word ‘category’ from the philosophy of Aristotle, Kant, and C. S. Peirce, but redefining it mathematically.

After their 1945 paper, it was not clear that the concepts of category theory would amount to more than a convenient language; this indeed was the status quo for about fifteen years. Category theory was employed in this manner by Eilenberg & Steenrod (1952), in an influential book on the foundations of algebraic topology, and by Cartan & Eilenberg (1956), in a ground breaking book on homological algebra. (Curiously, although Eilenberg & Steenrod defined categories, Cartan & Eilenberg simply assumed them!) These books allowed new generations of mathematicians to learn algebraic topology and homological algebra directly in the categorical language, and to master the method of diagrams. Indeed, without the method of diagram chasing, many results in these two books seem inconceivable, or at the very least would have required a considerably more intricate presentation.

The situation changed radically with Grothendieck’s (1957) landmark paper entitled “Sur quelques points d’algèbre homologique”, in which the author employed categories intrinsically to define and construct more general theories which he (Grothendieck 1957) then applied to specific fields, e.g., to algebraic geometry. Kan (1958) showed that adjoint functors subsume the important concepts of limits and colimits and could capture fundamental concepts in other areas (in his case, homotopy theory).

At this point, category theory became more than a convenient language, by virtue of two developments.

1. Employing the axiomatic method and the language of categories, Grothendieck (1957) defined in an abstract fashion types of categories, e.g., additive and Abelian categories, showed how to perform various constructions in these categories, and proved various results about them. (It should be pointed out that Mac Lane in his 1950 paper had made a previous attempt which introduced certain key ideas, for instance using arrows to define certain fundamental concepts and that Buchsbaum had essentially introduced the notion of an abelian category independently under the name of “exact category” in 1955.) In a nutshell, Grothendieck showed how to develop part of homological algebra in an abstract setting of this sort. From then on, a specific category of structures, e.g., a category of sheaves over a topological space X, could be seen as a token of an abstract category of a certain type, e.g., an Abelian category. One could therefore immediately see how the methods of, e.g., homological algebra could be applied to, for instance, algebraic geometry. Furthermore, it made sense to look for other types of abstract categories, ones that would encapsulate the fundamental and formal aspects of various mathematical fields in the same way that Abelian categories encapsulated fundamental aspects of homological algebra.
2. Thanks in large part to the efforts of Freyd and Lawvere, category theorists gradually came to see the pervasiveness of the concept of adjoint functors. Not only does the existence of adjoints to given functors permit definitions of abstract categories (and presumably those which are defined by such means have a privileged status) but as we mentioned earlier, many important theorems and even theories in various fields can be seen as equivalent to the existence of specific functors between particular categories. By the early 1970s, the concept of adjoint functors was seen as central to category theory.

With these developments, category theory became an autonomous field of research, and pure category theory could be developed. And indeed, it did grow rapidly as a discipline, but also in its applications, mainly in its source contexts, namely algebraic topology and homological algebra, but also in algebraic geometry and, after the appearance of Lawvere’s Ph.D. thesis, in universal algebra. This thesis also constitutes a landmark in this history of the field, for in it Lawvere proposed the category of categories as a foundation for category theory, set theory and, thus, the whole of mathematics, as well as using categories for the study of the logical aspects of mathematics.

Over the course of the 1960s, Lawvere outlined the basic framework for an entirely original approach to logic and the foundations of mathematics. He achieved the following:

- Axiomatized the category of sets (Lawvere 1964) and of categories (Lawvere 1966);
- Gave a categorical description of theories that was independent of syntactical choices and sketched how completeness theorems for logical systems could be obtained by categorical methods (Lawvere 1967);
- Characterized Cartesian closed categories and showed their connections to logical systems and various logical paradoxes (Lawvere 1969);
- Showed that the quantifiers and the comprehension schemes could be captured as adjoint functors to given elementary operations (Lawvere 1966, 1969, 1970, 1971);
- Argued that adjoint functors should generally play a major foundational role through the notion of “categorical doctrines” (Lawvere 1969).

Meanwhile, Lambek (1968, 1969, 1972) described categories in terms of deductive systems and employed categorical methods for proof-theoretical purposes.

All this work culminated in another notion, thanks to Grothendieck and his school: that of a _topos_. Even though toposes appeared in the 1960s, in the context of algebraic geometry, again from the mind of Grothendieck, it was certainly Lawvere and Tierney’s (1972) elementary axiomatization of a topos which gave impetus to its attaining foundational status. Very roughly, an elementary topos is a category possessing a logical structure sufficiently rich to develop most of “ordinary mathematics”, that is, most of what is taught to mathematics undergraduates. As such, an elementary topos can be thought of as a categorical theory of sets. But it is also a generalized topological space, thus providing a direct connection between logic and geometry. (For more on the history of categorical logic, see Marquis & Reyes 2012, Bell 2005.)

The 1970s saw the development and application of the topos concept in many different directions. The very first applications outside algebraic geometry were in set theory, where various independence results were recast in terms of topos (Tierney 1972, Bunge 1974, but also Blass & Scedrov 1989, Blass & Scedrov 1992, Freyd 1980, Mac Lane & Moerdijk 1992, Scedrov 1984). Connections with intuitionistic and, more generally constructive mathematics were noted early on, and toposes are still used to investigate models of various aspects of intuitionism and constructivism (Lambek & Scott 1986, Mac Lane & Moerdijk 1992, Van der Hoeven & Moerdijk 1984a, 1984b, 1984c, Moerdijk 1984, Moerdijk 1995a, Moerdijk 1998, Moerdijk & Palmgren 1997, Moerdijk & Palmgren 2002, Palmgren 2012, Palmgren 2018. For more on the history of topos theory, see McLarty 1992 and Bell 2012).

More recently, topos theory has been employed to investigate various forms of constructive mathematics or set theory (Joyal & Moerdijk 1995, Taylor 1996, Awodey 2008), recursiveness, and models of higher-order type theories generally. The introduction of the so-called “effective topos” and the search for axioms for synthetic domain theory are worth mentioning (Hyland 1982, Hyland 1988, 1991, Hyland _et al_. 1990, McLarty 1992, Jacobs 1999, Van Oosten 2008, Van Oosten 2002 and the references therein). Lawvere’s early motivation was to provide a new foundation for differential geometry, a lively research area which is now called “synthetic differential geometry” (Lawvere 2000, 2002, Kock 2006, Bell 1988, 1995, 1998, 2001, Moerdijk & Reyes 1991). This is only the tip of the iceberg; toposes could prove to be for the 21st century what Lie groups were to the 20th century.

From the 1980s to the present, category theory has found new applications. In theoretical computer science, category theory is now firmly rooted, and contributes, among other things, to the development of new logical systems and to the semantics of programming. (Pitts 2000, Plotkin 2000, Scott 2000, and the references therein). Its applications to mathematics are becoming more diverse, even touching on theoretical physics, which employs higher-dimensional category theory — which is to category theory what higher-dimensional geometry is to plane geometry — to study the so-called “quantum groups” and quantum field theory (Majid 1995, Baez & Dolan 2001 and other publications by these authors).

## 3. Philosophical Significance

Category theory challenges philosophers in two ways, which are not necessarily mutually exclusive. On the one hand, it is certainly the task of philosophy to clarify the general epistemological and ontological status of categories and categorical methods, both in the practice of mathematics and in the foundational landscape. On the other hand, philosophers and philosophical logicians can employ category theory and categorical logic to explore philosophical and logical problems. I now discuss these challenges, briefly, in turn.

Category theory is now a common tool in the mathematician’s toolbox; that much is clear. It is also clear that category theory organizes and unifies much of mathematics. Contemporary mathematical fields would not be what they are without category theory, for instance algebraic topology, homological algebra, homotopy theory and homotopical algebra, representation theory, arithmetic geometry and algebraic geometry. (See for instance Mac Lane 1971, 1998 or Pedicchio & Tholen 2004.) No one will deny these simple facts. Furthermore, vast portions of contemporary mathematics now rest on a different practice which rely, in large part, on the manipulation of new graphical notations, on the one hand, and on different levels of abstraction, on the other hand. It is not simply that category theory and the mathematical disciplines developed within that framework use commutative diagrams, although this in itself leads to some interesting philosophical explorations, as for instance in De Toffoli 2017, but category theorists have seen the need to develop systematic and formal graphical languages to express directly various forms of argumentations. (See, for instance, Joyal & Street 1993; Joyal, Street & Verity 1996; Fong & Spivak 2019, Other Internet Resources.) Whereas since Bourbaki, mathematics was done “up to isomorphism”, in some cases, it is now done “up to equivalence” or up to “bi-equivalence” or even up to “n-equivalence”. (For an attempt at clarifying what these levels of abstraction mean, see Marquis 2014, Marquis 2016.)

Doing mathematics in a categorical framework is almost always radically different from doing it in a set-theoretical framework (the exception being working with the internal language of a Boolean topos; whenever the topos is not Boolean, then the main difference lies in the fact that the logic is _intuitionistic_). Hence, as is often the case when a different conceptual framework is adopted, many basic issues regarding the nature of the objects studied, the nature of the knowledge involved, and the nature of the methods used have to be reevaluated. We will take up these three aspects in turn.

Two facets of the nature of mathematical objects within a categorical framework have to be emphasized. First, objects are always given in a category. An object exists in and depends upon an ambient category. Furthermore, an object is characterized by the morphisms going in it and/or the morphisms coming out of it. Second, objects are always characterized up to isomorphism (in the best cases, up to a unique isomorphism). There is no such thing, for instance, as _the_ natural numbers. However, it can be argued that there is such a thing as _the concept_ of natural numbers. Indeed, the concept of natural numbers can be given unambiguously, via the Dedekind-Peano-Lawvere axioms, but what this concept refers to in specific cases depends on the context in which it is interpreted, e.g., the category of sets or a topos of sheaves over a topological space. Thus, it seems that sense does not determine reference in a categorical context. It is hard to resist the temptation to think that category theory embodies a form of structuralism, that it describes mathematical objects as structures since the latter, presumably, are always characterized up to isomorphism. Thus, the key here has to do with the kind of criterion of identity at work within a categorical framework and how it resembles any criterion given for objects which are thought of as forms in general. One of the standard objections presented against this view is that if objects are thought of as structures and only as _abstract_ structures, meaning here that they are separated from any specific or concrete representation, then it is impossible to locate them within the mathematical universe. (See Hellman 2003 for a standard formulation of the objection, McLarty 1993, Awodey 2004, Landry & Marquis 2005, Shapiro 2005, Landry 2011, Linnebo & Pettigrew 2011, Hellman 2011, Shapiro 2011, McLarty 2011, Logan 2015 for relevant material on the issue.)

A slightly different way to make sense of the situation is to think of mathematical objects as _types_ for which there are tokens given in different contexts. This is strikingly different from the situation one finds in set theory, in which mathematical objects are defined uniquely and their reference is given directly. Although one can make room for types within set theory via equivalence classes or isomorphism types in general, the _basic_ criterion of identity within that framework is given by the axiom of extensionality and thus, ultimately, reference is made to specific sets. Furthermore, it can be argued that the relation between a type and its token is _not_ represented adequately by the membership relation. A token does not belong to a type, it is not an element of a type, but rather it is an instance of it. In a categorical framework, one always refers to a _token_ of a type, and what the theory characterizes directly is the type, not the tokens. In this framework, one does not have to locate a type, but tokens of it are, at least in mathematics, epistemologically required. This is simply the reflection of the interaction between the abstract and the concrete in the epistemological sense (and not the ontological sense of these latter expressions.) (See Ellerman 1988, Ellerman 2017, Marquis 2000, Marquis 2006, Marquis 2013.)

The history of category theory offers a rich source of information to explore and take into account for an historically sensitive epistemology of mathematics. It is hard to imagine, for instance, how algebraic geometry and algebraic topology could have become what they are now without categorical tools. (See, for instance, Carter 2008, Corfield 2003, Krömer 2007, Marquis 2009, McLarty 1994, McLarty 2006.) Category theory has lead to reconceptualizations of various areas of mathematics based on purely abstract foundations. Moreover, when developed in a categorical framework, traditional boundaries between disciplines are shattered and reconfigured; to mention but one important example, topos theory provides a direct bridge between algebraic geometry and logic, to the point where certain results in algebraic geometry are directly translated into logic and vice versa. Certain concepts that were geometrical in origin are more clearly seen as logical (for example, the notion of coherent topos). Algebraic topology also lurks in the background. (See, for instance, Caramello 2018 for a systematic exploitation of the idea of toposes as bridges in mathematics.) On a different but important front, it can be argued that the distinction between mathematics and metamathematics cannot be articulated in the way it has been. All these issues have to be reconsidered and reevaluated.

Moving closer to mathematical practice, category theory allowed for the development of methods that have changed and continue to change the face of mathematics. It could be argued that category theory represents the culmination of one of deepest and most powerful tendencies in twentieth century mathematical thought: the search for the most general and abstract ingredients in a given situation. Category theory is, in this sense, the legitimate heir of the Dedekind-Hilbert-Noether-Bourbaki tradition, with its emphasis on the axiomatic method and algebraic structures. (For a different reading, see Rodin 2014.) When used to characterize a specific mathematical domain, category theory reveals the frame upon which that area is built, the overall structure presiding to its stability, strength and coherence. The structure of this specific area, in a sense, might not need to rest on anything, that is, on some solid soil, for it might very well be just one part of a larger network that is without any Archimedean point, as if floating in space. To use a well-known metaphor: from a categorical point of view, Neurath’s ship has become a spaceship.

Still, it remains to be seen whether category theory should be “on the same plane,” so to speak, as set theory, whether it should be taken as a serious alternative to set theory as a foundation for mathematics, or whether it is foundational in a different sense altogether. (That this very question applies even more forcefully to topos theory will not detain us.)

Lawvere from early on promoted the idea that a category of categories could be used as a foundational framework. (See Lawvere 1964, 1966.) This proposal now rests in part on the development of higher-dimensional categories, also called weak n-categories. (See, for instance Makkai 1998.) The advent of topos theory in the seventies brought new possibilities. Mac Lane has suggested that certain toposes be considered as a genuine foundation for mathematics. (See Mac Lane 1986.) Lambek proposed the so-called free topos as the best possible framework, in the sense that mathematicians with different philosophical outlooks might nonetheless agree to adopt it. (See Couture & Lambek 1991, 1992, Lambek 1994.) He has also argued that there is no topos that can thoroughly satisfy a classical mathematician. (See Lambek 2004.) (For more on the various foundational views among category theorists, see Landry & Marquis 2005.)

Arguments have been advanced for and against category theory as a foundational framework. (Blass 1984 surveys the relationships between category theory and set theory. Feferman 1977, Bell 1981, and Hellman 2003 argue against category theory. See Marquis 1995 for a quick overview and proposal and McLarty 2004 and Awodey 2004 for replies to Hellman 2003.) The debate has advanced slowly but surely. It has been recognized that it is possible to present a foundational framework in the language of category theory, be it in the form of the Elementary Theory of the Category of Sets, ETCS, or a category of categories, of Makkai Structuralist foundations for abstract mathematics, SFAM. Thus, it seems that the community no longer question the logical and the conceptual autonomy of these approaches, to use the terminology introduced by Linnebo & Pettigrew 2011. The main issue seems to be whether one can provide a philosophically satisfying justification for one of those framework. (See Hellman 2013, Landry 2013, Marquis 2013b, McLarty 2018.)

This matter is further complicated by the fact that the foundations of category theory itself have yet to be clarified. For there may be many different ways to think of a universe of higher-dimensional categories as a foundations for mathematics. It is safe to say that we now have a good understanding of what are called (∞,1)-categories and important mathematical results have been obtained in that framework. (See, for instance, Cisinski 2019 for a presentation.) An adequate language for the universe of arbitrary higher-dimensional categories still has to be presented together with definite axioms for mathematics. (See Makkai 1998 for a short description of such a language. A different approach based on homotopy theory but with closed connections with higher-dimensional categories has been proposed by Voevodsky et al. and is being vigorously pursued. See the book _Homotopy Type Theory_, by Awodey et al. 2013.)

It is an established fact that category theory is employed to study logic and philosophy. Indeed, categorical logic, the study of logic by categorical means, has been under way for about 40 years now and still vigorous. Some of the philosophically relevant results obtained in categorical logic are:

- The hierarchy of categorical doctrines: regular categories, coherent categories, Heyting categories and Boolean categories; all these correspond to well-defined logical systems, together with deductive systems and completeness theorems; they suggest that logical notions, including quantifiers, arise naturally in a specific order and are not haphazardly organized (see Walsh 2017 for a philosophical justification of logical connectives using category theory and Halvorson & Tsementzis 2018 for a look from the point of view of scientific theories);
- Joyal’s generalization of Kripke-Beth semantics for intuitionistic logic to sheaf semantics (Lambek & Scott 1986, Mac Lane & Moerdijk 1992);
- Coherent and geometric logic, so-called, whose practical and conceptual significance has yet to be explored (Makkai & Reyes 1977, Mac Lane & Moerdiejk 1992, Johnstone 2002, Caramello 2011b, 2012a);
- The notions of generic model and classifying topos of a theory (Makkai & Reyes 1977, Boileau & Joyal 1981, Bell 1988, Mac Lane & Moerdijk 1992, Johnstone 2002, Caramello 2012b);
- The notion of strong conceptual completeness and the associated theorems (Makkai & Reyes 1977, Butz & Moerdijk 1999, Makkai 1981, Pitts 1989, Johnstone 2002);
- Geometric proofs of the independence of the continuum hypothesis and other strong axioms of set theory (Tierney 1972, Bunge 1974, Freyd 1980, 1987, Blass & Scedrov 1983, 1989, 1992, Mac Lane & Moerdijk 1992);
- Models and development of constructive mathematics (see bibliography below);
- Synthetic differential geometry, an alternative to standard and non-standard analysis (Kock 1981, Bell 1998, 2001, 2006);
- The construction of the so-called effective topos, in which every function on the natural numbers is recursive (McLarty 1992, Hyland 1982, 1991, Van Oosten 2002, Van Oosten 2008);
- Categorical models of linear logic, modal logic, fuzzy sets, and general higher-order type theories (Reyes 1991, Reyes & Zawadoski 1993, Reyes & Zolfaghari 1991, 1996, Makkai & Reyes 1995, Ghilardi & Zawadowski 2002, Rodabaugh & Klement 2003, Jacobs 1999, Taylor 1999, Johnstone 2002, Blute & Scott 2004, Awodey & Warren 2009, Awodey et al. 2013, Kishida 2018, Cockett &Seely 2018);
- A graphical syntax called “sketches” (Barr & Wells 1985, 1999, Makkai 1997a, 1997b, 1997c, Johnstone 2002).
- Quantum logic, the foundations of quantum physics and quantum field theory (Brunetti et al. 2003, Abramsky & Duncan 2006, Heunen et al. 2009, Baez & Stay 2010, Baez & Lauda 2011, Coecke 2011, Isham 2011, Döring 2011, Eva 2017, Coecke & Kissinger 2018).

Categorical tools in logic offer considerable flexibility, as is illustrated by the fact that almost all the surprising results of constructive and intuitionistic mathematics can be modeled in a proper categorical setting. At the same time, the standard set-theoretic notions, e.g. Tarski’s semantics, have found natural generalizations in categories. Thus, categorical logic has roots in logic as it was developed in the twentieth century, while at the same time providing a powerful and novel framework with numerous links to other parts of mathematics.

Category theory also bears on more general philosophical questions. From the foregoing disussion, it should be obvious that category theory and categorical logic ought to have an impact on almost all issues arising in philosophy of logic: from the nature of identity criteria to the question of alternative logics, category theory always sheds a new light on these topics. Similar remarks can be made when we turn to ontology, in particular formal ontology: the part/whole relation, boundaries of systems, ideas of space, etc. Ellerman (1988) has bravely attempted to show that category theory constitutes a theory of universals, one having properties radically different from set theory, which is also seen as a theory of universals. Moving from ontology to cognitive science, MacNamara & Reyes (1994) have tried to employ categorical logic to provide a different logic of reference. In particular, they have attempted to clarify the relationships between count nouns and mass terms. Other researchers are using category theory to study complex systems, cognitive neural networks, and analogies. (See, for instance, Ehresmann 2018, Ehresmann & Vanbremeersch 1987, 2007, Healy 2000, Healy & Caudell 2006, Arzi-Gonczarowski 1999, Brown & Porter 2006.) Finally, philosophers of science have turned to category theory to shed a new light on issues related to structuralism in science. (See, for instance, Brading & Landry 2006, Bain 2013, Lam & Wüthrich 2015, Eva 2016, Lal & Teh 2017, Landry 2007, 2012, 2018.)

Category theory offers thus many philosophical challenges, challenges which will hopefully be taken up in years to come.

## Bibliography

Readers may find the following useful:

[Programmatic Reading Guide](https://plato.stanford.edu/entries/category-theory/bib.html)

The citations in this guide and in the text above can all be found in the list below.

- Abramsky, S. & Duncan, R., 2006, “A Categorical Quantum Logic”, _Mathematical Structures in Computer Science_, 16 (3): 469–489.
- Adamek, J. _et al_., 1990, _Abstract and Concrete Categories: The Joy of Cats_, New York: Wiley.
- Adamek, J. _et al_., 1994, Locally Presentable and Accessible Categories, Cambridge: Cambridge University Press.
- Arzi-Gonczaworski, Z., 1999, “Perceive This as That — Analogies, Artificial Perception, and Category Theory”, _Annals of Mathematics and Artificial Intelligence_, 26 (1): 215–252.
- Awodey, S., 1996, “Structure in Mathematics and Logic: A Categorical Perspective”, _Philosophia Mathematica_, 3: 209–237.
- –––, 2004, “An Answer to Hellman’s Question: Does Category Theory Provide a Framework for Mathematical Structuralism”, _Philosophia Mathematica_, 12: 54–64.
- –––, 2006, _Category Theory_, Oxford: Clarendon Press.
- –––, 2007, “Relating First-Order Set Theories and Elementary Toposes”, _The Bulletin of Symbolic_, 13 (3): 340–358.
- –––, 2008, “A Brief Introduction to Algebraic Set Theory”, _The Bulletin of Symbolic_, 14 (3): 281–298.
- Awodey, S., et al., 2013, _Homotopy Type Theory: Univalent Foundations of Mathematics_, The Univalent Foundations Program.
- Awodey, S. & Butz, C., 2000, “Topological Completeness for Higher Order Logic”, _Journal of Symbolic Logic_, 65 (3): 1168–1182.
- Awodey, S. & Reck, E. R., 2002, “Completeness and Categoricity I. Nineteen-Century Axiomatics to Twentieth-Century Metalogic”, _History and Philosophy of Logic_, 23 (1): 1–30.
- –––, 2002, “Completeness and Categoricity II. Twentieth-Century Metalogic to Twenty-first-Century Semantics”, _History and Philosophy of Logic_, 23 (2): 77–94.
- Awodey, S. & Warren, M., 2009, “Homotopy theoretic Models of Identity Types”, _Mathematical Proceedings of the Cambridge Philosophical Society_, 146 (1): 45–55.
- Baez, J., 1997, “An Introduction to n-Categories”, _Category Theory and Computer Science_, Lecture Notes in Computer Science (Volume 1290), Berlin: Springer-Verlag, 1–33.
- Baez, J. & Dolan, J., 1998a, “Higher-Dimensional Algebra III. n-Categories and the Algebra of Opetopes”, _Advances in Mathematics_, 135: 145–206.
- –––, 1998b, “Categorification”, _Higher Category Theory_ (Contemporary Mathematics, Volume 230), Ezra Getzler and Mikhail Kapranov (eds.), Providence: AMS, 1–36.
- –––, 2001, “From Finite Sets to Feynman Diagrams”, _Mathematics Unlimited – 2001 and Beyond_, Berlin: Springer, 29–50.
- Baez, J. & Lauda, A.D., 2011, “A Pre-history of n-Categorical Physics”, _Deep Beauty: Understanding the Quantum World Through Mathematical Innovation_, H. Halvorson (ed.), Cambridge: Cambridge University Press, 13–128.
- Baez, J. & May, P. J., 2010, _Towards Higher Category Theory_, Berlin: Springer.
- Baez, J. & Stay, M., 2010, “Physics, Topology, Logic and Computation: a Rosetta Stone”, _New Structures for Physics_ (Lecture Notes in Physics 813), B. Coecke (ed.), New York, Springer: 95–172.
- Baianu, I. C., 1987, “Computer Models and Automata Theory in Biology and Medecine”, _Mathematical Modelling_, 7: 1513–1577.
- Bain, J., 2013, “Category-theoretic Structure and Radical Ontic Structural Realism”, _Synthese_, 190: 1621–1635.
- Barr, M. & Wells, C., 1985, _Toposes, Triples and Theories_, New York: Springer-Verlag.
- –––, 1999, _Category Theory for Computing Science_, Montreal: CRM.
- Batanin, M., 1998, “Monoidal Globular Categories as a Natural Environment for the Theory of Weak n-Categories”, _Advances in Mathematics_, 136: 39–103.
- Bell, J. L., 1981, “Category Theory and the Foundations of Mathematics”, _British Journal for the Philosophy of Science_, 32: 349–358.
- –––, 1982, “Categories, Toposes and Sets”, _Synthese_, 51 (3): 293–337.
- –––, 1986, “From Absolute to Local Mathematics”, _Synthese_, 69 (3): 409–426.
- –––, 1988, “Infinitesimals”, _Synthese_, 75 (3): 285–315.
- –––, 1988, _Toposes and Local Set Theories: An Introduction_, Oxford: Oxford University Press.
- –––, 1995, “Infinitesimals and the Continuum”, _Mathematical Intelligencer_, 17 (2): 55–57.
- –––, 1998, _A Primer of Infinitesimal Analysis_, Cambridge: Cambridge University Press.
- –––, 2001, “The Continuum in Smooth Infinitesimal Analysis”, _Reuniting the Antipodes — Constructive and Nonstandard Views on the Continuum_ (Synthese Library, Volume 306), Dordrecht: Kluwer, 19–24.
- –––, 2005, “The Development of Categorical Logic”, in _Handbook of Philosophical Logic_ (Volume 12), 2nd ed., D.M. Gabbay, F. Guenthner (eds.), Dordrecht: Springer, pp. 279–362.
- –––, 2012, “Types, Sets and Categories”, in _Handbook of the History of Logic: Sets and Extensions in the Twentieth Century_ (Volume 6), 1st edition, D. Gabbay, A. Kanamori, J. Woods (eds.), Amsterdam: North Holland, pp. 633–687.
- Birkoff, G. & Mac Lane, S., 1999, Algebra, 3rd ed., Providence: AMS.
- Blass, A., 1984, “The Interaction Between Category Theory and Set Theory”, in _Mathematical Applications of Category Theory_ (Volume 30), Providence: AMS, 5–29.
- Blass, A. & Scedrov, A., 1983, “Classifying Topoi and Finite Forcing”, _Journal of Pure and Applied Algebra_, 28: 111–140.
- –––, 1989, _Freyd’s Model for the Independence of the Axiom of Choice_, Providence: AMS.
- –––, 1992, “Complete Topoi Representing Models of Set Theory”, _Annals of Pure and Applied Logic_ , 57 (1): 1–26.
- Blute, R. & Scott, P., 2004, “Category Theory for Linear Logicians”, in _Linear Logic in Computer Science_, T. Ehrhard, P. Ruet, J-Y. Girard, P. Scott (eds.), Cambridge: Cambridge University Press, 1–52.
- Boileau, A. & Joyal, A., 1981, “La logique des topos”, _Journal of Symbolic Logic_, 46 (1): 6–16.
- Borceux, F., 1994, _Handbook of Categorical Algebra_, 3 volumes, Cambridge: Cambridge University Press.
- Brading, K. & Landry, E., 2006, “Scientific Structuralism: Presentation and Representation”, _Philosophy of Science_, 73: 571–581.
- Brown, R. & Porter, T., 2006, “Category Theory: an abstract setting for analogy and comparison”, _What is Category Theory?_, G. Sica (ed.), Monza: Polimetrica: 257–274.
- Brunetti, R. & Fredenhagen, K & Verch, R., 2003, “The Generally Covariant Locality Principle – a new paradigm for local quantum field theory”, _Communications in Mathematical Physics_, 237 (1–2): 31–68.
- Buchsbaum, D.A., 1955, “Exact Categories and Duality”, _Transactions of the American Mathematical Society_, 80 (1): 1–34.
- Bunge, M., 1974, “Topos Theory and Souslin’s Hypothesis”, _Journal of Pure and Applied Algebra_, 4: 159–187.
- –––, 1984, “Toposes in Logic and Logic in Toposes”, _Topoi_, 3 (1): 13–22.
- Caramello, O., 2011, “A Characterization Theorem for Geometric Logic”, _Annals of Pure and Applied Logic_,162, 4: 318–321.
- –––, 2012a, “Universal Models and Definability”, _Mathematical Proceedings of the Cambridge Philosophical Society_, 152 (2): 279–302.
- –––, 2012b, “Syntactic Characterizations of Properties of Classifying Toposes”, _Theory and Applications of Categories_, 26 (6): 176–193.
- –––, 2018, _Theories, Sites, Toposes_, Oxford: Oxford University Press.
- Carter, J., 2008, “Categories for the working mathematician: making the impossible possible”, _Synthese_, 162 (1): 1–13.
- Cisinski, J.-C., 2019, _Higher Categories and Homotopical Algebra_, Cambridge: Cambridge University Press.
- Cockett, J. R. B. & Seely, R. A. G., 2001, “Finite Sum-product Logic”, _Theory and Applications of Categories_ (electronic), 8: 63–99.
- Cockett, J. R. B. & Seely, R. A. G., 2018, “Proof Theory of the Cut Rule”, in _Categories for the Working Philosopher_, E. Landry (ed.), Oxford: Oxford University Press: 223–261.
- Coecke, B., 2011, “A Universe of Processes and Some of its Guises”, _Deep Beauty: Understanding the Quantum World through Mathematical Innovation_, Cambridge: Cambridge University Press: 129–186.
- Coecke, B. & Kissinger, A., 2018, “Categorical Quentum Mechanics I: Causal Quantum Processes”, _Categories for the Working Philosopher_, E. Landry (ed.), Oxford: Oxford University Press: 286–328.
- Couture, J. & Lambek, J., 1991, “Philosophical Reflections on the Foundations of Mathematics”, _Erkenntnis_, 34 (2): 187–209.
- –––, 1992, “Erratum:”Philosophical Reflections on the Foundations of Mathematics“”, _Erkenntnis_, 36 (1): 134.
- Crole, R. L., 1994, Categories for Types, Cambridge: Cambridge University Press.
- De Toffoli, S., 2017, “Chasing the diagram – the use of visualizations in algebraic reasoning ”, _The Review of Symbolic Logic_, 10 (1): 158–186.
- Dieudonné, J. & Grothendieck, A., 1960 [1971], _Éléments de Géométrie Algébrique_, Berlin: Springer-Verlag.
- Döring, A., 2011, “The Physical Interpretation of Daseinisation”, _Deep Beauty: Understanding the Quantum World through Mathematical Innovation_, Cambridge: Cambridge University Press: 207–238.
- Ehresmann, A., 2018, “Applications of Categories to Biology and Cognition”, _Categories for the Working Philosopher_, E. Landry (ed.), Oxford: Oxford University Press: 358–380.
- Ehresmann, A. & Vanbremeersch, J.-P., 2007, _Memory Evolutive Systems: Hierarchy, Emergence, Cognition_, Amsterdam: Elsevier
- –––, 1987, “Hierarchical Evolutive Systems: a Mathematical Model for Complex Systems”, _Bulletin of Mathematical Biology_, 49 (1): 13–50.
- Eilenberg, S. & Cartan, H., 1956, _Homological Algebra_, Princeton: Princeton University Press.
- Eilenberg, S. & Mac Lane, S., 1942, “Group Extensions and Homology”, _Annals of Mathematics_, 43: 757–831.
- –––, 1945, “General Theory of Natural Equivalences”, _Transactions of the American Mathematical Society_, 58: 231–294.
- Eilenberg, S. & Steenrod, N., 1952, _Foundations of Algebraic Topology_, Princeton: Princeton University Press.
- Ellerman, D., 1988, “Category Theory and Concrete Universals”, _Erkenntnis_, 28: 409–429.
- –––, 2017, “Category Theory and Set Theory as Theories about Complementary Types of Universals”, _Logic and Logical Philosophy_, 26 (2): 145–162.
- Eva, B., 2016, “Category Theory and Physical Structuralism”, _European Journal for Philosophy of Science_, 6 (2): 231–246.
- –––, 2017, “Topos Theoretic Quantum Realism”, _The British Journal for the Philosophy of Science_, 68 (4): 1149–1181.
- Feferman, S., 1977, “Categorical Foundations and Foundations of Category Theory”, _Logic, Foundations of Mathematics and Computability_, R. Butts (ed.), Reidel, 149–169.
- –––, 2004, “Typical Ambiguity: trying to have your cake and eat it too”, _One Hundred Years of Russell’s Paradox_, G. Link (ed.), Berlin: De Gruyter, 135–151.
- Freyd, P., 1964, _Abelian Categories. An Introduction to the Theory of Functors_, New York: Harper & Row.
- –––, 1965, “The Theories of Functors and Models”. _Theories of Models_, Amsterdam: North Holland, 107–120.
- –––, 1972, “Aspects of Topoi”, _Bulletin of the Australian Mathematical Society_, 7: 1–76.
- –––, 1980, “The Axiom of Choice”, _Journal of Pure and Applied Algebra_, 19: 103–125.
- –––, 1987, “Choice and Well-Ordering”, _Annals of Pure and Applied Logic_, 35 (2): 149–166.
- –––, 1990, _Categories, Allegories_, Amsterdam: North Holland.
- –––, 2002, “Cartesian Logic”, _Theoretical Computer Science_, 278 (1–2): 3–21.
- Freyd, P., Friedman, H. & Scedrov, A., 1987, “Lindembaum Algebras of Intuitionistic Theories and Free Categories”, _Annals of Pure and Applied Logic_, 35 (2): 167–172.
- Galli, A. & Reyes, G. & Sagastume, M., 2000, “Completeness Theorems via the Double Dual Functor”, _Studia Logical_, 64 (1): 61–81.
- Ghilardi, S., 1989, “Presheaf Semantics and Independence Results for some Non-classical first-order logics”, _Archive for Mathematical Logic_, 29 (2): 125–136.
- Ghilardi, S. & Zawadowski, M., 2002, _Sheaves, Games & Model Completions: A Categorical Approach to Nonclassical Porpositional Logics_, Dordrecht: Kluwer.
- Goldblatt, R., 1979, _Topoi: The Categorical Analysis of Logic, Studies in logic and the foundations of mathematics_, Amsterdam: Elsevier.
- Grothendieck, A., 1957, “Sur Quelques Points d’algèbre homologique”, _Tohoku Mathematics Journal_, 9: 119–221.
- Grothendieck, A. _et al_., _Séminaire de Géométrie Algébrique_, Vol. 1–7, Berlin: Springer-Verlag.
- Hatcher, W. S., 1982, _The Logical Foundations of Mathematics_, Oxford: Pergamon Press.
- Healy, M. J., 2000, “Category Theory Applied to Neural Modeling and Graphical Representations”, _Proceedings of the IEEE-INNS-ENNS International Joint Conference on Neural Networks: IJCNN200, Como, vol. 3_, M. Gori, S-I. Amari, C. L. Giles, V. Piuri (eds.), IEEE Computer Science Press, 35–40.
- Healy, M. J., & Caudell, T. P., 2006, “Ontologies and Worlds in Category Theory: Implications for Neural Systems”,_Axiomathes_, 16 (1–2): 165–214.
- Hellman, G., 2003, “Does Category Theory Provide a Framework for Mathematical Structuralism?”, _Philosophia Mathematica_, 11 (2): 129–157.
- –––, 2006, “Mathematical Pluralism: the case of smooth infinitesimal analysis”, _Journal of Philosophical Logic_, 35 (6): 621–651.
- –––, 2011,“Foundational Frameworks”, in _Foundational Theories of Classical and Constructive Mathematics_, G. Sommaruga (ed.), New York: Springer: 53–70.
- Hellman, G., 2013, “Neither Categorical nor Set-Theoretic Foundations”, _The Review of Symbolic Logic_, 6 (1): 16–23.
- Hermida, C. & Makkai, M. & Power, J., 2000, “On Weak Higher-dimensional Categories I”, _Journal of Pure and Applied Algebra_, 154 (1–3): 221–246.
- –––, 2001, “On Weak Higher-dimensional Categories 2”, _Journal of Pure and Applied Algebra_, 157 (2–3): 247–277.
- –––, 2002, “On Weak Higher-dimensional Categories 3”, _Journal of Pure and Applied Algebra_, 166 (1–2): 83–104.
- Heunen, C. & Landsmann, N. & Spitters, B., 2009, “A Topos for Algebraic Quantum Theory”, _Communications in Mathematical Physics_, 291 (1): 63–110.
- Hyland, J. M. E., 1982, “The Effective Topos”, _Studies in Logic and the Foundations of Mathematics_ (Volume 110), Amsterdam: North Holland, 165–216.
- –––, 1988, “A Small Complete Category”, _Annals of Pure and Applied Logic_, 40 (2): 135–165.
- –––, 1991, “First Steps in Synthetic Domain Theory”, _Category Theory (Como 1990)_ (Lecture Notes in Mathematics, Volume 1488), Berlin: Springer, 131–156.
- –––, 2002, “Proof Theory in the Abstract”, _Annals of Pure and Applied Logic_, 114 (1–3): 43–78.
- Hyland, J. M. E. & Robinson, E. P. & Rosolini, G., 1990, “The Discrete Objects in the Effective Topos”, _Proceedings of the London Mathematical Society (3)_, 60 (1): 1–36.
- Isham, C.J., 2011, “Topos Methods in the Foundations of Physics”, _Deep Beauty: Understanding the Quantum World through Mathematical Innovation_, Cambridge: Cambridge University Press: 187–206.
- Jacobs, B., 1999, _Categorical Logic and Type Theory_, Amsterdam: North Holland.
- Johnstone, P. T., 1977, _Topos Theory_, New York: Academic Press.
- –––, 1979a, “Conditions Related to De Morgan’s Law”, _Applications of Sheaves_ (Lecture Notes in Mathematics, Volume 753), Berlin: Springer, 479–491.
- –––, 1979b, “Another Condition Equivalent to De Morgan’s Law”, _Communications in Algebra_, 7 (12): 1309–1312.
- –––, 1981, “Tychonoff’s Theorem without the Axiom of Choice”, _Fundamenta Mathematicae_, 113 (1): 21–35.
- –––, 1982, _Stone Spaces_, Cambridge:Cambridge University Press.
- –––, 1985, “How General is a Generalized Space?”, _Aspects of Topology_, Cambridge: Cambridge University Press, 77–111.
- –––, 2001, “Elements of the History of Locale Theory”, _Handbook of the History of General Topology_, Vol. 3, Dordrecht: Kluwer, 835–851.
- –––, 2002a, _Sketches of an Elephant: a Topos Theory Compendium. Vol. 1_ (Oxford Logic Guides, Volume 43), Oxford: Oxford University Press.
- Joyal, A. & Moerdijk, I., 1995, _Algebraic Set Theory_, Cambridge: Cambridge University Press.
- Joyal, A. and Street, R., 1993, “Braided Tensor Categories”, _Advances in Mathematics_, 102 (1): 20–78.
- Joyal, A., Street, R. and Verity, D., 1996, “Traced Monoidal Categories”, _Mathematical Proceedings of the Cambridge Philosophical Society_, 119 (3): 447–468.
- Kan, D. M., 1958, “Adjoint Functors”, _Transactions of the American Mathematical Society_, 87: 294–329.
- Kishida, K., 2018, “Categories and Modalities”, in _Categories for the Working Philosopher_, E. Landry (ed.), Oxford, Oxford University Press: 163–222.
- Kock, A., 2006, _Synthetic Differential Geometry_ (London Mathematical Society Lecture Note Series, Volume 51), Cambridge: Cambridge University Press, 2nd ed.
- Krömer, R., 2007, _Tool and Objects: A History and Philosophy of Category Theory_, Basel: Birkhäuser.
- La Palme Reyes, M., John Macnamara, Gonzalo E. Reyes, and Houman Zolfaghari, 1994, “The non-Boolean Logic of Natural Language Negation”, _Philosophia Mathematica_, 2 (1): 45–68.
- –––, 1999, “Count Nouns, Mass Nouns, and their Transformations: a Unified Category-theoretic Semantics”, _Language, Logic and Concepts_, Cambridge: MIT Press, 427–452.
- Lal, R. & Teh, N., 2017, “Categorical Generalization and Physical Structuralism”, _British Journal for the Philosophy of Science_, 68 (1): 213–251.
- Lambek, J., 1968, “Deductive Systems and Categories I. Syntactic Calculus and Residuated Categories”, _Mathematical Systems Theory_, 2: 287–318.
- –––, 1969, “Deductive Systems and Categories II. Standard Constructions and Closed Categories”, _Category Theory, Homology Theory and their Applications I_, Berlin: Springer, 76–122.
- –––, 1972, “Deductive Systems and Categories III. Cartesian Closed Categories, Intuitionâ‰ istic Propositional Calculus, and Combinatory Logic”, _Toposes, Algebraic Geometry and Logic_ (Lecture Notes in Mathematics, Volume 274), Berlin: Springer, 57–82.
- –––, 1982, “The Influence of Heraclitus on Modern Mathematics”, _Scientific Philosophy Today_, J. Agassi and R.S. Cohen (eds.), Dordrecht, Reidel, 111–122.
- –––, 1986, “Cartesian Closed Categories and Typed lambda calculi”, _Combinators and Functional Programming Languages_ (Lecture Notes in Computer Science, Volume 242), Berlin: Springer, 136–175.
- –––, 1989a, “On Some Connections Between Logic and Category Theory”, _Studia Logica_, 48 (3): 269–278.
- –––, 1989b, “On the Sheaf of Possible Worlds”, _Categorical Topology and its relation to Analysis, Algebra and Combinatorics_, Teaneck: World Scientific Publishing, 36–53.
- –––, 1993, “Logic without Structural Rules”, _Substructural Logics_ (Studies in Logic and Computation, Volume 2), Oxford: Oxford University Press, 179–206.
- –––, 1994a, “Some Aspects of Categorical Logic”, _Logic, Methodology and Philosophy of Science IX_ (Studies in Logic and the Foundations of Mathematics, Volume 134), Amsterdam: North Holland, 69–89.
- –––, 1994b, “Are the Traditional Philosophies of Mathematics Really Incompatible?”, _Mathematical Intelligencer_, 16 (1): 56–62.
- –––, 1994c, “What is a Deductive System?”, _What is a Logical System?_ (Studies in Logic and Computation, Volume 4), Oxford: Oxford University Press, 141–159.
- –––, 2004, “What is the world of Mathematics? Provinces of Logic Determined”, _Annals of Pure and Applied Logic_, 126: 1–3, 149–158.
- Lambek, J. & Scott, P.J., 1981, “Intuitionistic Type Theory and Foundations”, _Journal of Philosophical Logic_, 10 (1): 101–115.
- –––, 1983, “New Proofs of Some Intuitionistic Principles”, _Zeitschrift für Mathematische Logik und Grundlagen der Mathematik_, 29 (6): 493–504.
- –––, 1986, _Introduction to Higher Order Categorical Logic_, Cambridge: Cambridge University Press.
- Lam, V. & Wütrich, C., 2015, “No Categorical Support for Radical Ontic Structural Realism”, _British Journal for the Philosophy of Science_, 66 (3): 605–634.
- Landry, E., 1999, “Category Theory: the Language of Mathematics”, _Philosophy of Science_, 66 (3) (Supplement): S14–S27.
- –––, 2001, “Logicism, Structuralism and Objectivity”, _Topoi_, 20 (1): 79–95.
- –––, 2007, “Shared Structure need not be Shared Set-structure”, _Synthese_, 158 (1): 1–17.
- –––, 2011, “How to be a Structuralist all the way down”, _Synthese_, 179: 435–454.
- –––, 2012, “Methodological Structural Realism”, in _Sructure, Objects, and Causality_, E. Landry & D. Rickles (eds.), Dordrecht, Reidel: 29–59.
- –––, 2013, “The Genetic versus The Axiomatic Method: responding to Feferman 1977”, _The Review of Symbolic Logic_, 6 (1): 24–50.
- –––, 2018, “Structural Realism and Category Mistakes”, in _Categories for the Working Philosopher_, E. Landry (ed.), Oxford, Oxford University Press: 430–449.
- Landry, E. & Marquis, J.-P., 2005, “Categories in Context: Historical, Foundational and philosophical”, _Philosophia Mathematica_, 13: 1–43.
- –––, 2017, _Categories for the Working Philosophers_, Oxford: Oxford University Press.
- Lawvere, F. W., 1963, “Functorial Semantics of Algebraic Theories”, _Proceedings of the National Academy of Sciences U.S.A._, 50: 869–872.
- –––, 1964, “An Elementary Theory of the Category of Sets”, _Proceedings of the National Academy of Sciences U.S.A._, 52: 1506–1511.
- –––, 1965, “Algebraic Theories, Algebraic Categories, and Algebraic Functors”, _Theory of Models_, Amsterdam: North Holland, 413–418.
- –––, 1966, “The Category of Categories as a Foundation for Mathematics”, _Proceedings of the Conference on Categorical Algebra_, La Jolla, New York: Springer-Verlag, 1–21.
- –––, 1969a, “Diagonal Arguments and Cartesian Closed Categories”, _Category Theory, Homology Theory, and their Applications II_, Berlin: Springer, 134–145.
- –––, 1969b, “Adjointness in Foundations”, _Dialectica_, 23: 281–295.
- –––, 1970, “Equality in Hyper doctrines and Comprehension Schema as an Adjoint Functor”, _Applications of Categorical Algebra_, Providence: AMS, 1–14.
- –––, 1971, “Quantifiers and Sheaves”, _Actes du Congrès International des Mathématiciens, Tome 1_, Paris: Gauthier-Villars, 329–334.
- –––, 1972, “Introduction”, _Toposes, Algebraic Geometry and Logic_, Lecture Notes in Mathematics, 274, Springer-Verlag, 1–12.
- –––, 1975, “Continuously Variable Sets: Algebraic Geometry = Geometric Logic”, _Proceedings of the Logic Colloquium Bristol 1973_, Amsterdam: North Holland, 135–153.
- –––, 1976, “Variable Quantities and Variable Structures in Topoi”, _Algebra, Topology, and Category Theory_, New York: Academic Press, 101–131.
- –––, 1992, “Categories of Space and of Quantity”, _The Space of Mathematics_, Foundations of Communication and Cognition, Berlin: De Gruyter, 14–30.
- –––, 1994a, “Cohesive Toposes and Cantor’s lauter Ensein ”, _Philosophia Mathematica_, 2 (1): 5–15.
- –––, 1994b, “Tools for the Advancement of Objective Logic: Closed Categories and Toposes”, _The Logical Foundations of Cognition_ (Vancouver Studies in Cognitive Science, Volume 4), Oxford: Oxford University Press, 43–56.
- –––, 2000, “Comments on the Development of Topos Theory”, _Development of Mathematics 1950–2000_, Basel: Birkhäuser, 715–734.
- –––, 2002, “Categorical Algebra for Continuum Micro Physics”, _Journal of Pure and Applied Algebra_, 175 (1–3): 267–287.
- –––, 2003, “Foundations and Applications: Axiomatization and Education. New Programs and Open Problems in the Foundation of Mathematics”, _Bulletin of Symbolic Logic_, 9 (2): 213–224.
- Lawvere, F. W. & Rosebrugh, R., 2003, _Sets for Mathematics_, Cambridge: Cambridge University Press.
- Lawvere, F. W. & Schanuel, S., 1997, _Conceptual Mathematics: A First Introduction to Categories_, Cambridge: Cambridge University Press.
- Leinster, T., 2002, “A Survey of Definitions of n-categories”, _Theory and Applications of Categories_, (electronic), 10: 1–70.
- –––, 2004, _Higher Operads, Higher Categories_, London Mathematical Society Lecture Note Series, 298, Cambridge: Cambridge University Press.
- –––, 2014, _Basic Category Theory_, Cambridge: Cambridge University Press.
- Linnebo, O. & Pettigrew, R., 2011, “Category Theory as an Autonomous Foundation”, _Philosophia Mathematica_, 19 (3): 227–254.
- Logan, S., 2015, “Category Theory is a Contentful Theory”, _Philosophia Mathematica_, 23 (1): 110–115.
- Lurie, J., 2009, _Higher Topos Theory_, Princeton: Princeton University Press.
- Mac Lane, S., 1950, “Dualities for Groups”, _Bulletin of the American Mathematical Society_, 56: 485–516.
- –––, 1969, “Foundations for Categories and Sets”, _Category Theory, Homology Theory and their Applications II_, Berlin: Springer, 146–164.
- –––, 1969, “One Universe as a Foundation for Category Theory”, _Reports of the Midwest Category Seminar III_, Berlin: Springer, 192–200.
- –––, 1971, “Categorical algebra and Set-Theoretic Foundations”, _Axiomatic Set Theory_, Providence: AMS, 231–240.
- –––, 1975, “Sets, Topoi, and Internal Logic in Categories”, _Studies in Logic and the Foundations of Mathematics_ (Volumes 80), Amsterdam: North Holland, 119–134.
- –––, 1981, “Mathematical Models: a Sketch for the Philosophy of Mathematics”, _American Mathematical Monthly_, 88 (7): 462–472.
- –––, 1986, _Mathematics, Form and Function_, New York: Springer.
- –––, 1988, “Concepts and Categories in Perspective”, _A nCentury of Mathematics in America, Part I_, Providence: AMS, 323–365.
- –––, 1989, “The Development of Mathematical Ideas by Collision: the Case of Categories and Topos Theory”, _Categorical Topology and its Relation to Analysis, Algebra and Combinatorics_, Teaneck: World Scientific, 1–9.
- –––, 1996, “Structure in Mathematics. Mathematical Structuralism”, _Philosophia Mathematica_, 4 (2): 174–183.
- –––, 1997, “Categorical Foundations of the Protean Character of Mathematics”, _Philosophy of Mathematics Today_, Dordrecht: Kluwer, 117–122.
- –––, 1998, _Categories for the Working Mathematician_, 2nd edition, New York: Springer-Verlag.
- Mac Lane, S. & Moerdijk, I., 1992, _Sheaves in Geometry and Logic_, New York: Springer-Verlag.
- MacNamara, J. & Reyes, G. (eds.), 1994, _The Logical Foundation of Cognition_, Oxford: Oxford University Press.
- Majid, S., 1995, _Foundations of Quantum Group Theory_, Cambridge: Cambridge University Press.
- Makkai, M., 1987, “Stone Duality for First-Order Logic”, _Advances in Mathematics_, 65 (2): 97–170.
- –––, 1988, “Strong Conceptual Completeness for First Order Logic”, _Annals of Pure and Applied Logic_, 40: 167–215.
- –––, 1997a, “Generalized Sketches as a Framework for Completeness Theorems I”, _Journal of Pure and Applied Algebra_, 115 (1): 49–79.
- –––, 1997b, “Generalized Sketches as a Framework for Completeness Theorems II”, _Journal of Pure and Applied Algebra_, 115 (2): 179–212.
- –––, 1997c, “Generalized Sketches as a Framework for Completeness Theorems III”, _Journal of Pure and Applied Algebra_, 115 (3): 241–274.
- –––, 1998, “Towards a Categorical Foundation of Mathematics”, _Lecture Notes in Logic_ (Volume 11), Berlin: Springer, 153–190.
- –––, 1999, “On Structuralism in Mathematics”, _Language, Logic and Concepts_, Cambridge: MIT Press, 43–66.
- Makkai, M. & Paré, R., 1989, _Accessible Categories: the Foundations of Categorical Model Theory_, Contemporary Mathematics 104, Providence: AMS.
- Makkai, M. & Reyes, G., 1977, _First-Order Categorical Logic_, Springer Lecture Notes in Mathematics 611, New York: Springer.
- –––, 1995, “Completeness Results for Intuitionistic and Modal Logic in a Categorical Setting”, _Annals of Pure and Applied Logic_, 72 (1): 25–101.
- Marquis, J.-P., 1993, “Russell’s Logicism and Categorical Logicisms”, _Russell and Analytic Philosophy_, A. D. Irvine & G. A. Wedekind (eds.), Toronto, University of Toronto Press, 293–324.
- –––, 1995, “Category Theory and the Foundations of Mathematics: Philosophical Excavations”, _Synthese_, 103: 421–447.
- –––, 2000, “Three Kinds of Universals in Mathematics?”, in _Logical Consequence: Rival Approaches and New Studies in Exact Philosophy: Logic, Mathematics and Science_, Vol. II, B. Brown & J. Woods (eds.), Oxford: Hermes, 191–212.
- –––, 2006, “Categories, Sets and the Nature of Mathematical Entities”, in _The Age of Alternative Logics. Assessing philosophy of logic and mathematics today_, J. van Benthem, G. Heinzmann, Ph. Nabonnand, M. Rebuschi, H. Visser (eds.), Springer, 181–192.
- –––, 2009, _From a Geometrical Point of View: A Study in the History and Philosophy of Category Theory_, Berlin: Springer.
- –––, 2013, “Mathematical Forms and Forms of Mathematics: leaving the shores of extensional mathematics”, _Synthese_, 190 (12): 2141–2164.
- –––, 2013b, “Categorical Foundations of Mathematics or how to provide foundations for abstract mathematics”, _The Review of Symbolic Logic_, 6 (1): 51–75.
- –––, 2014, “Mathematical Abstraction, Conceptual Variation and Identity”, _Logic, Methodology and Philosophy of science – logic and science facing the new technologies_, P. Schroeder-Heister, et al. (eds.), London: College Publications, 299–322.
- –––, 2016, “Stairway to Heaven”, _The Mathematical Intelligencer_, 38 (3): 41–51.
- Marquis, J.-P. & Reyes, G., 2012, “The History of Categorical Logic: 1963–1977”, _Handbook of the History of Logic_, Vol. 6, D. Gabbay & J. Woods (eds.), Amsterdam: Elsevier, 689–800.
- McLarty, C., 1986, “Left Exact Logic”, _Journal of Pure and Applied Algebra_, 41 (1): 63–66.
- –––, 1990, “Uses and Abuses of the History of Topos Theory”, _British Journal for the Philosophy of Science_, 41: 351–375.
- –––, 1991, “Axiomatizing a Category of Categories”, _Journal of Symbolic Logic_, 56 (4): 1243–1260.
- –––, 1992, _Elementary Categories, Elementary Toposes_, Oxford: Oxford University Press.
- –––, 1993, “Numbers Can be Just What They Have to”, _Noûs_, 27: 487–498.
- –––, 1994, “Category Theory in Real Time”, _Philosophia Mathematica_, 2 (1): 36–44.
- –––, 2004, “Exploring Categorical Structuralism”, _Philosophia Mathematica_, 12: 37–53.
- –––, 2005, “Learning from Questions on Categorical Foundations”, _Philosophia Mathematica_, 13 (1): 44–60.
- –––, 2006, “Emmy Noether’s set-theoretic topology: from Dedekind to the rise of functors”, _The Architecture of Modern Mathematics_, J.J. Gray & J. Ferreiros, Oxford: Oxford University Press, 187–208.
- –––, 2011, “Recent Debate over Categorical Foundations”, in _Foundational Theories of Classical and Constructive Mathematics_, G. Sommaruga (ed.), New York: Springer: 145–154.
- –––, 2018, “The Role of Set Theory in Mathematics”, in _Categories for the Working Philosopher_, E. Landry (ed.), Oxford, Oxford University Press: 1–17.
- Moerdijk, I., 1984, “Heine-Borel does not imply the Fan Theorem”, _Journal of Symbolic Logic_, 49 (2): 514–519.
- –––, 1995a, “A Model for Intuitionistic Non-standard Arithmetic”, _Annals of Pure and Applied Logic_, 73 (1): 37–51.
- –––, 1998, “Sets, Topoi and Intuitionism”, _Philosophia Mathematica_, 6 (2): 169–177.
- Moerdijk, I. & Palmgren, E., 1997, “Minimal Models of Heyting Arithmetic”, _Journal of Symbolic Logic_, 62 (4): 1448–1460.
- –––, 2002, “Type Theories, Toposes and Constructive Set Theory: Predicative Aspects of AST”, _Annals of Pure and Applied Logic_, 114 (1–3): 155–201.
- Moerdijk, I. & Reyes, G., 1991, _Models for Smooth Infinitesimal Analysis_, New York: Springer-Verlag.
- Palmgren, E., 2012, “Constructivist and Structuralist Foundations: Bishop’s and Lawvere’s Theories of Sets”, _Annals of Pure and Applied Logic_, 63: 1384–1399.
- Palmgren, E., 2018, “A Constructive Examination of a Russell-style Ramified Type Theory”, _The Bulletin of Symbolic Logic_, 24 (1): 90–106.
- Pareigis, B., 1970, _Categories and Functors_, New York: Academic Press.
- Pedicchio, M. C. & Tholen, W., 2004, _Categorical Foundations_, Cambridge: Cambridge University Press.
- Peirce, B., 1991, _Basic Category Theory for Computer Scientists_, Cambridge: MIT Press.
- Peruzzi, A., 2006, “The Meaning of Category Theory for 21st Century Philosophy”, _Axiomathes_, 16 (4): 424–459.
- –––, 2016, “Category Theory and the Search for Universals: A Very Short Guide for Philosophers”, in _Modern Logic 1850–1950, East and West_, F. Abeles & M. Muller (eds.), Basel: Birkhauser, 159–182.
- Pitts, A. M., 1987, “Interpolation and Conceptual Completeness for Pretoposes via Category Theory”, _Mathematical Logic and Theoretical Computer Science_ (Lecture Notes in Pure and Applied Mathematics, Volume 106), New York: Dekker, 301–327.
- –––, 1989, “Conceptual Completeness for First-order Intuitionistic Logic: an Application of Categorical Logic”, _Annals of Pure and Applied Logic_, 41 (1): 33–81.
- –––, 1992, “On an Interpretation of Second-order Quantification in First-order Propositional Intuitionistic Logic”, _Journal of Symbolic Logic_, 57 (1): 33–52.
- –––, 2000, “Categorical Logic”, _Handbook of Logic in Computer Science, Vol.5_, Oxford: Oxford Unversity Press, 39–128.
- Pitts, A. M. & Taylor, P., 1989, “A Note of Russell’s Paradox in Locally Cartesian Closed Categories”, _Studia Logica_, 48 (3): 377–387.
- Plotkin, B., 2000, “Algebra, Categories and Databases”, _Handbook of Algebra, Vol. 2_, Amsterdam: Elsevier, 79–148.
- Porter, T., 2004, “Interpreted Systems and Kripke Models for Multiagent Systems from a Categorical Perspective”, _Theoretical Computer Science_, 323 (1–3): 235–266.
- Reyes, G., 1991, “A Topos-theoretic Approach to Reference and Modality”, _Notre Dame Journal of Formal Logic_, 32 (3): 359–391.
- –––, 1974, “From Sheaves to Logic”, in _Studies in Algebraic Logic_, A. Daigneault (ed.), Providence: AMS.
- Reyes, G. & Zawadowski, M., 1993, “Formal Systems for Modal Operators on Locales”, _Studia Logica_, 52 (4): 595–613.
- Reyes, G. & Zolfaghari, H., 1991, “Topos-theoretic Approaches to Modality”, _Category Theory (Como 1990)_ (Lecture Notes in Mathematics, Volume 1488), Berlin: Springer, 359–378.
- –––, 1996, “Bi-Heyting Algebras, Toposes and Modalities”, _Journal of Philosophical Logic_, 25 (1): 25–43.
- Riehl, E., 2016, _Category Theory in Context_, Mineola: Dover.
- Rodabaugh, S. E. & Klement, E. P. (eds.), _Topological and Algebraic Structures in Fuzzy Sets: A Handbook of Recent Developments in the Mathematics of Fuzzy Sets_ (Trends in Logic, Volume 20), Dordrecht: Kluwer.
- Rodin, A., 2014, _Axiomatic Method and Category Theory_ (Synthese Library: Volume 364), New York: Springer.
- Scedrov, A., 1984, _Forcing and Classifying Topoi_, Providence: AMS.
- Scott, P.J., 2000, “Some Aspects of Categories in Computer Science”, _Handbook of Algebra, Vol. 2_, Amsterdam: North Holland, 3–77.
- Seely, R. A. G., 1984, “Locally Cartesian Closed Categories and Type Theory”, _Mathematical Proceedings of the Cambridge Mathematical Society_, 95 (1): 33–48.
- Shapiro, S., 2005, “Categories, Structures and the Frege-Hilbert Controversy: the Status of Metamathematics”, _Philosophia Mathematica_, 13 (1): 61–77.
- –––, 2011,“Foundations: Structures, Sets, and Categories”, in _Foundational Theories of Classical and Constructive Mathematics_, G. Sommaruga (ed.), New York: Springer: 97–110.
- Sica, G. (ed.), 2006, _What is Category Theory?_, Firenze: Polimetrica.
- Simpson, C., 2011, _Homotopy Theory of Higher Categories_, Cambridge: Cambridge University Press.
- Spivak, D., 2014, _Category Theory for the Sciences_, Cambridge: MIT Press.
- Taylor, P., 1996, “Intuitionistic sets and Ordinals”, _Journal of Symbolic Logic_, 61: 705–744.
- –––, 1999, _Practical Foundations of Mathematics_, Cambridge: Cambridge University Press.
- Tierney, M., 1972, “Sheaf Theory and the Continuum Hypothesis”, _Toposes, Algebraic Geometry and Logic_, F.W. Lawvere (ed.), Springer Lecture Notes in Mathematics 274, 13–42.
- Van Oosten, J., 2002, “Realizability: a Historical Essay”, _Mathematical Structures in Computer Science_, 12 (3): 239–263.
- –––, 2008, _Realizability: an Introduction to its Categorical Side_ (Studies in Logic and the Foundations of Mathematics, Volume 152), Amsterdam: Elsevier.
- Van der Hoeven, G. & Moerdijk, I., 1984a, “Sheaf Models for Choice Sequences”, _Annals of Pure and Applied Logic_, 27 (1): 63–107.
- –––, 1984b, “On Choice Sequences determined by Spreads”, _Journal of Symbolic Logic_, 49 (3): 908–916.
- –––, 1984c, “Constructing Choice Sequences for Lawless Sequences of Neighbourhood Functions”, _Models and Sets_ (Lecture Notes in Mathematics, Volume 1103), Berlin: Springer, 207–234.
- Walsh, P., 2017, “Categorical Harmony and Path Induction”, _The Review of Symbolic Logic_, 10 (2): 301–321.
- Wood, R.J., 2004, “ Ordered Sets via Adjunctions”, _Categorical Foundations_, M. C. Pedicchio & W. Tholen (eds.), Cambridge: Cambridge University Press.
- Yanofski, N., 2003, “A Universal Approach to Self-Referential Paradoxes, Incompleteness and Fixed Points”, _The Bulletin of Symbolic Logic_, 9 (3): 362–386.

## Academic Tools

> |   |   |
> |---|---|
> |![sep man icon](https://plato.stanford.edu/symbols/sepman-icon.jpg)|[How to cite this entry](https://plato.stanford.edu/cgi-bin/encyclopedia/archinfo.cgi?entry=category-theory).|
> |![sep man icon](https://plato.stanford.edu/symbols/sepman-icon.jpg)|[Preview the PDF version of this entry](https://leibniz.stanford.edu/friends/preview/category-theory/) at the [Friends of the SEP Society](https://leibniz.stanford.edu/friends/).|
> |![inpho icon](https://plato.stanford.edu/symbols/inpho.png)|[Look up topics and thinkers related to this entry](https://www.inphoproject.org/entity?sep=category-theory&redirect=True) at the Internet Philosophy Ontology Project (InPhO).|
> |![phil papers icon](https://plato.stanford.edu/symbols/pp.gif)|[Enhanced bibliography for this entry](https://philpapers.org/sep/category-theory/) at [PhilPapers](https://philpapers.org/), with links to its database.|

## Other Internet Resources

- Cheng, E. & Lauda, A., 2004, [_Higher-Dimensional Categories: an illustrated guide book_](http://eugeniacheng.com/wp-content/uploads/2017/02/cheng-lauda-guidebook.pdf).
- Fong, B. and Spivak, D., 2019, “[Graphical Regular Logic](https://arxiv.org/pdf/1812.05765v2.pdf)”, available at arXiv.org.
- [The category theory mailing list](http://www.mta.ca/~cat-dist/) (with many links and useful information)
- [The n-category Cafe, A blog on higher-dimensional categories, physics and philosophy](http://golem.ph.utexas.edu/category/)
- [The nLab](https://ncatlab.org/nlab/show/HomePage/) (an open access resource on categories and higher-dimensional categories)
- [Logic Matters](https://www.logicmatters.net/categories/) Peter Smith’s blog on logic. It contains a page on category theory with many references and discussions.
- [The Catsters’ Category Theory Videos, introducing the basic concepts of category theory](https://www.youtube.com/watch?v=yeQcmxM2e5I&list=PLlGXNwjYhXYxKVa67r0pKuYufECy713bv/)
- [Math3Ma](https://www.math3ma.com/categories/) A math blog that contains introductions to the main concepts of category theory, set theory and other mathematical topics

## Related Entries

[logic: classical](https://plato.stanford.edu/entries/logic-classical/) | [mathematics, philosophy of](https://plato.stanford.edu/entries/philosophy-mathematics/) | [set theory](https://plato.stanford.edu/entries/set-theory/)