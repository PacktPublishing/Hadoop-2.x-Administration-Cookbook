# Hadoop 2.x Administration Cookbook
This is the code repository for [Hadoop 2.x Administration Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/hadoop-2x-administration-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781787126732), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Hadoop enables the distributed storage and processing of large data sets across clusters of computers. Learning to administer Hadoop is crucial to exploit its unique features. With this book, you will be able to overcome common problems encountered in Hadoop administration.

The book begins with laying the foundation by showing you the steps needed to set up the Hadoop cluster and its various nodes. You will get a better understanding of how to maintain Hadoop cluster, especially on the HDFS layer and using YARN and MapReduce. Further on, you will explore durability and high availability of a Hadoop cluster.

You’ll get a better understanding of the schedulers in Hadoop and how to configure and use them for your tasks. You will also get hands-on experience with the back up and recovery options and the performance tuning aspects of Hadoop. Finally, you will get a better understanding of troubleshooting, diagnostics, and best practices in Hadoop administration.

By the end of this book, you will have a proper understanding of working with Hadoop clusters and will also be able to secure, encrypt it, and configure auditing for your Hadoop clusters.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

Chapter 10 does not contains any code files

The code will look like the following:
```
<property>
    <name>dfs.hosts.exclude</name>
    <value>/home/hadoop/excludes</value>
    <final>true</final>
</property>
```

To go through the recipes in this book, users need any Linux distribution, which could be Ubuntu, Centos, or any other flvor, as long as it supports running JVM. We use Centos in our recipe, as it is the most commonly used operating system for Hadoop clusters.

Hadoop runs on both virtualized and physical servers, so it is recommended to have at least 8 GB for the base system, on which about three virtual hosts can be set up. Users do not need to set up all the recipes covered in this book all at once; they can run only those daemons that are necessary for that particular recipe. This way, they can keep the resource requirements to the bare minimum. It is good to have at least four hosts to practice all the recipes in this book. These hosts could be virtual or physical.

In terms of software, users need JDK 1.7 minimum, and any SSH client, such as PuTTY in Windows or Terminal, to connect to the Hadoop nodes.

## Related Products
* [Hadoop: Data Processing and Modelling](https://www.packtpub.com/big-data-and-business-intelligence/hadoop-data-processing-and-modelling?utm_source=github&utm_medium=repository&utm_campaign=9781787125162)

* [Hadoop Real-World Solutions Cookbook - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/hadoop-real-world-solutions-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781784395506)

* [Elasticsearch for Hadoop](https://www.packtpub.com/big-data-and-business-intelligence/elasticsearch-hadoop?utm_source=github&utm_medium=repository&utm_campaign=9781785288999)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.

