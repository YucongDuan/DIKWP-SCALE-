# DIKWP-SCALE²

Created by Yucong Duan (段玉聪).

Semantic Compute Allocation, Locality, Energy and Sovereignty Execution Fabric  
无定义意图驱动的数—算—电—网联邦执行与主权调度系统

Semantic Runtime: DIKWP-MESH 5.0

DIKWP-SCALE² is a reference execution fabric that compiles definition-free intent fields and problem-relationship kernels into auditable, multi-objective AI execution plans across heterogeneous models, accelerators, regions, energy windows and data-sovereignty boundaries.

It is not a new ontology and does not define intelligence, safety, sovereignty or public benefit. It preserves observer differences and UAX residuals, runs all 25 ordered DIKWP×DIKWP primitives, and refuses to collapse non-negotiable constraints into a single score.

## Why this project

Existing DIKWP projects cover semantic runtime, trust, governance, forecasting, agent cooperation, public action, incident recovery and human continuity. The missing execution layer is the translation from those semantic and institutional objects into real compute placement, model selection, precision choice, energy timing, locality, fallback and recovery.

SCALE² is designed to sit:

- above Kubernetes/Kueue/Volcano/Ray/OpenXLA and heterogeneous inference runtimes;
- below MESH-RUNTIME, TRUSTFABRIC, COOPSTACK, IMMUNET, PACT and public-action systems;
- across national compute hubs, public clouds, private clusters, university capacity and edge nodes.

## Core objects

1. Semantic Workload Envelope (SWE)
2. Resource Capability Passport (RCP)
3. Model Execution Passport (MEP)
4. Data Locality and Transformation Contract
5. Pareto Execution Plan
6. Semantic Quality-of-Service and Loss Ledger
7. Allocation Receipt
8. Recovery / Replanning Record

## Quick start

```bash
cd DIKWP_SCALE2_MVP
PYTHONPATH=src python -m scale2.cli demo --root . --out outputs --workloads 120 --seed 50721
PYTHONPATH=src python -m unittest discover -s tests -v
```

Open `outputs/dashboard.html`.

## Demonstration boundary

All nodes, models, workloads, prices, carbon intensity, water intensity and performance values are synthetic. The reference implementation does not connect to a cloud, Kubernetes cluster, power system, model API or public-service workflow. It does not certify legal compliance or authorize real workloads.

## Repository layout

- `src/scale2/`: deterministic reference implementation
- `schemas/`: machine-readable objects
- `config/`: synthetic resource and model catalog
- `tests/`: executable constraints
- `outputs/`: generated receipts, metrics and dashboard
- `docs/`: RFC and threat model

## License

Apache-2.0.
