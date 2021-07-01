
# Start making a syntactic disambiguator

## Sets



Sentence delimiters are the following: "<.>" "<...>" "<!>" "<?>" "<¶>"








### Part-of-Speech
* N = noun
* A = adjective
* Num = numeral
* V = verb
* CC = conjunction
* CS = subjunction
* Adv = adverb
* Pr = preposition
* Po = postposition
* Pron = pronoun
* Interj = interjection


### Numerus
* Sg = Singular
* Pl = Plural
* Sg1 = Singular 1.p.
* Sg2 = Singular 2.p.
* Sg3 = Singular 3.p.
* Pl1 = Plural 1.p.
* Pl2 = Plural 2.p.
* Pl3 = Plural 3.p.
### Cases
* Nom
* Gen
* Acc
* Par
* Ine
* Ill
* Ela
* Ade
* Abe
* All
* Abl
* Ess
* Tra
* Ins
* Com
* SUBJ-CASE = Nom Par



### Types
* Prop = Proper noun
* Interr = Interrogative
* Dem = demonstrative pron
* Rel = Relative pron
Relpronpl "mikkä ja "jokka"
Relpronsg "mikä" ja "joka"
Interrpronpl "kuka" ja "mikä"
* Pers = Personal pron
* Indef = Indef pron

* Inf = Infinitive
* ConNeg = Conjugated as Negative form
* PrfPrc = Perfectum Particip
* Imprt = Imperative
* Act = Active
* Neg = Negation verb




* COMMA = comma
* Foc/kaan = focus clitic -kaan
* Sem/Fem = feminin propernoun
* @CVP = Conjunction or subjunction that conjoins finite verb phrases.
* @CNP = Local conjunction or subjunction.




## Sets with more members

* WORD = all PoS

* NPMOD = these can modify a noun
* NPMODADV = NPMOD plus adverb

* NOT-NPMOD = these cannot modify a noun

* NOT-NPMODADV = these cannot modify a noun, and is not adverb

* QVANT-ADV = e.g. paljon, vähän
* KUNKA = e.g. kunka missä (adverbs that start a sentence)


* S-BOUNDARY = words that start a sentence

* VFIN = finite verb

* COPULAS = olla

* MOD-ASP = auxilaries

* AUX-OR-MAIN = verbs which can be both auxilary and mainverb

* AUX = verbs which can be auxilary

* SV-BOUNDARY = words that start a sentence and finite verb


















































* * *
<small>This (part of) documentation was generated from [../src/cg3/disambiguator.cg3](http://github.com/giellalt/lang-mpj/blob/main/../src/cg3/disambiguator.cg3)</small>