---
layout: relation
title: 'conj'
shortdef: 'conjunct'
udver: '2'
---

The conjunct relation holds between coordinated elements. We treat
coordination asymmetrically: The head of the relation is the first
conjunct and other conjuncts depend on it via the `conj` relation.

~~~ sdparse
1500 euros par an et par enfant \n 1500 euros per child and per year
conj(an, enfant)
~~~

~~~ sdparse
Une seconde d' hésitation , d' inattention ou de retard  \n A second of hesitation, carelessness or delay
conj(hésitation, inattention)
conj(hésitation, retard)
~~~

FrenchSpoken does not use the simple `conj` relation. Three different subrelations are used instead: [conj:appos](), [conj:coord]() and [conj:dicto]().

