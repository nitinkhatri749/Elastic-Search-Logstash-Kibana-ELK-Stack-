# Elastic-Search-Logstash-Kibana-ELK-Stack-
Big Data Tools
For Big Data Analysis, Log Analysis and Monitoring modern applications.

##### Prerequisites-
Java Runtime

Verify installed version of Java Runtime Environment or install it. Latest JDK is strongly recommended.

Check available JDK using command line: java -version. Expected output: java version 1.8.0_73. Last numbers might be different, but 1.8 is expected.

Check system variables. Required environment variable: JAVA_HOME pointing to install location of JDK. Example:
JAVA_HOME: C:\Program Files\Java\jre1.8.0_73


"ELK" is the acronym for three open source projects: Elasticsearch, Logstash, and Kibana. Elasticsearch is a search and analytics engine. Logstash is a server‑side data processing pipeline that ingests data from multiple sources simultaneously, transforms it, and then sends it to a "stash" like Elasticsearch. Kibana lets users visualize data with charts and graphs in Elasticsearch. 

Log management and analytics solution that enables engineers to overcome the challenge of monitoring what are highly distributed, dynamic and noisy environments. 

    E stands for ElasticSearch: used for storing logs
    L stands for LogStash : used for both shipping as well as processing and storing logs
    K stands for Kibana: is a visutalization tool (a web interface)

![image21-1024x328](https://user-images.githubusercontent.com/46655831/75623865-9f2de180-5bd4-11ea-9bcd-04b63d2452fd.png)

### Filebeat
Filebeat is part of the Elastic Stack, meaning it works seamlessly with Logstash, Elasticsearch, and Kibana. Whether you want to transform or enrich your logs and files with Logstash, fiddle with some analytics in Elasticsearch, or build and share dashboards in Kibana, Filebeat makes it easy to ship your data to where it matters most.
Filebeat is a log shipper belonging to the Beats family — a group of lightweight shippers installed on hosts for shipping different kinds of data into the ELK Stack for analysis. Each beat is dedicated to shipping different types of information — Winlogbeat, for example, ships Windows event logs, Metricbeat ships host metrics, and so forth. Filebeat, as the name implies, ships log files.

[Download](https://www.elastic.co/downloads/beats/filebeat) Filebeat- 

### Logstash
Logstash is the data collection pipeline tool. It collects data inputs and feeds into the Elasticsearch. It gathers all types of data from the different source and makes it available for further use.

Logstash can unify data from disparate sources and normalize the data into your desired destinations. It allows you to cleanse and democratize all your data for analytics and visualization of use cases.

It consists of three components:

Input: passing logs to process them into machine understandable format.<br/>
Filters: It is a set of conditions to perform a particular action or event.<br/>
Output: Decision maker for processed event or log.<br/>

Features of Logstash-

Events are passed through each phase using internal queues.<br/>
Allows different inputs for your logs.<br/>
Filtering/parsing for your logs.<br/>

[Download](https://www.elastic.co/downloads/logstash) Logstash- 

### ElasticSearch 
Elasticsearch is a NoSQL database. It is based on Lucene search engine, and it is built with RESTful APIS. It offers simple deployment, maximum reliability, and easy management. It also offers advanced queries to perform detail analysis and stores all the data centrally. It is helpful for executing a quick search of the documents.

Elasticsearch also allows you to store, search and analyze big volume of data. It is mostly used as the underlying engine to powers applications that completed search requirements. It has been adopted in search engine platforms for modern web and mobile applications. Apart from a quick search, the tool also offers complex analytics and many advanced features.

Features of Elastic search:

Open source search server is written using Java.<br/>
Used to index any kind of heterogeneous data.<br/>
Has REST API web-interface with JSON output.<br/>
Full-Text Search.<br/>
Near Real Time (NRT) search.<br/>
Sharded, replicated searchable, JSON document store.<br/>
Schema-free, REST & JSON based distributed document store.<br/>
Multi-language & Geolocation support.<br/>
    
[Download](https://www.elastic.co/downloads/elasticsearch) ElasticSearch- 

### Kibana
##### Important Terms used in Elastic Search-

Cluster - A cluster is a collection of nodes which together holds data and provides joined indexing and search capabilities.

Node - A node is an elasticsearch Instance. It is created when an elasticsearch instance begins.

Index - An index is a collection of documents which has similar characteristics. e.g., customer data, product catalog. It is very useful while performing indexing, search, update, and delete operations. It allows you to define as many indexes in one single cluster.

Document - It is the basic unit of information which can be indexed. It is expressed in JSON (key: value) pair. '{"user": "nullcon"}'. Every single Document is associated with a type and a unique id.

Shard - Every index can be split into several shards to be able to distribute data. The shard is the atomic part of an index, which can be distributed over the cluster if you want to add more nodes.

[Download](https://www.elastic.co/downloads/kibana) Kibana- 


### Elasticsearch in Detail-

* Configuration-

Location of configuration file: {install-path}\config\elasticsearch.yml. This is a text file using YAML format and that can be edited in any text editor.
