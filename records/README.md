# Compliance Records

Completed review outcomes are stored as one JSON document per request.

Schema:

```json
{
  "request_id": "CR-XXXX-XXX",
  "product_line": "...",
  "min_verification_hours": 0,
  "policy_source": "path or URL of the authoritative policy",
  "upstream_repository": "owner/name"
}
```
