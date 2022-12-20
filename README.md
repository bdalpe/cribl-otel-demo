# Cribl Demo for OTEL

This is a simulated OTEL Trace demo using Grafana [k6](https://k6.io/) and [Tempo](https://grafana.com/oss/tempo/). [Cribl Stream](https://cribl.io/stream/) acts as an OTEL collector being able to process and transform traces and metrics.

Currently, only tracing data is emitted from the k6 source.

## Run

To start the demo:

```bash
docker compose up -d
```
To stop the demo:

```bash
docker compose down
```

## UI Access

To access the Cribl UI (with default credentials `admin/admin`), open your browser to:

[http://localhost:9000](http://localhost:9000)

To see the traces in Grafana, open your browser to:

[http://localhost:3000/explore](http://localhost:9000)
