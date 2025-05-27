# CS-360-Assignment-1-solution

Download Here: [CS 360 Assignment 1 solution](https://jarviscodinghub.com/assignment/cs-360-assignment-1-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. For each of the following statements, prove the statement if it is always holds true (for
every choice of sets x, Y, Z), and provide a counter example if not:
(a) If every member if Y is an infinite set, then so is T
Y .
(b) If Y ⊆ Z then T
Y ⊆
T
Z.
2. Let Y = {B ⊆ N : (N \ B) is a finite set}. Describe the set T
Y explicitly (recall that
T
Y = {z : ∀x ∈ Y, : z ∈ x}. That is, we assume that all members of Y are sets and
take their intersection).
3. Is the following statement true? Prove your claim.
For any non-empty language, L ⊆ {0, 1}
∗
,
 ∈ L if and only if L ⊆ LL
(where  denotes the empty string).
4. Define a language Ltimes ⊆ {a, b, c}
∗ by structural induction as I(A, P) where :
• A = {abaca}
• P = {F1, F2} where, for every i, j, k, F1(a
i
baj
cak
) = a
i+1baj
cak+j and F2(a
i
baj
cak
) =
a
i
baj+1cak+i
.
In other words, a string is in Ltimes if and only if the above rules imply that it has to
be there.
For each of the following strings, determine if it is in Ltimes or not:
(i) ababab. (ii) aaabaacaaaaaa. (iii) aabacaaaa.
Prove each statement you make (to prove that a string belongs to the language, provide
a sequence of strings, such that each string there is either abaca or its membership in
the language is implied by applying the functions F1, F2, to previous strings in the
sequence. To prove that a string is not in Ltimes, prove that some property of strings
holds for all members of Ltimes but fails for that string).
1
5. You are sitting in a restaurant with two glasses in front of you, each filled to 3/4 of its
capacity. The first glass contains wine and the second contains water. Out of boredom,
you start playing the following game: You pour liquid from one glass to the other, and
mix the liquid in that other glass. You then repeat your pouring game over and over
again (without spilling anything). Prove, that as long as you follow the above steps,
there will always be more wine than water in the first glass. (Hint: use structural
induction on the set of all obtainable states of the glasses).
6. Consider the regular expressions, r1 = λ + (0 + 1)∗1 and r2 = (0∗1)∗
. Prove that
L(r1) = L(r2). Recall, that you should show two sided inclusion between these two
languages.
7. For each of the languages listed below, give a regular expression that represents the
language. Briefly justify your answer. The languages are all over alphabet Σ = {a, b}.
(a) The language of all strings with two consecutive a’s, but no three consecutive a’s.
(e.g. aa, aabaa, babaa are in the language but abab, aaaab are not).
(b) The set of strings whose first and last letters are different.
