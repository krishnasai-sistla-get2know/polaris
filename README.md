# Polaris

### 📦 Apache Polaris Iceberg REST Catalog – Docker Images
This repository provides a Dockerized version of the Apache Polaris REST catalog and Polaris admin tool. It is not part of the Apache Iceberg project i.e., `UNOFFICIAL` hence, use it at your own risk. It simplifies deployment of the REST catalog by packaging it into a ready-to-use Docker image, suitable for development, testing, or production environments.

✨ Features
Prebuilt Docker image of Apache Polaris REST catalog and Polaris Admin Tool

Easily configurable via environment variables

Ready for integration with Iceberg clients (e.g., Spark, Flink, Trino, DuckDB)

Compatible with MinIO, AWS S3, Nessie, and other Iceberg-compatible backends

Lightweight and minimal base image

### 🚀 Getting Started
```bash
docker run -p 8181:8181 ghcr.io/krishnasai-sistla-get2know/polaris:latest
docker run -p 8181:8181 ghcr.io/krishnasai-sistla-get2know/polaris-admin-tool:latest
```

### 📝 License
This project packages and redistributes software licensed under the Apache License 2.0. See [NOTICE](./NOTICE) and [LICENSE](./LICENSE) for details.
