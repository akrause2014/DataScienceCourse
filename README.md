# DataScienceCourse

This notebook shows how to implement k-means clustering in Spark.

Prerequisites:
Java 8. Does not work with Java 9 or 10.

Installation:
Download latest version of Spark and unzip.

Installation on MacOS with Homebrew:
```
brew install scala
brew install apache-spark
```

Installation of notebook:

```
git clone https://github.com/akrause2014/DataScienceCourse.git
conda create --name dataScience
conda install -n dataScience numpy matplotlib scikit-learn pyspark Jupyter
```
This example requires an installation of Spark at the location $SPARK_HOME and it uses sklearn for creating a random dataset.
Then start PySpark with the notebook as follows:
```
source activate dataScience
PYSPARK_DRIVER_PYTHON=jupyter PYSPARK_DRIVER_PYTHON_OPTS=notebook $SPARK_HOME/bin/pyspark
```

