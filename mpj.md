Noun inflection
The Wangkajunga language nouns inflect in cases.

















temporal and spatial nouns - have a limited set of specific case endings, and do not have pronoun
clitics





demonstrative lexicons











Proper noun inflection
The Wangkajunga language proper nouns inflect in the same cases as regular
nouns, but with a colon (':') as separator.








# Symbol affixes





Adjective inflection
The Wangkajunga language adjectives compare.



Verb inflection
The Wangkajunga language verbs inflect in persons.




lexicon Verb_prefixes (above) -> lexicon Verb_stems (separate file) -> following lexicons, depending on
relevant conjugation:


















is positioning of +V here okay? or better with separate lexicon / before prefixes?























=================================== !
The Wangkajunga morphophonological/twolc rules file !
=================================== !















* *pilyurr%>^P^A*
* *pilyurr%>pa*












INTRODUCTION TO MORPHOLOGICAL ANALYSER OF Wangkajunga LANGUAGE.


 # Definitions for Multichar_Symbols

## Analysis symbols
The morphological analyses of wordforms for the Wangkajunga
language are presented in this system in terms of the following symbols.
(It is highly suggested to follow existing standards when adding new tags).

The parts-of-speech are:
 *  +N  
 *  +A  
 *  +Adv  
 *  +V  
 *  +Pron  
 *  +CS  
 *  +CC  
 *  +Adp  
 *  +Po  
 *  +Pr  
 *  +Interj  
 *  +Pcle  
 *  +Num   

Transitivity:
 *  +IV    Intransitive (i.e. with Abs)
 *  +TV   Transitive (i.e. with Erg + Abs)

 * +Abs  
 * +Erg  
 * +Dat  

 * +Abl  
 * +Gen  
 * +Loc  
 * +Perl  
 * +All  
 * +Avoid  







Verb affixes
tense inflections 

irrealis tense inflections ! TODO: work on tags. Irrealis/Admon? But two separate morphophonemes

affixes following from irrealis inflections

serial and nominalised inflections

verb derivation affixes

temporal relative affix

verb directional affixes


verb post-inflection affixes

verb compounds

Reduplication

Clitics

Demonstrative affixes TODO: change tag names



Flag diacritics for verb conjugations

Flag diacritics for noun cases
DCASE = derivational case


SCASE = semantic case

Flag diacritics for clitics (to ensure the same clitic does not appear twice on a single word)
CLT = clitic


Flag diacritics for pronoun clitics (to ensure the same case is not used twice within a cluster).
CLCASE = pronoun clitic case TODO: consider changing name to PCCASE



















integrate the things to come:



The parts of speech are further split up into:

The Usage extents are marked using following tags:

The nominals are inflected in the following Case and Number

The possession is marked as such:
The comparative forms are:
Numerals are classified under:

Verb moods are:

Other verb forms are

 * +Symbol = independent symbols in the text stream, like £, €, ©
Special symbols are classified with:
The verbs are syntactically split according to transitivity:
Special multiword units are analysed with:
Non-dictionary words can be recognised with:

Question and Focus particles:

Semantics are classified with


Derivations are classified under the morphophonetic form of the suffix, the
source and target part-of-speech.

Morphophonology

## Flag diacritics
We have manually optimised the structure of our lexicon using following
flag diacritics to restrict morhpological combinatorics - only allow compounds
with verbs if the verb is further derived into a noun again:
 |  @P.NeedNoun.ON@ | (Dis)allow compounds with verbs unless nominalised
 |  @D.NeedNoun.ON@ | (Dis)allow compounds with verbs unless nominalised
 |  @C.NeedNoun@ | (Dis)allow compounds with verbs unless nominalised

For languages that allow compounding, the following flag diacritics are needed
to control position-based compounding restrictions for nominals. Their use is
handled automatically if combined with +CmpN/xxx tags. If not used, they will
do no harm.
 |  @P.CmpFrst.FALSE@ | Require that words tagged as such only appear first
 |  @D.CmpPref.TRUE@ | Block such words from entering ENDLEX
 |  @P.CmpPref.FALSE@ | Block these words from making further compounds
 |  @D.CmpLast.TRUE@ | Block such words from entering R
 |  @D.CmpNone.TRUE@ | Combines with the next tag to prohibit compounding
 |  @U.CmpNone.FALSE@ | Combines with the prev tag to prohibit compounding
 |  @P.CmpOnly.TRUE@ | Sets a flag to indicate that the word has passed R
 |  @D.CmpOnly.FALSE@ | Disallow words coming directly from root.

Use the following flag diacritics to control downcasing of derived proper
nouns (e.g. Finnish Pariisi -> pariisilainen). See e.g. North Sámi for how to use
these flags. There exists a ready-made regex that will do the actual down-casing
given the proper use of these flags.
 |  @U.Cap.Obl@ | Allowing downcasing of derived names: deatnulasj.
 |  @U.Cap.Opt@ | Allowing downcasing of derived names: deatnulasj.

The word forms in Wangkajunga language start from the lexeme roots of basic
word classes, or optionally from prefixes:

Nouns
Nouns in the Wangkajunga language are things.





Prefixes
Prefixes in the Wangkajunga language are bound to beginning of other words.



Pronouns
Pronouns in the Wangkajunga language are references to things.



Adjectives
Adjectives in the Wangkajunga language describe things.


Verbs
Verbs in the Wangkajunga language are actions.








Numerals
Numerals in the Wangkajunga language are numbers.






Pronoun clitics (quite long)



































































% komma% :,      Root ;
% tjuohkkis% :%. Root ;
% kolon% :%:     Root ;
% sárggis% :%-   Root ; 
% násti% :%*     Root ; 




We describe here how abbreviations are in Wangkajunga are read out, e.g.
for text-to-speech systems.

For example:

 * s.:syntynyt # ;  
 * os.:omaa% sukua # ;  
 * v.:vuosi # ;  
 * v.:vuonna # ;  
 * esim.:esimerkki # ; 
 * esim.:esimerkiksi # ; 


