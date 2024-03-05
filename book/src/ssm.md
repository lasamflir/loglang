# SSM overview
The SSM works entirely without stress or tone to allow for reasonably flexible root words and allow for marking of scope on particles and predicate class on roots.
# Allowed syllable group structure
Syllable group structure is given by:
`((C)C)C(V)V(HV)...(N)`
* C is bcdfghjklprstvwz
* V is aeiouy
* H is ',
* N is mnqx

There may be an arbitrary number of HV parts. Syllable groups are not syllables. A cluster may unpronounceable like "bp" if it's in the middle of a word and able to "lean on" the preceding vowel. Where syllable boundaries are is unimportant to the SSM scheme because it depends only on patterns of vowels and consonants. A word like `stolobpo` breaks into syllables `sto lob po` but is considered to have a consonant cluster `bp` for SSM purposes, even though that could never be pronounced as a cluster.
# Syllable group types
There are 4 types of syllable group.

| Name | Form                       | Meaning                                                                                                                                                                                                                           |
| ---- | -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| A    | Permitted starting (C)CC-  | Start of a predicate word. Since only a subset of consonant clusters are permitted in A syllable group s, A syllable group clusters are always easy to pronounce independently, or following a final nasal from a previous word.              |
| B    | CV(V)- with no final nasal | Particle or middle of a predicate word.                                                                                                                                                                                           |
| BN   | CV(V)- with final nasal    | Particle or middle of a predicate word.                                                                                                                                                                                           |
| C    | Non-starting CC-           | Optional middle or end of a predicate word. Monosyllabic predicate words do not need a C syllable group but C syllable groups are obligatory at the end of multisyllabic predicate words. Consonant triples are not permitted in C syllables. |
# Allowed word structure
Predicate words can be monosyllabic. In that case, they can only consist of an A syllable group. Otherwise, they must end in a C syllable group. Between the A and final C syllable group, there may be any number of B, BN and C syllable groups. BN groups cannot be followed by C groups.

Any sequence of B and BN between C and A is a sequence of particles, as the A marks the start of a new predicate word and any multisyllabic predicate words must end in C. With full context, it's always possible to know where every predicate word starts and ends, but in the middle of a predicate word, a C syllable isn't necessarily the end of the word. This scheme allows for a reasonable level of flexibility in adapting words from other languages while retaining the advantage of not needing stress or tone.

To put it simply: Any sequence of only B and BN between C and A or A and A are particles. Otherwise, predicates extend from A to the last C followed by only B or BNs before another A or the end of text.

As an example, `ABNBABNBCBCBNBCBBBABABCBNA` is split like so:
1. ABNBABNBCBCBNBCBBB is followed by an A. This means that the last three Bs break off and are separate words. The rest is a grouped by A starting words. `A BN B ABNBCBCBNBC B B B`
2. ABABCBN starts with monosyllabic predicate word followed by a particle. The lack of a C syllable after the first B before the next A means it doesn't "attach" and become part of a multisyllabic predicate. ABC is the next predicate word. It is followed by a particle that must not be part of the word because it's not followed by a C before the next A, which starts the last word.
3. The final breakdown is therefore `ABNBABNBCBCBNBC B B B A B ABC BN A`.

In almost all situations, spaces will be written anyway sparing the reader of the effort of applying these rules. However, a self-segregating morphology is a requirement of all logical languages so that they can be spoken and parsed by a computer without ambiguity.