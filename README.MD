# InferOpt

InferOpt is a simulator and planner for transformer inference scheduling under
memory, latency, and hardware constraints.

This project models:
- transformer execution as coarse-grained graphs
- heterogeneous accelerator clusters
- request arrival and execution dynamics
- scheduling and planning policies

The system does not execute models.
It simulates inference to study scheduling tradeoffs.
