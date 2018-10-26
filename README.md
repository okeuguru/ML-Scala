# Iris data set classification model in Scala
The iris data set model in scala was taken from the Apache Spark website and I will show how to run the example in jupyter notebook.

### Assumptions:
* Jupyter is already set up on your computer
* You are running a mac

### Dependencies
* [Apache Spark](https://spark.apache.org/downloads.html)
* [Scala](https://www.scala-lang.org/)
* [Apache Toree](https://toree.apache.org/docs/current/user/installation/) 

### Set up Jupyter with Apache Toree
Setting up apache spark with apache toree is extremely simple. 
1. Download spark from the [apache spark website](https://spark.apache.org/downloads.html) 
2. Save the unzipped download to a safe location. I suggest `/usr/local/bin/{apache-spark-download-folder}`
3. Follow the steps detailed in the [Apache Toree website](https://toree.apache.org/docs/current/user/installation/)
+    pip install toree
+    jupyter toree install --spark_home=/usr/local/bin/{apache-spark-download-folder}`

### Done!
