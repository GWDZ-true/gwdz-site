---
title: "Understanding Conditionals"
author: "GWDZ"
categories: comment
tags: [logic,epistemology,phillang]
layout: post
---

I recently polled my followers with a logic question:

> There are five subjects, *A* through *E*. You say, "Raise your hand if you like oranges!". *A*, *B*, and *C* raise their hands. The rest do not. Supposing they can be trusted, which of these statements do you think is more likely?
> 1. *A* likes oranges
> 2. *E* does not like oranges
> 3. Just as likely

Here are the results:

| Option | Percentage | *n* |
|:------|:---------:|:--:|
|*A* likes oranges | 40% | 8 |
|*E* does not like oranges | 10% | 2 |
| Just as likely | 50% | 10 |

The right answer is (2): "*E* does not like oranges". Only 10% of respondents answered correctly, lower than what would have been if they guessed at random. Let's discuss why (2) is correct, and why few would give that answer.

## Why Option (2) is correct

Suppose *A* does not like oranges. Can she still raise her hand? 

Our five subjects can be trusted, so they will not disobey our instruction to raise their hands if they like oranges. In other words, they will not act in a way that renders statement **P** false:

: <br /> **P**: If a subject likes oranges, then that subject's hand is raised.

<br />
However, we did not instruct them not to raise their hand if they do not like oranges. To clarify the difference between the two instructions, let's restate this second instruction as a statement that the subjects must not render false:

: <br /> **Q**: If a subject does not like oranges, that subject's hand is not raised.

<br />
These two statements are not equivalent. **P** can be true when **Q** is false, and vice versa. To see why, consider an analogous pair of sentences of a similar form:

: <br /> **R**: If someone tests positive for Covid, then they have Covid.
: <br /> **S**: If someone tests negative for Covid, then they do not have Covid.

**R** is true when the set of people who test positive is completely contained in the set of people with Covid. If you are in the set of people who test positive, then you are also in the set of people who have Covid. However, the set of people who have Covid may also contain some others who tested negative. After all, not everyone with Covid tests positive for Covid. There might be some Covid cases the test fails to pick up (false negatives). Consequently, even if someone tests negative for Covid, they might still have Covid. Hence, **S** will be false.

In the limit, you might even design a (very poor) Covid test that returns negative for everyone, whether they have Covid or not. With this test, no one will test positive for Covid. Consequently, no one will test positive *and* still not have Covid. Hence, no part of the (empty) set of people who test positive will lie beyond the set of people with Covid. This means **R** is true. But if there is at least one Covid case, then **S** would be false.[^2]

Analogously, **P** is true so long as the set of subjects who like oranges is completely contained in the set of subjects with their hands up. However, this does not entail that everyone who raises their hand likes oranges. The set of subjects raising their hands may contain some that dislike oranges. So long as it also contains everyone who does like oranges, it will be true that if a subject likes oranges, then they are in the set of people with their hands up. Thus, a subject would not render **P** false by raising her hand even though she dislikes oranges. In the absence of instruction **Q**, a subject like *A* can raise her hand even though she dislikes oranges, while also following our instruction.

One might argue that when we give instruction **P**, we are also tacitly giving instruction **Q**. The subjects are expected by social convention not to raise their hands if they do not like oranges. Perhaps. But the information provided does not guarantee that these social conventions apply, or will be followed. Hence we cannot eliminate the possibility, however trivial, that *A* is a pedantic logician who raised her hand even though she dislikes oranges, simply out of whimsy. We thus cannot be 100% certain that *A* likes oranges. At best, we can be extremely confident it's true.

In contrast, suppose for the sake of argument that *E* likes oranges. Since she did not raise her hand, there would be at least one person who likes oranges but did not raise up their hand, rendering **P** false. We know *E* is trustworthy, and hence will not render **P** false. Thus we can deduce, with 100% certainty, that *E* does not like oranges. 

Since we can be 100% certain that *E* does not like oranges, but only less than 100% certain that *A* likes oranges, (2) is the right answer.

## Why few would choose Option (2)

One possibility is that we are led astray by our social conditioning to expect that instruction **Q** is implicit in the scenario. Comparing to similar past social interactions, we expect the subjects not to raise their hands if they do not like oranges. We thus do not consider the possibility that *A* can buck the trend and raise her hand.

If this is the primary cause leading respondents astray, we might expect a better performance when we present a different scenario where such social conventions do not apply. I thus polled my respondents with this follow-up question:

> Suppose you are a police officer at a bar. You see a group of young drinkers, *A* through *E*. You say, "Raise your hand if you are of the minimum legal age for drinking!". *A*, *B*, and *C* raise their hands. The rest do not. Supposing they can be trusted, which of these statements do you think is more likely?[^1]
> 1. *A* is legal
> 2. *E* is underage
> 3. Just as likely

In this scenario, we suspend the social expectation that subjects would not raise their hands if they are underage. It is plausible for subjects like *A* to raise their hands even when underage to avoid arrest. By exaggerating the probability that *A* raises her hand despite being underage, respondents are more likely to engage with it. If the respondent further considers that *A* would not thereby flout the given instruction, then the respondent would be lead to the correct answer. We might thus expect a better performance.

The results I received do not confirm this hypothesis. But they do lend some support:

| Option | Percentage | $n$ |
|:------|:---------:|:--:|
|*A* is legal | 12% | 2 |
|*E* is underage | 19% | 3 |
| Just as likely | 69% | 11 |

It is promising that more respondents gave the correct response than the clearly incorrect option (1). The fact that some respondents switched from option (1) to option (3) also indicates that though the change in scenario could not lead respondents to the correct answer, it did cause them to reconsider if *A*'s response really implies that she is legal. However, since the experiment was hardly controlled, and many respondents to the first poll did not respond to the second, I cannot reliably draw any conclusions.

## Blame our language?

Another possibility is that our language uses the words "if... then..." too loosely, expressing different meanings in different cases. For instance, if a mother tells her children "if you don't eat your greens then you won't get your dessert", but, when her children do eat their greens, refuse them dessert on the grounds that her earlier promise does not imply the promise "if you eat your greens then you will get your dessert", she will have very annoyed children indeed. In this case, the mother's words might be interpreted as expressing both promises.

Statements in the form of "if ... then ..." are called conditional statements. By using conditional statements to express different meanings, we are predisposed towards conflating the meanings of conditional statements, or disambiguating them based on social context. Thus, we must both broaden our logical analyses of conditional statements to admit their varying meanings, and change our language to differentiate between these meanings.

I explore these issues in part 2 of this post.




[^1]: Inspired by [Cosmides and Tooby's (1992)](https://www.cep.ucsb.edu/papers/Cogadapt.pdf) social enforcement variation of the Wason Selection Task.

[^2]: See related: [Test Sensitivity and Specificity](https://uk.cochrane.org/news/sensitivity-and-specificity-explained-cochrane-uk-trainees-blog).