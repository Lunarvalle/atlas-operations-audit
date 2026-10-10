# Evidence Map
**Expose unsupported, stale or contradicted claims.**

Product ID: `evidence-map` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/evidence-map.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 1 result rows and 1 findings. This is not evidence of customer savings.

## Input contract
- A: `claim_id, claim, required_evidence, max_age_days`.
- B: `evidence_id, claim_id, source_url, observed_at, outcome`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Expose unsupported, stale or contradicted claims.
Uses your evidence labels and distinct URLs. Does not read sources or establish truth or independence.

## Italiano
Evidenzia affermazioni non supportate, obsolete o contraddette.
Usa le tue etichette e URL distinti. Non legge le fonti né ne dimostra verità o indipendenza.

## Français
Repérez les affirmations insuffisamment étayées, anciennes ou contredites.
Utilise vos étiquettes et URL distinctes. Ne lit pas les sources et ne prouve ni vérité ni indépendance.

## 简体中文
标记证据不足、过时或被反驳的主张。
使用用户提供的证据标签和不同网址。不读取来源，也不证明真实性或独立性。

## Español
Detecta afirmaciones sin respaldo, desactualizadas o contradichas.
Usa tus etiquetas y URL distintas. No lee fuentes ni demuestra verdad o independencia.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
