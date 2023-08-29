# WikiDBs: A Corpus Of Relational Databases From Wikidata

WikiDBs is an open-source corpus of relational databases based on data from [Wikidata](https://www.wikidata.org/). Each database consists of mutliple tables that are connected by foreign keys.

## Full Dataset
The full dataset of 10,000 databases is available via Zenodo here: [https://zenodo.org/record/8227452](https://zenodo.org/record/8227452).

## Dataset Sample
To give a first impression of WikiDBs, we offer a couple of sample databases for download here: [Sample_WikiDBs.zip](data/Sample_WikiDBs.zip)

## License
We release WikiDBs under the [Creative Commons Attributions 4.0 International](https://creativecommons.org/licenses/by/4.0/) license (CC BY 4.0). Information regarding the license of data in Wikidata can be found [on this page](https://www.wikidata.org/wiki/Wikidata:Licensing).

## Publication
Details about the dataset construction and characteristics can be found in [our paper](https://ceur-ws.org/Vol-3462/TADA3.pdf). 

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

## About
WikiDBs is developed by Liane Vogel and Carsten Binnig from the Systems Group at the Technical University of Darmstadt, Germany. 

We thank Till Döhmen and Madelon Hulsebos for generously providing the table statistics from their [GitSchemas dataset](https://github.com/tdoehmen/gitschemas) and Jan-Micha Bodensohn for converting the dataset to SQLite files.
This work has been supported by the BMBF and the state of Hesse as part of the NHR Program and the BMBF project KompAKI (grant number 02L19C150), as well as the HMWK cluster project 3AI. Finally, we want to thank hessian.AI, and DFKI Darmstadt for their support.
