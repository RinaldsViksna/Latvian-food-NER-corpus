# Latvian Twitter NER Sub-corpus
- **tweets-test.conll** contains 744 tweets split into conll-2003 like format and marked with 4 entity classes: PER, LOC, ORG, MISC mostly following MUC-7 guidelines. This corpus was annotated with reduced entity set as Balanced State-of-the-Art Multilayer Corpus for NLU (https://github.com/LUMII-AILab/FullStack/tree/master/NamedEntities) by converting 9-entity tagset to 4-entity tagset: keeping PERSON and ORGANIZATION, joining LOCATION and GPE into LOCATION and joining the rest of classes into MISC category. Annotation done by 2 annotators with third resolving conflicts.
Corpus contains:
 188 MISC entities
 99 LOC entities
 55 PER entitites
 68 ORG entities
 
 
- **ltec-sentiment-annotated-test.conll** - 
- **ltec-sentiment-annotated-test.tsv**
- **ltec-sentiment-annotated-test.xmi**
These 3 files contain the same content in 3 formats. Contents is the same as above, but TIME is not joined into MISC, and has all the food entities annotated.

Thanks to https://github.com/M4t1ss for providing tweets and help with annotation. Source with more tweets here: 
https://github.com/Usprogis/Latvian-Twitter-Eater-Corpus/tree/master/sub-corpora/sentiment-analysis

 Publications
---------

If you use this corpus or scripts, please cite the following paper:


# Other files
