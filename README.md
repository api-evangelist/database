# Database (database)
An index and topic collection covering managed databases and database-as-a-service offerings exposing APIs. Database APIs enable developers to provision, configure, query, migrate, and scale relational, document, key-value, wide-column, vector, graph, time-series, and analytical data stores through programmatic interfaces rather than through manual server administration. This collection includes managed PostgreSQL platforms like Neon, Supabase, and Render; MySQL platforms like PlanetScale and Vitess; document databases like MongoDB Atlas and Couchbase; key-value and wide-column stores like DynamoDB, Cassandra, and Aerospike; serverless databases like Fauna, Convex, and Cloudflare D1; vector databases like Pinecone, Weaviate, Qdrant, and Milvus; graph databases like Neo4j and Stardog; time-series databases like InfluxDB, TimescaleDB, and QuestDB; and analytical data warehouses like Snowflake, BigQuery, Redshift, Databricks, ClickHouse, and Firebolt.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Database, DBaaS, Managed Database, SQL, NoSQL, Document Database, Graph Database, Vector Database, Time Series, Data Warehouse, Key-Value Store

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Database Instance Schema](https://raw.githubusercontent.com/api-evangelist/database/refs/heads/main/json-schema/database-instance-schema.json)
- [JSONSchema - Schema Migration Schema](https://raw.githubusercontent.com/api-evangelist/database/refs/heads/main/json-schema/database-schema-migration-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/database/refs/heads/main/json-ld/database-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/database/refs/heads/main/vocabulary/database-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Programmatic Database Provisioning | Database APIs let teams create, configure, resize, and tear down database instances on demand without filing tickets or running infrastructure scripts. |
| Branching and Forking | Modern serverless database platforms like Neon, PlanetScale, and Supabase expose branching APIs that let developers create isolated copies of a production database for development, testing, and pull request previews. |
| HTTP and SQL-over-HTTP Query Interfaces | Databases like Neon, Supabase, PlanetScale, and Cloudflare D1 expose SQL execution through HTTPS endpoints, enabling stateless query access from serverless functions and edge runtimes. |
| Vector Search and Embeddings | Vector databases like Pinecone, Weaviate, Qdrant, and Milvus expose APIs for storing high-dimensional embeddings and running nearest-neighbor similarity search. |
| Schema Migration and Versioning | Database platforms provide APIs for managing schema migrations, deploy requests, and zero-downtime schema changes, integrating database evolution into CI/CD pipelines. |
| Analytical Query and Warehouse APIs | Cloud data warehouses like Snowflake, BigQuery, Redshift, Databricks, and ClickHouse expose REST and SQL APIs for executing analytical queries and managing warehouses. |
| Multi-Region Replication and Edge Reads | Distributed and serverless databases expose APIs for configuring read replicas, regional failover, and edge-local reads. |
| Backups, Snapshots, and Point-in-Time Recovery | Managed database APIs provide programmatic control over backups, snapshots, restore points, and point-in-time recovery. |

## Use Cases

| Name | Description |
|------|-------------|
| Serverless Application Backends | Developers use serverless database APIs from Neon, Supabase, Fauna, Convex, and Cloudflare D1 to back serverless functions and edge applications. |
| Database-per-Tenant Provisioning | SaaS platforms use database provisioning APIs to spin up isolated database instances or branches per customer for strong tenant isolation. |
| Retrieval-Augmented Generation (RAG) | AI applications use vector database APIs from Pinecone, Weaviate, Qdrant, and Milvus to index embeddings and retrieve semantically relevant context for LLM prompts. |
| Real-Time Analytics and Observability | Time-series and columnar APIs from ClickHouse, InfluxDB, TimescaleDB, QuestDB, and Tinybird power real-time dashboards and observability on high-volume event streams. |
| Data Warehouse Integration and ELT | Analytics teams use APIs from Snowflake, BigQuery, Redshift, and Databricks to load data, run transformations, and integrate with dbt and orchestration tooling. |
| Schema Migrations in CI/CD | Teams use deploy-request and migration APIs from PlanetScale, Neon, and Supabase to gate schema changes through pull requests and apply them safely to production. |
| Graph Workloads and Knowledge Graphs | Applications use graph database APIs from Neo4j, Stardog, and Amazon Neptune to model relationships and back knowledge graphs and recommendation engines. |
| Edge and Mobile Data Sync | Edge databases like Cloudflare D1, Convex, and Supabase synchronize state between edge runtimes, mobile clients, and central data stores. |

## Integrations

| Name | Description |
|------|-------------|
| Neon | Serverless PostgreSQL platform with branching, scale-to-zero compute, and an HTTP query endpoint for serverless and edge runtimes. |
| Supabase | Open-source PostgreSQL platform with auto-generated REST and GraphQL APIs, realtime subscriptions, auth, storage, and edge functions. |
| PlanetScale | Serverless MySQL platform built on Vitess with non-blocking schema changes, deploy requests, and branching. |
| MongoDB Atlas | Managed multi-cloud document database with Atlas Data API, Atlas Search, Atlas Vector Search, and a control plane API. |
| Snowflake | Cloud data warehouse with SQL API, REST control plane, and Snowpipe for streaming ingestion across AWS, Azure, and GCP. |
| Pinecone | Managed vector database with REST and gRPC APIs for storing embeddings and running low-latency similarity search. |
| Databricks | Lakehouse platform with REST APIs for SQL warehouses, jobs, Unity Catalog, model serving, and Delta Lake table management. |
| Fauna | Distributed document-relational serverless database with a unified HTTP API, FQL query language, and ACID transactions across regions. |

## Artifacts

Machine-readable database API specifications organized by format.

### JSON Schema

- [Database Instance Schema](json-schema/database-instance-schema.json)
- [Schema Migration Schema](json-schema/database-schema-migration-schema.json)

### JSON Structure

- [Database Instance Structure](json-structure/database-instance-structure.json)
- [Schema Migration Structure](json-structure/database-schema-migration-structure.json)

### JSON-LD

- [Database Context](json-ld/database-context.jsonld)

## Vocabulary

- [Database Vocabulary](vocabulary/database-vocabulary.yaml) — Unified taxonomy mapping core database resources, actions, workflows, and personas across managed databases, DBaaS, vector databases, graph databases, time-series databases, and data warehouses

## Network

This index references the following managed database and DBaaS repositories:

- [Aerospike](https://github.com/api-evangelist/aerospike)
- [Amazon DynamoDB](https://github.com/api-evangelist/amazon-dynamodb)
- [Amazon Neptune](https://github.com/api-evangelist/amazon-neptune)
- [Amazon Redshift](https://github.com/api-evangelist/amazon-redshift)
- [Apache Cassandra](https://github.com/api-evangelist/cassandra)
- [Apache CouchDB](https://github.com/api-evangelist/apache-couchdb)
- [Appwrite](https://github.com/api-evangelist/appwrite)
- [Azure Cosmos DB](https://github.com/api-evangelist/azure-cosmos-db)
- [ClickHouse](https://github.com/api-evangelist/clickhouse)
- [CockroachDB](https://github.com/api-evangelist/cockroachdb)
- [Convex](https://github.com/api-evangelist/convex)
- [Couchbase](https://github.com/api-evangelist/couchbase)
- [Databricks](https://github.com/api-evangelist/databricks)
- [Fauna](https://github.com/api-evangelist/fauna)
- [Google BigQuery](https://github.com/api-evangelist/google-bigquery)
- [InfluxDB](https://github.com/api-evangelist/influxdb)
- [Milvus](https://github.com/api-evangelist/milvus)
- [MongoDB Atlas](https://github.com/api-evangelist/mongodb-atlas)
- [Neo4j](https://github.com/api-evangelist/neo4j)
- [Neon](https://github.com/api-evangelist/neon)
- [Pinecone](https://github.com/api-evangelist/pinecone)
- [PlanetScale](https://github.com/api-evangelist/planetscale)
- [PostgreSQL](https://github.com/api-evangelist/postgresql)
- [Qdrant](https://github.com/api-evangelist/qdrant)
- [QuestDB](https://github.com/api-evangelist/questdb)
- [Snowflake](https://github.com/api-evangelist/snowflake)
- [Supabase](https://github.com/api-evangelist/supabase)
- [TimescaleDB](https://github.com/api-evangelist/timescaledb)
- [Upstash](https://github.com/api-evangelist/upstash)
- [Weaviate](https://github.com/api-evangelist/weaviate)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
