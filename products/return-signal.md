# Return Signal
**Compare physical returns with the supplied sales cohort.**

Product ID: `return-signal` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/return-signal.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 0 findings. This is not evidence of customer savings.

## Input contract
- A: `line_id, sku, units, unit_price, currency`.
- B: `return_id, line_id, units, reason, refund_amount, handling_cost`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Compare physical returns with the supplied sales cohort.
Returns must match exact sales-line IDs. Refunds and handling costs do not establish profit.

## Italiano
Confronta i resi fisici con la coorte di vendite fornita.
I resi devono corrispondere agli ID delle righe vendita. Rimborsi e costi di gestione non dimostrano l’utile.

## Français
Comparez les retours physiques à la cohorte de ventes fournie.
Correspondance exacte des identifiants de lignes requise. Remboursements et frais ne déterminent pas le bénéfice.

## 简体中文
将实物退货与所提供的销售群组进行比较。
必须精确匹配销售行标识。退款和处理成本不能证明利润。

## Español
Compara devoluciones físicas con la cohorte de ventas proporcionada.
Se requieren identificadores exactos de líneas. Reembolsos y costes de gestión no prueban beneficios.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
