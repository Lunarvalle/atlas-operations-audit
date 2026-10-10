# Equal snapshots can look different in exports

HTTP status string "200" and number 200 represent the same validated status. Uppercase and lowercase SHA256 hex can represent identical bytes. Treating these formatting differences as website changes creates false alerts.

The corrected local [Change Proof](../products/change-proof.md) compares status codes numerically and SHA256 hex case-insensitively, while retaining genuine status/hash changes, added URLs and missing URLs. Inspect its [synthetic example](../examples/change-proof.json).

This is not a crawler, monitoring service or visual regression system. Both snapshots are supplied by the user. A genuinely different hash does not explain the cause of a change. Preserve source captures and review the actual page before taking action.
