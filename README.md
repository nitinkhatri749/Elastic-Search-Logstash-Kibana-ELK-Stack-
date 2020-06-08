# Elastic-Search-Logstash-Kibana-ELK-Stack-
Big Data Tools

For Big Data Analysis, Log Analysis and Monitoring modern applications.

Log management and analytics solution that enables engineers to overcome the challenge of monitoring what are highly distributed, dynamic and noisy environments. 

"ELK" is the acronym for three open source projects: Elasticsearch, Logstash, and Kibana. Elasticsearch is a search and analytics engine. Logstash is a server‑side data processing pipeline that ingests data from multiple sources simultaneously, transforms it, and then sends it to a "stash" like Elasticsearch. Kibana lets users visualize data with charts and graphs in Elasticsearch. 

    E stands for ElasticSearch: used for storing logs
    L stands for LogStash : used for both shipping as well as processing and storing logs
    K stands for Kibana: is a visutalization tool (a web interface)

![image21-1024x328](https://user-images.githubusercontent.com/46655831/75623865-9f2de180-5bd4-11ea-9bcd-04b63d2452fd.png)

### Filebeat
Filebeat is part of the Elastic Stack, meaning it works seamlessly with Logstash, Elasticsearch, and Kibana. Whether you want to transform or enrich your logs and files with Logstash, fiddle with some analytics in Elasticsearch, or build and share dashboards in Kibana, Filebeat makes it easy to ship your data to where it matters most.
Filebeat is a log shipper belonging to the Beats family — a group of lightweight shippers installed on hosts for shipping different kinds of data into the ELK Stack for analysis. Each beat is dedicated to shipping different types of information — Winlogbeat, for example, ships Windows event logs, Metricbeat ships host metrics, and so forth. Filebeat, as the name implies, ships log files.

Download Filebeat- Link(https://www.elastic.co/downloads/beats/filebeat)
