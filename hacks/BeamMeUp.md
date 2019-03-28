---
hackname: Beam Me Up
quicksummary: Stream processing with the Apache Beam Framework to move data around and do smart things
resource: true
categories: [hack]
---

Apache Beam
========

There is a common data plumbing problem: You want to get data from system A to B. Back in the days this was easy, you just dumped the data to a file and loaded it to the target system. (Maybe with some transformations in between.) As the industry is moving towards a streaming world where the data has in fact no end in sight, new approaches to this problem have emerged: Enter Apache Beam.

Why Do It?
----------

Beam is a unified model for batch and stream processing supporting multiple runtimes and languages. It is widely applicable within the Tamedia umbrella of organizations. It does not matter if you have an Apache Spark, Apache Flink cluster, or a Google Cloud environment: You can deploy Beam pipelines in it. The Framework supports currently Java and Python, with Golang being almost production ready.

The initial phase is to connect Apache Kafka with Apache Solr. The greater plan will be joining streams and implementing fraud detection in a streaming fashion given the current implementation that is batch-based as a starting point. [Apache Beam](https://beam.apache.org)

Requirements
------------

As Google is handing out $300 worth of free credits to any newly registered GMail address, we should be good to go for hacking. Development happens locally, when a pipeline works locally, we should be ready to deploy it with the push of a button.

Could use help with...
----------------------

- Java
- Python
- Apache Solr
- Machine Learning (there, I said it)

Links
-----

- https://beam.apache.org - The official Apache Beam website
- https://www.oreilly.com/ideas/the-world-beyond-batch-streaming-101 - The world beyond batch, streaming 101
- https://www.oreilly.com/ideas/the-world-beyond-batch-streaming-102 - The world beyond batch, streaming 102
- https://ai.google/research/pubs/pub43864 - The Dataflow paper


Who's Participating?
--------------------

* [Kacper Zielinski](/tamedia-hackdays/whoami/kacperzielinski)
* [Tobias Kaymak](/tamedia-hackdays/whoami/tobiaskaymak)
* Further help welcome...

