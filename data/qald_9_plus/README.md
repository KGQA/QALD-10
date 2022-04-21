# Data description

This is the part of the original [QALD-9-plus](https://github.com/KGQA/qald_9_plus) dataset over Wikidata. The following changes were made to it:
* The field `answers` was obtained based on the following SPARQL [endpoint](http://sems-vm-1.informatik.uni-hamburg.de:443/api/endpoint/sparql).
* The questions with empty answer sets were eliminated.