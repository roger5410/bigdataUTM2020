# Fundamentals of Big Data

## Big data

Big Data is a term that describes a large volume of data, (both structured and unstructured) and its immediate analysis to find hidden information, recurring patterns, new correlations, etc .; The data set is so large and complex that traditional means of processing are ineffective.

## Open data and private data

Open Data is digital information that is under license and availability of any person, and that specifically has some stipulations, includes data from the private sector that companies decide to open for their own fines, for example, to satisfy potential investors or improve your corporate reputation. The hackathones organized by financial institutions based on their own information is a good example of this category of open data.
In contrast, closed data frequently restricts its use, tying it to licenses for privacy or security restrictions. An example of closed data includes financial information that can only be accessed by its owner. This may include sales data of a company with profit fines, other consumers or corporate information that is "sensitive."

## Structured and unstructured data

Structured data consists of clearly defined types of data whose pattern makes them easy to search; while unstructured data is made up of data that is generally not easy to search, including formats such as audio, video and social media publications.

## Stored data and moving data

Stored data (or at rest) is a term referring to inactive data that is physically stored in any digital format (eg, databases, data stores, spreadsheets, files, tapes, remote backups, mobile devices, etc. ..).
Moving data is data that is being transmitted on a network. Moving data is particularly vulnerable to attackers, since they do not need to be near the computer where this data is stored: they simply need to be at some point in the path that data is traveling.

# Fundamentals of data analysis

## Analysis of data

It is the process of inspecting, cleaning, transforming and modeling data in order to discover that useful information we need.
We can distinguish different types of data analysis based on what our objective is to perform it.
* If we want to know how to act we will find a Prescriptive Analysis.
* If we want to know what will happen we will have a Predictive Analysis.
* If we want to know why it has happened we will be facing a Diagnostic Analysis.
* If we want to know what to do to make it happen we will have a descriptive analysis.

## Impact of data analysis in organizations
  
Currently, the monetization of the data is carried out, a term that refers to the use of the data to obtain a quantifiable economic benefit, this includes methods such as the exchange and sale of information to third parties.
That is why organizations of all types and sizes collect, store, process and exchange large volumes of information with the desire to create new products and services from the data that generate greater benefits, reduce costs and reinforce customer loyalty, and offer authentic competitive advantages.
This demonstrates that the analysis of data in the organizational field is of great importance as it serves as a tool to better know your customers and create products and services that have the success they both seek.

# Commands

* Git init: Initializes a new repository in the folder where we are positioned.

Example: git ini MyProject.

* Git status: Shows the current status of new, modified or tracked files.

Example: git status.

* Git add "file_name.extension": Add a file to be tracked or for review.

Example: git add File.txt.

* Git commit -m "message": Track all files added with permanently add in the history.

Example: git commit -m "Version 2"

* Nano "filename.extension": We create or open a file with the nano text editor in the folder where we are.

Example: Nano File.txt

* Git rm "filename.extension": Deletes the file from the work tree and the index.

Example: git rm File.txt

* Git log: Shows the version history of each branch and file as well as the messages of each commit.

Example: git log

* Git diff: Shows the differences in content between 2 branches.

Example: git diff

# Concepts

## MapReduce

This process is divided into 2 processes, a Map that consists of dividing the data in the cluster and then a Reduce process that allows us to regroup the data and then these data allow us to make calculations to determine the information we need.

## Hadoop

It is a framework that allows distributed processing of large amounts of data using simple programming models on a machine cluster that makes use of the hard disk of the equipment in the cluster.

## HDFS

It is the Hadoop storage system, so if a node falls, we will have the data in the rest of the configured nodes.

## Apache Spark

It is a computer system of open clusters, unified analysis engine, ultrafast for Big Data and Machine Learning.
Spark can be 100 times faster than Hadoop for large-scale data processing by exploiting memory computing and other optimizations.

## Architecture Lambda and Kappa

The architecture Lambda is divided into three parts: batch layer, serving layer (query layer) and speed layer (stream processing layer).

* Batch layer. It manages the raw master data set and adds the new data to the existing ones, which are not modified.

* Serving layer. Its mission is to index the batch views (static) and expose them so that they can be consulted optimally and in real time.

* Speed ​​Layer. The analysis of the information that is not yet represented in the serving layer is the mission of the speed layer. To achieve instant response times, apply fast and incremental algorithms to recent data.

Streaming processing system Kappa, proposes an architecture in four steps:

* Kafka or a similar application for data intake and storage of data that can be reprocessed. You can dump the data to HDFS (disk) if there are memory limitations.

* A streaming stream whose results are stored in an associated table. The client application queries this table. If it is necessary to reprocess the data, start a second processing flow to obtain a new table with the recomputed data.

* When the new table is ready, the application starts reading from that table, which is fed by the second processing flow.

## Docker container

Docker packages software in standardized units called containers that include everything necessary for the software to run, including libraries, system tools, code and runtime. Each container runs on a Container Host, which can be a Windows or Linux machine.

###### Roger Iván Argáez Cocom
