# Dataproc Metastore Toolkit

This repository provides tools for [Dataproc Metastore](https://cloud.google.com/dataproc-metastore/docs) on [Google Cloud Platform](https://cloud.google.com).

## Hive Metastore Schema

The MySQL schemas of [Apache Hive](https://github.com/apache/hive) used by Dataproc Metastore are located at `hive-metastore/schema/{hive-version}/mysql/hive-schema.sql`. The supported Hive versions are `1.2.2`, `2.2.0`, `2.3.6`, and `3.1.2`. The schemas can be used to verify the metadata compatibility before migrating Hive metadata to Dataproc Metastore using [the import feature](https://cloud.google.com/dataproc-metastore/docs/import-metadata).
