# BAQP Benchmark

Benchmark data for evaluating Approximate Query Processing (AQP) on Hyperledger Fabric. The experiments use the TPC-H `lineitem` table at 1 GB and 10 GB scale factors, tested across varying network sizes (5–28 orgs).

## Repository Contents

- **`AQP Data/`** — Query accuracy and speed comparisons (synopsis vs. full database)
- **`Block Creation Time Data/`** — Block commit latency across different org counts
- **`Block Creation Time Sample Database/`** — Block creation time using sample-based synopses
- **`Queries Per Second Data/`** — Throughput measurements and the SQL queries used

Each experiment was run for 10 iterations. All results are stored as CSV files.
