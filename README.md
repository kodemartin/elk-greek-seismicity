# Using the Elastic stack to process seismicity data in Greece

This is a simple demonstration of the use of ElasticSearch, Kibana, Logstash,
and Filebeat, to index and post-process seismicity data in Greece.

It is inspired by the following official tutorials:

* [Earthquake data with the Elastic Stack][elk-demo-full]
* [Elasticon tour 16 demo][elasticon16-demo]

I have made a [fork][personal-fork-dev] of the latter to implement the steps
with ELK 7.2 in Docker. This demonstration follows the docker implementation.

## Setup

### System requirements

* `docker`
* `docker-compose`

[elk-demo-full]: https://www.elastic.co/blog/earthquake-data-with-the-elastic-stack
    "Earthquake data with the Elastic Stack"
[elasticon16-demo]: https://github.com/tbragin/elasticon_tour16_demo
    "ElasticON 16 Kibana demo"
[personal-fork-dev]: https://github.com/kodemartin/elasticon_tour16_demo/tree/docker-elk-7
