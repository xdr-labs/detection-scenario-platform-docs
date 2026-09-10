# Detection Scenario Platform Documentation

Mintlify documentation source for **Detection Scenario Platform (DSP)**.

- Product source: https://github.com/xdr-labs/xdr-poc-script
- Documentation repository: https://github.com/xdr-labs/detection-scenario-platform-docs
- Custom hostname: `dsp.xdr.ooo`
- Languages: English and Korean

The public documentation is grounded in the current DSP `release/v1.4.0-rc` operator branch and Release 1.0 validation material. Customer-facing positioning is intentionally focused on **XDR and NDR POC validation**.

## Reader path

The navigation is task-oriented:

1. **Start Here** — understand DSP and run it quickly
2. **POC Guide** — choose scenarios, run a POC, and collect evidence
3. **Setup & Operation** — install, configure, use webshell mode, and troubleshoot
4. **Reference** — CLI, validation boundaries, architecture, and release notes

## Important product boundary

DSP generates observable security activity and execution evidence. It does not automatically assert that a vendor alert fired, that an attack succeeded, or that an XDR case was correlated. Those outcomes require evidence from the connected XDR/NDR platform and human verification.

## Public install path

The bootstrap installer uses `$HOME/xdr-poc-script` by default, so the public Quick Start can be copied and run without a user-specific hard-coded path.
