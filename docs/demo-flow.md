# Demo Flow

This document describes the product story a reviewer should take away from the materials in this repository.

## Operator Flow

1. A builder creates a new prompt asset for an AI-backed feature.
2. The asset receives a versioned update with a change summary and lifecycle state.
3. The team promotes one approved version to active.
4. Application services consume only the active version through a stable interface.
5. Execution events are recorded so operators can inspect behavior and operational metrics.

## Developer Flow

1. An application team references a named asset rather than hardcoding prompt content everywhere.
2. The application requests the approved version at runtime or during controlled release workflows.
3. Prompt changes can be reviewed and promoted without forcing broad code rewrites.
4. Operational data feeds back into future prompt revisions and release decisions.

## Why This Matters

Echo Prompt is not just a prompt editor. It is an operating layer for prompt change management.

The product value comes from giving teams:

- a controlled source of truth for prompt assets
- a release model for prompt changes
- an audit trail around AI behavior changes
- a cleaner contract between application code and prompt operations

## Repository Limits

This document intentionally avoids:

- concrete proprietary prompts
- internal release rules
- private evaluation criteria
- production endpoint details
