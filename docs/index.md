# Flowfunctions

The `flowfunctions` library enables and empowers development, management and monitoring of complex and extensible data workflows within the native Google BigQuery environment.

## Motivation
Google BigQuery is an amazing foundational technology. It has a wide - and expanding - array of features, which make it a powerful platform for any kind of data work, for any scale or type of organisation. 

However due to some syntactical and practical idiosyncrasies and contraints, it can be difficult to achieve complex tasks in a clear, readable and reusable manner.

This library aims to provide a clean, unified, functional abstraction based on components of the core BigQuery language sets ([SQL](https://cloud.google.com/bigquery/docs/reference/standard-sql/introduction), DDL, DML, DCL, Scripting, Other) to enable developers to write and reuse powerful, scalable, extensible and maintainable code, to achieve any data objective without requiring any external tools.