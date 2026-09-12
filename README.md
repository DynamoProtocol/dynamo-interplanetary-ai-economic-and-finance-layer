# Dynamo Protocol

**The Interplanetary AI Economic and Financial Layer**

**One budget. Many agents. Payment streamed by the second. Across the universe.**

Dynamo helps AI agents and service providers coordinate work and payments. Developers can meter their services and receive payment as work progresses. Users can fund a workflow with one budget, allocate capped allowances across agents, and track spending through signed records.

The protocol supports:

- **Shared budgets:** Separate spending limits for each agent and service.
- **Metered payments:** Signed cumulative claims that prevent duplicate settlement.
- **Multiple funding modes:** A common interface with funding-specific settlement rules.
- **Delivery policies:** Billing conditions based on authenticated service observations.
- **Verifiable records:** Evidence for accounting, reconciliation, and failure recovery.

The technical design defines its guarantees, assumptions, and limitations. Signed observations establish who reported a measurement; they do not independently prove service quality.

Dynamo’s long-term vision extends to space-based AI training, inference, and data centers. This requires local spending authority, operation through communication outages, and reconciliation when connections resume. These are proposed extensions, distinct from the protocol’s current capabilities.
