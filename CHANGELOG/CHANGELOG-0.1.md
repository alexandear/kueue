## v0.1.1

Changes since `v0.1.0`:

- Fixed number of pending workloads in a BestEffortFIFO ClusterQueue.
- Fixed bug in a BestEffortFIFO ClusterQueue where a workload might not be
  retried after a transient error.