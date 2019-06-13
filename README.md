# Kafka Backup

`kafka-backup` is a tool to backup and restore Kafka Topics **and**
Conumer Offsets.

Backing up Kafka is not trivial. Apart from `kafka-backup` there is
(to the best of our knowledge) no reliable and data-saving way to
backup data from Kafka that also ensures the backup and restore of
consumer offsets.

It is architected as two connectors for Kafka
Connect: A sink connector (backing data up) and a source connector
(restoring data).

Currently `kafka-backup` supports backup and restore to/from the file
system.

## Maturity of the project

* Very early stage
* There are some sucessful tests
* Seems to work overall
* There will be definitely breaking changes in the near future
* [ ] Documentation is coming!
* [ ] More tests are coming!


## Documentation

* [High Level
  Introduction](./docs/Blogposts/2019-06_Introducing_Kafka_Backup.md)
* [Usage](./docs/Usage.md)
* [Comparing Kafka Backup
  Solutions](./docs/Comparing_Kafka_Backup_Solutions.md)
* [Build and Run](./docs/Build_and_Run.md)