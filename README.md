# Similarity & Association 

For a clear definition of semantic similarity and association, refer to 

Lofi, C. Measuring Semantic Similarity and Relatedness with Distributional and Knowledge-based Approaches. Information and Media Technologies 10, 493–501 (2015).

# Gold Standards
## Semantic Similarity
- French SIMLEX-999: Modified from [siabar/Multilingual_Wordpairs](https://github.com/siabar/Multilingual_Wordpairs)

    Deleted duplicated word pairs.
    Some article removal, adjustment of pronominal verbs.
    Unapproriate translations are redone with score copied from [original](https://fh295.github.io/simlex.html) SIMLEX-999 standard.

## Semantic Association
- French WS Relatedness: Translation by [siabar/Multilingual_Wordpairs](https://github.com/siabar/Multilingual_Wordpairs), Extraction of relevant word pairs according to WordSimilarity 353 [WS-353](http://www.cs.technion.ac.il/~gabr/resources/data/wordsim353/)

    Some translations are redone.

# Part Of Speech Tagging

Lemmatizer and POS Tagger: [LEFFF](https://github.com/ClaudeCoulombe/FrenchLefffLemmatizer)

In principle the word pairs should have the same POS tags. 

POS tags are categorized into noun (n), verb (v), adjective (a), adverb (b).