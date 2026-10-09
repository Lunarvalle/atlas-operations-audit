# Atlas Operations Audit

**Find operational exceptions before they become the next expensive cleanup.**

Ten focused tools turn supplied CSV or JSON exports into a reviewable report: what needs attention, which rows support it, and what to check next. Built for operators who need a second check without handing an agent permission to change their systems.

## Explore the ten tools

| Product | For | What you get |
| --- | --- | --- |
| [Stock Window](products/stock-window.md) | Inventory purchasing | Turn stock, reserved units, inbound units, lead times and buying constraints into a reviewable reorder worksheet. |
| [Return Signal](products/return-signal.md) | Returns operations | Join returned line items to the matching sales cohort; separate refunds, handling cost and product/reason patterns. |
| [Payout Bridge](products/payout-bridge.md) | Settlement review | Match transaction batches to payout records by exact ID and currency; expose missing batches and arithmetic differences. |
| [Redirect Guard](products/redirect-guard.md) | Website migrations | Check a planned redirect map for duplicate sources, chains, loops and gaps in a supplied traffic inventory before deployment. |
| [Campaign QA](products/campaign-qa.md) | Marketing operations | Audit a batch of campaign links for missing or repeated UTM fields, inconsistent naming and sensitive query parameters. |
| [Queue Focus](products/queue-focus.md) | Support operations | Build a review queue from explicit deadlines, assignment and last-update timestamps. |
| [CRM Cleanroom](products/crm-cleanroom.md) | CRM migrations | Find exact email/phone duplicate candidates and flag conflicting identity and contact-permission fields before a merge. |
| [Webhook Ledger](products/webhook-ledger.md) | Integration incident review | Audit exported event logs for repeated identities, conflicting payloads, ordering anomalies and sensitive field names. |
| [Locale Shield](products/locale-shield.md) | Translation releases | Compare JSON dictionaries for missing/empty strings, simple placeholder and tag differences, and review signals. |
| [BOM Delta](products/bom-delta.md) | Engineering procurement | Compare two flat BOM revisions, separating quantity/cost changes from part, unit and currency conflicts. |

## See the result before choosing a tool

Each product page links to a small synthetic input and its actual computed report. Nothing in these examples is a customer case study. The commercial engine is not distributed in this documentation repository.

The browser edition runs locally: open the app, load or map the columns, review and export. It makes no external network requests. The MCP/CLI edition uses the same engine, with a catalog of input contracts, bounded reports, complete CSV output on request and SHA-256 fingerprints for reproducible checks. Provide `asOf` to fix the evaluation time; it is mandatory for Queue Focus.

## Availability — 9 October 2026

- **Built:** ten browser/CLI audit tools.
- **Internally checked:** 32 engine tests; 20 Chromium paths across narrow and wide viewports; 20 CLI executions; five MCP tests, including all ten tools and the real stdio entry point.
- **Not yet established:** customer willingness to pay, independent usability, hosted paid delivery and payout.
- **MCPize:** a draft project exists; deployment and commercial checkout qualification are still required. This is not a live hosted-service link.

The public artifacts are an evaluation preview. Do not send customer records to an unqualified hosting endpoint. A hosted edition may be subject to the host's data-retention policy even when our process does not persist inputs.

## Why these checks are deliberately narrow

Refunds are not automatically physical returns. Payout records are not bank receipts. Duplicate candidates are not permission to merge contacts. A redirect plan is not a live crawl. We keep these distinctions visible in every product's boundaries.

No tool sends orders, changes prices, replays webhooks, merges records, makes payments or certifies engineering decisions. You receive findings and a review path.

## Integrations

See [the MCP contract](INTEGRATION.md) and [the machine-readable product catalog](catalog-public.json). A local authorized MCP client launches `node mcp-server.cjs`; first call `atlas_catalog`, then the named tool. Hosted endpoint details will be added only after a live test.

Documentation and synthetic fixtures may be copied to evaluate or integrate the service. Product engine rights are reserved. These previews carry no promise of savings, accuracy for unsupported data, or guaranteed commercial outcomes.
