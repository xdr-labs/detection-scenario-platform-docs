# Detection Scenario Platform Documentation

Mintlify documentation source for **Detection Scenario Platform (DSP)**.

- Product source: https://github.com/xdr-labs/xdr-poc-script
- Documentation repository: https://github.com/xdr-labs/detection-scenario-platform-docs
- Recommended custom hostname: `dsp.xdr.ooo`

The documentation is grounded in the current DSP `release/v1.4.0-rc` operator branch and Release 1.0 validation material. Older architecture/catalog documents may describe historical profile names or planned scenario status; customer-facing pages prefer current runtime behavior when the sources differ.

## Documentation structure

- Overview / Quick Start
- Customer POC Program
- Installation and Configuration
- Local and Webshell Execution
- Scenario Coverage
- CLI Reference
- 3rd-Party Alert & Case Demo
- Reports & Evidence
- Validation Status
- Safety & Guardrails
- Troubleshooting
- Architecture
- Release Notes

## Important product boundary

DSP generates observable security activity and execution evidence. It does not automatically assert that a vendor alert fired, that an attack succeeded, or that an XDR case was correlated. Those outcomes require evidence from the connected security platform and human verification.
