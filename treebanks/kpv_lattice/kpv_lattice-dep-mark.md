---
layout: base
title:  'Statistics of mark in UD_Komi_Zyrian-Lattice'
udver: '2'
---

## Treebank Statistics: UD_Komi_Zyrian-Lattice: Relations: `mark`

This relation is universal.

36 nodes (2%) are attached to their parents as `mark`.

32 instances of `mark` (89%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.75.

The following 5 pairs of parts of speech are connected with `mark`: <tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_lattice-pos-SCONJ.html">SCONJ</a></tt> (28; 78% instances), <tt><a href="kpv_lattice-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kpv_lattice-pos-SCONJ.html">SCONJ</a></tt> (3; 8% instances), <tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_lattice-pos-CCONJ.html">CCONJ</a></tt> (3; 8% instances), <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-SCONJ.html">SCONJ</a></tt> (1; 3% instances), <tt><a href="kpv_lattice-pos-PRON.html">PRON</a></tt>-<tt><a href="kpv_lattice-pos-SCONJ.html">SCONJ</a></tt> (1; 3% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 mark	color:blue
1	Меным	ме	PRON	Pron	Case=Dat|Number=Sing|Person=1|PronType=Prs	2	obl	_	_
2	кажитчӧ	кажитчыны	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	SpaceAfter=No
3	,	,	PUNCT	CLB	_	2	punct	_	_
4	мый	мый	SCONJ	CS	_	5	mark	_	_
5	зэрӧ	зэрны	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	2	csubj	_	SpaceAfter=No
6	.	_	PUNCT	CLB	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 1 mark	color:blue
1	Кӧть	кӧть	SCONJ	CS	_	5	mark	_	_
2	луныс	лун	NOUN	N	Case=Nom|Number=Sing|Number[psor]=Sing|Person[psor]=3	5	nsubj	_	_
3	вӧлі	вӧвны	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	5	cop	_	_
4	зэв	зэв	ADV	Adv	_	5	advmod	_	_
5	мича	мича	ADJ	A	Case=Nom|Number=Sing	0	root	_	SpaceAfter=No
6	.	.	PUNCT	CLB	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 5 mark	color:blue
1	Тайӧ	тайӧ	PRON	Pron	Case=Nom|Number=Sing|PronType=Dem	3	det	_	_
2	Петрсянь	Петр	NOUN	N	Case=Egr|Number=Sing	3	obl	_	_
3	письмӧ	письмӧ	NOUN	N	Case=Nom|Number=Sing	0	root	_	SpaceAfter=No
4	,	,	PUNCT	CLB	_	5	punct	_	_
5	да	да	CCONJ	CC	_	8	mark	_	_
6	сійӧс	сійӧ	PRON	Pron	Case=Acc|Number=Sing|Person=3|PronType=Prs	8	obj	_	_
7	тӧрыт	тӧрыт	ADV	Adv	_	8	advmod	_	_
8	вайисны	вайны	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	3	advcl	_	SpaceAfter=No
9	.	.	PUNCT	CLB	_	3	punct	_	_

~~~


