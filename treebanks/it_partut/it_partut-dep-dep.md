---
layout: base
title:  'Statistics of dep in UD_Italian-ParTUT'
udver: '2'
---

## Treebank Statistics: UD_Italian-ParTUT: Relations: `dep`

This relation is universal.

5 nodes (0%) are attached to their parents as `dep`.

3 instances of `dep` (60%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.4.

The following 4 pairs of parts of speech are connected with `dep`: <tt><a href="it_partut-pos-VERB.html">VERB</a></tt>-<tt><a href="it_partut-pos-ADP.html">ADP</a></tt> (2; 40% instances), <tt><a href="it_partut-pos-ADP.html">ADP</a></tt>-<tt><a href="it_partut-pos-NOUN.html">NOUN</a></tt> (1; 20% instances), <tt><a href="it_partut-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_partut-pos-ADP.html">ADP</a></tt> (1; 20% instances), <tt><a href="it_partut-pos-PROPN.html">PROPN</a></tt>-<tt><a href="it_partut-pos-ADP.html">ADP</a></tt> (1; 20% instances).


~~~ conllu
# visual-style 37	bgColor:blue
# visual-style 37	fgColor:white
# visual-style 36	bgColor:blue
# visual-style 36	fgColor:white
# visual-style 36 37 dep	color:blue
1	L'	il	DET	RD	Definite=Def|Number=Sing|PronType=Art	2	det	_	SpaceAfter=No
2	eroe	eroe	NOUN	S	Gender=Masc|Number=Sing	21	nsubj:pass	_	_
3	di	di	ADP	E	_	5	case	_	_
4	il	il	DET	RD	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	5	det	_	_
5	titolo	titolo	NOUN	S	Gender=Masc|Number=Sing	2	nmod	_	_
6	di	di	ADP	E	_	7	case	_	_
7	una	uno	PRON	PI	Gender=Fem|Number=Sing|PronType=Ind	5	nmod	_	_
8	di	di	ADP	E	_	10	case	_	_
9	le	il	DET	RD	Definite=Def|Gender=Fem|Number=Plur|PronType=Art	10	det	_	_
10	tragedie	tragedia	NOUN	S	Gender=Fem|Number=Plur	7	nmod	_	_
11	più	più	ADV	B	_	12	advmod	_	_
12	famose	famoso	ADJ	A	Gender=Fem|Number=Plur	10	amod	_	_
13	di	di	ADP	E	_	14	case	_	_
14	Shakespeare	Shakespeare	PROPN	SP	_	10	nmod	_	SpaceAfter=No
15	,	,	PUNCT	FF	_	7	punct	_	_
16	Amleto	Amleto	PROPN	SP	_	7	appos	_	SpaceAfter=No
17	,	,	PUNCT	FF	_	2	punct	_	_
18	è	essere	AUX	VA	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	21	aux	_	_
19	stato	essere	AUX	VA	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	21	aux:pass	_	_
20	forse	forse	ADV	B	_	21	advmod	_	_
21	trattato	trattare	VERB	V	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	0	root	_	_
22	più	più	ADV	B	_	21	obl	_	_
23	di	di	ADP	E	_	26	case	_	_
24	qualsiasi	qualsiasi	DET	DI	Number=Sing|PronType=Ind	26	det	_	_
25	altro	altro	ADJ	A	Gender=Masc|Number=Sing	26	amod	_	_
26	personaggio	personaggio	NOUN	S	Gender=Masc|Number=Sing	22	obl	_	_
27	shakespeariano	shakespeariano	ADJ	A	Gender=Masc|Number=Sing	26	amod	_	SpaceAfter=No
28	,	,	PUNCT	FF	_	21	punct	_	_
29	specialmente	specialmente	ADV	B	_	34	advmod	_	_
30	per	per	ADP	E	_	34	case	_	_
31	il	il	DET	RD	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	34	det	_	_
32	suo	suo	DET	AP	Gender=Masc|Number=Sing|Poss=Yes|PronType=Prs	34	det:poss	_	_
33	famoso	famoso	ADJ	A	Gender=Masc|Number=Sing	34	amod	_	_
34	monologo	monologo	NOUN	S	Gender=Masc|Number=Sing	21	obl	_	_
35	che	che	PRON	PR	PronType=Rel	36	nsubj	_	_
36	inizia	iniziare	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	34	acl:relcl	_	_
37	con	con	ADP	E	_	36	dep	_	SpaceAfter=No
38	:	:	PUNCT	FC	_	21	punct	_	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 11 dep	color:blue
1	Quando	quando	SCONJ	CS	_	7	mark	_	_
2	la	il	DET	RD	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	4	det	_	_
3	tua	tuo	DET	AP	Gender=Fem|Number=Sing|Poss=Yes|PronType=Prs	4	det:poss	_	_
4	presenza	presenza	NOUN	S	Gender=Fem|Number=Sing	7	nsubj	_	_
5	su	su	ADP	E	_	6	case	_	_
6	Facebook	Facebook	PROPN	SP	_	4	nmod	_	_
7	aumenta	aumentare	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	29	advcl	_	_
8	grazie	grazie	ADP	E	_	15	case	_	SpaceAfter=No
9	,	,	PUNCT	FF	_	8	punct	_	_
10	ad	a	ADP	E	_	11	case	_	_
11	esempio	esempio	NOUN	S	Gender=Masc|Number=Sing	8	dep	_	SpaceAfter=No
12	,	,	PUNCT	FF	_	11	punct	_	_
13	a	a	ADP	E	_	8	fixed	_	_
14	la	il	DET	RD	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	15	det	_	_
15	combinazione	combinazione	NOUN	S	Gender=Fem|Number=Sing	7	obl	_	_
16	di	di	ADP	E	_	17	case	_	_
17	Pagine	Pagine	PROPN	SP	_	15	nmod	_	_
18	o	o	CCONJ	CC	_	19	cc	_	_
19	eventi	evento	NOUN	S	Gender=Masc|Number=Plur	17	conj	_	_
20	Facebook	Facebook	PROPN	SP	_	19	nmod	_	_
21	e	e	CCONJ	CC	_	22	cc	_	_
22	inserzioni	inserzione	NOUN	S	Gender=Fem|Number=Plur	17	conj	_	SpaceAfter=No
23	,	,	PUNCT	FF	_	7	punct	_	_
24	il	il	DET	RD	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	26	det	_	_
25	tuo	tuo	DET	AP	Gender=Masc|Number=Sing|Poss=Yes|PronType=Prs	26	det:poss	_	_
26	messaggio	messaggio	NOUN	S	Gender=Masc|Number=Sing	29	nsubj	_	_
27	pubblicitario	pubblicitario	ADJ	A	Gender=Masc|Number=Sing	26	amod	_	_
28	può	potere	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	29	aux	_	_
29	trasformar	trasformare	VERB	V	VerbForm=Inf	0	root	_	_
30	si	si	PRON	PC	Clitic=Yes|Person=3|PronType=Prs	29	expl	_	_
31	in	in	ADP	E	_	36	case	_	_
32	un	uno	DET	RI	Definite=Ind|Gender=Masc|Number=Sing|PronType=Art	36	det	_	_
33	vero	vero	ADJ	A	Gender=Masc|Number=Sing	36	amod	_	_
34	e	e	CCONJ	CC	_	35	cc	_	_
35	proprio	proprio	ADJ	A	Gender=Masc|Number=Sing	33	conj	_	_
36	passa-parola	passa-parola	NOUN	S	Gender=Masc	29	obl	_	SpaceAfter=No
37	,	,	PUNCT	FF	_	29	punct	_	_
38	da	da	ADP	E	_	40	case	_	_
39	il	il	DET	RD	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	40	det	_	_
40	momento	momento	NOUN	S	Gender=Masc|Number=Sing	29	obl	_	_
41	che	che	SCONJ	CS	_	57	mark	_	_
42	gli	il	DET	RD	Definite=Def|Gender=Masc|Number=Plur|PronType=Art	43	det	_	_
43	amici	amico	NOUN	S	Gender=Masc|Number=Plur	57	nsubj	_	_
44	di	di	ADP	E	_	46	case	_	_
45	gli	il	DET	RD	Definite=Def|Gender=Masc|Number=Plur|PronType=Art	46	det	_	_
46	utenti	utente	NOUN	S	Number=Plur	43	nmod	_	_
47	che	che	PRON	PR	PronType=Rel	50	nsubj	_	_
48	hanno	avere	AUX	VA	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	50	aux	_	_
49	già	già	ADV	B	_	50	advmod	_	_
50	stabilito	stabilire	VERB	V	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	46	acl:relcl	_	_
51	una	uno	DET	RI	Definite=Ind|Gender=Fem|Number=Sing|PronType=Art	52	det	_	_
52	connessione	connessione	NOUN	S	Gender=Fem|Number=Sing	50	obj	_	_
53	con	con	ADP	E	_	56	case	_	_
54	i	il	DET	RD	Definite=Def|Gender=Masc|Number=Plur|PronType=Art	56	det	_	_
55	tuoi	tuo	DET	AP	Gender=Masc|Number=Plur|Poss=Yes|PronType=Prs	56	det:poss	_	_
56	prodotti	prodotto	NOUN	S	Gender=Masc|Number=Plur	52	nmod	_	_
57	visualizzeranno	visualizzare	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Fut|VerbForm=Fin	40	acl	_	_
58	i	il	DET	RD	Definite=Def|Gender=Masc|Number=Plur|PronType=Art	60	det	_	_
59	tuoi	tuo	DET	AP	Gender=Masc|Number=Plur|Poss=Yes|PronType=Prs	60	det:poss	_	_
60	contenuti	contenuto	NOUN	S	Gender=Masc|Number=Plur	57	obj	_	SpaceAfter=No
61	.	.	PUNCT	FS	_	29	punct	_	_

~~~


~~~ conllu
# visual-style 22	bgColor:blue
# visual-style 22	fgColor:white
# visual-style 21	bgColor:blue
# visual-style 21	fgColor:white
# visual-style 21 22 dep	color:blue
1	Conformemente	conformemente	ADV	B	_	15	advmod	_	_
2	anche	anche	ADV	B	_	5	advmod	_	_
3	a	a	ADP	E	_	5	case	_	_
4	la	il	DET	RD	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	5	det	_	_
5	raccomandazione	raccomandazione	NOUN	S	Gender=Fem|Number=Sing	1	obl	_	_
6	di	di	ADP	E	_	8	case	_	_
7	il	il	DET	RD	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	8	det	_	_
8	valutatore	valutatore	NOUN	S	Gender=Masc|Number=Sing	5	nmod	_	_
9	di	di	ADP	E	_	11	case	_	_
10	il	il	DET	RD	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	11	det	_	_
11	programma	programma	NOUN	S	Gender=Masc|Number=Sing	8	nmod	_	_
12	Pericle	Pericle	PROPN	SP	_	11	nmod	_	SpaceAfter=No
13	,	,	PUNCT	FF	_	1	punct	_	_
14	è	essere	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	15	cop	_	_
15	opportuno	opportuno	ADJ	A	Gender=Masc|Number=Sing	0	root	_	_
16	estendere	estendere	VERB	V	VerbForm=Inf	15	csubj	_	_
17	tale	tale	DET	DD	Number=Sing|PronType=Dem	18	det	_	_
18	programma	programma	NOUN	S	Gender=Masc|Number=Sing	16	obj	_	_
19	vista	vedere	VERB	V	Gender=Fem|Number=Sing|Tense=Past|VerbForm=Part	15	advcl	_	_
20	la	il	DET	RD	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	21	det	_	_
21	necessità	necessità	NOUN	S	Gender=Fem	19	nsubj:pass	_	_
22	di	di	ADP	E	_	21	dep	_	SpaceAfter=No
23	:	:	PUNCT	FC	_	15	punct	_	_

~~~


