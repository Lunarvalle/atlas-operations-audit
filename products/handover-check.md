# Handover Check
**Close handover gaps in ownership, acceptance, evidence and next actions.**

Product ID: `handover-check` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/handover-check.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 5 findings. This is not evidence of customer savings.

## Input contract
- A: `item_id, from_owner, to_owner, next_action, due_at, evidence_ref, accepted`.
- B: `not required`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Close handover gaps in ownership, acceptance, evidence and next actions.
Uses recorded acceptance only; does not obtain consent or transfer responsibility automatically.

## Italiano
Individua vuoti nei passaggi di consegne: responsabilità, accettazione, prove e azioni.
Usa l’accettazione registrata; non ottiene consenso né trasferisce responsabilità automaticamente.

## Français
Repérez les lacunes de passation : responsabilité, acceptation, preuves et actions.
Utilise l’acceptation enregistrée ; n’obtient pas de consentement ni ne transfère la responsabilité.

## 简体中文
发现交接中的负责人、接收确认、证据及下一步缺口。
仅使用记录中的接收状态；不获取同意，也不自动转移责任。

## Español
Detecta lagunas en traspasos: responsabilidad, aceptación, pruebas y acciones.
Usa la aceptación registrada; no obtiene consentimiento ni transfiere responsabilidades automáticamente.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
