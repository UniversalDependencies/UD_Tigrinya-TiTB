# Summary

TiTB is a manually annotated Universal Dependencies treebank of Tigrinya, an Ethio-Semitic language spoken in Eritrea and northern Ethiopia. The sentences were constructed to cover the main morphosyntactic structures of Tigrinya and to illustrate the constructions described in the UD guidelines.

# Introduction

The Tigrinya Treebank (TiTB) is the first Universal Dependencies treebank of Tigrinya. It contains 221 sentences (1,287 tokens, 1,598 syntactic words) written in the Ge'ez script (called Ethiopic in Unicode).

The treebank consists of reference sentences constructed by the annotators. They were designed for two purposes: to cover the main morphosyntactic structures of Tigrinya, and to capture the syntactic constructions described in the UD guidelines, so that the treebank shows how each of these constructions is annotated in Tigrinya. The sentences therefore serve both as data and as a practical reference for the Tigrinya annotation guidelines.

Most sentences were first segmented and tagged automatically with a morphological analyser (HornMorpho), and then corrected and annotated manually in Arborator-Grew; the remaining sentences were annotated manually. The annotation covers word segmentation, lemmas, universal part-of-speech tags, morphological features and basic dependency relations.

Tokenization and word segmentation: Tigrinya orthographic words often contain several syntactic words. Prepositions written as prefixes, possessive suffixes, subordinating prefixes, negation affixes, the coordinating suffix -ን and enclitics are split off and represented as multiword tokens in the CoNLL-U files. Subject and object agreement and other verb morphology are not segmented.

Each surface token has a transliteration in the MISC column (Translit).

Detailed annotation guidelines are available in the Tigrinya UD documentation: https://universaldependencies.org/ti/index.html

# Acknowledgments

The work of Nazareth Amlesom Kifle on this treebank was carried out as part of her research time funded by Østfold University College (Høgskolen i Østfold), Norway.

## References

* Nazareth Amlesom Kifle. 2011. *Tigrinya Applicatives in Lexical-Functional Grammar*. PhD dissertation, University of Bergen. https://bora.uib.no/bora-xmlui/handle/1956/5730
* Michael Gasser. 2011. HornMorpho: a system for morphological processing of Amharic, Oromo, and Tigrinya. In *Proceedings of the Conference on Human Language Technology for Development*, pages 94–99, Alexandria, Egypt. Bibliotheca Alexandrina.
* Michael Gasser and Nazareth Amlesom Kifle. 2025. UD Annotation of Experience Clauses in Tigrinya. In *Proceedings of the Eighth International Conference on Dependency Linguistics (Depling, SyntaxFest 2025)*, pages 120–129, Ljubljana, Slovenia. Association for Computational Linguistics. https://aclanthology.org/2025.depling-1.12/
* Nazareth Amlesom Kifle and Michael Gasser. 2026. Clefting and beyond in Tigrinya. In *Proceedings of the Ninth Workshop on Universal Dependencies (UDW 2026)*, pages 54–59, Palma de Mallorca, Spain. ELRA Language Resources Association (ELRA). https://aclanthology.org/2026.udw-1.3/

# Changelog

* [TODO: release date] [TODO: release number]
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: [TODO: release number, e.g. UD v2.19]
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: grammar-examples
Lemmas: automatic with corrections
UPOS: automatic with corrections
XPOS: not available
Features: automatic with corrections
Relations: manual native
Contributors: Kifle, Nazareth Amlesom; Gasser, Michael
Contributing: here
Contact: nazareth.a.kifle@hiof.no, onlyskybl@gmail.com
===============================================================================
</pre>
