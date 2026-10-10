# Invoice Match
**Compare order and invoice quantities and unit prices**

Product ID: `invoice-match` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/invoice-match.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 3 result rows and 3 findings. This is not evidence of customer savings.

## Input contract
- A: `line_id, order_id, sku, quantity, unit_price, currency`.
- B: `line_id, order_id, sku, quantity, unit_price, currency`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

Quantities: nonnegative decimals with at most **4 decimal places**, up to 900719925474.0991. Excess precision is rejected rather than rounded into a false match.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Find quantity and unit-price differences between orders and invoices.
Exact order/SKU two-way match. Consolidate split invoices first; no tax or payment verification.

## Italiano
Trova differenze di quantità e prezzo tra ordini e fatture.
Corrispondenza esatta ordine/SKU. Consolida prima le fatture parziali; nessuna verifica fiscale o dei pagamenti.

## Français
Repérez les écarts de quantité et prix entre commandes et factures.
Rapprochement exact commande/SKU. Consolidez les factures fractionnées ; aucune vérification fiscale ou de paiement.

## 简体中文
查找订单和发票之间的数量及单价差异。
精确匹配订单/SKU。需先合并拆分发票；不核验税务或付款。

## Español
Detecta diferencias de cantidad y precio entre pedidos y facturas.
Coincidencia exacta pedido/SKU. Consolida facturas parciales; sin validación fiscal ni de pagos.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
