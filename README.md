KSQL

KSQL Implementation for RPB service status.

Problem statement: KSQL Implementation for RPB service status using KSQLDB streams and tables.

Solution : Developed an API to read notification message from KSQL streams and table to get RPB service status(Up/Down) for given business date which is published on to 'XYZ' kafka topic. Once message is published into kafka topic KSQL stream should read the message put into KTable after stream processing with structure format.

           * ksqlDB is a database for building stream processing applications on top of Apache Kafka.
           * Streams and tables - Create relations with schemas over your Apache Kafka topic data
           * Push queries       - Continuous queries that push incremental results to clients in real time.
           * Pull queries       - Query materialized views on demand, much like with a traditional database

Benefits: ksqlDB allow you to query, read, write and process the data in apache kafka in real-time and at scale using SQL like syntex.

Components: Kafka,KSQLDB and SpringBoot Rest API.
