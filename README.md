# Embedded Elasticsearch 6 Cluster [![Travis build status](https://travis-ci.org/nitishgoyal13/elasticsearch-6-embedded-cluster.svg?branch=master)](https://travis-ci.org/nitishgoyal13/elasticsearch-6-embedded-cluster)

This bundle starts embedded elasticsearch 6 cluster

## Usage
The bundle This bundle starts embedded elasticsearch 6 cluster 
 
### Build instructions
  - Clone the source:

        git clone https://github.com/nitishgoyal13/elasticsearch-6-embedded-cluster.git

  - Build

        mvn install

### Maven Dependency
Use the following repository:
```xml
<repository>
    <id>clojars</id>
    <name>Clojars repository</name>
    <url>https://clojars.org/repo</url>
</repository>
```
Use the following maven dependency:
```xml
    <dependency>
         <groupId>org.elasticsearch-6</groupId>
         <artifactId>elasticsearch-embedded-cluster</artifactId>
         <version>1.0-SNAPSHOT</version>
    </dependency>
```

### Using Embedded cluster bundle

Just include this maven dependency in the project. It will start an elasticsearch cluster for you

