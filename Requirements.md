# Flux — Requirements v1.0

## Status
Version: 1.0  
Maturity: Baseline Requirements

## Purpose
Flux is a decentralized, event-native system in which orchestration emerges from observation, response, and convergence rather than control.

Flux observes changes in complex environments, records them as attestable events, and enables autonomous Sensors to act when their conditions are met. The system continuously converges toward stable states while remaining open to disruption by new signals.

## Architectural Intent
- No Central Orchestrator
- Events as the Sole Driver
- Sensors as First-Class Actors
- Emergent Orchestration
- Ordering Is Not Required
- Convergence Over Completion
- Verifiable Truth over Authority

## Relationship to xDAO / CATF
Flux leverages the xDAO platform and CATF as its trust, attestation, and verification substrate.

CATF establishes what happened. Flux determines what reacts next.

## Platform Injection Model
Flux is platform-agnostic. Platforms inject signals but do not control orchestration.

Examples:
- AWS: CloudWatch / EventBridge
- Azure: Event Grid / Activity Log
- Other platforms via adapters

## Explicit Non-Goals
- Workflow engines
- DAG execution
- Step sequencing
- Global locks
- Central controllers
- Exactly-once delivery
