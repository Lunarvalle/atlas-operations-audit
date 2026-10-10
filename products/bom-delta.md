# BOM Delta
**Compare flat BOM quantities, revisions and manufacturer parts**

Product ID: `bom-delta` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/bom-delta.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 3 result rows and 4 findings. This is not evidence of customer savings.

## Input contract
- A: `part_id, quantity, unit, manufacturer_part, revision, unit_cost, currency`.
- B: `part_id, quantity, unit, manufacturer_part, revision, unit_cost, currency`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Compare flat BOM quantities, parts, revisions and costs.
No nested assembly expansion or engineering substitution approval.

## Italiano
Confronta quantità, componenti, revisioni e costi di distinte piatte.
Nessuna esplosione di assiemi annidati o approvazione di equivalenze tecniche.

## Français
Comparez quantités, composants, révisions et coûts de nomenclatures plates.
Pas de décomposition d’assemblages imbriqués ni validation de substitutions techniques.

## 简体中文
比较平面物料清单的数量、零件、版本和成本。
不展开嵌套装配，也不批准工程替代件。

## Español
Compara cantidades, piezas, revisiones y costes de listas planas de materiales.
Sin expansión de conjuntos anidados ni aprobación de sustituciones técnicas.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
