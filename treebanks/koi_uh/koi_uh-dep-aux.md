---
layout: base
title:  'Statistics of aux in UD_Komi_Permyak-UH'
udver: '2'
---

## Treebank Statistics: UD_Komi_Permyak-UH: Relations: `aux`

This relation is universal.
There are 2 language-specific subtypes of `aux`: <tt><a href="koi_uh-dep-aux-cnd.html">aux:cnd</a></tt>, <tt><a href="koi_uh-dep-aux-neg.html">aux:neg</a></tt>.

5 nodes (1%) are attached to their parents as `aux`.

5 instances of `aux` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.6.

The following 1 pairs of parts of speech are connected with `aux`: <tt><a href="koi_uh-pos-VERB.html">VERB</a></tt>-<tt><a href="koi_uh-pos-AUX.html">AUX</a></tt> (5; 100% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 aux	color:blue
1	Эз	оз	AUX	_	Person=3|Polarity=Neg|Tense=Past|VerbType=Aux	3	aux:neg	_	GTtags=Prt1,3
2	позь	позьны	AUX	_	Connegative=Yes	3	aux	_	GTtags=ConNeg
3	бӧрйыны	бӧрйыны	VERB	_	VerbForm=Inf	0	root	_	GTtags=Inf
4	не	не	CCONJ	Polarity=Neg	_	6	cc:preconj	_	_
5	Питер	Питер	PROPN	_	Animacy=Hum|Case=Nom|Number=Sing	3	obj	_	GTtags=Prop,Sg,Nom
6	Смитӧс	Смит	PROPN	_	Animacy=Hum|Case=Acc|Number=Sing	5	flat:name	_	GTtags=Prop,Sg,Acc|SpaceAfter=No
7	,	,	PUNCT	CLB	_	10	punct	_	_
8	не	не	CCONJ	Polarity=Neg	_	10	cc	_	_
9	Мери	Мери	PROPN	_	Animacy=Hum|Case=Nom|Number=Sing	6	conj	_	GTtags=Prop,Sg,Nom
10	Браунӧс	Браун	PROPN	_	Animacy=Hum|Case=Acc|Number=Sing	9	flat:name	_	GTtags=Prop,Sg,Acc|SpaceAfter=No
11	.	.	PUNCT	CLB	_	3	punct	_	_

~~~


