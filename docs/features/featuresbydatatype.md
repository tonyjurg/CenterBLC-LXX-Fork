Doc4TF pages for [LXX](https://github.com/CenterBLC/LXX) (version 1935)
# Overview features by data type
Overview by [name](featuresbyname.md), [node type](featuresbynodetype.md), or [feature type](featuresbytype.md).
## Integer

Feature|Featuretype|Available on nodes|Description|Examples
---|---|---|---|---
[`chapter`](chapter.md#readme)|[`Node`](featuresbytype.md#node)|[`chapter`](featuresbynodetype.md#chapter) [`word`](featuresbynodetype.md#word) |chapter|`1` `2` `3` `4`
[`verse`](verse.md#readme)|[`Node`](featuresbytype.md#node)|[`verse`](featuresbynodetype.md#verse) [`subverse`](featuresbynodetype.md#subverse) [`word`](featuresbynodetype.md#word) |verse|`2` `3` `1` `4`
## String

Feature|Featuretype|Available on nodes|Description|Examples
---|---|---|---|---
[`abc_order`](abc_order.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |dictionary order|`9434` `7030` `2164` `4638`
[`bol_gloss`](bol_gloss.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |BOL English gloss|`the` `` `and, even, also, namely` `he, she, it, they, them, same`
[`bol_lexeme_dict`](bol_lexeme_dict.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |BOL dictionary form of lemma|`` `ὁ, ἡ, τό` `καί` `αὐτός, -ή, -ό`
[`book`](book.md#readme)|[`Node`](featuresbytype.md#node)|[`book`](featuresbynodetype.md#book) [`word`](featuresbynodetype.md#word) |book|`1Chr` `1Esdr` `1Kgs` `1Mac`
[`case`](case.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |case|`` `Acc` `Gen` `Nom`
[`degree`](degree.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |degree|`` `Superlative` `Compar`
[`freq_lemma`](freq_lemma.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |frequency of word in corpus|`88444` `62231` `29396` `14316`
[`g_cons_utf8`](g_cons_utf8.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |word without accents|`ο` `και` `αυτος` `εν`
[`gloss`](gloss.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |gloss|`the` `and; even` `he; him` `in`
[`gn`](gn.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |gender|`` `Masc` `Fem` `Neut`
[`lex`](lex.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |lemma transliteration|`o` `kai` `autos` `en`
[`lex_utf8`](lex_utf8.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |normalized word|`ὁ` `καί` `αὐτός` `ἐν`
[`mood`](mood.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |mood|`` `Ind` `Part` `Infin`
[`morphology`](morphology.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |morphology|`C` `P` `N.NSM` `D`
[`nu`](nu.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |number|`Sing` `` `Plur` `Dual`
[`orig_order`](orig_order.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |original word order|`1` `10` `100` `1000`
[`oslots`](oslots.md#readme)|[`Edge`](featuresbytype.md#edge)||No feature description|No values
[`otype`](otype.md#readme)|[`Node`](featuresbytype.md#node)||No feature description|No values
[`ps`](ps.md#readme)|[`Node`](featuresbytype.md#node)|[`book`](featuresbynodetype.md#book) [`word`](featuresbynodetype.md#word) |person|``
[`sp`](sp.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |part of speech|`noun` `verb` `pronoun, article` `conjunction`
[`strongs`](strongs.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |strongs number|`G3588` `G2532` `` `G846`
[`subverse`](subverse.md#readme)|[`Node`](featuresbytype.md#node)|[`subverse`](featuresbynodetype.md#subverse) [`word`](featuresbynodetype.md#word) |subverse|`` `k` `l` `Jan`
[`tense`](tense.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |tense|`` `Aor` `Pres` `Fut`
[`translit_SBL`](translit_SBL.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |SBL transliteration|`kai` `en` `tou` `autou`
[`voice`](voice.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |voice|`` `Act` `Mid` `Pass`
[`word`](word.md#readme)|[`Node`](featuresbytype.md#node)|[`word`](featuresbynodetype.md#word) |text realized word|`καὶ` `ἐν` `τοῦ` `αὐτοῦ`


Created on Nov. 03, 2024 using [Doc4TF version 0.5.2 (July 10, 2024)](https://github.com/tonyjurg/Doc4TF/blob/main/CreateFeatureDoc.ipynb)