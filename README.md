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

Matīss Rikters, Rinalds Vīksna, Edison Marrese-Taylor (2024). "[Annotations for Exploring Food Tweets from Multiple Aspects.](https://aclanthology.org/2024.lrec-main.111/)" In Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation ([LREC-COLING 2024](https://lrec-coling-2024.org/)) (2024).

```bibtex
@inproceedings{rikters-etal-2024-annotations-exploring,
    title = "Annotations for Exploring Food Tweets from Multiple Aspects",
    author = "Rikters, Matiss  and
      V{\=\i}ksna, Rinalds  and
      Marrese-Taylor, Edison",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italy",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.111",
    pages = "1233--1238"
}

```

# Other files
