# Bayora Shield — Interactive Prototype

A lightweight, responsive browser prototype for the Bayora Shield adversarial AI safety testing infrastructure concept.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox).
3. No package install or server is required.

## Demo features
- Overview dashboard and evaluation pipeline flowchart
- Trust-zone architecture for Red Team, Client LLM, and Blue Team
- Sandbox run configuration with simulated policy outcomes
- Security validation checklist
- Demo audit trail with filtering and CSV export
- Responsive desktop and mobile layout

## Important limitations
This is a **front-end concept prototype**. It does not launch real Linux containers, enforce seccomp, configure network namespaces, contact an LLM, isolate KV caches, or produce cryptographically secure audit evidence. The "hash chain" is illustrative only and is not suitable for security claims. All run and validation outcomes are simulated in the browser.

## Suggested next implementation step
Build a FastAPI backend with authenticated RBAC, per-run job orchestration, real container isolation, policy-enforced networking, structured audit storage, and independently verifiable signed checkpoints. Run security tests against that implementation before describing controls as verified.
