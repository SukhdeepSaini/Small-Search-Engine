Search Engine:

======================================================================================
Working:
======================================================================================
Read in the tokenized and stemmed document collection provided in the file tccorpus.txt
Build a simple inverted indexer that reads the corpus and writes the index.
Implemented the BM25 ranking algorithm to provide a ranked list of documents for a file with one or more queries.
Output top 100 document IDs and their BM25 scores for each test query.

======================================================================================
Please see below the Instructions to compile and run ======================================================================================

Source Files:Indexer.javaBM25Implementation.javaInput files:
tccorpus.txtqueries.txtSteps to run the program:First Run the Indexer.java program Compile Indexer.java as followsjavac Indexer.javaExecute the Indexer program then:Java Indexer tccorpus.txtOutput Of Indexer:Index.out: This file contains the term frequencies in the form of inverted lists.AverageLength.txt: This file contains the Documents and their respective averages, which is used in BM25 algorithm implementation for calculating value of K.Run the BM25Implementation.java:Compile the program first using:Javac BM25Implementation.javaExecute the program:Java BM25Implementation.java Index.out queries.txt 100 or by using the below query if result is to be expected in a separate fileJava BM25Implementation.java Index.out queries.txt 100 > results.evalOutput:Output will be displayed in the console i.e. first 100 document IDs for each query in the queries.txt file based on the BM25 score when sorted in descending order.If used the second option in which output is requested in a file then a file will be created as a result file containing the output.
