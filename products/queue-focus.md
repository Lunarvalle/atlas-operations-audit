# Queue Focus
**Prioritize overdue, unassigned and inactive support tickets.**

Product ID: `queue-focus` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/queue-focus.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 4 findings. This is not evidence of customer savings.

## Input contract
- A: `ticket_id, status, priority, created_at, updated_at, due_at, assignee`.
- B: `not required`.
- Options: `{"staleHours":48}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Prioritize overdue, unassigned and inactive support tickets.
Requires explicit deadlines. Does not reconstruct business-hour SLA clocks or send replies.

## Italiano
Dai priorità a ticket scaduti, non assegnati e inattivi.
Richiede scadenze esplicite. Non ricostruisce SLA in ore lavorative e non invia risposte.

## Français
Priorisez les tickets en retard, non attribués ou inactifs.
Échéances explicites requises. Ne reconstruit pas les SLA en heures ouvrées et n’envoie pas de réponses.

## 简体中文
优先处理逾期、未分配和长期未更新的工单。
需要明确截止时间。不重建工作时间 SLA，也不发送回复。

## Español
Prioriza tickets vencidos, sin asignar e inactivos.
Requiere plazos explícitos. No reconstruye SLA en horas laborables ni envía respuestas.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
