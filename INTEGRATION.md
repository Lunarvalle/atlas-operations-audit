# MCP integration contract

Transport: newline-delimited JSON-RPC over stdio. Protocol versions: 2025-11-25, 2025-06-18, 2025-03-26 and 2024-11-05. Initialize before requesting tools.

`atlas_catalog` returns exact required columns, options, limitations and synthetic examples. Ten analysis tools use snake_case product IDs, e.g. `payout_bridge`.

Arguments: `a` (CSV text or source JSON text), `b` where required, product-specific `options`, explicit ISO `asOf`, optional `reportLimit` (1–5000, default 100), `includeCsv` (default false). Queue Focus requires `asOf`. Never supply a URL expecting it to be fetched. It will only be treated as input text.

Output: `structuredContent` plus equivalent JSON text; full report counts, bounded preview, action groups and input/result SHA-256. Optional CSV contains complete rows/findings and protects spreadsheet formula prefixes. A preview can be truncated; the metadata says so. A missing input is an error, not an empty success.

Retries: audits have no external effects. Fix `asOf` for a reproducible result. A changed input or version may change the fingerprint. This is not a signed payment receipt.

The process reads only its bundled code and catalog. It does not persist customer input/report files, make network requests or execute instructions contained in data. Hosting platforms may retain transport logs. Before a hosted commercial release, test anonymous rejection, paid entitlements, quotas, all ten sample calls and real delivery independently.

The commercial package supplies the server implementation. This public repository deliberately contains contracts and synthetic fixtures only; no working public endpoint is promised yet.
