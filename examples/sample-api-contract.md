# Sample Interface Shapes

The examples below are sanitized and illustrative. They are not a full public API reference and should not be interpreted as a production contract.

## Asset Summary Response

```json
{
  "id": 42,
  "name": "support_response_policy",
  "asset_type": "prompt",
  "description": "Policy layer for a support assistant",
  "owner": "platform-team",
  "tags": ["support", "policy"],
  "created_at": "2026-04-01T10:15:00Z",
  "updated_at": "2026-04-02T08:30:00Z"
}
```

## Active Version Lookup Response

```json
{
  "asset_name": "support_response_policy",
  "asset_type": "prompt",
  "version_tag": "v1.3",
  "status": "active",
  "change_summary": "Tightened escalation guidance and response framing"
}
```

## Execution Event Example

```json
{
  "asset_version_id": 133,
  "request_id": "req_demo_001",
  "latency_ms": 842,
  "token_usage": 1294,
  "created_at": "2026-04-02T09:40:00Z"
}
```

## Notes

- prompt bodies, guardrails, workflow definitions, and evaluation data are intentionally excluded
- internal identifiers, deployment details, and model-routing behavior are intentionally excluded
