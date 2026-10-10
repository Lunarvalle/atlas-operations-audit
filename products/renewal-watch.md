# Renewal Watch
**Review contract renewal and notice windows before decisions are late.**

Product ID: `renewal-watch` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/renewal-watch.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 1 findings. This is not evidence of customer savings.

## Input contract
- A: `contract_id, renewal_at, notice_days, owner, auto_renew`.
- B: `not required`.
- Options: `{"lookaheadDays":30}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Review contract renewal and notice windows before decisions are late.
Elapsed calendar days, not business days or legal interpretation. No cancellation, renewal or reminder is sent.

## Italiano
Rivedi finestre di rinnovo e preavviso prima che sia tardi.
Giorni di calendario trascorsi, non lavorativi o interpretazione legale. Nessuna disdetta, rinnovo o notifica.

## Français
Examinez les échéances de renouvellement et préavis avant retard.
Jours calendaires écoulés, pas jours ouvrés ni interprétation juridique. Aucun renouvellement, résiliation ou rappel.

## 简体中文
在决策逾期前检查合同续约及通知期限。
按实际日历天数计算，不按工作日，也不解释法律条款。不取消、续约或发送提醒。

## Español
Revisa renovaciones y plazos de preaviso antes de decidir tarde.
Días naturales transcurridos, no laborables ni interpretación jurídica. No cancela, renueva ni envía avisos.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
