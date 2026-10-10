# Document Control
**Find outdated document acknowledgements and overdue reviews.**

Product ID: `document-control` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/document-control.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 1 result rows and 4 findings. This is not evidence of customer savings.

## Input contract
- A: `document_id, current_version, owner, review_due`.
- B: `ack_id, document_id, reader, version_read, read_at`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Find outdated document acknowledgements and overdue reviews.
Metadata only. No proof of reading, comprehension, signature validity or full audience coverage.

## Italiano
Trova prese visioni di versioni obsolete e revisioni scadute.
Solo metadati. Non prova lettura, comprensione, validità delle firme o copertura di tutti i destinatari.

## Français
Repérez accusés de lecture obsolètes et révisions en retard.
Métadonnées seulement. Ne prouve ni lecture, compréhension, validité des signatures ni couverture complète.

## 简体中文
发现旧版文档确认记录及逾期审查。
仅检查元数据。不证明实际阅读、理解、签名有效性或所有读者均已覆盖。

## Español
Detecta acuses de versiones obsoletas y revisiones vencidas.
Solo metadatos. No prueba lectura, comprensión, firmas válidas ni cobertura completa del público.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
