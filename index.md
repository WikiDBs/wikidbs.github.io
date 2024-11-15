# WikiDBs: A Large-Scale Corpus Of Relational Databases From Wikidata

WikiDBs is a large-scale corpus of relational databases based on data from [Wikidata](https://www.wikidata.org/). Each database consists of multiple tables that are connected by foreign keys. 

## Download WikiDBs
WikiDBs is available via Zenodo here: [https://zenodo.org/record/11559814](https://zenodo.org/record/11559814).

## License Information
We release WikiDBs under the [Creative Commons Attributions 4.0 International](https://creativecommons.org/licenses/by/4.0/) license (CC BY 4.0). Information regarding the license of data in Wikidata can be found [on this page](https://www.wikidata.org/wiki/Wikidata:Licensing).

## Publication
WikiDBs was published as a Spotlight paper at the Dataset & Benchmarks track at NeurIPS 2024. 

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

## About
WikiDBs is developed by Liane Vogel, Jan-Micha Bodensohn and Carsten Binnig from the Systems Group at the Technical University of Darmstadt, Germany as well as DFKI. 

# Acknowledgments
We thank Till Döhmen and Madelon Hulsebos for generously providing the table statistics from their [GitSchemas dataset](https://github.com/tdoehmen/gitschemas).
This work has been supported by the BMBF and the state of Hesse as part of the NHR Program and the BMBF project KompAKI (grant number 02L19C150), as well as the HMWK cluster project 3AI. Finally, we want to thank hessian.AI, and DFKI Darmstadt for their support.
