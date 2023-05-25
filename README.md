# QALD-10

This is the repository for the **10th Question Answering over Linked Data Challenge**.

## Dataset
The QALD-10 **training data** and a description can be found in https://github.com/KGQA/QALD_10/blob/main/data/qald_9_plus/
This dataset is a multilingual KGQA dataset with 412 questions pairs. Check [this paper](https://www.computer.org/csdl/proceedings-article/icsc/2022/341800a229/1BYIptAeqty) for more detai.

The QALD-10 **test data** and a description can be found in https://github.com/KGQA/QALD_10/tree/main/data/qald_10
It is also multilingual with 394 question answer pairs. Our paper about this dataset will be publicly available soon.

More information about the challenge can be found at https://www.nliwod.org/challenge

## Endpoint
To run the benchmark replicably, please use our provided stable SPARQL endpoint at https://skynet.coypu.org/wikidata/.
We decide to set up our local endpoint to cope with problems in version changes of the endpoint and endpoint technology.
This problem is especially true when switching between the graph stores HDT and Fuseki, which leads to different answer sets. This is due to syntax errors and execution timeouts in their internal optimizations such as basic graph pattern reordering or indexing. Providing a stable endpoint in connection with a stable dump and dataset, helps to alleviate this challenge.
This endpoint is hosted in our own server and created using a wikidata dump.

