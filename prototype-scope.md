# Prototype scope

## User journey
1. Open Overview and understand the Configure → Isolate → Execute → Verify → Report flow.
2. Navigate to Sandbox Runs and choose a scenario/profile/resource tier.
3. Run the simulation and review control outcomes.
4. Inspect Trust Zones to understand logical role boundaries.
5. Use Security Validation to populate an illustrative checklist.
6. Filter or export the demo Audit Trail as CSV.

## Concepts represented
- Container/sandbox isolation
- Network segmentation and default-deny access
- LLM session context separation
- Tamper-evident audit trail concept
- Resource governance
- Automated security validation

## Not implemented
- User authentication / real RBAC
- FastAPI endpoints or database
- Docker/Podman orchestration
- Linux namespaces/seccomp/cgroups
- Network policies/firewall rules
- Actual LLM inference or KV-cache separation
- Production cryptography, signed checkpoints, or durable audit storage
