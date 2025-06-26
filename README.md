# Avro Schemas Common Repository

This repository serves as a common location for all projects that need to use Kafka schemas.

## Schema Organization

Kafka schemas are generally grouped in the `src/main/avro` directory.

- Each subfolder in `src/main/avro` is named after the recipient or producer of the given data flow.
  - For example, the `fetcher` folder contains schemas for requests to fetch player data and for the results produced by the fetcher.

## Publishing Policy

Nothing is published unless the `version` in `build.gradle` is incremented.

