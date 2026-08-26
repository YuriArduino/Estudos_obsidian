https://plato.stanford.edu/entries/possible-worlds/

_First published Fri Oct 18, 2013; substantive revision Mon Feb 8, 2016_

Anne is working at her desk. While she is directly aware only of her immediate situation — her being seated in front of her computer, the music playing in the background, the sound of her husband's voice on the phone in the next room, and so on — she is quite certain that this situation is only part of a series of increasingly more inclusive, albeit less immediate, situations: the situation in her house as a whole, the one in her neighborhood, the city she lives in, the state, the North American continent, the Earth, the solar system, the galaxy, and so on. On the face of it, anyway, it seems quite reasonable to believe that this series has a _limit_, that is, that there is a maximally inclusive situation encompassing all others: _things, as a whole_ or, more succinctly, _the actual world_.

Most of us also believe that things, as a whole, needn't have been just as they are. Rather, things might have been different in countless ways, both trivial and profound. History, from the very beginning, could have unfolded quite other than it did in fact: the matter constituting a distant star might never have organized well enough to give light; species that survived might just as well have died off; battles won might have been lost; children born might never have been conceived and children never conceived might otherwise have been born. In any case, no matter how things had gone they would still have been part of a single, maximally inclusive, all-encompassing situation, a single world. Intuitively, then, the actual world is only one among many _possible worlds_.

The idea of possible worlds is evocative and appealing. However, possible worlds failed to gain any real traction among philosophers until the 1960s when they were invoked to provide the conceptual underpinnings of some powerful developments in modal logic. Only then did questions of their nature become a matter of the highest philosophical importance. Accordingly, Part 1 of this article will provide an overview of the role of possible worlds in the development of modal logic. Part 2 explores three prominent philosophical approaches to the nature of possible worlds.[[1](https://plato.stanford.edu/entries/possible-worlds/notes.html#1)] Although many of the finer philosophical points of Part 2 do presuppose the technical background of Part 1, the general philosophical landscape laid out in Part 2 can be appreciated independently of Part 1.

- [1. Possible Worlds and Modal Logic](https://plato.stanford.edu/entries/possible-worlds/#ModalLogicAndPWs)
    - [1.1 Extensionality Lost](https://plato.stanford.edu/entries/possible-worlds/#ExtensionalityLost)
    - [1.2 Extensionality Regained](https://plato.stanford.edu/entries/possible-worlds/#ExtReg)
    - [1.3 Two Applications: The Analysis of Intensions and the _De Re_ / _De Dicto_ Distinction](https://plato.stanford.edu/entries/possible-worlds/#Applications)
- [2. Three Philosophical Conceptions of Possible Worlds](https://plato.stanford.edu/entries/possible-worlds/#ConceptionsOfPWs)
    - [2.1 Concretism](https://plato.stanford.edu/entries/possible-worlds/#Concretism)
        - [2.1.1 Concrete Worlds and Existence Therein](https://plato.stanford.edu/entries/possible-worlds/#ConcWorlds)
        - [2.1.2 Actuality](https://plato.stanford.edu/entries/possible-worlds/#Actuality)
        - [2.1.3 Modal Reductionism, Counterparts, and the Analysis of Intensions](https://plato.stanford.edu/entries/possible-worlds/#Reductionism)
        - [2.1.4 Plenitude and Recombination](https://plato.stanford.edu/entries/possible-worlds/#Plenitude)
        - [2.1.5 A Brief Assessment of Concretism](https://plato.stanford.edu/entries/possible-worlds/#ConcBriefAssess)
    - [2.2 Abstractionism](https://plato.stanford.edu/entries/possible-worlds/#Abstractionism)
        - [2.2.1 Abstract Possible Worlds and Existence Therein](https://plato.stanford.edu/entries/possible-worlds/#AbstractPWs)
        - [2.2.2 Irreducible Modality and Intensional Entities](https://plato.stanford.edu/entries/possible-worlds/#AbsModIntEnt)
        - [2.2.3 Actuality and Actualism](https://plato.stanford.edu/entries/possible-worlds/#AandA)
        - [2.2.4 A Brief Assessment of Abstractionism](https://plato.stanford.edu/entries/possible-worlds/#AbsBriefAssess)
    - [2.3 Combinatorialism](https://plato.stanford.edu/entries/possible-worlds/#Combinatorialism)
        - [2.3.1 The Basic Ontology of Combinatorialism](https://plato.stanford.edu/entries/possible-worlds/#BasicOntComb)
        - [2.3.2 States of Affairs and Recombination](https://plato.stanford.edu/entries/possible-worlds/#Recombination)
        - [2.3.3 Structural States of Affairs and Supervenience](https://plato.stanford.edu/entries/possible-worlds/#Supervenience)
        - [2.3.4 Combinatorial Possible Worlds and Existence Therein](https://plato.stanford.edu/entries/possible-worlds/#CombPWs)
        - [2.3.5 Analytic and Emergent Modalities; Essential Properties](https://plato.stanford.edu/entries/possible-worlds/#Emergence)
        - [2.3.6 Fewer Things and Other Things: Modified Combinatorialism](https://plato.stanford.edu/entries/possible-worlds/#ModComb)
        - [2.3.7 A Brief Assessment of Combinatorialism](https://plato.stanford.edu/entries/possible-worlds/#CombBriefAssess)
- [Bibliography](https://plato.stanford.edu/entries/possible-worlds/#Bib)
- [Academic Tools](https://plato.stanford.edu/entries/possible-worlds/#Aca)
- [Other Internet Resources](https://plato.stanford.edu/entries/possible-worlds/#Oth)
- [Related Entries](https://plato.stanford.edu/entries/possible-worlds/#Rel)

---

## 1. Possible Worlds and Modal Logic

Although ‘possible world’ has been part of the philosophical lexicon at least since Leibniz, the notion became firmly entrenched in contemporary philosophy with the development of _possible world semantics_ for the languages of propositional and first-order modal logic. In addition to the usual sentence operators of [classical logic](https://plato.stanford.edu/entries/logic-classical/) such as ‘and’ (‘∧’), ‘or’ (‘∨’), ‘not’ (‘¬’), ‘if...then’ (‘→’), and, in the first-order case, the quantifiers ‘all’ (‘∀’) and ‘some’ (‘∃’), these languages contain operators intended to represent the modal adverbs ‘necessarily’ (‘□’) and ‘possibly’ (‘◇’). Although a prominent aspect of logic in both Aristotle's work and the work of many medieval philosophers, modal logic was largely ignored from the modern period to the mid-20th century. And even though a variety of modal deductive systems had in fact been rigorously developed in the early 20th century, notably by Lewis and Langford (1932), there was for the languages of those systems nothing comparable to the elegant semantics that Tarski had provided for the languages of classical first-order logic. Consequently, there was no rigorous account of what it means for a sentence in those languages to be _true_ and, hence, no account of the critical semantic notions of validity and logical consequence to underwrite the corresponding deductive notions of theoremhood and provability. A concomitant philosophical consequence of this void in modal logic was a deep skepticism, voiced most prominently by Quine, toward any appeal to modal notions in metaphysics generally, notably, the notion of an essential property. (See Quine 1953 and 1956, and the appendix to Plantinga 1974.) The purpose of the following two subsections is to provide a simple and largely ahistorical overview of how possible world semantics fills this void; the final subsection presents two important applications of the semantics. (Readers familiar with basic possible world semantics can skip to §2 with no significant loss of continuity.)

### 1.1 Extensionality Lost

Since the middle ages at least, philosophers have recognized a semantical distinction between _extension_ and _intension_. The extension of a denoting expression, or _term_, such as a name or a definite description is its referent, the thing that it refers to; the extension of a predicate is the set of things it applies to; and the extension of a sentence is its truth value. By contrast, the intension of an expression is something rather less definite — its _sense_, or _meaning_, the semantical aspect of the expression that determines its extension. For purposes here, let us say that a _logic_ is a formal language together with a semantic theory for the language, that is, a theory that provides rigorous definitions of truth, validity, and logical consequence for the language.[[2](https://plato.stanford.edu/entries/possible-worlds/notes.html#2)] A logic is _extensional_ if the truth value of every sentence of the logic is determined entirely by its form and the extensions of its component sentences, predicates, and terms. An extensional logic will thus typically feature a variety of valid _substitutivity principles_. A substitutivity principle says that, if two expressions are coextensional, that is, if they have the same extension, then (subject perhaps to some reasonable conditions) either can be substituted for the other in any sentence _salva veritate_, that is, without altering the original sentence's truth value. In an [_intensional_ logic](https://plato.stanford.edu/entries/logic-intensional/), the truth values of some sentences are determined by something over and above their forms and the extensions of their components and, as a consequence, at least one classical substitutivity principle is typically rendered invalid.

Extensionality is a well known and generally cherished feature of classical propositional and predicate logic. Modal logic, by contrast, is intensional. To illustrate: the substitutivity principle for sentences tells us that sentences with the same truth value can be substituted for one another _salva veritate_. So suppose that John's only pets are two dogs, Algol and BASIC, say, and consider two simple sentences and their formalizations (the predicates in question indicating the obvious English counterparts):

|   |   |   |
|---|---|---|
|||All John's dogs are mammals: ∀_x_(_Dx_ → _Mx_).|

|   |   |   |
|---|---|---|
|||All John's pets are mammals: ∀_x_(_Px_ → _Mx_)|

As both sentences are true, they have the same extension. Hence, in accordance with the classical substitutivity principle for sentences, we can replace the occurrence of (1) with (2) in the false sentence

|   |   |   |
|---|---|---|
|||Not all John's dogs are mammals: ¬∀_x_(_Dx_ → _Mx_)|

and the result is the equally false sentence

|   |   |   |
|---|---|---|
|||Not all John's pets are mammals: ¬∀_x_(_Px_ → _Mx_).|

However, when we make the same substitution in the true sentence

|   |   |   |
|---|---|---|
|||Necessarily, all John's dogs are mammals: □∀_x_(_Dx_ → _Mx_),|

the result is the sentence

|   |   |   |
|---|---|---|
|||Necessarily, all John's pets are mammals: □∀_x_(_Px_ → _Mx_),|

which is intuitively false, as John surely could have had a non-mammalian pet. In a modal logic that accurately represents the logic of the necessity operator, therefore, the substitutivity principle for sentences will have to fail.

The same example illustrates that the substitutivity principle for predicates will have to fail in modal logic as well. For, according to our example, the predicates ‘_D_’ and ‘_P_’ that are true of John's dogs and of John's pets, respectively, are coextensional, i.e., ∀_x_(_Dx_ ↔ _Px_). However, while substituting the latter predicate for the former in (3) results in a sentence with the same truth value, the same substitution in (5) does not.

Modal logic, therefore, is intensional: in general, the truth value of a sentence is determined by something over and above its form and the extensions of its components. Absent a rigorous semantic theory to identify the source of its intensionality and to systematize intuitions about modal truth, validity, and logical consequence, there was little hope for the widespread acceptance of modal logic.

### 1.2 Extensionality Regained

The idea of possible worlds raised the prospect of extensional respectability for modal logic, not by rendering modal logic itself extensional, but by endowing it with an extensional semantic theory — one whose own logical foundation is that of classical predicate logic and, hence, one on which possibility and necessity can ultimately be understood along classical Tarskian lines. Specifically, in _possible world semantics_, the modal operators are interpreted as _quantifiers_ over possible worlds, as expressed informally in the following two general principles:

|   |   |   |
|---|---|---|
|**Nec**||A sentence of the form ⌈Necessarily, φ⌉ (⌈◻φ⌉) is true if and only if φ is true in every possible world.[[3](https://plato.stanford.edu/entries/possible-worlds/notes.html#3)]|

|   |   |   |
|---|---|---|
|**Poss**||A sentence of the form ⌈Possibly, φ⌉ (⌈◇φ⌉) is true if and only if φ is true in some possible world.|

Given this, the failures of the classical substitutivity principles can be traced to the fact that modal operators, so interpreted, introduce contexts that require subtler notions of meaning for sentences and their component parts than are provided in classical logic; in particular, a subtler notion (to be clarified shortly) is required for predicates than that of the set of things they happen to apply to.

**Tarskian Semantics.** Standard model theoretic semantics for the languages of predicate logic deriving from the work of Tarski (1933, 1944) is the paradigmatic semantic theory for extensional logics. Given a standard first-order language ℒ, a Tarskian _interpretation_ **I** _for_ ℒ specifies a set **D** for the quantifiers of ℒ to range over (typically, some set of things that ℒ has been designed to describe) and assigns, to each term (constant or variable) τ of ℒ, a referent **a**τ ∈ **D** and, to each _n_-place predicate π of ℒ, an appropriate extension **E**π — a truth value (TRUE or FALSE) if _n_ = 0, a subset of **D** if _n_ = 1, and a set of _n_-tuples of members of **D** if _n_ > 1. Given these assignments, sentences are evaluated as true under the interpretation **I** — true**I**, for short — according to a more or less familiar set of clauses. To facilitate the definition, let **I**[ν/**a**] be the interpretation that assigns the individual **a** to the variable ν and is otherwise exactly like **I**. Then we have:

- An atomic sentence ⌈πτ1...τ_n_⌉ (of ℒ) is _true_**I** if and only if
    - _n_ = 0 (i.e., π is a sentence letter) and the extension of π is the truth value TRUE; or
    - _n_ = 1 and **a**τ1 is in the extension of π; or
    - _n_ > 1 and ⟨**a**τ1, ..., **a**τ_n_⟩ is in the extension of π.
- A negation ⌈¬ψ⌉ is true**I** if and only if ψ is not true**I**.
- A material conditional⌈ψ → θ⌉ is true**I** iff, if ψ is true**I**, then θ is true**I**.
- A universally quantified sentence ⌈∀νψ⌉ is true**I** if and only if, for all individuals **a** ∈ **D**, ψ is true**I**[ν/**a**].[[4](https://plato.stanford.edu/entries/possible-worlds/notes.html#4)]

Clauses for the other standard Boolean operators and the existential quantifier under their usual definitions follow straightaway from these clauses. In particular, where

|   |   |   |
|---|---|---|
|||∃νφ =_def_ ¬∀ν¬φ|

it follows that:

- An existentially quantified sentence ⌈∃νψ⌉ is is true**I** if and only if, for some individual **a** ∈ **D**, ψ is true**I**[ν/**a**].

It is easy to verify that, in each of the above cases, replacing one coextensional term, predicate, or sentence for another has no effect on the truth values rendered by the above clauses, thus guaranteeing the validity of the classical substitutivity principles and, hence, the extensionality of first-order logic with a Tarskian semantics.

**From Tarskian to Possible World Semantics.** The truth conditional clauses for the three logical operators directly reflect the meanings of the natural language expressions they symbolize: ‘¬’ means _not_; ‘→’ means _if...then_; ‘∀’ means _all_. It is easy to see, however, that we cannot expect to add an equally simple clause for sentences containing an operator that symbolizes necessity. For a Tarskian interpretation _fixes_ the domain of quantification and the extensions of all the predicates. Pretty clearly, however, to capture necessity and possibility, one must be able to consider alternative “possible” domains of quantification and alternative “possible” extensions for predicates as well. For, intuitively, under different circumstances, fewer, more, or other things might have existed and things that actually exist might, in those circumstances, have had very different properties. (6), for example, is false because John could have had non-mammalian pets: a canary, say, or a turtle, or, under _very_ different circumstances, a dragon. A bit more formally put: Both the domain of quantification and the extension of the predicate ‘_P_’ could, in some sense or other, have been different.

Possible world semantics, of course, uses the concept of a possible world to give substance to the idea of alternative extensions and alternative domains of quantification. (Possible world semantics can be traced most clearly back to the work of Carnap (1947), its basic development culminating in the work of Hintikka (1957, 1961), Bayart (1958, 1959), and Kripke (1959, 1963a, 1963b).[[5](https://plato.stanford.edu/entries/possible-worlds/notes.html#5)]) Similar to Tarskian semantics, a possible world interpretation **M** of a modal language ℒ specifies a nonempty set **D**, although thought of now as the set of “possible individuals” of **M**. Also as in Tarskian semantics, **M** assigns each term τ of ℒ a referent **a**τ in **D**.[[6](https://plato.stanford.edu/entries/possible-worlds/notes.html#6)] Additionally however, **M** specifies a set **W**, the set of “possible worlds” of **M**, one of which is designated its “actual world”, and each world **w** in **W** is assigned its own domain of quantification, **d**(**w**) ⊆ **D**, intuitively, the set of individuals that exist in **w**.[[7](https://plato.stanford.edu/entries/possible-worlds/notes.html#7)] To capture the idea of both the actual and possible extensions of a predicate, **M** assigns to each _n_-place predicate π a function **M**π — the _intension_ of π — that, for each possible world **w**, returns the _ex_tension **M**π(**w**) of π _at_ **w**: a truth value, if _n_ = 0; a set of individuals, if _n_ = 1; and a set of _n_-tuples of individuals, if _n_ > 1.[[8](https://plato.stanford.edu/entries/possible-worlds/notes.html#8)] We can thus rigorously define a “possible extension” of a predicate π to be any of its _**w**-extensions_ **M**π(**w**), for any world **w**.

The Tarskian truth conditions above are now generalized by relativizing them to worlds as follows: for any possible world **w** (the _world of evaluation_):

- An atomic sentence ⌈πτ1...τ_n_⌉ (of ℒ) is _true_**M** _at_ **w** if and only if:
    - _n_ = 0 and the **w**-extension of π is the truth value TRUE; or
    - _n_ = 1 and _a_τ1 is in the **w**-extension of π; or
    - _n_ > 1 and ⟨**a**τ1,..., **a**τ_n_⟩ is in the **w**-extension of π.
- A negation ⌈¬ψ⌉ is true**M** at **w** if and only ψ is not true**M** in **w**.
- A material conditional⌈ψ→θ⌉ is true**M** at **w** iff, if ψ is true**M** at **w**, then θ is true**M** at **w**.
- A quantified sentence ⌈∀νψ⌉ is true**M** at **w** if and only if, for all individuals **a** that exist in **w**, ψ is true**M**[ν/**a**].

And to these, of course, is added the critical modal case that explicitly interprets the modal operator to be a quantifier over worlds, as we'd initially anticipated informally in our principle [**Nec**](https://plato.stanford.edu/entries/possible-worlds/#Nec):

- A necessitation ⌈◻ψ⌉ is true**M** at **w** if and only if, for all possible worlds **u** of **M**, ψ is true**M** at **u**.[[9](https://plato.stanford.edu/entries/possible-worlds/notes.html#9)]

A sentence φ is _false_**M** at **w** just in case it is not true**M** at **w**, and φ is said to be _true_**M** just in case φ is true**M** at the actual world of **M**.

On the assumption that there is a (nonempty) set of all possible worlds and a set of all possible individuals, we can define “objective” notions of truth at a world and of truth _simpliciter_, that is, notions that are not simply relative to formal, mathematical interpretations but, rather, correspond to objective reality in all its modal glory. Let ℒ be a modal language whose names and predicates represent those in some fragment of ordinary language (as in our examples (5) and (6) above). Say that **M** is the “intended” interpretation of ℒ if (i) its set **W** of “possible worlds” is in fact the set of all possible worlds, (ii) its designated “actual world” is in fact the actual world, (iii) its set **D** of “possible individuals” is in fact the set of all possible individuals, and (iv) the referents assigned to the names of ℒ and the intensions assigned to the predicates of ℒ are the ones they in fact have. Then, where **M** is the intended interpretation of ℒ, we can say that a sentence φ of ℒ is _true at_ a possible world **w** just in case φ is true**M** at **w**, and that φ is _true_ just in case it is true**M** at the actual world. (Falsity at **w** and falsity, _simpliciter_, are defined accordingly.) Under the assumption in question, then, the modal clause above takes on pretty much the exact form of our informal principle [**Nec**](https://plato.stanford.edu/entries/possible-worlds/#Nec).

Call the above _basic_ possible world semantics. Spelling out the truth conditions for (6) (relative to the intended interpretation of its language), basic possible world semantics tells us that (6) is true if and only if

|   |   |   |
|---|---|---|
|||For all possible worlds **w**, ‘∀_x_(_Px_ → _Mx_)’ is true at **w**.|

And by unpacking (8) in terms of the quantificational, material conditional, and atomic clauses above we have that (6) is true if and only if

|   |   |   |
|---|---|---|
|||For all possible worlds **w**, and for all possible individuals **a** that exist in **w**, if **a** is in the **w**-extension of ‘_P_’ then **a** is in the **w**-extension of ‘_M_’.|

Since we are evaluating (6) with regard to the intended interpretation of its language, the **w**-extension of ‘_P_’ that is returned by its intension, for any world **w**, is the (perhaps empty) set of John's pets in **w** and that of ‘_M_’ is the set of mammals in **w**. Hence, if **w** is a world where John has a pet canary — COBOL, say — COBOL is in the **w**-extension of ‘_P_’ but not that of ‘_M_’ , i.e., ‘∀_x_(_Px_ → _Mx_)’ is false at **w** and, hence, by the truth condition (9), (6) is false at the actual world — that is, (6) is false _simpliciter_, as it should be.

Note that interpreting modal operators as quantifiers over possible worlds provides a nice theoretical justification for the usual definition of the possibility operator in terms of necessity, specifically:

|   |   |   |
|---|---|---|
|||⌈◇φ⌉ =_def_ ⌈¬◻¬φ⌉.|

That is, a sentence is possible just in case its negation isn't necessary. Since, semantically speaking, the necessity operator is _literally_ a universal quantifier, the definition corresponds exactly to the definition [(7)](https://plato.stanford.edu/entries/possible-worlds/#EQDef) of the existential quantifier. For, unpacking the right side of definition (10) according to the negation and necessitation clauses above (and invoking the definitions of truth and truth at a world _simpliciter_), we have:

|   |   |   |
|---|---|---|
|||⌈◇φ⌉ is true iff it is not the case that, for all possible worlds **w**, φ is not true at **w**.|

Clearly, however, if it is not the case that φ fails to be true at all possible worlds, then it must be true at some world; hence:

|   |   |   |
|---|---|---|
|||⌈◇φ⌉ is true iff, for some possible world **w**, φ is true at **w**.|

And that corresponds exactly to our intuitive truth condition [**Poss**](https://plato.stanford.edu/entries/possible-worlds/#Poss) above. Thus, spelling out the negation ‘¬□∀_x_(_Px_ → _Mx_)’ of our false sentence [(6)](https://plato.stanford.edu/entries/possible-worlds/#FalseNecessityExample) above in accordance with definition (10) (and the standard definition of conjunction ∧), we have:

|   |   |   |
|---|---|---|
|||Possibly, one of John's pets is not a mammal: ◇∃_x_(_Px_ ∧ ¬_Mx_),|

for which (12) and the possible world truth conditions for quantified, Boolean, and atomic sentences yield the correct truth condition:

|   |   |   |
|---|---|---|
|||There is a possible world **w** and an individual **a** existing in **w** that is in the **w**-extension of ‘_P_’ but not that of ‘_M_’,|

that is, less stuffily, there is a possible world in which, among John's pets, at least one is not a mammal.

**Summary: Intensionality and Possible Worlds.** Analyzed in terms of possible world semantics, then, the general failure of classical substitutivity principles in modal logic is due, not to an irreducibly intensional element in the meanings of the modal operators, but rather to a sort of mismatch between the surface syntax of those operators and their semantics: syntactically, they are unary sentence operators like negation; but semantically, they are, quite literally, quantifiers. Their syntactic similarity to negation suggests that, like negation, the truth values of ⌈□φ⌉ and ⌈◇φ⌉, insofar as they are determinable at all, must be determined by the truth value of φ. That they are not (in general) so determined leads to the distinctive substitutivity failures noted above. The possible worlds analysis of the modal operators as quantifiers over worlds reveals that the unary syntactic form of the modal operators obscures a semantically relevant parameter. When the modal operators are interpreted as quantifiers, this parameter becomes explicit and the reason underlying the failure of extensionality in modal logic becomes clear: That the truth values of ⌈□φ⌉ and ⌈◇φ⌉ are not in general determined by the truth value of φ at the world of evaluation is, semantically speaking, nothing more than the fact that the truth values of ‘∀_xFx_’ and ‘∃_xFx_’ are not in general determined by the truth value of ‘_Fx_’, for any particular value of ‘_x_’. Possible world semantics, therefore, _explains_ the intensionality of modal logic by revealing that the syntax of the modal operators prevents an adequate expression of the meanings of the sentences in which they occur. Spelled out as possible world truth conditions, those meanings can be expressed in a wholly extensional fashion. (For a more formal exposition of this point, see the supplemental article [The Extensionality of Possible World Semantics](https://plato.stanford.edu/entries/possible-worlds/semantics-extensionality.html).)

### 1.3 Two Applications: The Analysis of Intensions and the _De Re_ / _De Dicto_ Distinction

As noted, the focus of the present article is on the metaphysics of possible worlds rather than applications. Of course, the semantics of modal languages is itself an application, but one that is of singular importance, both for historical reasons and because most applications are in fact themselves applications of (often extended or modified versions of) the semantical apparatus. Two particularly important examples are the analysis of intensions and a concomitant explication of the _de re_/_de dicto_ distinction.[[10](https://plato.stanford.edu/entries/possible-worlds/notes.html#10)]

**The Analysis of Intensions.** As much a barrier to the acceptance of modal logic as intensionality itself was the need to appeal to intensions _per se_ — properties, relations, propositions, and the like — in semantical explanations. Intensional entities have of course featured prominently in the history of philosophy since Plato and, in particular, have played natural explanatory roles in the analysis of [intentional attitudes](https://plato.stanford.edu/entries/prop-attitude-reports/) like [belief](https://plato.stanford.edu/entries/belief/) and [mental content](https://plato.stanford.edu/entries/mental-representation/). For all their prominence and importance, however, the nature of these entities has often been obscure and controversial and, indeed, as a consequence, they were easily dismissed as ill-understood and metaphysically suspect “creatures of darkness” (Quine 1956, 180) by the naturalistically oriented philosophers of the early- to mid-20th century. It is a virtue of possible world semantics that it yields rigorous _definitions_ for intensional entities. More specifically, as described above, possible world semantics assigns to each _n_-place predicate π a certain function **I**π — π's intension — that, for each possible world **w**, returns the extension **I**π(**w**) of π at **w**. We can define an intension _per se_, independent of any language, to be any such function on worlds. More specifically:

- A _proposition_ is any function from worlds to truth values.
- A _property_ is any function from worlds to sets of individuals.
- An __n_-place relation_ (_n_ > 1) is any function from worlds to sets of _n_-tuples of individuals.

The adequacy of this analysis is a matter of lively debate that focuses chiefly upon whether or not intensions, so defined, are too “coarse-grained” to serve their intended purposes. (See, e.g., Stalnaker 1987 and 2012 for a strong defense of the analysis.) However, Lewis (1986, §1.5) argues that, even if the above analysis fails for certain purposes, it does not follow that intensions cannot be analyzed in terms of possible worlds, but only that more subtle constructions might be required. This reply appears to side-step the objections from granularity while preserving the great advantage of the possible worlds analysis of intensions, viz., the rigorous definability of these philosophically significant notions.

**The _De Re_ / _De Dicto_ Distinction.** A particularly rich application of the possible world analysis of intensions concerns the analysis of the venerable distinction between _de re_ and _de dicto_ modality.[[11](https://plato.stanford.edu/entries/possible-worlds/notes.html#11)] Among the strongest modal intuitions is that the possession of a property has a modal character — that things exemplify, or fail to exemplify, some properties _necessarily_, or _essentially_, and others only _accidentally_. Thus, for example, intuitively, John's dog Algol is a pet accidentally; under less fortunate circumstances, she might have been, say, a stray that no one ever adopted. But she is a dog essentially; she couldn't have been a flower, a musical performance, a crocodile or any other kind of thing.

Spelling out this understanding in terms of worlds and the preceding analysis of intensions, we can say that an individual **a** has a property **F** essentially if **a** has **F** in every world in which it exists, that is, if, for all worlds **w** in which **a** exists, **a** ∈ **F**(**w**). Likewise, **a** has **F** accidentally if **a** has **F** in the actual world @ but lacks it in some other world, that is, if **a** ∈ **F**(@) but, for some world **w** in which **a** exists, **a** ∉ **F**(**w**). Thus, let ‘_G_’ and ‘_T_’ symbolize ‘is a dog’ and ‘is someone's pet’, respectively; then, where ‘_E!x_’ is short for ‘∃_y_(_x_=_y_)’ (and, hence, expresses that _x_ exists), we have:

|   |   |   |
|---|---|---|
|||Algol is a dog essentially: □(_E!a_ → _Ga_)|

|   |   |   |
|---|---|---|
|||Algol is a pet accidentally: _Ta_ ∧ ◇(_E!a_ ∧ ¬_Ta_)|

More generally, sentences like (15) and (16) in which properties are ascribed to a specific individual in a modal context — signaled formally by the occurrence of a name or the free occurrence of a variable in the scope of a modal operator — are said to exhibit modality _de re_[[12](https://plato.stanford.edu/entries/possible-worlds/notes.html#12)] (modality _of the thing_). Modal sentences that do not, like

|   |   |   |
|---|---|---|
|||Necessarily, all dogs are mammals: □∀_x_(_Gx_ → _Mx_)|

are said to exhibit modality _de dicto_ (roughly, modality _of the_ _proposition_). Possible world semantics provides an illuminating analysis of the key difference between the two: The truth conditions for both modalities involve a commitment to possible worlds; however, the truth conditions for sentences exhibiting modality _de re_ involve in addition a commitment to the meaningfulness of [_transworld identity_](https://plato.stanford.edu/entries/identity-transworld/), the thesis that, necessarily, every individual (typically, at any rate) exists and exemplifies (often very different) properties in many different possible worlds. More specifically, basic possible world semantics yields intuitively correct truth values for sentences of the latter sort by (i) permitting world domains to overlap and (ii) assigning intensions to predicates, thereby, in effect, relativizing predicate extensions to worlds. In this way, one and the same individual can be in the extension of a given predicate at all worlds in which they exist, at some such worlds only, or at none at all. (For further discussion, see the entry on [essential vs. accidental properties](https://plato.stanford.edu/entries/essential-accidental/).)

## 2. Three Philosophical Conceptions of Possible Worlds

The power and appeal of basic possible world semantics is undeniable. In addition to providing a clear, extensional formal semantics for a formerly somewhat opaque, intensional notion, cashing possibility as truth in some possible world and necessity as truth in every such world seems to tap into very deep intuitions about the nature of modality and the meaning of our modal discourse. Unfortunately, the semantics leaves the most interesting — and difficult — philosophical questions largely unanswered. Two arise with particular force:

|   |   |   |
|---|---|---|
|**QW**||What, exactly, is a possible world?|

And, given **QW**:

|   |   |   |
|---|---|---|
|**QE**||What is it for something to exist in a possible world?|

In this section we will concern ourselves with, broadly speaking, the three most prominent philosophical approaches to these questions.[[13](https://plato.stanford.edu/entries/possible-worlds/notes.html#13)]

### 2.1 Concretism

Recall the informal picture that we began with: a world is, so to say, the “limit” of a series of increasingly more inclusive situations. Fleshed out philosophical accounts of this informal idea generally spring from rather different intuitions about what one takes the “situations” in the informal picture to be. A particularly powerful intuition is that situations are simply structured collections of physical objects: the immediate situation of our initial example above, for instance, consists of, among other things, the objects in Anne's office — notably Anne herself, her desk and her computer, with her seated at the former and typing on the latter — and at least some of the things in the next room — notably, her husband and the phone he is talking on. On this view, for one situation **s** to include another **r** is simply for **r** to be a (perhaps rather complex and distributed) physical part of **s**. The actual world, then, as the limit of a series of increasingly more inclusive situations in this sense, is simply the entire physical universe: all the things that are some spatiotemporal distance from the objects in some arbitrary initial situation, structured as they in fact are; and other possible worlds are things of exactly the same sort. Call this the _concretist_ intuition, as possible worlds are understood to be concrete physical situations of a special sort.

#### 2.1.1 Concrete Worlds and Existence Therein

The originator and, by far, the best known proponent of concretism is [David Lewis](https://plato.stanford.edu/entries/david-lewis/). For Lewis and, as noted, concretists generally, the actual world is the concrete physical universe as it is, stretched out in space-time. As he rather poetically expresses it (1986, 1):

> The world we live in is a very inclusive thing....There is nothing so far away from us as not to be part of our world. Anything at any distance is to be included. Likewise the world is inclusive in time. No long-gone ancient Romans, no long-gone pterodactyls, no long-gone primordial clouds of plasma are too far in the past, nor are the dead dark stars too far in the future, to be part of this same world....[N]othing is so alien in kind as not to be part of our world, provided only that it does exist at some distance and direction from here, or at some time before or after or simultaneous with now.

The actual world provides us with our most salient example of what a possible world is. But, for the concretist, other possible worlds are no different in kind from the actual world (_ibid._, 2):

> There are countless other worlds, other very inclusive things. Our world consists of us and all our surroundings, however, remote in time and space; just as it is one big thing having lesser things as parts, so likewise do other worlds have lesser other-worldly things as parts.

It is clear that spatiotemporal relations play a critical role in Lewis's conception. However, it is important to note that Lewis understands such relations in a very broad and flexible way so as to allow, in particular, for the possibility of spirits and other entities that are typically thought of as non-spatial; so long as they are located in time, Lewis writes, “that is good enough” (_ibid._, 73). So with this caveat, let us say that that an object **a** is _connected_ if any two of its parts bear some spatiotemporal relation to each other,[[14](https://plato.stanford.edu/entries/possible-worlds/notes.html#14)] and that **a** is _maximal_ if none of its parts is spatiotemporally related to anything that is not also one of its parts. Then we have the following concretist answers to our questions:

|   |   |   |
|---|---|---|
|**AW1**||**w** is a possible world =_def_ **w** is a maximal connected object.[[15](https://plato.stanford.edu/entries/possible-worlds/notes.html#15)]|

And, hence, to exist in a world is simply to be a part of it:

|   |   |   |
|---|---|---|
|**AE1**||Individual **a** exists in world **w** =_def_ **a** is a part of **w**.|

It follows from **AW1** (and reasonable assumptions) that distinct worlds do not overlap, spatiotemporally; that no spatiotemporal part of one world is part of another.[[16](https://plato.stanford.edu/entries/possible-worlds/notes.html#16)] Moreover, given [Lewis's counterfactual analysis of causation](https://plato.stanford.edu/entries/causation-counterfactual/), it follows from this that objects in distinct worlds bear no causal relations to one another; nothing that occurs in one world has any causal impact on anything that occurs in any other world.

#### 2.1.2 Actuality

Critically, for Lewis, worlds and their denizens do not differ in the _manner_ in which they exist. The actual world does not enjoy a kind of privileged existence that sets it apart from other worlds. Rather, what makes the actual world actual is simply that it is _our_ world, the world that we happen to inhabit. Other worlds and their inhabitants exist just as robustly as we do, and in precisely the same sense; all worlds and all of their denizens are equally _real_.[[17](https://plato.stanford.edu/entries/possible-worlds/notes.html#17)] A significant semantic corollary of this thesis for Lewis is that the word ‘actual’ in the phrase ‘the actual world’ does not indicate any special _property_ of the actual world that distinguishes it from all other worlds; likewise, an assertion of the form ‘**a** is actual’ does not indicate any special property of the individual **a** that distinguishes it from the objects existing in other worlds. Rather, ‘actual’ is simply an _indexical_ whose extension is determined by the context of utterance. Thus, the referent of ‘the actual world’ in a given utterance is simply the world of the speaker, just as the referent of an utterance of ‘the present moment’ is the moment of the utterance; likewise, an utterance of the form ‘**a** is actual’ indicates only that **a** shares the same world as the speaker. The speaker thereby ascribes no special property to **a** but, essentially, expresses no more than when she utters ‘**a** is _here_’, understood in the broadest possible sense. By the same token, when we speak of non-actual _possibilia_ — Lewis's preferred label for the denizens of possible worlds — we simply pick out those objects that are _not_ here in the broadest sense. In the mouth of an other-worldly metaphysician, we here are all among the non-actual _possibilia_ of which she speaks in her lectures on _de re_ modality.

#### 2.1.3 Modal Reductionism, Counterparts, and the Analysis of Intensions

**Modal Reductionism and Counterparts.** Lewis parted ways dramatically with his mentor [W. V. O. Quine](https://plato.stanford.edu/entries/quine/) on modality. Quine (1960, §41) stands in a long line of philosophers dating back at least to [David Hume](https://plato.stanford.edu/entries/hume/) who are skeptical, at best, of the idea that modality is an objective feature of reality and, consequently, who question whether modal assertions in general can be objectively true or false, or even coherent. Lewis, by contrast, wholly embraces the objectivity of modality and the coherence of our modal discourse. What he denies, however, is that modality is a fundamentally _irreducible_ feature of the world. Lewis, that is, is a _modal reductionist_. For Lewis, modal notions are not primitive. Rather, truth conditions for modal sentences can be given in terms of worlds and their parts; and worlds themselves, Lewis claims, are defined entirely in non-modal terms. The earliest presentation of Lewis's theory of modality (Lewis 1968) — reflecting Quine's [method of regimentation](https://plato.stanford.edu/entries/quine/#MethRegiTheo) — offers, rather than a possible world semantics, a scheme for _translating_ sentences in the language of modal predicate logic into sentences of ordinary first-order logic in which the modal operators are replaced by explicit quantifiers over worlds.[[18](https://plato.stanford.edu/entries/possible-worlds/notes.html#18)] The mature account of Lewis 1986 is much more semantic in orientation: it avoids any talk of translation and offers instead a (somewhat informal) account of concretist possible world truth conditions for a variety of modal assertions. Nonetheless, it is useful to express the logical forms of these truth conditions explicitly in terms of worlds, existence in a world (in the sense of **AE1**, of course), and the _counterpart_ relation, which will be discussed shortly:

|   |   |   |
|---|---|---|
|_Wx_:||_x_ is a _world_|
|_Ixy_:||_x_ _exists in_ world _y_|
|_Cxy_:||_x_ is a _counterpart_ of _y_|

For sentences like [(17)](https://plato.stanford.edu/entries/possible-worlds/#DeDicto) involving only _de dicto_ modalities, Lewis's truth conditions are similar in form to the truth conditions generated by the modal clauses of basic possible world semantics; specifically, for (17):

|   |   |   |
|---|---|---|
|||For every world **w**, every individual **x** in **w** that is a dog is a mammal: ∀_w_(_Ww_ → ∀_x_(_Ixw_ → (_Gx_ → _Mx_))).|

As in possible world semantics, the modal operators ‘□’ and ‘◇’ “turn into” quantifiers over worlds in concretist truth conditions (1986, 5). Also as in possible world semantics, a quantifier (in effect) ranging over individuals that occurs in the scope of a quantifier (in effect) ranging over worlds — ‘∀_x_’ and ‘∀_w_’, respectively, in (18) — is, for each value **w** of the bound world variable, restricted to the objects existing in **w**. However, unlike possible world semantics, predicates are not to be thought of as having different extensions at different worlds. Rather, for Lewis, each (_n_-place) predicate has a single extension that can contain (_n_-tuples of) objects across many different worlds — intuitively, all of the objects that have the property (or _n_-tuples of objects that stand in the relation) expressed by the predicate across all possible worlds. Thus, in particular, the predicate ‘_G_’ picks out, not just this-worldly dogs but other-worldly canines as well. Likewise, the pet predicate ‘_T_’ picks out both actual and other-worldly pets. Such a move is not feasible in basic possible world semantics, which is designed for a metaphysics in which one and the same individual can exemplify a given property in some worlds in which they exist but not others. Hence, a typical predicate will be true of an individual with respect to some worlds and false of it with respect to others. But, for Lewis, as we've seen, distinct possible worlds do not overlap and, hence, objects are worldbound, thereby eliminating the need to relativize predicate extensions to worlds.

However, this very feature of Lewis's account — worldboundedness — might appear to threaten its coherence. For example, since Algol is in fact a pet, given worldboundedness and the definition [**AE1**](https://plato.stanford.edu/entries/possible-worlds/#AE1) of existence in a world **w**, we have:

|   |   |   |
|---|---|---|
|||There is no world **w** such that Algol exists in **w** and fails to be someone's pet: ¬∃_w_(_Iaw_ ∧ ¬_Ta_),|

But, according to Lewis's analysis, the modal operators ‘□’ and ‘◇’, semantically, are quantifiers over worlds. Hence, (19) might appear to be exactly the concretist truth condition for the denial of (the right conjunct of) ([16](https://plato.stanford.edu/entries/possible-worlds/#Acc)), i.e., it might appear that, on Lewis's analysis, Algol is not a pet accidentally but essentially; likewise, more generally, any individual and any intuitively accidental property of that individual.

In fact, Lewis whole-heartedly accepts that things have accidental properties and, indeed, would accept that [(16)](https://plato.stanford.edu/entries/possible-worlds/#Acc) is robustly true. His explanation involves one of the most interesting and provocative elements of his theory: the doctrine of _counterparts_. Roughly, an object **y** in a world **w**2 is a counterpart of an object **x** in **w**1 if **y** resembles **x** and nothing else in **w**2 resembles **x** more than **y**.[[19](https://plato.stanford.edu/entries/possible-worlds/notes.html#19)] Each object is thus its own (not necessarily unique) counterpart in the world it inhabits but will typically differ in important ways from its other-wordly counterparts. A typical other-worldly counterpart of Algol, for example, might resemble her very closely up to some point in her history — a point, say, after which she continued to live out her life as a stray instead of being brought home by our kindly dog-lover John. Hence, sentences making _de re_ assertions about what _Algol_ might have done or what _she_ could or could not have been are unpacked, semantically, as sentences about her _counterparts_ in other possible worlds. Thus, when we analyze (16) accordingly, we have the entirely unproblematic concretist truth condition:

|   |   |   |
|---|---|---|
|||Algol is a pet, but there is a world in which exists a counterpart of hers that is not:  <br>_Ta_ ∧ ∃_w_(_Ww_ ∧ ∃_x_(_Ixw_ ∧ _Cxa_ ∧ ¬_Tx_)).|

Ascriptions of essential properties, as in ([15](https://plato.stanford.edu/entries/possible-worlds/#Ess)), are likewise unpacked in terms of counterparts: to say that Algol is a dog essentially is to say that

|   |   |   |
|---|---|---|
|||All of Algol's counterparts in any world are dogs:  <br>∀_w_(_Ww_ → ∀_x_((_Ixw_ ∧ _Cxa_) → _Gx_)).|

**The Analysis of Intensions.** Lewis's possible world truth conditions are expressed in classical non-modal logic and, hence, they are to be interpreted by means of standard Tarskian semantics. Thus, _n_-place predicates π are assigned extensions **E**π — in particular, for 1-place predicates, sets of individuals — as their semantic values, as described in the exposition in [§1.2](https://plato.stanford.edu/entries/possible-worlds/#ExtReg) above. However, given worldboundedness and the fact that predicate extensions are drawn not simply from the actual world but from all possible worlds, these extensions are able to serve as _in_tensions in Lewis's theory. As in basic possible world semantics, intensional entities in general can be defined in terms of the basic ontology of the theory independent of the linguistic roles they can play as the intensions of predicates. And because individuals are worldbound, Lewis is able to simplify the definitions given in [§1.3](https://plato.stanford.edu/entries/possible-worlds/#Applications) by defining intensions as sets rather than functions:

- A _proposition_ is any set of worlds.
- A _property_ is any set of individuals.
- An __n_-place relation_ (_n_ > 1) is any set of _n_-tuples of individuals.[[20](https://plato.stanford.edu/entries/possible-worlds/notes.html#20)]

Thus, on this analysis, a proposition **p** is _true in_ a world **w** just in case **w** ∈ **p** and an individual **a** has a property **P** just in case **a** ∈ **P**. (Note that propositions are thus simply properties of worlds on these definitions.) **a** has **P** _accidentally_ just in case **a** ∈ **P** but **b** ∉ **P** for some other-worldly counterpart of **b** of **a**; and **a** has **P** _essentially_ if **b** ∈ **P** for every counterpart **b** of **a**.

In Lewis's theory of modality, then, modal operators are understood semantically to be quantifiers over concrete worlds, predicates denote intensions understood as sets of (_n_-tuples of) parts of those worlds, and sentences involving _de re_ modalities are understood in terms of counterparts. To the extent that these notions are free of modality, Lewis has arguably reduced modal notions to non-modal.

#### 2.1.4 Plenitude and Recombination

That Lewis's truth conditions for modal statements are themselves free of modality and, hence, that his theory counts as a genuine reduction of modal notions to non-modal is not terribly controversial (albeit not undisputed — see Lycan 1991, 224–27; Divers and Melia 2002, 22–24). Significantly more controversial, and perhaps far more critical to the project, is whether or not his account is _complete_, that is, whether or not, for all modal statements φ, (i) if φ is intuitively true, then its Lewisian truth condition holds (ii) if φ is intuitively false, then its Lewisian truth condition fails.[[21](https://plato.stanford.edu/entries/possible-worlds/notes.html#21)] The challenge to Lewis, then, is that his account can be considered _successful_ only if it is complete in this sense.

The chief question Lewis faces in this regard is whether there are _enough_ worlds to do the job. The truth condition ([20](https://plato.stanford.edu/entries/possible-worlds/#Acc-Trans)) for the intuitively true ([16](https://plato.stanford.edu/entries/possible-worlds/#Acc)) says that there exists a possible world in which a counterpart of Algol is no one's pet. By virtue of what in Lewis's theory does such a world exist? The ideal answer for Lewis would be that some principle in his theory guarantees a _plenitude_ of worlds, a maximally abundant array of worlds that leaves “no gaps in logical space; no vacancies where a world might have been, but isn't” (Lewis 1986, 86). From this it would follow that the worlds required by the concretist truth condition for any intuitive modal truth exist. Toward this end, Lewis initially considers the evocative principle:

|   |   |   |
|---|---|---|
|**Ways**||Absolutely every way that a world could be is a way that some world is.|

Since, in particular, a world satisfying ([20](https://plato.stanford.edu/entries/possible-worlds/#Acc-Trans)) seems quite obviously to be a way a world could be, by **Ways** such a world exists. But there is a fatal flaw here: Lewis himself (1973, 84) identifies _ways_ that a world could be with worlds themselves. So understood, **Ways** collapses into the triviality that every world is identical to some world.[[22](https://plato.stanford.edu/entries/possible-worlds/notes.html#22)]

Lewis finds a replacement for **Ways** in a principle of _recombination_ whereby “patching together parts of different possible worlds yields another possible world” (1986, 87–88). The principle has two aspects. The first is the principle that “anything can coexist with anything”. For “if there could be a dragon, and there could be a unicorn,” Lewis writes, “but there couldn't be a dragon and a unicorn side by side, that would be ... a failure of plenitude” (_ibid_., 88). Given that individuals are worldbound, however, the principle is expressed more rigorously (and more generally) in terms of other-worldly _duplicates_:

|   |   |   |
|---|---|---|
|**R1**||For any (finite or infinite) number of objects **a**1, **a**2, ..., there is a world containing any number of duplicates of each of those objects in any spatiotemporal arrangement (size and shape permitting).|

The second aspect of the principle expresses “the Humean denial of necessary connections” (_ibid_., 87), that is, the idea that anything can _fail_ to coexist with anything else. For “if there could be a talking head contiguous to the rest of a living human body, but there couldn't be a talking head separate from the rest of a human body, that too would be a failure of plenitude” (_ibid_). To express this a bit more rigorously, say that objects **a**1, **a**2, ..., are _independent of_ objects **b**1, **b**2, ..., if no sum of any parts of the former are parts or duplicates of any sum of any parts of the latter and vice versa; then we have:

|   |   |   |
|---|---|---|
|**R2**||For any world **w** any (finite or infinite number of) objects **a**1, **a**2, ..., in **w** and any objects **b**1, **b**2, ..., in **w** that are independent of **a**1, **a**2, ..., there is a world containing duplicates of **a**1, **a**2, ..., and no duplicates of **b**1, **b**2, ... .|

Worlds that satisfy the concretist truth conditions for workaday possibilities like ([16](https://plato.stanford.edu/entries/possible-worlds/#Acc)) are easily conceived as consisting of duplicates of relevant parts of the actual world — suitably organized to retain their actual properties, or not, as needed. Hence, the existence of such worlds does indeed appear to follow from the existence of the actual world by recombination. Worlds containing talking donkeys, exotic species resulting from a wholly different evolutionary history, worlds with silicon-based life forms, and so on present a bigger challenge to the view. Nonetheless, it is not entirely implausible to think such worlds exist given suitable duplication and reorganization of microphysical objects.[[23](https://plato.stanford.edu/entries/possible-worlds/notes.html#23)]

Whether recombination completely captures our modal intuitions regarding plenitude is still a matter of some dispute.[[24](https://plato.stanford.edu/entries/possible-worlds/notes.html#24)] However, even if it doesn't, it is less than clear whether this counts against the success of Lewis's reductionist project. For, as a realist about worlds, Lewis does not seem to be under any obligation to “derive” plenitude from more fundamental principles. Hence, there is no obvious reason why he cannot respond to charges of incompleteness by saying that it is simply a presupposition of his theory that logical space has no gaps, that there are always enough worlds to satisfy the concretist truth condition for any intuitive modal truth.[[25](https://plato.stanford.edu/entries/possible-worlds/notes.html#25)] So understood, the role of recombination for a realist about worlds like Lewis is something like the role of such axioms as powerset and replacement for a realist about sets: given some sets, these principles provide us with a detailed — but always less than complete — characterization of what further sets there are. Their role, therefore, is to give us insight into the richness and diversity of set theoretic space, not a complete mechanism for proving which particular sets do or do not exist. Likewise recombination vis-à-vis worlds and logical space.

#### 2.1.5 A Brief Assessment of Concretism

Lewis's theory is particularly commendable for its striking originality and ingenuity and for the simple and straightforward answers **AW1** and **AE1** that it provides to our two questions **QW** and **QE** above. Furthermore, because worlds are (plausibly) defined entirely in nonmodal terms, the truth conditions provided by Lewis's translation scheme themselves appear to be free of any implicit modality. Hence, unlike many other popular accounts of possible worlds (notably, the abstractionist accounts discussed in the following section), Lewis's promises to provide a genuine _analysis_ of the modal operators.

Perhaps the biggest — if not the most philosophically sophisticated — challenge to Lewis's theory is “the incredulous stare”, i.e., less colorfully put, the fact that its ontology is wildly at variance with common sense. Lewis faces this objection head on: His theory of worlds, he acknowledges, “_does_ disagree, to an extreme extent, with firm common sense opinion about what there is” (1986, 133). However, Lewis argues that no other theory explains so much so economically. With worlds in one's philosophical toolkit, one is able to provide elegant explanations of a wide variety of metaphysical, semantical, and intentional phenomena. As high as the intuitive cost is, Lewis (135) concludes, the existence of worlds “ought to be accepted as true. The theoretical benefits are worth it.”

Additional discussion of, and objections to, concretism can be found in the supplemental document [Further Problems for Concretism](https://plato.stanford.edu/entries/possible-worlds/problems-concretism.html).

### 2.2 Abstractionism

A rather different set of intuitions about situations is that they are _abstract_ entities of a certain sort: They are _states_ or _conditions_, of varying detail and complexity, that a concrete world could be in — they are _ways_ that things, as a whole, could be.[[26](https://plato.stanford.edu/entries/possible-worlds/notes.html#26)] Thus, returning to our original example, one very simple way things could be is for our philosopher Anne to be in her office. We can now imagine, as in our example, further detail being successively added to that description to yield more complex ways things could be: Anne working at her desk in her office; music being in the background; her husband being on the phone in the next room; her neighbor mowing the lawn next door; and so on. Roughly speaking, then, a possible world for an abstractionist is the _limit_ of such a “process” of consistently extending and adding detail to some initial state of the world; it is a _total_ way things could be, a consistent state of the world that settles every possibility; a consistent state to which no further detail could be added without rendering it inconsistent.

#### 2.2.1 Abstract Possible Worlds and Existence Therein

To give the notion of a state, or condition, of the world a little more metaphysical substance, abstractionists typically appeal to more traditional ontological categories. Thus, for example, that things could be in the simple state described above might be spelled out in one of the following ways:

- The _proposition_ **that Anne is in her office and at her desk** is possibly true.
- The _set of propositions_ {**that Anne is in her office**, **that Anne is at her desk**} is such that, possibly, all of its members are true.
- The _property_ **being such that Anne is in her office and at her desk** is possibly exemplified (by “things as a whole”).

Possible worlds are then defined as special cases of the type of entity in question that are in some relevant sense _total_. Adams (1974), for example, defines possible worlds to be consistent sets of propositions that are total in the sense of containing, for every proposition **p**, either **p** or its negation; Fine (1977), fleshing out ideas of Prior, defines a possible world to be a consistent proposition **w** that is total in the sense that, for every proposition **p**, **w** entails either **p** or its negation. For purposes here, however, we will sketch the fundamentals of the abstractionist view in terms of _states of affairs_, following the basic features of the account developed by Plantinga (1974, 1976), an account that, in the literature, frequently serves as a particularly trenchant abstractionist counterpoint to Lewis's concretism.[[27](https://plato.stanford.edu/entries/possible-worlds/notes.html#27)]

States of affairs (SOAs) are abstract, intensional entities typically signified by sentential gerundives like “Algol's being John's pet” and “There being more than ten solar planets”. Importantly, SOAs constitute a primitive ontological category for the abstractionist; they are not defined in terms of possible worlds in the manner that propositions are in [§1.3](https://plato.stanford.edu/entries/possible-worlds/#Applications). Just as some propositions are true and others are not, some SOAs are _actual_ and others are not.[[28](https://plato.stanford.edu/entries/possible-worlds/notes.html#28)] Note, then, that to say an SOA is non-actual is _not_ to say that it does not actually _exist_. It is simply to say that it is not, in fact, a condition, or state, that the concrete world is actually in. However, because ‘____ is actual’ is often used simply to mean ‘____ exists’, there is considerable potential for confusion here. So, henceforth, to express that an SOA is actual we will usually say that it _obtains_.

An SOA is said to be _possible_ (_necessary_, _impossible_) insofar as it is possible (necessary, impossible) that it obtain. One SOA **s** is said to _include_ another **t** if, necessarily, **s** obtains only if **t** does; **s** _precludes_ **t** if, necessarily, **s** obtains only if **t** doesn't. So, for example, **Algol's being John's pet** includes **Algol's being someone's pet** and precludes **there being no pets**. Thus, on the abstractionist's understanding of a situation as a state or condition of the physical world rather than a concrete, structured piece of it, the inclusion of one situation in another is a purely _logical_ relation, not a [mereological](https://plato.stanford.edu/entries/mereology/) one. Finally, say that an SOA **s** is _total_ if, for every SOA **t**, **s** either includes or precludes **t**. (Abstractionists often use ‘maximal’ instead of ‘total’, but we have already introduced this term in the context of concretism.) Abstractionist possible worlds are now definable straightaway:

|   |   |   |
|---|---|---|
|**AW2**||**w** is a possible world =_def_ **w** is an SOA that is both possible and total.[[29](https://plato.stanford.edu/entries/possible-worlds/notes.html#29)]|

It is easy to see that this definition covers the more intuitive characterizations of abstract possible worlds above: they are consistent — i.e., possible — states of the world that settle every possibility, consistent states to which no further detail could be added without rendering them inconsistent. Note also that, for the abstractionist, as for the concretist, the actual world is no different in kind from any other possible world; all possible worlds exist, and in precisely the same sense as the actual world. The actual world is simply the total possible SOA that, in fact, obtains. And non-actual worlds are simply those total possible SOAs that do not.

What of existence in such worlds? As we've seen, on Lewis's account, to exist in a concrete world **w** is literally to exist _in **w**_, that is, within the spatiotemporal boundaries of **w**. Clearly, because SOAs are abstract, individuals cannot exist in abstractionist worlds in anything like the same literal, mereological sense. Accordingly, the abstractionist defines existence in a world simply to be a special case of the inclusion relation:

|   |   |   |
|---|---|---|
|**AE2**||Individual **a** _exists in_ possible world **w** =_def_ **w** includes ****a**'s existing**.|

Unlike concretism, then, abstractionism does not entail that individuals are worldbound; there is no inconsistency whatever in the idea that many distinct worlds can include the existence of one and the same individual. Indeed, typically, abstractionists are staunchly committed to transworld identity and hold that most any given individual exists in many possible worlds and, moreover, that contingent individuals, at least, can exemplify very different properties from world to world. Abstractionists, therefore, have no need to appeal to counterparts to understand _de re_ modalities and can therefore accept the truth conditions for such modalities given by basic possible world semantics (spelled out, of course, in terms of their definitions **AW2** and **AE2**). In particular, they can take the standard possible world truth condition for, e.g., the right conjunct of ([16](https://plato.stanford.edu/entries/possible-worlds/#Acc)) at face value: ‘◇(_E!a_ ∧ ¬_Ta_)’ is true on the abstractionist's approach if and only if there is a world in which Algol herself, rather than some counterpart of hers, exists but fails to be anyone's pet.

#### 2.2.2 Irreducible Modality and Intensional Entities

It is important to note that the possible worlds of abstractionism do not yield a reductive analysis of modality. The reason for this is clear: abstract possible worlds are defined in irreducibly modal terms — a possible world is an SOA that (among other things) _possibly_ obtains; or a set of propositions such that it is _possible_ that all of its members are true; or a property that is _possibly_ exemplified; and so on. Hence, unpacked in terms of the abstractionist's definitions, the possible world truth conditions for modal propositions are themselves irreducibly modal. For example, when we unpack Plantinga's definition of a possible world in the semantic clause for sentences of the form ⌈◻ψ⌉ in order to derive the truth condition for [(17)](https://plato.stanford.edu/entries/possible-worlds/#DeDicto), ‘□∀_x_(_Gx_ → _Mx_)’, we end up with this:

|   |   |   |
|---|---|---|
|||For all SOAs **w**, if (i) _possibly_, **w** obtains and (ii) for all SOAs **s**, either (a) _necessarily_, **w** obtains only if **s** does or (b) _necessarily_, **w** obtains only if **s** doesn't, then, ‘∀_x_(_Gx_ → _Mx_)’ is true at **w**.|

If we now unpack the modal operators in (22) using the corresponding truth conditional clauses of standard possible world semantics, the result will contain further world quantifiers. And spelling out those world quantifiers in turn using Plantinga’s definition will re-introduce those same modal operators yet again.

More generally, and a bit more exactly, put: As noted above, the logical framework of basic possible world semantics is classical predicate logic. The logical framework of abstractionism is modal predicate logic. Hence, if possible world semantics is supplemented with abstractionist definitions of possible worlds, then the logical framework of possible world semantics becomes modal predicate logic as well and, as a consequence, the extensionality of the semantics is lost once again. (This point is expressed somewhat more formally in the supplemental document [The Intensionality of Abstractionist Possible World Semantics](https://plato.stanford.edu/entries/possible-worlds/semantics-abstractionist-intensionality.html).) Since, as noted above, the central motivation for possible world semantics was to deliver an extensional semantics for modal languages, any motivation for abstractionism as a semantic theory is arguably undermined.[[30](https://plato.stanford.edu/entries/possible-worlds/notes.html#30)]

However, it is not entirely clear that this observation constitutes an objection to abstractionism. For abstractionists can argue that the goal of their analysis is the converse of the reductionist's goal: The reductionist wants to understand modality in terms of worlds; the abstractionist, by contrast, wants to understand worlds in terms of modality. That is, abstractionists can argue that we begin with a primitive notion of modality and, typically upon a certain amount of philosophical reflection, we subsequently discover an intimate connection to the notion of a possible world, as revealed in the principles [**Nec**](https://plato.stanford.edu/entries/possible-worlds/#Nec) and [**Poss**](https://plato.stanford.edu/entries/possible-worlds/#Poss). The analysis that abstractionists provide is designed to make this connection explicit, ideally, in such a way that **Nec** and **Poss** fall out as theorems of their theory (see, e.g., Plantinga 1985 and Menzel and Zalta 2014).

Hand in glove with the irreducible nature of modality is the nature of intensional entities. Concretists define intensional entities in terms of worlds, as described in [§2.1.3](https://plato.stanford.edu/entries/possible-worlds/#Reductionism). Abstractionists, by contrast, define worlds in terms of intensional entities. This divergence in their choice of ontological primitives reflects, not only their differing stances toward modality, but also an important methodological difference with regard to metaphysical inquiry. The concretist is far more pragmatic; notions of _property_, _relation_, _proposition_, and the like play certain roles in our theorizing and are subject to a “jumble of conflicting _desiderata_” (Lewis 1986, 54). Within a given theory, any entities that can play those roles fruitfully for the purposes at hand are justifiably identified with those notions — regardless of how well they comport with pre-theoretic intuitions. Thus, Lewis finds it to be a strength of his position that he is able to adopt the set theoretic definitions in §2.1.3. By contrast, at least some abstractionists — Plantinga (1987) perhaps most notably — believe that we have intuitive, pre-theoretic knowledge of intensional entities that precludes their being identified with set theoretic constructions of any sort.[[31](https://plato.stanford.edu/entries/possible-worlds/notes.html#31)] (See Stalnaker 1976 for a particularly illuminating discussion of the contrast between concretism and abstractionism with respect to the treatment intensional entities.)

#### 2.2.3 Actuality and Actualism

As was noted in [§2.1.2](https://plato.stanford.edu/entries/possible-worlds/#Actuality), for the concretist, there is no special property of the actual world — _actuality_ — that distinguishes it, in any absolute sense, from all of the others; it is simply the world that _we_ inhabit. For abstractionists, however, actuality _is_ a special property that distinguishes exactly one possible world from all others — the actual world is the only world that happens to _obtain_; it is the one and only way things could be that is the way things as a whole, in fact, _are_. However, for most abstractionists, the distinctiveness of the actual world does not lie simply in its actuality but in its ontological comprehensiveness: the actual world encompasses all that there is. In a word: most abstractionists are _actualists_.

[Actualism](https://plato.stanford.edu/entries/possibilism-actualism/) is the thesis that everything that there is, everything that has _being_ in any sense, is actual. In terms of possible worlds: Everything that exists in any world exists in the actual world.[[32](https://plato.stanford.edu/entries/possible-worlds/notes.html#32)] Possibilism, by contrast, is the denial of actualism; it is the thesis that there are _mere possibilia_, i.e., things that are not actual, things that exist in other possible worlds but fail to exist in the actual world. Concretists are obviously not actualists (on their understanding of ‘actual’, at any rate).[[33](https://plato.stanford.edu/entries/possible-worlds/notes.html#33)] Indeed, for the concretist, since individuals are worldbound, everything that exists in any nonactual possible world is distinct from everything in the actual world. However, although possibilism and abstractionism are entirely compatible — Zalta (1983), for example, embraces both positions — abstractionists _tend_ to be actualists. The reason for this is clear: Basic possible world semantics appears to be committed to possibilism and abstractionism promises a way of avoiding that commitment.

The specter of possibilism first arises with regard to _non-actual_ possible worlds, which would seem by definition to be prime examples of mere _possibilia_. However, we have just seen that the abstractionist can avoid this apparent commitment to possibilism by defining possible worlds to be SOAs of a certain sort. So defined, non-actual worlds, i.e., worlds that fail to obtain, can still actually exist. Hence, the commitment of basic possible world semantics to non-actual worlds does not in itself threaten the actualist's ontological scruples.

However, the specter of possibilism is not so easily exorcised. For non-actual worlds are not the only, or even the most compelling, examples of mere _possibilia_ that seem to emerge out of basic possible world semantics. For instance, it is quite reasonable to think that evolution could have taken a very different course (or, if you like, that God could have made very different creative choices) and that there could have been individuals — call them _Exotics_ — that are biologically very different from all actually existing individuals; so different, in fact, that no actually existing thing could possibly have been an Exotic. According to basic possible world semantics, the sentence ‘There could have been Exotics’ or, more formally,

|   |   |   |
|---|---|---|
|||◇∃_xEx_|

is true just in case there is a world in which ‘∃_xEx_’ is true, i.e., when all is said and done, just in case:

|   |   |   |
|---|---|---|
|||There is a possible world **w** and an individual **a** in **w** such that **a** is an Exotic in **w**,|

which, a bit less formally, is simply to say that

|   |   |   |
|---|---|---|
|||Some individual is an Exotic in some possible world.|

However, since no actually existing thing could have been an Exotic, anything that is an Exotic in some possible world cannot be among the things that exist in the actual world. Thus, the truth conditions that basic possible world semantics assigns to some of our intuitive modal beliefs appear to entail that there are non-actual individuals as well as non-actual possible worlds. Defining possible worlds as SOAs provided a way for the actualist to embrace non-actual worlds without compromising her actualism. But how is the actualist to understand the apparent commitment to non-actual _individuals_ in such truth conditions as (25)?

Answers that have been given to this question represent a rather deep divide between actualist abstractionists. On the one hand, “trace” actualists introduce actually existing entities into their ontologies that can play the role of mere _possibilia_ in (25) and its like. Trace actualists come in two varieties: _new_ actualists and _haecceitists_. New actualists like Linsky and Zalta (1996) and Williamson (1998, 2000, 2013) argue that, in fact, all individuals are actually existing, necessary beings but not all of them are necessarily _concrete_. Some concrete individuals — those traditionally (mis-)categorized as contingent beings — are only contingently concrete. Likewise, some non-concrete individuals — those, like possible Exotics, traditionally (mis-)categorized as contingently non-actual mere _possibilia_ — are only contingently non-concrete.[[34](https://plato.stanford.edu/entries/possible-worlds/notes.html#34)]

This novel take on modal metaphysics allows the new actualist to reinterpret possible world semantics so as to avoid possibilism. Notably, the domain **d**(**w**) of a world **w** is understood not as the set of things that exist in **w** — for all individuals exist in all worlds — but the set of things that are _concrete_ in **w**.[[35](https://plato.stanford.edu/entries/possible-worlds/notes.html#35)] Hence, for the new actualist, the correct truth condition for ([23](https://plato.stanford.edu/entries/possible-worlds/#PossExoticsFormal)) is:

|   |   |   |
|---|---|---|
|||There is a possible world **w** and an individual **a** that is (i) concrete in **w** and (ii) an Exotic in **w**.|

On the other hand, haecceitists like Plantinga introduce special properties — haecceities — to similar ends. The haecceity of an individual **a** is the property of being _that very individual_, the property **being **a****. A property is a _haecceity_, then, just in case it is possible that it is the haecceity of some individual.[[36](https://plato.stanford.edu/entries/possible-worlds/notes.html#36)] It is a necessary truth that everything has a haecceity. More importantly, for haecceitists, haecceities are necessary beings. Thus, not only is it the case that, had any particular individual **a** failed to exist, its haecceity **ha** would still have existed, it is also the case that, for any “merely possible” individual **a**, there is an actually existing haecceity that would have been **a**'s haecceity had **a** existed. More generally (and more carefully) put: Necessarily, for any individual **a**, (i) **a** has a haecceity **h** and (ii) necessarily, **h** exists.

Like the new actualists, then, the metaphysics of the haecceitists enables them to systematically reinterpret possible world semantics in such a way that the truth conditions of modal discourse are expressed solely in term of actually existing entities of some sort rather than actual and non-actual individuals. More specifically, for the haecceitist, the domain **d**(**w**) of a world **w** is taken to be the set of haecceities that are _exemplified_ in **w**, that is, the set of haecceities **h** such that **w** includes ****h**'s being exemplified**. Likewise, the **w**-extension of a (1-place) predicate π is taken to be a _set_ of haecceities — intuitively, those haecceities that are coexemplified in **w** with the property expressed by π. So reinterpreted, the truth condition for ([23](https://plato.stanford.edu/entries/possible-worlds/#PossExoticsFormal)) is:

|   |   |   |
|---|---|---|
|||There is a possible world **w** and a haecceity **h** that is (i) exemplified in **w** and (ii) coexemplified with the property **being an Exotic** in **w**.|

By contrast, “no-trace”, or _strict_, actualists like Prior (1957), Adams (1981), and Fitch (1996) hew closely to the intuition that, had a contingent individual **a** failed to exist, there would have been absolutely no trace, no metaphysical vestige, of **a** — neither **a** itself in some non-concrete state nor any abstract proxy for **a**. Hence, unlike trace actualism, there are no such vestiges in the actual world of objects that are not actual but only could have been. The logical consequences for no-trace actualists, however, appear to be severe; at the least they cannot provide a standard [compositional](https://plato.stanford.edu/entries/compositionality/) semantics for modal languages, according to which (roughly) the meaning of a sentence is determined by its logical form and the meanings of its semantically significant constituents. In particular, if there is nothing to play the role of a “possible Exotic”, nothing that is, or represents, an Exotic in some other possible world — a mere _possibile_, a contingently non-concrete individual, an unexemplified haecceity — then the strict actualist cannot provide standard, compositional truth conditions for quantified propositions like ([23](https://plato.stanford.edu/entries/possible-worlds/#PossExoticsFormal)) that yield the intuitively correct truth value. For, understood compositionally, ([23](https://plato.stanford.edu/entries/possible-worlds/#PossExoticsFormal)) is true if and only if ‘∃_xEx_’ is true at some world **w**. And that, in turn, is true at **w** if and only if ‘_Ex_’ is true at **w** for some value of ‘_x_’. But, as just noted, for the strict actualist, there is no such value of ‘_x_’. Hence, for the strict actualist, ‘_Ex_’ is false at **w** for all values of ‘_x_’ and, hence, ([23](https://plato.stanford.edu/entries/possible-worlds/#PossExoticsFormal)) is false as well. (These issues are explored in much greater detail in the entry on the [possibilism-actualism debate](https://plato.stanford.edu/entries/possibilism-actualism/).)

#### 2.2.4 A Brief Assessment of Abstractionism

Like concretism, abstractionism provides a reasonably clear and intuitive account of what worlds are and what it is to exist in them, albeit from a decidedly different perspective. Although, as noted in [§2.2.2](https://plato.stanford.edu/entries/possible-worlds/#AbsModIntEnt), the fact that modality is a primitive in abstractionist definitions of possible worlds arguably compromises its ability to provide semantically illuminating truth conditions for the modal operators, those definitions can be taken to illuminate the connection between our basic modality concepts and the evocative notion of a possible world that serves as such a powerful conceptual tool for constructing philosophical arguments and for analyzing and developing solutions to philosophical problems. In this regard, particularly noteworthy are: Plantinga's (1974) influential work on [the ontological argument](https://plato.stanford.edu/entries/ontological-arguments/) and the free will defense against [the problem of evil](https://plato.stanford.edu/entries/evil/); Adams' (1974, 1981) work on [actualism](https://plato.stanford.edu/entries/possibilism-actualism/) and actuality; and Stalnaker's (1968, 1987) work on [counterfactual conditionals](https://plato.stanford.edu/entries/conditionals/#NeaPosWor) and [mental content](https://plato.stanford.edu/entries/content-nonconceptual/).

A number of important objections have been voiced in regard to abstractionism. Some of these are addressed in the document [Problems with Abstractionism](https://plato.stanford.edu/entries/possible-worlds/problems-abstractionism.html).

### 2.3 Combinatorialism

As its name might suggest, our third approach — _combinatorialism_ — takes possible worlds to be recombinations, or rearrangements, of certain metaphysical simples. Both the nature of simples and the nature of recombination vary from theory to theory. Quine (1968) and Cresswell (1972), for example, suggest taking simples to be space-time points (modeled, perhaps, as triples of real numbers) and worlds themselves to be arbitrary sets of such points, each set thought of intuitively as a way that matter could be distributed throughout space-time. (A world _w_, so construed, then, is _actual_ just in case a space-time point _p_ is a member of _w_ if and only if _p_ is occupied by matter.) Alternatively, some philosophers define states a world could be in, and possible worlds themselves, simply to be maximally consistent sets of sentences[[37](https://plato.stanford.edu/entries/possible-worlds/notes.html#37)] in an expressively rich language — “recombinations”, certainly, of the sentences of the language. (Lewis refers to this view as _linguistic ersatzism_.[[38](https://plato.stanford.edu/entries/possible-worlds/notes.html#38)]) However, the predominant version of combinatorialism finds its origins in Russell's (1918/1919) theory of [logical atomism](https://plato.stanford.edu/entries/logical-atomism/) and Wittgenstein's (1921, 1922, 1974) short but enormously influential [_Tractatus Logico-Philosophicus_](https://plato.stanford.edu/entries/wittgenstein/#TracLogiPhil). A suggestive paper by Skyrms (1981) spelling out some of the ideas in the _Tractatus_, in turn, inspired a rich and sophisticated account that is developed and defended in great detail in an important series of books and articles by D. M. Armstrong (1978a, 1978b, 1986a, 1989, 1997, 2004b, 2004c). In this section, we present a somewhat simplified version of combinatorialism that draws primarily upon Armstrong's work. Unless otherwise noted, this is what we shall mean by ‘combinatorialism’ for the remainder.

#### 2.3.1 The Basic Ontology of Combinatorialism

Wittgenstein famously asserted that the world is the totality of _facts_, not of things (_ibid._, §1.1). The combinatorialist spells out Wittgenstein's aphorism explicitly in terms of an ontology of objects (a.k.a., particulars), universals (a.k.a., properties and relations), and facts. Facts are either atomic or molecular. Every atomic fact — _Sachverhalt_, in the language of the _Tractatus_ — is “constituted” by an _n_-place relation (= property, for _n_=1) and _n_ objects that _stand in_, or _exemplify_, that relation. Thus, for example, suppose that John is 1.8 meters tall. Then, in addition to John and the property **being 1.8 meters tall**, there is for the combinatorialist the atomic fact of John's exemplifying that property. More generally, atomic facts exist according to the following principle:

|   |   |   |
|---|---|---|
|**AF**||Objects **a**1, ..., **a**_n_ exemplify _n_-place relation **R** iff there is the fact **a1, ..., a_n_'s exemplifying R** ([**R**,**a**1,...,**a**_n_], for short).|

Say that the **a**_i_ are the _constituent objects_ of the fact in question and **R** its _constituent universal_, and that **R** and the **a**_i_ all _exist in_ [**R**,**a**1,...,**a**_n_].

A fact is _monadic_ if its constituent universal is a property. A _molecular_ fact **f** is a conjunction of atomic facts. Its constituent objects and universals are exactly those of its conjuncts and an entity exists in **f** just in case it exists in one of its conjuncts. (For simplicity, we stipulate that an atomic fact has (only) itself as a conjunct and, hence, is “trivially” molecular.) One fact **f** _includes_ another **g** if every conjunct of **g** is a conjunct of **f**. (Note, importantly, that inclusion, so defined, is quite different from the homonymous notion defined in the discussion of abstractionism above — most notably, combinatorial inclusion is not a _modal_ notion.) For purposes below, say that an object **a** is a _bare particular in_ a molecular fact **f** if there is no monadic conjunct of **f** of which **a** is the constituent object, no conjunct of the form **a exemplifies F**, for some property **F**. **a** is a _bare particular_ if it is bare in every molecular fact. Intuitively, of course, a bare particular is an unpropertied object.

There is no upper bound on the “size” of a molecular fact and no restriction on which atomic facts can form a conjunction; for any atomic facts at all, there is a molecular fact whose conjuncts are exactly those facts. As a first cut, then, we can spell out Wittgenstein's characterization of the (actual) world as the totality of facts by defining the world to be the largest molecular fact, the molecular fact that includes all of the atomic facts.[[39](https://plato.stanford.edu/entries/possible-worlds/notes.html#39)]

Although objects and universals are typically included along with facts in the basic ontology of combinatorialism, facts are typically considered more fundamental. Indeed, taking his queue from the Tractarian thesis that the world consists of facts, not things, Armstrong (1986a, 577) argues that facts alone are ontologically basic and that objects and universals are simply “aspects of, abstractions from” facts. Accordingly, he calls the object constituent of a fact of the form [**P**,**a**] a “thin” particular, an object “considered in abstraction from all its [intrinsic] properties” (1993, 433); and where **N** is the conjunction of “all the non-relational properties of that particular (which would presumably include **P**), the atomic fact **a's exemplifying N** itself is the corresponding “thick” particular ” (_ibid_., 434 — we will occasionally use italics to distinguish a thin particular _a_ from the corresponding thick particular **a**). Though not all combinatorialists of every stripe buy into Armstrong's “factualist” metaphysics (Bricker 2006), they do generally agree that facts are more fundamental, at least to the extent that both the notion of a bare particular, i.e., an object exemplifying no properties, and that of an unexemplified property are considered incoherent; insofar as they exist at all, the existence of both particulars and universals depends on their “occurring” in some fact or other. Whatever their exact ontological status, it is an important combinatorialist thesis that exactly _what_ objects and universals exist is ultimately a matter for natural science, not metaphysics, to decide.

Objects can be either simple or complex. An object is _simple_ if it has no proper parts, and _complex_ otherwise. Like objects, universals too divide into simple and complex. A universal is simple if it has no other universal as a constituent, and complex otherwise. Complex universals accordingly come in two varieties: conjunctive — the constituents of which are simply its conjuncts — and structural. A structural universal **U** is one that is exemplified by a complex object **O**, and its constituents are universals (distinct from **U**) exemplified by simple parts of **O** that are relevant to **O**'s being an instance of **U**.[[40](https://plato.stanford.edu/entries/possible-worlds/notes.html#40)] It is important to note that, for Armstrong, the constituency relation is not the mereological parthood relation. Rather, complex universals (hence also complex facts of which they are constituents) enjoy a “non-mereological mode of composition” (1997, 119–123) that, in particular, allows for a richer conception of their structure.[[41](https://plato.stanford.edu/entries/possible-worlds/notes.html#41)] (An assumption of our simplified account here will be that both the _proper part of_ relation and the constituency relation are well-founded. It follows that (i) there is no [_gunk_](https://plato.stanford.edu/entries/mereology/#AtoOthOpt), i.e., that every complex object is composed, ultimately, entirely of simples and (ii) complex universals — hence the complex facts in which they are exemplified — are ultimately “grounded” in simple facts, i.e., that they cannot be infinitely decomposed into further complex universals/facts.[[42](https://plato.stanford.edu/entries/possible-worlds/notes.html#42)])

To illustrate the basic idea: in Figure 1, the left-hand diagram depicts a water molecule **W** comprising an oxygen atom **o** and two hydrogen atoms **h1** and **h2**. For the combinatorialist, “thick” particulars like the molecule itself as well as its constituent atoms are themselves facts: **o** is the fact [**O**,_o_] in which the universal **oxygen** (**O**) is exemplified by a thin particular _o_;[[43](https://plato.stanford.edu/entries/possible-worlds/notes.html#43)] likewise **h1** and **h2**. **W** in turn comprises those monadic facts and the relational facts [**B**,**o**,**h**1], [**B**,**o**,**h**2] wherein the covalent bonding relation **B** holds between the oxygen atom and the two hydrogen atoms. The structural universal **Water** itself, then, shares this structure — it is, so to say, an _isomorph_ consisting of the monadic universals **O** and **H** and the binary relation **B**, structured as indicated in the right-hand diagram of Figure 1.[[44](https://plato.stanford.edu/entries/possible-worlds/notes.html#44)]

![diagram of structure of water](https://plato.stanford.edu/entries/possible-worlds/Water.png)

Figure 1: A Water Molecule **W** and the Structural Universal **Water**

#### 2.3.2 States of Affairs and Recombination

It should be clear from [principle **AF**](https://plato.stanford.edu/entries/possible-worlds/#AF) that all atomic facts _hold_; that is, all of them reflect actual exemplification relations. Obviously, however, possibility encompasses more than what is actual, that is, there are _possible_ facts as well as actual facts; the world's universals might have been exemplified by its objects very differently. If they had — if the world's objects and universals had combined in a very different way — there would have been a very different set of atomic facts and, hence, a very different world.

To spell out the idea of a possible fact, the combinatorialist introduces the more general notion of an atomic _(combinatorial) state of affairs_, that is, an entity that simply has the _form_ of an atomic fact — _n_ objects exemplifying an _n_-place relation — but without any requirement that the exemplification relation in question actually holds between them. More exactly:

|   |   |   |
|---|---|---|
|**AS**||For any objects **a**1, ..., **a**_n_ and any _n_-place relation **R**, there is an atomic (combinatorial) state of affairs **a**1, ..., **a**_n_'s exemplifying **R** (again, [**R**,**a**1,...,**a**_n_], for short).|

Thus, even if the two hydrogen atoms **h**1 and **h**2 in a water molecule do not in fact stand in the covalent bonding relation **B**, there is nonetheless the (non-factual) state of affairs [**B**,**h**1,**h**2].

Combinatorialism takes facts to be literal, structured parts of the physical world. This suggests that a non-factual state of affairs — a merely _possible_ fact — must be part of a merely possible physical world. This idea is at odds with the strong, scientifically-grounded form of actualism that typically motivates combinatorialism. Two options are available: The combinatorialist can follow the (actualist) abstractionists and define states of affairs to be philosophical or mathematical constructs consisting only of actual objects, properties, relations, and facts. For example, the state of affairs [**R**,**a**1,...,**a**_n_] can simply be identified with the ordered _n_-tuple ⟨**R**,**a**1,...,**a**_n_⟩. So long as the combinatorialist is willing to adopt the additional metaphysical or set theoretic machinery, this sort of approach offers a way of introducing non-factual states of affairs that does not involve any untoward ontological commitments to merely possible entities. Alternatively, following Armstrong (1989, 46–51; 1997, 172–4), the combinatorialist can refuse to grant non-factual states of affairs any genuine ontological status and adopt a form of [modal fictionalism](https://plato.stanford.edu/entries/fictionalism-modal/) that nonetheless permits one to speak _as if_ such states of affairs exist. The exposition to follow will remain largely neutral between these options.

Constituency for states of affairs is understood as for facts. Additionally, analogous to molecular facts, there are molecular states of affairs — conjunctions of atomic states of affairs. Inclusion between states of affairs is understood exactly as it is between facts and being a _bare particular_ in a molecular state of affairs **s** is understood as for facts: **a** is a bare particular in **s** if there is no monadic conjunct of **s** of the form ****a** exemplifies F**. The notion of recombination is now definable straightaway:

|   |   |   |
|---|---|---|
|||**s** is a _recombination_ of a molecular state of affairs **f** =_def_ **s** is a molecular state of affairs whose constituent objects and constituent universals are exactly those of **f**. **s** is a _non-trivial_ recombination of **f** if it does not include the same states of affairs as **f**.|

Very roughly then, a _possible world_ will be a certain sort of recombination of (some portion of) the _actual_ world, the molecular fact that includes all of the atomic facts. This idea will be refined in the following sections.

#### 2.3.3 Structural States of Affairs and Supervenience

Say that a state of affairs is _structural_ if it is atomic and its constituent universal is structural or it is molecular and includes a structural state of affairs; and say that it is _simple_ otherwise. The difference between structural and simple universals and states of affairs is particularly significant with regard to the important concept of _supervenience_ (Armstrong 1989, Ch 8).[[45](https://plato.stanford.edu/entries/possible-worlds/notes.html#45)] Entity or entities **S** supervene on entity or entities **R** if and only if the existence of **R** necessitates that of **S** (_ibid._, 103). (Necessitation here is, of course, ultimately to be spelled out in terms of combinatorial possible worlds.) Non-structural states of affairs supervene directly on their atomic conjuncts.[[46](https://plato.stanford.edu/entries/possible-worlds/notes.html#46)] However, things are not in general quite so straightforward for structural states of affairs. For, although structural states of affairs are ultimately constituted entirely by simple states of affairs, unlike non-structural states of affairs, structural states of affairs typically supervene on more than the totality of their constituents. For, in many cases, whether or not a structural fact exists depends not only on the existence of its constituent facts but also on the _absence_ of certain others (Armstrong 1997, 34ff). For example, as noted in our example above, our water molecule **W** comprises two further facts in which two hydrogen atoms **h**1 and **h**2 both stand in the covalent binding relation with an oxygen atom **o**. However, if **o** were to bind with a further hydrogen atom **h**3, then, despite the fact that the constituent facts of **W** would still hold, **W** would not be water; there would be no such fact as **W's being water**.[[47](https://plato.stanford.edu/entries/possible-worlds/notes.html#47)] Rather, **W** would exist only as a complex part of a hydronium ion; the new binding [**B**,**o**,**h**3] would, so to say, “spoil” the instantiation of **Water**. Thus, more generally, whether or not a structural state of affairs **S** exists in a possible world typically requires something over and above its constituent states of affairs being “welded together” in the right sort of way (Armstrong, 1997, 36); it requires also that there be no relevant “spoilers” for **S**.[[48](https://plato.stanford.edu/entries/possible-worlds/notes.html#48)] Armstrong draws directly on the initial passages of the _Tractatus_[[49](https://plato.stanford.edu/entries/possible-worlds/notes.html#49)] for the necessary apparatus: a structural state of affairs **S** in any possible world **w**, supervenes, not simply on its constituent atomic states of affairs but on a certain _higher-order_ state of affairs **T****w**, namely, the state of affairs that the (first-order) atomic states of affairs of **w** are _all the (first-order) atomic states of affairs_ and, hence, that **w** includes no spoilers for **S**. Armstrong (_ibid._, 35, 134–5, 196–201) calls **Tw** the _totality_ state of affairs for the atomic states of affairs of **w**.[[50](https://plato.stanford.edu/entries/possible-worlds/notes.html#50)]

#### 2.3.4 Combinatorial Possible Worlds and Existence Therein

The idea of possibility being rooted in arbitrary recombinations of the actual world, rearrangements of its objects and universals, is intuitively appealing. Clearly, however, not just any such recombination can count as a possible world. Some states of affairs are intuitively impossible — [**being an elephant**, **e**], where **e** is an individual electron, say — and some pairs of states of affairs, while individually possible, are not _com_possible — the states of affairs [**having 1kg mass**, **a**] and [**having 2kg mass**, **a**] for a given object **a**, or, for a given mereological sum **m** of simples, the states of affairs [**being a baboon**, **m**] and [**being a hoolock**, **m**]. But nothing that has been said rules out the existence of recombinations of the actual world — rearrangements of its objects and universals — that include such states of affairs. Obviously, however, such recombinations cannot be thought to represent genuinely possible worlds. Of course, like the abstractionist, the combinatorialist could simply stipulate as part of the definition that all legitimate recombinations must be genuinely _possible_ states of affairs of a certain sort, genuinely _possible_ recombinations. But this will not do. For, like concretism, combinatorialism purports to be a _reductive_ account of modality, an account of possible worlds that does not depend ultimately on modal notions (see Armstrong 1989, 33).[[51](https://plato.stanford.edu/entries/possible-worlds/notes.html#51)]

Here the distinction between simple and structural states of affairs together with the combinatorialist's strong notion of supervenience come to the fore. For, given that structural facts supervene on simple facts and the actual totality fact **T**@, the actual world can be defined more parsimoniously as the molecular fact that includes all the _simple_ atomic facts and the totality fact **T**@. And at the level of simples, there are no limitations whatever on recombination (Wittgenstein 1921, 2.062-2.063); hence, any recombination of simple objects and universals is by definition considered possible. Thus Armstrong (1986a, 579):

> The simple individuals, properties, and relations may be combined in _all_ ways to yield possible [simple] atomic states of affairs, provided only that the form of atomic facts is respected. That is the combinatorial idea.

Worlds, in particular, can be defined as special cases of such recombinations, together with appropriate totality facts. To state this, we need a condition that ensures the existence of a unique actual world:

|   |   |   |
|---|---|---|
|||States of affairs **s** and **t** are identical iff they include exactly the same states of affairs.|

Given this, we have:

|   |   |   |
|---|---|---|
|||The (combinatorial) actual world =_def_ the fact @ that includes exactly all the simple atomic facts and the totality state of affairs **T**@ for the conjunction of those facts.|

|   |   |   |
|---|---|---|
|**AW3**||**w** is a (combinatorial) possible world =_def_ **w** is a recombination of the simple atomic facts of the actual world conjoined with the totality fact **Tw** for that recombination.[[52](https://plato.stanford.edu/entries/possible-worlds/notes.html#52)]|

Armstrong's ontological commitments are notoriously rather slippery but, given **AW3**, a reasonably complete notion of existence in a world is forthcoming. First, let us note that, for Armstrong, the “combinatorial idea” yields a substantial metaphysical thesis, as well, viz., the _ontological free lunch_ (1986, 12ff), i.e., the thesis that “[w]hat supervenes is no addition of being”; that “whatever supervenes ... is not something ontologically additional to the subvenient entity or entities.” Hence, for Armstrong, it appears that _simple_ states of affairs and their constituents exist most fundamentally and that the existence of more complex entities is in a certain sense _derivative_. Thus:

|   |   |   |
|---|---|---|
|||Entity **a** exists _fundamentally_ in (combinatorial) possible world **w** =_def_ (i) **a** is a simple state of affairs that **w** includes or (ii) **a** is a constituent or conjunct of an entity that exists fundamentally in **w**.|

Given this, existence in a world generally — both fundamental and derivative — both for simples and (_first-order_[[53](https://plato.stanford.edu/entries/possible-worlds/notes.html#53)]) non-simples alike, is definable as follows:

|   |   |   |
|---|---|---|
|**AE3**||Entity **a** exists in (combinatorial) possible world **w** =_def_ either (i) **a** exists fundamentally in **w** or (ii) **a** supervenes on entities that exist in **w**.|

Semantics receives rather short shrift in Armstrong's version of combinatorialism — at least, semantics in the model theoretic sense of [§1.2](https://plato.stanford.edu/entries/possible-worlds/#ExtReg) — but, as it has played an important role in our discussion of concretism and abstractionism, we note briefly how the ontology of combinatorialism might be taken to populate a possible world interpretation of the language of modal predicate logic. Specifically, we can take the range of the modal operators — understood, semantically, as quantifiers — to be all of the combinatorial possible worlds in the sense of **AW3**. The domain **d**(**w**) of each world **w** is the set of all simple and complex objects that exist in **w** according to **AE3** and the **w**-extension **I**π(**w**) of a predicate π expressing a simple or complex universal **R** is the set of all _n_-tuples, ⟨**a**1, ..., **a**_n_⟩ such that the atomic fact [**R**,**a**1,...,**a**_n_] exists in **w**.

#### 2.3.5 Analytic and Emergent Modalities; Essential Properties

There are, then, for the combinatorialist no intrinsically modal phenomena; there are just all of the various worlds that exist on unrestricted combinatorial grounds alone. Ultimately, all genuine possibilities, simple or not, are just states of affairs that exist in these combinatorial worlds in the sense of **AE3**. However, it is not immediately as clear how to understand many intuitive _necessities_/_impossibilities_ involving complex structural universals, for example, the impossibilities noted in the previous section, viz., that something simultaneously have a mass of both 1kg and 2kg or simultaneously be both a baboon and a hoolock. Likewise, it is not entirely clear how combinatorialism accounts for intuitive facts about essential properties, such as that our water molecule **W** is essentially water or that Algol is essentially a dog. Combinatorialists argue that such modal facts can nevertheless be explained in terms that require no appeal to primitive modal features of the world (Armstrong 2004b, 15).

**Analytic Modalities.**  Armstrong argues that many intuitive modal facts — notably, the impossibility of an object exemplifying more than one determinate of the same determinable — can be understood ultimately as logical, or analytic, modalities that are grounded in meaning rather than any primitive modal features of reality. For example, intuitively it is impossible that an object simultaneously exemplify the structural properties **having 2kg mass** and **having 1kg mass**. The combinatorial reason for this (cf. Armstrong 1989, 79) is that, for an object **a** to exemplify the former property is simply for there to be a division of **a** into two wholly distinct parts, both of which exemplify the latter property. Moreover, this division into parts is entirely arbitrary, that is, for _any_ part **a**1 of **a** exemplifying **having 1kg mass**, there is a (unique) part **a**2 of **a** wholly distinct from **a**1 that also exemplifies that property. It follows that, if our 2kg object **a** itself _also_ exemplifies **having 1kg mass**, then, as **a** is a part of itself, there must be a 1kg part of **a** that is wholly distinct from **a**. And that is analytically false, false “solely by virtue of the meaning we attach to” the word ‘part’ (_ibid_., 80).[[54](https://plato.stanford.edu/entries/possible-worlds/notes.html#54)]

**Emergent Modalities.**   Combinatorialism purports to explain a further class of intuitive modal facts as features that simply “emerge” from facts about structural properties.[[55](https://plato.stanford.edu/entries/possible-worlds/notes.html#55)] The discussion of structural states of affairs and supervenience above provides an example. Let us suppose the actual world **w**1 includes our water molecule **W** from Figure 1 plus a further hydrogen atom **h**3. In this world, only **h**1 and **h**2 bind to **o**. Hence, this world includes the state of affairs **W's being water** but not the state of affairs **I's being hydronium** in which **o**, **h**1, **h**2, and **h**3 are so bonded as to constitute a hydronium ion **I**. Conversely, however, given the unrestricted nature of recombination, there is a world **w**2 that includes **W** structured as it actually is in **w**1 but which also includes the spoiler [**B**,**o**,**h**3] — where **o** and **h**3 bond — and, hence, the structural state of affairs **I's being hydronium**. Thus, the absence of [**B**,**o**,**h**3] in **w**1 enables the emergence of **W's being water** and precludes **I's being hydronium** whilst its presence in **w2** enables the emergence of the latter but precludes the former. As a consequence, it is impossible that the states of affairs **W's being water** and **I's being hydronium** coexist.[[56](https://plato.stanford.edu/entries/possible-worlds/notes.html#56)]

![diagram of structure of water](https://plato.stanford.edu/entries/possible-worlds/Water-and-Hydronium.png)

Figure 2: **W**'s being water and (given a bond between **o** and **h**3) **I**'s being hydronium

Although more dramatic, large-scale examples of incompatible states of affairs — such as a thing's being simultaneously both a baboon and a hoolock — might be vastly more complex, there is no obvious reason why their impossibility could not have the same sort of combinatorial explanation.

**Essential Properties.**   It follows from the unrestricted nature of recombination that, for any simple object **a** and simple universal **P**, **a** recombines with **P** in some worlds and fails to recombine with **P** in others. Generalizing from this fact, it follows that no simple or sum of simples has any simple universal or conjunction of simple universals essentially. It also follows that no such object has any structural property essentially. For assume **o** is such an object and that it exemplifies a structural property **P**. Since **P** is structural, it supervenes on some set of simple states of affairs. But by the nature of recombination, there are combinatorial worlds in which those states of affairs do not exist and, hence, in which **P** doesn't but **o** — being a simple or a sum of simples — does.

Thick particulars like our water molecule **W** don't fare much better because of the possibility of spoilers. For Armstrong (1997, 35), **W** is simply the conjunction of its constituent states of affairs. As we've just seen, however, in the presence of spoilers, that conjunction would exist — hence, **W** would exist — without being **Water**. Hence, it would seem that at least some properties that, intuitively, are essential to their bearers turn out not to be for the combinatorialist. The problem is compounded by the fact that some intuitively non-essential properties of some thick particulars are arguably essential for the combinatorialist. The shape properties of a thick particular **A**, for example, would seem to be a function of its constituent states of affairs. Moreover, the exemplification of such properties are not obviously subject to spoilers the way that natural kind properties like **Water** are. Hence, as **A** is identical to the conjunction of its constituent states of affairs, it would seem that it will have the same shape in any world in which it exists, i.e., it will have that shape essentially.

That said, combinatorialism can arguably provide a reasonably robust analysis of intuitions about the essential properties of ordinary thick particulars like dogs or persons. Such objects can be taken to be temporal successions of sums of simples and each sum in the succession as its temporal parts. Sums in the same rough temporal neighborhood are composed of roughly the same simples and are structured in roughly the same way. Similarities between such objects across worlds in turn determine counterpart relations. Following Lewis, the essential properties of such objects can then be identified with those properties exemplified by (all of the temporal parts of) all of its counterparts in every world in which it exists (Armstrong 1997, 99–103, 169).[[57](https://plato.stanford.edu/entries/possible-worlds/notes.html#57)]

#### 2.3.6 Fewer Things and Other Things: Modified Combinatorialism

Since a possible world is a recombination of the actual world and every recombination includes states of affairs involving every simple individual and every simple universal, by **AE3**, every simple entity exists in every world. Hence, there could not have been fewer of them; nor could there have been simples other than the ones there actually are. In this section, we address this issue and the issue of contingent existence generally in combinatorialism.

**Fewer things.**  Combinatorialism as it stands has no problem accounting for the general intuition that there could have been fewer things. We have already noted in [§2.3.3](https://plato.stanford.edu/entries/possible-worlds/#Supervenience) and again in [§2.3.5](https://plato.stanford.edu/entries/possible-worlds/#EmergentModalities) how our water molecule **W**, as such, might not have existed. More generally, given the unrestricted nature of recombination, for any **a** involving a structural fact **S**, there are recombinations of the actual world wherein either (a) some of the relations among **a**'s constituents that are critical to **S**'s structure fail to be exemplified by those constituents, or (b) there are further states of affairs included by those recombinations that act as spoilers for **S**. Consequently, the combinatorialist seems to have no difficulty explaining how there might have been fewer water molecules, humans, etc.

Intuitively, however, there isn't anything in the idea of a simple that suggests that simples are necessary beings — especially if, as combinatorialists generally agree, simples are physical things of some sort and simple universals are properties of, and relations among, those things. For there is nothing in the nature of a simple object to suggest that any given simple had to have existed. Likewise, there is nothing in the nature of a simple universal to suggest it had to have been exemplified and, hence, on the combinatorialist's own conception of universals, that it had to exist. Otherwise put, as simples exist only insofar as they are constituents of facts, there seems no reason why there couldn't have been a very small number of facts, indeed, just a single simple, atomic, monadic fact and, hence, a lone simple object and a lone simple universal.

In fact, however, **AW3** can be easily modified to accommodate these intuitions without doing any serious violence to combinatorialist intuitions. Specifically, the combinatorialist can admit “contracted” worlds in which fewer simples exist by allowing any recombination of _any_ simple fact — that is, equivalently, by allowing any state of affairs — to count as a possible world:

|   |   |   |
|---|---|---|
|**AW3′**||**w** is a (combinatorial) possible world =_def_ **w** is a recombination of some simple fact **f** conjoined with the totality state of affairs **Tw** for that recombination.|

**AE3** requires no modification, as it was defined with sufficient generality above. Under **AW3′**, however, **AE3** entails that all entities alike — objects and universals, simple and structural — are contingent and, indeed, that every simple object is the sole constituent of some combinatorial possible world.

**Other things.**  Intuitively, not only could there have been fewer things, there could have been more things or, more generally, things _other_ than those that actually exist. As above, combinatorialism as it stands seems able to account for many instances of this intuition: Figure 2 illustrates how a non-actual hydronium ion **I** might exist in another world. Likewise, there seems no reason to deny, e.g., that there are rearrangements **w** of the actual world's simples wherein exist all of the human beings that actually exist (at, say, 0000GMT 1 January 2013) and more besides that are composed of simples that, in fact, constitute things other than human beings (Armstrong 1997, 165).[[58](https://plato.stanford.edu/entries/possible-worlds/notes.html#58)] Combinatorialism also seems able to account for the possibility of conjunctive and structural universals that are simply rearrangements of actual simples. It is not implausible to think that such recombinations can give rise to, say, exotic biological kinds that have no actual instances (Armstrong 1989, 55–56). Thus, in particular, combinatorialism seems quite able to provide the truth condition ([24](https://plato.stanford.edu/entries/possible-worlds/#TC1-PossExoticsFormal)) for ([23](https://plato.stanford.edu/entries/possible-worlds/#PossExoticsFormal)) and, hence, can account for some possibilities involving “missing” universals that, intuitively, ought to be possible.

However, it is far from clear that such possibilities exhaust the modal intuition that other things could have existed. Notably, intuitively, there could have been different _simple_ universals distinct from any that actually exist — different fundamental properties of simples, for example. Likewise for simple objects. Either way, there seems to be nothing in the idea of a simple object or simple universal that suggests there couldn't have been simples other than, or in addition to, the simples there are in fact. But **AW3**′ does not allow for this; the simples of every possible world are a subset of the actual simples and there is no obvious way of modifying the principle to accommodate the intuition. Nor is there any obvious way of modifying the principle to accommodate the intuition in question.[[59](https://plato.stanford.edu/entries/possible-worlds/notes.html#59)]

The combinatorialist could of course abandon actualism and include merely possible simples into her ontology. Again, she could follow the new actualists and draw a division between actually concrete and non-actual, possibly concrete simples; or she could introduce Plantinga-style haecceities to go proxy for merely possible simples. But all of these options would be badly out of step with the strong, naturalist motivations for combinatorialism: There is but the one physical world comprising all of the facts; recombinations of (at least some of) those facts — arbitrary rearrangements of their simple objects and universals — determine the possible worlds. Mere _possibilia_, merely possible non-_concretia_, and non-qualitative haecceities have no real place in that picture.

The “purest” option for the combinatorialist is simply to brazen it out and argue that the actual simples are, in fact, all the simples there could be (Armstrong 1989, 54ff; Driggers 2011, 56–61). A more robust option suggested by Skyrms (1981) makes some headway against the problem by introducing an “outer”, or “second-grade” realm of possibility, but at the cost of moving beyond the basic intuitions of combinatorialism (Armstrong 1989, 60; 1997, 165–167). Finally, Sider (2005, 681) suggests that combinatorialists who (like Armstrong) are modal fictionalists can deal with the problem of missing entities simply by appealing to yet more fictionalism: As the combinatorialist fiction _already_ includes non-actual states of affairs with actually existing constituents, there seems no reason not to extend the fiction to include non-actual states of affairs whose constituents include non-actual particulars and universals. Fictionalism itself, however, leaves the combinatorialist with the deep problems detailed by Kim (1986), Lycan (1993), and Rosen (1993).[[60](https://plato.stanford.edu/entries/possible-worlds/notes.html#60)]

#### 2.3.7 A Brief Assessment of Combinatorialism

As with concretism and abstractionism, combinatorialism provides reasonably clear definitions of possible worlds and existence in a world and is noteworthy for its attempt to avoid what might be thought of as the metaphysical excesses of the two competing views. In contrast to concretism, combinatorialism is staunchly actualist: instead of an infinity of alternative physical universes, each with its own unique inhabitants existing as robustly as the inhabitants of the actual world, the worlds of combinatorialism are simply rearrangements of the universals and particulars of the actual world; and commitment even to them might be avoided if some version of fictionalism is tenable. Likewise, in contrast to abstractionism's rather rich and unrestrained ontology of SOAs, combinatorialism's states of affairs are comparatively modest. Moreover, in contrast to nearly all versions of abstractionism, combinatorialism shares with concretism the virtue of a reductive theory of modality: Modal statements, ultimately, are true or false in virtue of how things stand with respect to worlds that are themselves defined in non-modal terms.

Combinatorialism's ontological modesty, however, is also a weakness. For, unlike, the two competing approaches, there are modal intuitions that the combinatorialist is not easily able to account for, notably, the intuition that there could have been other things. Additional difficulties are discussed in the supplemental document [Further Problems for Combinatorialism](https://plato.stanford.edu/entries/possible-worlds/problems-combinatorialism.html).

## Bibliography

- Adams, R., 1974. ‘Theories of Actuality’, _Noûs_, 8: 211–31; reprinted in Loux (1979): 190–209
- –––, 1981. ‘Actualism and Thisness’, _Synthese_, 49: 3–41
- Armstrong, D. M., 1978a, _Universals and Scientific Realism, Volume I: Nominalism and Realism_, Cambridge: Cambridge University Press.
- –––, 1978b, _Universals and Scientific Realism, Volume II: A Theory of Universals_, Cambridge: Cambridge University Press.
- –––, 1986a, ‘The Nature of Possibility’, _The Canadian Journal of Philosophy_, 16(4): 575–594.
- –––, 1986b. ‘In Defense of Structural Universals’, _Australasian Journal of Philosophy_, 64(1): 85–88.
- –––, 1989. _A Combinatorial Theory of Possibility_, New York: Cambridge University Press.
- –––, 1993. ‘A World of States of Affairs’, in J. Tomberlin (ed.), _Philosophical Perspectives_, 7: 429–440.
- –––, 1997. _A World of States of Affairs_, New York: Cambridge University Press.
- –––, 2004a. ‘Theorie Combinatoire Revue et Corrigée’, in J-M. Monnoyer (Ed.) _La Structure du Mond: Objets, Propriétés, États et Choses_, Paris: Vrin, 185–198.
- –––, 2004b. ‘Combinatorialism Revisited’, translation (with minor corrections) of Armstrong 2004a, URL = [http://eprints.nottingham.ac.uk/716/](http://eprints.nottingham.ac.uk/716/), ISBN: 2-7116-1627-4.
- –––, 2004c. _Truth and Truthmakers_, Cambridge: Cambridge University Press.
- –––, 2009. ‘Reply to Keller,’, in Monnoyer 2007, 157–162.
- Barcan, R., 1946. ‘A Functional Calculus of First Order Based on Strict Implication’, _Journal of Symbolic Logic_, 11: 1–16.
- Bayart, A., 1958, ‘La correction de la logique modale du premier et second ordre S5’, _Logique et Analyse_, 1: 28–44. Translated in Cresswell forthcoming.
- –––, 1959, ‘Quasi-adéquation de la logique modale de second ordre S5 et adéquation de la logique modale de premier ordre S5’, _Logique et Analyse_, 2: 99–121.
- Beall, J., 2000. ‘A Neglected Response to the Grim result’, _Analysis_, 60(1): 38–41.
- Bigelow, J. and R. Pargetter, 1987. ‘Beyond the Blank Stare’, _Theoria_, 53: 97–114.
- Bradley, R., 1989. ‘Possibility and Combinatorialism: Wittgenstein Versus Armstrong’, _Canadian Journal of Philosophy_, 19(1): 15–41.
- Bricker, P., 1980. ‘Prudence’, _Journal of Philosophy_, 77(7): 381–401.
- –––, 1987. ‘Reducing Possible Worlds to Language’, _Philosophical Studies_, 52(3): 331–355.
- –––, 1996. ‘Isolation and Unification: The Realist Analysis of Possible Worlds’, _Philosophical Studies_, 84(2/3): 225–238.
- –––, 2001. ‘Island Universes and the Analysis of Modality’, in G. Preyer, F. Siebelt (eds.), _Reality and Humean Supervenience: Essays on the Philosophy of David Lewis_, Rowman and Littlefield.
- –––, 2006. ‘The Relation Between General and Particular: Supervenience vs. Entailment’, in D. Zimmerman (ed.), _Oxford Papers in Metaphysics_, vol. 3, Oxford: Oxford University Press, 251–287.
- –––, 2008. ‘Concrete Possible Worlds’, in T. Sider, J. Hawthorne, and D. Zimmerman (eds.), _Contemporary Debates in Metaphysics_ Blackwell Publishing, 111–134.
- Bringsjord, S., 1985. ‘Are There Set Theoretic Possible Worlds?’, _Analysis_, 45(1): 64.
- Bueno, O., C. Menzel, and E. Zalta, 2014. ‘Worlds and Propositions Set Free’, _Erkenntnis_, 79: 797–820.
- Carnap, R., 1947. _Meaning and Necessity_. Chicago: The University of Chicago Press.
- Chihara, C., 1998. _The Worlds of Possibility_, Oxford: Clarendon Press
- Copeland, B. J., 2002. ‘The Genesis of Possible Worlds Semantics’, _Journal of Philosophical Logic_, 31: 99–137.
- –––, 2006. ‘Meredith, Prior, and the History of Possible Worlds Semantics’, _Synthese_, 150(3): 373–397.
- Cresswell, M. J., 1972. ‘The World is Everything that is the Case’, _Journal of Philosophy_, 50: 1–13. Reprinted in Loux (1979), 129–145.
- –––, 1973. _Logics and Languages_, London, Methuen.
- –––, 1985a. _Structured Meanings: The Semantics of Propositional Attitudes_, Bradford Books/MIT Press.
- –––, 1985b. _Adverbial Modification_. Dordrecht, Reidel.
- –––, 1988. _Semantical Essays: PossibleWorlds and Their Rivals_. Dordrecht, Kluwer Academic Publishers.
- –––, 1990. _Entities and Indices_. Dordrecht, Kluwer.
- –––, 1994. _Language in the World_. Cambridge: Cambridge University Press.
- –––, 1996. _Semantic Indexicality_. Dordrecht: Kluwer.
- –––, 2004. ‘Adequacy Conditions for Counterpart Theory’, _Australasian Journal of Philosophy_, 82(1): 28–41.
- –––, 2015. ‘Arnould Bayart's Modal Completeness Theorems — Translated with an Introduction and Commentary’, _Logique et Analyse_, 229: 89–142.
- Darby G., and D. Watson, 2010. ‘Lewis's Principle of Recombination: Reply to Efird and Stoneham’, _Dialectica_, 64(3): 435–445.
- Davies, M., 1981. _Meaning, Quantification, Necessity: Themes in Philosophical Logic_, London: Routledge and Kegan Paul.
- DeRosset, L., 2009a. ‘Possible Worlds I: Modal Realism’, _Philosophy Compass_, 4(6): 998–1008.
- –––, 2009b. ‘Possible Worlds II: Non-reductive Theories of Possible Worlds’, _Philosophy Compass_, 4(6): 1009–1021.
- Divers, J., 2002. _Possible Worlds_, London: Routledge.
- Divers, J. and J. Melia, 2002. ‘The Analytic Limit of Genuine Modal Realism’, _Mind_, 111(441): 15–36.
- Driggers, R. K., 2011. ‘M-Combinatorialism and the Semantics of SQML’, M.A. Thesis, Texas A&M University. URL = [http://hdl.handle.net/1969.1/ETD-TAMU-2011-05-9484](http://hdl.handle.net/1969.1/ETD-TAMU-2011-05-9484)
- Eddon, M., 2007. ‘Armstrong on Quantities and Resemblance’, _Philosophical Studies_, 136(3): 385–404.
- Efird, D. and T. Stoneham, 2008. ‘What is the Principle of Recombination?’, _Dialectica_, 62(4): 483–494.
- Egan, A., 2004. ‘Second-order predication and the Metaphysics of Properties’, _Australasian Journal of Philosophy_, 82(1): 48–66.
- Etchemendy, J., 1990. _The Concept of Logical Consequence_, Cambridge, MA: Harvard University Press. (Reissued by Stanford: CSLI Publications, 1999.)
- Feldman, F., 1971. ‘Counterparts’, _Journal of Philosophy_, 68: 406–9.
- Fara, D. G., 2009. ‘Dear Haecceitism’, _Erkenntnis_, 70: 285–297.
- Fara, M. and T. Williamson, 2005. ‘Counterparts and Actuality’, _Mind_, 114(453): 1–30.
- Fine, K., 1977. ‘Postscript’, in Prior 1977, 116–161.
- –––, 1978. ‘Model Theory for Modal Logics: Part I — The _De Re_/_De Dicto_ Distinction’, _Journal of Philosophical Logic_, 7: 125–56.
- Forbes, G., 1985. _The Metaphysics of Modality_, Oxford: Clarendon Press.
- –––, 1982. ‘Canonical Counterpart Theory’, _Analysis_, 42(1): 33–37.
- Fitch, G. W., 1996, ‘In Defense of Aristotelian Actualism’, _Philosophical Perspectives_, 10: 53–71.
- Forrest, P. and D. M. Armstrong, 1984. ‘An Argument against David Lewis's Theory of Possible Worlds’, _Australasian Journal of Philosophy_, 62: 164–168.
- Garson, J., 2006. _Modal Logic for Philosophers_. New York: Cambridge University Press.
- Goldblatt, R., 2003. “Mathematical Modal Logic: A View of its Evolution”, in D. M. Gabbay and J. Woods (eds.), _Handbook of the History of Logic, Vol. 7: Logic and the Modalities in the Twentieth Century_. Amsterdam: Elsevier, pp. 1–98.
- Grim, P., 1986. ‘On Sets and Worlds: A Reply to Menzel’, _Analysis_, 46(4): 186–191.
- Hazen, A., 1979. ‘Counterpart Theoretic Semantic for Modal logic’, _Journal of Philosophy_, 76: 319–338.
- Hunter, G. and W. Seager, 1981. ‘The Discreet Charm of Counterpart Theory’, _Analysis_, 41(2): 73–76.
- Heil, J., 2007. ‘The Legacy of Linguisticism’, _Australasian Journal of Philosophy_, 84(2): 233–244.
- Hintikka, J., 1957. ‘Modality as referential multiplicity’, _Ajatus_, 20: 49–64.
- –––, 1961. ‘Modality and Quantification’, _Theoria_, 27: 119–28.
- Hughes, G. and Cresswell, M., 1968. _An Introduction to Modal Logic_, London: Methuen.
- Jager, T., 1982. ‘An Actualist Semantics for Quantified Modal Logic’, _Notre Dame Journal of Formal Logic_, 23(3) (July): 335–49.
- Kanger, S., 1957. _Provability in Logic_, Stockholm: Almqvist and Wiksell.
- Kaplan, D., 1975. ‘How to Russell a Frege-Church’, _Journal of Philosophy_, 72: 716–29; reprinted in Loux (1979), pp. 210–24.
- Kaplan, D., 1979. ‘Transworld Heir Lines’, in Loux (1979), pp. 88–109.
- –––, 1995. ‘A Problem in Possible World Semantics’, in W. Sinnott-Armstrong, D. Raffman, and N. Asher (eds.), _Modality, Morality and Belief: Essays in Honor of Ruth Barcan Marcus_, Cambridge: Cambridge University Press, 41–52.
- Keller, P., 2007. ‘A World of Truthmakers’, in Monnoyer 2007, 105–156.
- –––, 2009. ‘Review of D. M. Armstrong, Truth and Truthmakers’, _Mind_, 118(472): 1101–1105.
- Kemeny, J. G., 1956a. ‘A New Approach to Semantics — Part I’, _The Journal of Symbolic Logic_, 21(1): 1–27.
- –––, 1956b. ‘A New Approach to Semantics — Part II’, _The Journal of Symbolic Logic_, 21(2): 149–161.
- Kim, J., 1986. ‘Possible Worlds and Armstrong's Combinatorialism’, _Canadian Journal of Philosophy_, 16(4): 595–612.
- Kripke, S., 1959. ‘A Completeness Theorem in Modal Logic’, _Journal of Symbolic Logic_, 24(1): 1–14.
- –––, 1963a. ‘Semantical Analysis of Modal Logic I: Normal Modal Propositional Calculi’, _Zeitschrift für Mathematische Logik und Grundlagen der Mathematik_, 9: 67–96.
- –––, 1963b. ‘Semantical Considerations on Modal Logic’, _Acta Philosophica Fennica_, 16: 83–94.
- –––, 1972. ‘Naming and Necessity’, Cambridge, Massachusetts: Harvard, 1980.
- Lewis, D., 1968. ‘Counterpart Theory and Quantified Modal Logic’, _Journal of Philosophy_, 65: 113–126.
- –––, 1970. ‘General Semantics’, _Synthese_, 22: 18–67.
- –––, 1973. _Counterfactuals_, Cambridge, Massachussetts: Harvard University Press.
- –––, 1986. _On The Plurality of Worlds_, Oxford: Blackwell.
- –––, 1986a. ‘Against Structural Universals’, _Australasian Journal of Philosophy_, 64(1): 25–46.
- –––, 1991. _Parts of Classes_, Oxford: Basil Blackwell Ltd.
- –––, 1992, ‘Critical Notice: Armstrong, D. M., _A Combinatorial Theory of Possibility_’, _Australasian Journal of Philosophy_, 70(2): 211–224.
- Lewis, C. I. and C. H. Langford, 1932. _Symbolic Logic_, New York: The Appleton-Century Company; reprinted in paperback by New York: Dover Publications, 1951.
- Linsky, B. and E. Zalta, 1994. ‘In Defense of the Simplest Quantified Modal Logic’, in J. Tomberlin (ed.), _Philosophical Perspectives_, 8: 431–458.
- –––, 1996. ‘In Defense of the Contingently Concrete’, _Philosophical Studies_, 84: 283–294.
- Loux, M. (ed.), 1979. _The Possible and the Actual_, Ithaca: Cornell.
- Lycan, W., 1988. ‘On the Plurality of Worlds by David Lewis’, _The Journal of Philosophy_, 85(1): 42–47.
- –––, 1991. ‘Two — No, Three — Concepts of Possible Worlds’, _Proceedings of the Aristotelian Society, New Series_, 91: 215–227.
- –––, 1993. ‘Armstrong's New Combinatorial Theory of Modality’, in J. Bacon, K. Campbell, and L. Reinhardt (eds.), _Ontology, Causality, and Mind: Essays in Honour of D. M. Armstrong_, Cambridge: Cambridge University Press, 3–22.
- Maddy, P., 1980. ‘Perception and Mathematical Intuition’, _The Philosophical Review_, 89(2): 163–196.
- Mates, B., 1968. ‘Leibniz on Possible Worlds’, in B. van Rootselaar and J. F. Staal (eds.), _Logic, Methodology and Philosophy of Science_, vol. 3, Amsterdam: North-Holland Publishing Company, 507–29; reprinted in H. Frankfurt (ed.), _Leibniz_, Notre Dame: University of Notre Dame Press (1972), 335–364.
- Marcus, R., 1986. ‘Possibilia and Possible Worlds’, _Grazer Philosophische Studien_, 25/26 (1985/1986): 107–33.
- McDaniel, K., 2006. ‘Modal Realisms”, _Philosophical Perspectives_, 20: 303–331.
- McNamara, P., 1993. ‘Does the Actual World Actually Exist?’, _Philosophical Studies_, 69: 59–81.
- Menzel, C., 1986. ‘On Set Theoretic Possible Worlds’, _Analysis_, 46(2): 68–72.
- –––, 1989. ‘On an Unsound Proof of the Existence of Possible Worlds’, _Notre Dame Journal of Formal Logic_, 30(4): 598–603.
- –––, 1990. ‘Actualism, Ontological Commitment, and Possible Worlds Semantics’, _Synthese_, 85: 355–89.
- –––, 1991. ‘The True Modal Logic’, _Journal of Philosophical Logic_, 20: 331–374.
- –––, 2012. ‘Sets and Worlds Again’, _Analysis_, 72(2): 304–309.
- Menzel, C., and E. Zalta, 2014, ‘The Fundamental Theorem of World Theory’, _Journal of Philosophical Logic_, 43(2): 333–363.
- Meredith, C. and A. Prior, 1956. ‘Interpretations of Different Modal Logics in the “Property Calculus”’, in Copeland, B. (ed.) 1996, _Logic and Reality: Essays on the Legacy of Arthur Prior_, Oxford: Clarendon Press.
- Merricks, T., 2003. ‘The End of Counterpart Theory ’, _The Journal of Philosophy_, 100(10): 521–549.
- Merrill, G., 1978. ‘Formalization, Possible Worlds and the Foundations of Modal Logic’, _Erkenntnis_, 12: 305–327.
- Monnoyer, J. (ed.), 2007. _Metaphysics and Truthmakers_, Frankfurt am Main: Ontos Verlag.
- Montague, R., 1974. _Formal Philosophy_, New Haven, CT: Yale University Press
- Moreland, J. P., 2011. ‘Exemplification and Constituent Realism: A Clarification and Modest Defense’, _Axiomathes_, online. doi:10.1007/s10516-011-9148-x
- Nolan, D., 1996. ‘Recombination Unbound’, _Philosophical Studies_, 84(2/3): 239–262.
- Nortmann, U., 2002. ‘The Logic of Necessity in Aristotle: An Outline of Approaches to the Modal Syllogistic, Together with a General Account of _de dicto_- and _de re_-Necessity’, _History and Philosophy of Logic_, 23: 253–265.
- Novakofski, J. M. S. Brewer, N. Mateus-Pinilla, J. Killefer, and R. H. McCusker, 2005. ‘Prion Biology Relevant to Bovine Spongiform Encephalopathy’, _Journal of Animal Science_, 83(6): 1455–1476. doi:10.2527/2005.8361455x
- Pickavance, T., 2014. ‘Bare Particulars and Exemplification’, _American Philosophical Quarterly_, 51(2): 95–108.
- Plantinga, A., 1974. _The Nature of Necessity_, Oxford: Oxford University Press.
- –––, 1976. ‘Actualism and Possible Worlds’, _Theoria_, 42: 139–60; reprinted in Loux (1979): 253–73.
- –––, 1985. ‘Replies’, in _Alvin Plantinga_, J. Tomberlin and P. van Inwagen (eds.), Dordrecht: D. Reidel: 313–96.
- –––, 1987. ‘Two Concepts of Modality: Realism and Modal Reductionism’, in J. Tomberlin (ed.), _Philosophical Perspectives_, 1: 189–231.
- Pollock, J., 1985. ‘Plantinga on Possible Worlds’, in _Alvin Plantinga_, J. Tomberlin and P. van Inwagen (eds.), Dordrecht: D. Reidel, pp. 121–44.
- Prior, A. N., 1952. ‘Modality _de dicto_ and modality _de re_, _Theoria_, 18(3): 174–180.
- –––, 1977. _Worlds, Times, and Selves_, Amherst: University of Massachusetts Press.
- –––, 1956. ‘Modality and Quantification in S5’, _Journal of Symbolic Logic_, 21: 60–2.
- Pruss, A., 2001. ‘The Cardinality Objection to David Lewis's Modal Realism’, _Philosophical Studies_, 104: 169–178.
- Quine, W. V. O., 1948. ‘On What There Is’, in _From a Logical Point of View_, New York: Harper, 1953, 1–19.
- –––, 1953. ‘Three Grades of Modal Involvement’, _Proceedings of the XIth International Congress of Philosophy_, 14: 65–81.
- –––, 1956. ‘Quantifiers and Propositional Attitudes’, _The Journal of Philosophy_, 53: 177–187.
- –––, 1960. _Word and Object_, Cambridge, MA: MIT Press.
- –––, 1968. ‘Propositional Objects’, _Critica: Revista Hispanoamericana de Filosofia_, 2(5): 3–29. Reprinted in W. V. Quine, 1977, _Ontological Relativity_, Columbia University Press: 139–160.
- Rosen, G., 1993. ‘A Problem for Fictionalism about Possible Worlds’, _Analysis_, 53(2): 71–81.
- Roy, T., 1995. ‘In Defense of Linguistic Ersatzism’, _Philosophical Studies_, 80(3): 217–242.
- Russell, B., 1918/1919. ‘The Philosophy of Logical Atomism’, _The Monist_, 28: 495–527; 29: 32–63, 190–222, 345–380. Reprinted in Russell 1956, 177–281 and published in book form as Russell 1985.
- –––, 1956. _Logic and Knowledge_, London: Allen and Unwin.
- –––, 1985. _The Philosophy of Logical Atomism_, with an introduction by D. Pears, London: Routledge.
- Salmon, N., 1988. ‘Review of _On the Plurality of Worlds_, _Philosophical Review_, 97(2): 237–244.
- Shalkowski, S., 1994. ‘The Ontological Ground of the Alethic Modality’, _The Philosophical Review_, 103(4): 669–688.
- Schneider, S., 2001. ‘Alien Individuals, Alien Universals, and Armstrong's Combinatorial Theory of Possibility’, _The Southern Journal of Philosophy_, 39: 575–593.
- Sider, T., 2002. ‘The Ersatz Pluriverse’, _Journal of Philosophy_, 99(6): 279–315.
- –––, 2005. ‘Another Look at Armstrong's Combinatorialism’, _Noûs_, 39(4): 679–695.
- Skyrms, B., 1981. ‘Tractarian Nominalism’, _Philosophical Studies_, 40(2): 199–206.
- Stalnaker, R., 1968. ‘A Theory of Conditionals’ in _Studies in Logical Theory_, _American Philosophical Quarterly_ Monograph Series, 2. Oxford: Blackwell, pp. 98–112.
- –––, 1976. ‘Possible Worlds’, _Noûs_, 10(1): 65–75.
- –––, 1987. _Inquiry_, Boston: Bradford Books, MIT Press.
- –––, 2012. _Mere Possibilities: Metaphysical Foundations of Modal Semantics_, Princeton: Princeton University Press.
- Tarski, A., 1933. ‘The concept of truth in the languages of the deductive sciences’ (Polish), _Prace Towarzystwa Naukowego Warszawskiego, Wydzial III Nauk Matematyczno-Fizycznych_, 34, Warsaw; expanded English translation in Tarski (1983), 152–278.
- –––, 1944. ‘The semantic conception of truth’, _Philosophy and Phenomenological Research_, 4: 13–47.
- –––, 1983. _Logic, Semantics, Metamathematics, papers from 1923 to 1938_, edited by John Corcoran. Indianapolis: Hackett Publishing Company.
- Tomberlin, J., and van Inwagen, P. (eds.), 1985. _Profiles: Alvin Plantinga_, Dordrecht: D. Reidel, pp. 121–44.
- van Inwagen, P., 1986. ‘Two Concepts of Possible Worlds’, in _Midwest Studies in Philosophy, XI_, P. French, T. Uehling, and H. Wettstein (eds.), Minneapolis: University of Minnesota Press, 185–213.
- –––, 2008. ‘McGinn on Existence’, _The Philosophical Quarterly_, 58(20): 36–58.
- Washington, C., 1998. ‘Use/Mention Distinction and Quotation’, in _Routledge Encyclopedia of Philosophy_, vol. 9, W. Craig (ed.), London and New York: Routledge.
- Williamson, T., 1998. ‘Bare Possibilia’, _Erkenntnis_, 48: 257–273.
- –––, 2000. ‘The Necessary Framework of Objects’, _Topoi_, 19: 201–208.
- –––, 2013. _Modal Logic as Metaphysics_. Oxford: Oxford University Press.
- Wittgenstein, L., 1921. ‘Logisch-Philosophische Abhandlung’, with a forward by Bertrand Russell, _Annalen der Naturphilosophie_, 14, published by Wilhelm Ostwald, Leipzig: Verlag Unesma: 185–262. Also available online in HTML, PDF, and ePub formats in a side-by-side presentation with the translations Wittgenstein (1922) and Wittgenstein (1974) at [http://people.umass.edu/klement/tlp/](http://people.umass.edu/klement/tlp/).
- –––, 1922. _Tractatus Logico-Philosophicus_, trans. of Wittgenstein (1921) by C. K. Ogden, Routledge & Kegan Paul.
- –––, 1974. _Tractatus Logico-Philosophicus_, revised edition, trans. of Wittgenstein (1921) by D. F. Pears and B. F. McGuinness, New York and London: Routledge & Kegan Paul.
- Yagisawa, T., 2010. _Worlds and Individuals, Possible and Otherwise_, Oxford: Oxford University Press.
- Zalta, E., 1983. _Abstract Objects: An Introduction to Axiomatic Metaphysics_, Dordrecht: D. Reidel.
- –––, 1993. ‘Twenty-Five Basic Theorems in Situation and World Theory’, _Journal of Philosophical Logic_, 22(4): 385–428.

## Academic Tools

> |   |   |
> |---|---|
> |![sep man icon](https://plato.stanford.edu/symbols/sepman-icon.jpg)|[How to cite this entry](https://plato.stanford.edu/cgi-bin/encyclopedia/archinfo.cgi?entry=possible-worlds).|
> |![sep man icon](https://plato.stanford.edu/symbols/sepman-icon.jpg)|[Preview the PDF version of this entry](https://leibniz.stanford.edu/friends/preview/possible-worlds/) at the [Friends of the SEP Society](https://leibniz.stanford.edu/friends/).|
> |![inpho icon](https://plato.stanford.edu/symbols/inpho.png)|[Look up topics and thinkers related to this entry](https://www.inphoproject.org/entity?sep=possible-worlds&redirect=True) at the Internet Philosophy Ontology Project (InPhO).|
> |![phil papers icon](https://plato.stanford.edu/symbols/pp.gif)|[Enhanced bibliography for this entry](https://philpapers.org/sep/possible-worlds/) at [PhilPapers](https://philpapers.org/), with links to its database.|

## Other Internet Resources

- Browse papers by related topics at Phil Papers:
    - [actualism and possibilism](https://philpapers.org/browse/actualism)
    - [counterpart theory](https://philpapers.org/browse/counterpart-theory)
    - [essentialism and _de re_ modality](https://philpapers.org/browse/essentialism-and-de-re-modality-misc)
    - [essentialism and quantified modal logic](https://philpapers.org/browse/essentialism-and-quantified-modal-logic)
    - [modal ersatzism](https://philpapers.org/browse/modal-ersatzism) (roughly what is referred to as abstractionism in this entry)
    - [modal fictionalism](https://philpapers.org/browse/modal-fictionalism)
    - [modal realism](https://philpapers.org/browse/modal-realism) (referred to as "concretism" in this entry)
    - [possible worlds](https://philpapers.org/browse/possible-worlds-misc)
    - [possible world semantics](https://philpapers.org/browse/possible-world-semantics)
    - [Theories of modality](https://philpapers.org/browse/theories-of-modality-misc)
    - [modal primitivism](https://philpapers.org/browse/modal-primitivism)
    - [universals](https://philpapers.org/browse/universals)

## Related Entries

[essential vs. accidental properties](https://plato.stanford.edu/entries/essential-accidental/) | [identity: transworld](https://plato.stanford.edu/entries/identity-transworld/) | [Lewis, David: metaphysics](https://plato.stanford.edu/entries/lewis-metaphysics/) | [logic, history of: modal logic](https://plato.stanford.edu/entries/logic-modal-origins/) | [logic: classical](https://plato.stanford.edu/entries/logic-classical/) | [logic: intensional](https://plato.stanford.edu/entries/logic-intensional/) | [logic: modal](https://plato.stanford.edu/entries/logic-modal/) | [modality: epistemology of](https://plato.stanford.edu/entries/modality-epistemology/) | [natural kinds](https://plato.stanford.edu/entries/natural-kinds/) | [possibilism-actualism debate](https://plato.stanford.edu/entries/possibilism-actualism/) | [possible objects](https://plato.stanford.edu/entries/possible-objects/) | [Prior, Arthur](https://plato.stanford.edu/entries/prior/) | [rigid designators](https://plato.stanford.edu/entries/rigid-designators/) | [states of affairs](https://plato.stanford.edu/entries/states-of-affairs/)

### Acknowledgments

The author wishes to express his deep gratitude to Phillip Bricker and Max Cresswell for extensive comments on several drafts of this entry and for numerous illuminating discussions of its content and related topics. The entry is vastly better for their generous input. Errors and other infelicities that remain are of course the sole responsibility of the author. A great deal of this entry was written with the support of the Alexander von Humboldt Foundation while the author was a Visiting Fellow at the Munich Center for Mathematical Philosophy in 2011–12. Thanks are due to the Center's director, Professor Hannes Leitgeb, for making the author's stay at this remarkable venue possible. Finally, the author would like to express his thanks to the SEP Editors for their extraordinary patience in dealing with the very tardy author of a badly-needed entry.