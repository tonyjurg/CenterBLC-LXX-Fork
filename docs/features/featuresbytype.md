Doc4TF pages for [LXX](https://github.com/CenterBLC/LXX) (version 1935)
# Overview features by feature type
Overview by [name](featuresbyname.md), [node type](featuresbynodetype.md), or [data type](featuresbydatatype.md).
## Node

Feature|Datatype|Available on nodes|Description|Examples
---|---|---|---|---
[`abc_order`](abc_order.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |dictionary order|`9434` `7030` `2164` `4638`
[`bol_gloss`](bol_gloss.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |BOL English gloss|`the` `` `and, even, also, namely` `he, she, it, they, them, same`
[`bol_lexeme_dict`](bol_lexeme_dict.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |BOL dictionary form of lemma|`` `ὁ, ἡ, τό` `καί` `αὐτός, -ή, -ό`
[`book`](book.md#readme)|[`String`](featuresbydatatype.md#string)|[`book`](featuresbynodetype.md#book) [`word`](featuresbynodetype.md#word) |book|`1Chr` `1Esdr` `1Kgs` `1Mac`
[`case`](case.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |case|`` `Acc` `Gen` `Nom`
[`chapter`](chapter.md#readme)|[`Integer`](featuresbydatatype.md#integer)|[`chapter`](featuresbynodetype.md#chapter) [`word`](featuresbynodetype.md#word) |chapter|`1` `2` `3` `4`
[`degree`](degree.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |degree|`` `Superlative` `Compar`
[`freq_lemma`](freq_lemma.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |frequency of word in corpus|`88444` `62231` `29396` `14316`
[`g_cons_utf8`](g_cons_utf8.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |word without accents|`ο` `και` `αυτος` `εν`
[`gloss`](gloss.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |gloss|`the` `and; even` `he; him` `in`
[`gn`](gn.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |gender|`` `Masc` `Fem` `Neut`
[`lex`](lex.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |lemma transliteration|`o` `kai` `autos` `en`
[`lex_utf8`](lex_utf8.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |normalized word|`ὁ` `καί` `αὐτός` `ἐν`
[`mood`](mood.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |mood|`` `Ind` `Part` `Infin`
[`morphology`](morphology.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |morphology|`C` `P` `N.NSM` `D`
[`nu`](nu.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |number|`Sing` `` `Plur` `Dual`
[`orig_order`](orig_order.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |original word order|`1` `10` `100` `1000`
[`otype`](otype.md#readme)|[`String`](featuresbydatatype.md#string)||No feature description|No values
[`ps`](ps.md#readme)|[`String`](featuresbydatatype.md#string)|[`book`](featuresbynodetype.md#book) [`word`](featuresbynodetype.md#word) |person|``
[`sp`](sp.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |part of speech|`noun` `verb` `pronoun, article` `conjunction`
[`strongs`](strongs.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |strongs number|`G3588` `G2532` `` `G846`
[`subverse`](subverse.md#readme)|[`String`](featuresbydatatype.md#string)|[`subverse`](featuresbynodetype.md#subverse) [`word`](featuresbynodetype.md#word) |subverse|`` `k` `l` `Jan`
[`tense`](tense.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |tense|`` `Aor` `Pres` `Fut`
[`translit_SBL`](translit_SBL.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |SBL transliteration|`kai` `en` `tou` `autou`
[`verse`](verse.md#readme)|[`Integer`](featuresbydatatype.md#integer)|[`verse`](featuresbynodetype.md#verse) [`subverse`](featuresbynodetype.md#subverse) [`word`](featuresbynodetype.md#word) |verse|`2` `3` `1` `4`
[`voice`](voice.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |voice|`` `Act` `Mid` `Pass`
[`word`](word.md#readme)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |text realized word|`καὶ` `ἐν` `τοῦ` `αὐτοῦ`
## Edge

Feature|Datatype|Available on nodes|Description|Examples
---|---|---|---|---
[`oslots`](oslots.md#readme)|[`String`](featuresbydatatype.md#string)||No feature description|No values


Created on Nov. 03, 2024 using [Doc4TF version 0.5.2 (July 10, 2024)](https://github.com/tonyjurg/Doc4TF/blob/main/CreateFeatureDoc.ipynb)