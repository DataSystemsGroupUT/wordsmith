FROM bde2020/spark-java-template:3.0.2-hadoop3.2

MAINTAINER Erika Pauwels <erika.pauwels@tenforce.com>
MAINTAINER Gezim Sejdiu <g.sejdiu@gmail.com>

ADD target/original-spark-examples_2.12-3.0.1.jar .

ENV SPARK_APPLICATION_JAR_NAME original-spark-examples_2.12-3.0.1.jar
ENV SPARK_APPLICATION_MAIN_CLASS  org.apache.spark.examples.JavaWorldCount
ENV SPARK_APPLICATION_ARGS "foo bar baz"