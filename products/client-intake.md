# Client Intake
**Find missing intake answers, owners and prerequisites.**

Product ID: `client-intake` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/client-intake.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 3 result rows and 2 findings. This is not evidence of customer savings.

## Input contract
- A: `field_id, required, depends_on`.
- B: `field_id, value, owner`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Find missing intake answers, owners and prerequisites.
Presence and dependency checks only. Answers are not judged or included in reports; no client is contacted.

## Italiano
Trova risposte, responsabili e prerequisiti mancanti nell’avvio cliente.
Solo presenza e dipendenze. Le risposte non sono valutate né incluse nei rapporti; nessun cliente contattato.

## Français
Repérez réponses, responsables et prérequis manquants à l’accueil client.
Présence et dépendances uniquement. Réponses non évaluées ni incluses dans les rapports ; aucun contact client.

## 简体中文
发现客户入门资料中缺失的答案、负责人和前置条件。
仅检查是否存在及依赖关系。不判断答案，也不将答案值写入报告；不会联系客户。

## Español
Detecta respuestas, responsables y requisitos previos faltantes en la incorporación.
Solo presencia y dependencias. No evalúa ni incluye respuestas en informes; no contacta clientes.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
