![WikiDBs logo](WikiDBs.png)
![WikiDBs authors](authors.png)

# WikiDBs: A corpus of 100,000 real-world databases

WikiDBs is a large-scale corpus containing 100,000 relational databases from various domains. WikiDBs is based on data from [Wikidata](https://www.wikidata.org/). Each database consists of multiple tables that are connected by foreign keys. 

With WikiDBs, we aim to support the development of foundation models for tabular data and relational databases, as existing work on tabular representation learning so far mostly focuses on individual tables. 
WikiDBs contains the database schemas, as well as table contents.

## Download WikiDBs
In WikiDBs, the database tables are provided as CSV files, and each database schema as JSON. The 100,000 databases are available in five splits, containing 20k databases each. In total, around 165 GB of disk space are needed for the full corpus.

Download WikiDBs via Zenodo here: [https://zenodo.org/record/11559814](https://zenodo.org/record/11559814).

Datasheet: [WikiDBs_Datasheet.pdf](WikiDBs_Datasheet.pdf)

## License Information
We release WikiDBs under the [Creative Commons Attributions 4.0 International](https://creativecommons.org/licenses/by/4.0/) license (CC BY 4.0). Information regarding the license of data in Wikidata can be found [on this page](https://www.wikidata.org/wiki/Wikidata:Licensing).

## Publication
WikiDBs was published as a Spotlight paper at the Dataset & Benchmarks track at NeurIPS 2024. 

Read our paper: [https://openreview.net/pdf?id=abXaOcvujs](https://openreview.net/pdf?id=abXaOcvujs)

```
@inproceedings{vogel2024wikidbs,
  title={WikiDBs: A Large-Scale Corpus Of Relational Databases From Wikidata},
  author={Vogel, Liane and Bodensohn, Jan-Micha and Binnig, Carsten},
  booktitle={The Thirty-eight Conference on Neural Information Processing Systems Datasets and Benchmarks Track},
  year = {2024}
  url={https://openreview.net/pdf?id=abXaOcvujs}
}

```

## Adapt WikiDBs to your needs
The code of WikiDBs can be found on GitHub here: [https://github.com/DataManagementLab/wikidbs-public](https://github.com/DataManagementLab/wikidbs-public)

You can adapt WikiDBs depending on your use case, e.g. by creating databases with particular data characteristics or in other languages that are included in Wikidata.

## 10k Version of WikiDBs
A preliminary version of WikiDBs ([WikiDBs 10k](https://ceur-ws.org/Vol-3462/TADA3.pdf)) was published at the first TaDA workshop at VLDB in 2023. 
The dataset of 10,000 databases is available via Zenodo here: [https://zenodo.org/record/8227452](https://zenodo.org/record/8227452).

To give a first impression of WikiDBs 10k, we offer a couple of sample databases for download here: [Sample_WikiDBs.zip](data/Sample_WikiDBs.zip)

```
@inproceedings{Vogel2023WikiDBs,
  title        = {WikiDBs: {A} Corpus of Relational Databases From Wikidata},
  author       = {Liane Vogel and Carsten Binnig},
  booktitle    = {Joint Proceedings of Workshops at the 49th International Conference
                  on Very Large Data Bases {(VLDB} 2023), Vancouver, Canada, August
                  28 - September 1, 2023},
  series       = {CEUR Workshop Proceedings},
  volume       = {3462},
  publisher    = {CEUR-WS.org},
  url          = {https://ceur-ws.org/Vol-3462/TADA3.pdf},
  year         = {2023},
}
```

# Acknowledgments
We thank Till Döhmen and Madelon Hulsebos for generously providing the table statistics from their [GitSchemas dataset](https://github.com/tdoehmen/gitschemas).
This work has been supported by the BMBF and the state of Hesse as part of the NHR Program and the HMWK cluster project 3AI. It was also partially funded by the LOEWE Spitzenprofessur of the state of Hesse. We also thank DFKI Darmstadt and hessian.AI for their support.
