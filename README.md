# Challenge

We have a collection of N documents. In our case we have one file per document and the name of a file is simply the indice of the document.

To get started, we want a dictionary that matches every word from the documents with a unique id.

Using both the dataset and the dictionary we would like to build a way to search all documents by keywords.

We want a solution that works on a massive dataset. Our algorithm has to be able to run on a distributed system so we are not limited by the amount of storage, memory and CPU of a single machine.
