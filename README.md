# KBase Relation Engine

This repo holds the code associated with the KBase relation engine, previously held in https://github.com/kbase/relation_engine_api and https://github.com/kbase/relation_engine_spec.

## Relation Engine Spec
### `spec/`

The `spec/` directory holds the schemas for [stored queries](spec/stored_queries), [collections](spec/collections), [views](spec/views) and [migrations](spec/migrations) for the relation engine graph database service.

These specifications are used by the [Relation Engine API](relation_engine_server).

## Relation Engine API
### `relation_engine_server/`

The relation engine server (`relation_engine_server/`) is a simple API that allows KBase community developers to interact with the Relation Engine graph database. You can run stored queries or do bulk updates on documents.

## Relation Engine builds

The Relation Engine is available on dockerhub as `kbase/relation_engine_api`. Automated builds are performed whenever there is a new push to `master` or `develop`.