---
layout: post
title: "An Implication of the Preface Paradox"
author: "GWDZ"
categories: shower
tags: [epistemology,paradoxes]

---

Suppose an author has written a book. As she has done due dilligence in checking her sources while writing, for each proposition $p$ in the book, she believes $p$ is true. Nontheless, since the book was long, and knowing that she is fallible, she writes in the preface that there must be at least one mistake in the book.  Though she does not know where this mistake is, she does not believe that the conjunction of every proposition in the book is true.

This scenario leads to a contradiction when we add this principle:

**Agglomeration Principle**

: If $Bp$ $\land$ $Bq$ then $B(p \land q)$.

Now let the set of propositions in the book be $A = \\{p_0 ... p_n\\}$. Having done her due dilligence, the author believes each proposition $p \in A$ . That is, $Bp_0 \land ... \land Bp_n$. By the agglomeration principle, $B(p_0 \land ... \land p_n)$. However, as stated in the preface, $\neg B(p_0 \land ... \land p_n)$. Contradiction.

### Interesting Implication

I argue that the preface paradox entails another undesirable result: belief is not necessary for knowledge. As the author has diligently checked each source, it is conceivable that for each proposition $p \in A$, the author knows that $p$. That is, $\forall p \in A(Kp)$. However, as stated in the preface, $\neg B(p_0 \land ... \land p_n)$. By the  Agglomeration Principle, $\neg Bp_0 \lor ... \lor \neg Bp_n$. That is, $\exists p \in A(\neg Bp)$. Since $A$ is nonempty, $\exists p \in A(\neg Bp \land Kp)$.

However, this result is trivial as it already follows from the original contradiction by explosion.
