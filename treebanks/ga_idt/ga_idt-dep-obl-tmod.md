---
layout: base
title:  'Statistics of obl:tmod in UD_Irish-IDT'
udver: '2'
---

## Treebank Statistics: UD_Irish-IDT: Relations: `obl:tmod`

This relation is a language-specific subtype of <tt><a href="ga_idt-dep-obl.html">obl</a></tt>.
There are also 1 other language-specific subtypes of `obl`: <tt><a href="ga_idt-dep-obl-prep.html">obl:prep</a></tt>.

193 nodes (0%) are attached to their parents as `obl:tmod`.

148 instances of `obl:tmod` (77%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.81347150259067.

The following 15 pairs of parts of speech are connected with `obl:tmod`: <tt><a href="ga_idt-pos-VERB.html">VERB</a></tt>-<tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt> (117; 61% instances), <tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt> (29; 15% instances), <tt><a href="ga_idt-pos-VERB.html">VERB</a></tt>-<tt><a href="ga_idt-pos-NUM.html">NUM</a></tt> (13; 7% instances), <tt><a href="ga_idt-pos-VERB.html">VERB</a></tt>-<tt><a href="ga_idt-pos-PART.html">PART</a></tt> (11; 6% instances), <tt><a href="ga_idt-pos-VERB.html">VERB</a></tt>-<tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt> (5; 3% instances), <tt><a href="ga_idt-pos-VERB.html">VERB</a></tt>-<tt><a href="ga_idt-pos-ADV.html">ADV</a></tt> (4; 2% instances), <tt><a href="ga_idt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt> (3; 2% instances), <tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ga_idt-pos-NUM.html">NUM</a></tt> (3; 2% instances), <tt><a href="ga_idt-pos-ADV.html">ADV</a></tt>-<tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt> (2; 1% instances), <tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ga_idt-pos-ADV.html">ADV</a></tt> (1; 1% instances), <tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ga_idt-pos-X.html">X</a></tt> (1; 1% instances), <tt><a href="ga_idt-pos-NUM.html">NUM</a></tt>-<tt><a href="ga_idt-pos-NUM.html">NUM</a></tt> (1; 1% instances), <tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt> (1; 1% instances), <tt><a href="ga_idt-pos-VERB.html">VERB</a></tt>-<tt><a href="ga_idt-pos-ADJ.html">ADJ</a></tt> (1; 1% instances), <tt><a href="ga_idt-pos-VERB.html">VERB</a></tt>-<tt><a href="ga_idt-pos-ADP.html">ADP</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 5 obl:tmod	color:blue
1	Tháinig	tar	VERB	VI	Form=Len|Mood=Ind|Tense=Past	0	root	_	_
2	sé	sé	PRON	Pers	Gender=Masc|Number=Sing|Person=3	1	nsubj	_	_
3	abhaile	abhaile	ADV	Dir	_	1	advmod	_	_
4	an	an	DET	Art	Definite=Def|Number=Sing|PronType=Art	5	det	_	_
5	oíche	oíche	NOUN	Noun	Case=NomAcc|Definite=Def|Gender=Fem|Number=Sing	1	obl:tmod	_	_
6	sin	sin	DET	Det	PronType=Dem	5	det	_	SpaceAfter=No
7	.	.	PUNCT	.	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 obl:tmod	color:blue
1	Agus	agus	SCONJ	Subord	_	2	mark	_	_
2	dul	dul	NOUN	Noun	VerbForm=Inf	0	root	_	_
3	isteach	isteach	ADV	Dir	_	2	advmod	_	_
4	chuig	chuig	ADP	Simp	_	6	case	_	_
5	an	an	DET	Art	Definite=Def|Number=Sing|PronType=Art	6	det	_	_
6	obair	obair	NOUN	Noun	Gender=Fem|Number=Sing	2	nmod	_	_
7	Dé	Dé	NOUN	Subst	Number=Sing	6	obl:tmod	_	_
8	Sathairn	Satharn	NOUN	Noun	Case=Gen|Gender=Masc|Number=Sing	7	flat	_	_
9	chomh	chomh	ADV	Its	_	10	advmod	_	_
10	maith	maith	ADJ	Adj	Degree=Pos	2	amod	_	SpaceAfter=No
11	.	.	PUNCT	.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 7 obl:tmod	color:blue
1	Thugamar	tabhair	VERB	VTI	_	0	root	_	_
2	aghaidh	aghaidh	NOUN	Noun	_	1	obj	_	_
3	ar	ar	ADP	Simp	_	5	case	_	_
4	an	an	DET	Art	PronType=Art	5	det	_	_
5	mbialann	bialann	NOUN	Noun	_	1	obl	_	_
6	ag	ag	ADP	Simp	_	7	case	_	_
7	3.00	3.00	NUM	Num	_	1	obl:tmod	_	_
8	pm	pm	X	Abr	Abbr=Yes	7	flat	_	SpaceAfter=No
9	.	.	PUNCT	.	_	1	punct	_	_

~~~


