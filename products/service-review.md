# Service Review
**Compare supplied event counts with service targets and error budgets.**

Product ID: `service-review` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/service-review.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 2 findings. This is not evidence of customer savings.

## Input contract
- A: `service_id, period_start, period_end, total_events, bad_events, target_percent, owner`.
- B: `not required`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Compare supplied event counts with service targets and error budgets.
Event-count SLOs only, not time-weighted availability or contractual SLA judgments. Missing coverage is not detectable.

## Italiano
Confronta eventi osservati con obiettivi di servizio e budget d’errore.
Solo SLO su conteggi, non disponibilità temporale o giudizi contrattuali. Copertura mancante non rilevabile.

## Français
Comparez les événements fournis aux objectifs de service et budgets d’erreur.
SLO par comptage uniquement, pas disponibilité temporelle ni jugement contractuel. Couverture manquante indétectable.

## 简体中文
将所提供的事件数量与服务目标和错误预算比较。
仅按事件计数计算 SLO，不计算时间加权可用性或判断合同 SLA。无法发现未提供的观测。

## Español
Compara eventos proporcionados con objetivos de servicio y presupuestos de error.
Solo SLO por conteo, no disponibilidad temporal ni evaluación contractual. No detecta cobertura ausente.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
