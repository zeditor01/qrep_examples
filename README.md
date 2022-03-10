## Description

The goal of this github respository is to provide practical worked examples of implementing Q Replication and MQ Event Publishing solutions on z/OS and Linux. 
It contains  

* 9 documents that illustrate a range of tasks from installation through to operations and monitoring
* code samples for some of the  tasks.

Q Replication is a cross-platform data replication infrastructure for Db2 databases.
 
* It does provide support for Oracle, Informix, SQL Server and Sybase, but CDC Replication provides more extensive support for heterogenous scenarios including 
event streaming platforms like Kafka. 
* It's strengths lie in deeper support for homogeneous Db2 environments, including 

* DDL replication 
* GDPS Active-Active High Availability
* MQ Event Publishing

The worked examples in these papers are centred upon Db2 z/OS, Db2 for Linux, and MQ Publishing.

Code samples for the demo application used in this Redpaper can be downloaded at [code sample](https://github.com/zeditor01/cdc_examples/tree/main/code%20sample).

<p align="center">
  <img alt="CDC and DIH" src="images/cdc/zdim.png">
</p>

## Table of Contents

[Chapter 1.  Environment for Q Replication Worked Examples.](QREP_environment.md)

[Chapter 2.  Devops Options for Q Replication.](QREP_devops.md)

[Chapter 3.  Security for Q Replication.](QREP_security.md)

[Chapter 4.  Setting Up Q Replication for Db2 z/OS.](QREP_zos.md)

[Chapter 5.  Setting Up Q Replication ASNMON on z/OS.](QREP_asnmon.md)

[Chapter 6.  Setting Up Q Replication for Db2 on Linux.](QREP_linux.md)

[Chapter 7.  ASNCLP Scripting.](QREP_asnclp.md)

[Chapter 8.  ASNMON Altering.](QREP_alerting.md)

[Chapter 9.  ZOWE Devops COnsole for Q Replication.](QREP_zowe.md)



[Appendix](C016_appendix.md)

[Glossary](C017_glossary.md)


