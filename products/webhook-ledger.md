# Webhook Ledger
**Distinguish repeated events, ID collisions and ordering anomalies.**

Product ID: `webhook-ledger` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/webhook-ledger.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 4 result rows and 5 findings. This is not evidence of customer savings.

## Input contract
- A: `event_id, event_type, entity_id, occurred_at, payload`.
- B: `not required`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Distinguish repeated events, ID collisions and ordering anomalies.
Offline log audit only. Payload values are omitted; no event is replayed.

## Italiano
Distingui eventi ripetuti, collisioni degli ID e anomalie d’ordine.
Solo controllo offline dei log. Valori dei payload omessi; nessun evento reinviato.

## Français
Distinguez événements répétés, collisions d’identifiants et anomalies d’ordre.
Audit hors ligne des journaux. Valeurs des charges utiles omises ; aucun événement rejoué.

## 简体中文
区分重复事件、标识冲突和顺序异常。
仅离线检查日志。报告不含载荷值，不会重放事件。

## Español
Distingue eventos repetidos, colisiones de identificadores y anomalías de orden.
Solo auditoría de registros sin conexión. Se omiten los valores del contenido; no se reenvían eventos.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
