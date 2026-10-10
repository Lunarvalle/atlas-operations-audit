# Meeting Follow-through
**Track meeting actions that lack owners, proof or timely completion.**

Product ID: `meeting-followthrough` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/meeting-followthrough.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 3 findings. This is not evidence of customer savings.

## Input contract
- A: `action_id, meeting_id, action, owner, due_at, status, completion_ref`.
- B: `not required`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Track meeting actions that lack owners, proof or timely completion.
Structured action register, not transcription. Exact text duplicates only; no messages sent.

## Italiano
Controlla azioni delle riunioni senza responsabile, prove o completamento tempestivo.
Registro strutturato, non trascrizione. Solo duplicati testuali esatti; nessun messaggio inviato.

## Français
Suivez les actions de réunion sans responsable, preuve ou achèvement à temps.
Registre structuré, pas transcription. Doublons textuels exacts seulement ; aucun message envoyé.

## 简体中文
跟踪缺少负责人、证据或及时完成记录的会议行动项。
使用结构化行动表，不转录会议。仅识别规范化文本完全相同的重复项；不发送消息。

## Español
Controla acciones de reuniones sin responsable, pruebas o finalización puntual.
Registro estructurado, no transcripción. Solo duplicados de texto exacto; no envía mensajes.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
