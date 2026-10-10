# Campaign QA
**Check campaign URL tags, naming consistency and duplicates.**

Product ID: `campaign-qa` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/campaign-qa.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 3 result rows and 6 findings. This is not evidence of customer savings.

## Input contract
- A: `link_id, url`.
- B: `not required`.
- Options: `{"allowedSources":"newsletter,partner"}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Check campaign URL tags, naming consistency and duplicates.
No live Analytics verification or attribution guarantee. Sensitive query values are masked.

## Italiano
Controlla tag delle campagne, coerenza dei nomi e duplicati.
Nessuna verifica Analytics live o garanzia di attribuzione. I valori sensibili sono mascherati.

## Français
Vérifiez les tags de campagne, la cohérence des noms et les doublons.
Aucune vérification Analytics en direct ni garantie d’attribution. Valeurs sensibles masquées.

## 简体中文
检查营销链接标签、命名一致性和重复项。
不进行实时 Analytics 核验，也不保证归因。敏感查询值会被遮蔽。

## Español
Comprueba etiquetas de campañas, coherencia de nombres y duplicados.
Sin verificación de Analytics en directo ni garantía de atribución. Los valores sensibles se ocultan.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
