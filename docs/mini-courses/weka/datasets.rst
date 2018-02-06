
Hi, now that you have Weka installed, you need to load data.

Weka is designed to load data in a native format called ARFF. It is a modified CSV format that includes additional information about the types of each attribute (column).

Your Weka installation includes a subdirectory with a number of standard machine learning datasets in ARFF format ready for you to load.

Weka also supports loading data from raw CSV files as well as a database and converts the data to ARFF as needed.

In this lesson, you will load a standard dataset in the Weka Explorer.

    1. Start Weka (click on the bird icon), this will start the Weka GUI Chooser.
    2. Click the “Explorer” button, this will open the Weka Explorer interface.
    3. Click the “Open file…” button and navigate to the data/ directory in your Weka installation and load the diabetes.arff dataset.

Note, if you do not have a data/ directory in your Weka installation, or you cannot find it, download the .zip version of Weka from the `Weka download page`_, unzip it and access the data/ directory.

You have just loaded your first dataset in Weka.

Try loading some of the other datasets in the data/ directory.

Try downloading a raw CSV file from the `UCI Machine Learning repository`_ and loading it in Weka.

In the next lesson, you will learn how to use descriptive stats and data visualization in Weka.


.. _Weka download page:https://www.cs.waikato.ac.nz/ml/weka/downloading.html?__s=rdmdrq7krrztsjmuqzpo
.. _UCI Machine Learning repository: http://archive.ics.uci.edu/ml/index.php