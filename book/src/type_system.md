# Type system

Hkaltui distinguishes three different types of arguments for predicates. These are only differentiated by how many "holes" or "focus particles" they have. The three types are:

| Type  | Number of holes  | Description |
| ----- | ---------------- | ----------- |
|Proposition| 0                | Used for nested clauses in sentences, like those in English that start with "that", such as "I didn't know **that it was raining**" |
|Property   | 1                | Used for describing properties such as "redness" or "being talked to". Also used for concrete nouns, as those also have 1 hole. |
|Relationship| 2              | Used for relationships. These have two holes, and word order swapping is needed if the relationship needs to be reversed, if applicable. |

# Definition format

Merging properties and "concrete" nouns allows for every type to marked on root words without needing that many. Whether a property noun is a property or concrete is entirely determined by the verb governing it. Since this would lead to many definitions needing to say "The thing which has property _ is ...", there will be a short notation for this of using C rather than the hole number (0) after the case.

Examples:

* `SC is a cat`
* `SC gives OC to IC`
* `SC has property O1`