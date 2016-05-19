# docker-zeppelin-datascience

## A docker image for Apache Zeppelin with pyspark and sparkr configured to use Python3.
## With pre-installed datascience packages.

### Description

This docker image contains:
- Apache Zeppelin and Spark
- Python3, PySpark and Pip3
- R and SparkR
- Some Python3 packages: numpy, pandas, scipy, scikit-learn, pydataset...

For more informations about Apache Zeppelin project: https://zeppelin.incubator.apache.org/

### Installation

First, get the image:

```
docker pull gmousse/docker-zeppelin-datascience
```

Then, launch the container:

```
docker run -it -p 8080:8080 -p 8081:8081 gmousse/docker-zeppelin-datascience
```

You can access to zeppelin on **localhost:8080** in your web browser.
