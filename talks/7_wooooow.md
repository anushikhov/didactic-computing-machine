propositional → first-order → second-order → higher order → type theory   
   
After propositional → first-order → second-order → higher-order, you basically hit a fork where there are **multiple independent axes of “stronger”**.   
   
### The “order” ladder does continue   
   
* **(n)-th order logic**: quantify over (n)-level objects (individuals, sets of individuals, sets of sets, …).   
* **Full higher-order logic**: quantify over *all* higher types.   
   
But after second order, a lot of nice meta-theorems drop away (completeness/compactness/LS), depending on semantics.   
   
### Type theory isn’t just “next order”   
   
Type theory is more like: **change the foundations** (terms + types + judgments), rather than “add another quantifier level.”   
   
* **Simple type theory** (Church) is close in spirit to higher-order logic.   
* **Dependent type theory** (Martin-Löf) is a bigger jump.   
* Then you get things like **HoTT / univalent foundations**, where equality itself becomes richer.   
   
### Other ways it “goes on” (different directions)   
   
Even starting from first-order, you can extend in non-order ways:   
   
* **Many-sorted / typed first-order logic** (more structure, often still first-order behavior)   
* **Infinitary logics** (L_{\kappa,\lambda}) (allow infinite conjunctions/disjunctions, long quantifier blocks)   
* **Fixed-point / inductive definitions** (e.g., FO(LFP), μ-calculus) — huge in CS   
* **Modal / temporal / dynamic logics** (new operators; different semantics)   
* **Second-order under Henkin semantics** (a “weaker” SOL that behaves more like FOL)   
   
### A useful “map” takeaway   
   
* If you want a stable spine:   
  **Propositional → FOL → (a bunch of extensions)**   
* “Second order / higher order / type theory” are **stronger frameworks**, but you stop getting a single monotone ladder of “more expressive therefore next.”   
   
---------------------------------------------------      
   
Here’s a clean **main road** (with a couple optional “side roads” you can ignore until you feel like exploring).   
   
## The Main Road   
   
1. **Propositional logic**   
   (connectives, truth tables, natural deduction)   
   
2. **First-order logic (FOL)**   
   (quantifiers over individuals; predicates; structures/models)   
   
3. **First-order with equality + theories**   
   (Peano arithmetic, groups, fields; proof systems + semantics)   
   
4. **Second-order logic (SOL)**   
   (quantify over predicates/sets; “categoricity” shows up; power increases)   
   
5. **Higher-order logic (HOL)**   
   (quantify over functions, predicates of predicates…; types often appear here)   
   
6. **Simple Type Theory** *(a.k.a. typed HOL / Church)*   
   (types tame higher-order logic; functions become first-class citizens)   
   
7. **Dependent Type Theory** *(Martin-Löf)*   
   (types can depend on terms; propositions-as-types becomes *the* vibe)   
   
8. **Type theories with universes + inductives**   
   (a practical foundation for math + programs)   
   
9. **Proof assistants’ cores** *(e.g., CIC-style)*   
   (dependent types + inductives + universes → “real machinery”)   
   
10. **Homotopy Type Theory (HoTT) / Univalence / Higher Inductive Types**   
    (equality becomes geometric; types behave like spaces)   
   
…and yes, it *keeps going*:   
   
11. **Cubical Type Theory**   
    (computational control over equality/univalence)   
   
12. **Higher / ∞-stuff (categorical logic side meets type theory)**   
    (∞-groupoids, ∞-categories, ∞-toposes — the “many-dimensional foundations” feel)   
   
## One-line poetic “forward”   
   
**Truth → Quantifiers → Structures → Quantifying predicates → Quantifying functions → Types → Dependent types → Universes/Induction → Univalent equality → Higher dimensions.**   
   
