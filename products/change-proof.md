# Change Proof
**Compare supplied HTTP status and SHA256 snapshots**

Product ID: `change-proof` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/change-proof.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 3 result rows and 3 findings. This is not evidence of customer savings.

## Input contract
- A: `url, status_code, content_hash`.
- B: `url, status_code, content_hash`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

Equivalent numeric/string HTTP codes and uppercase/lowercase SHA256 hex are treated as the same validated values. No website is fetched.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Compare website snapshot hashes and HTTP status records.
No crawler or visual comparison. A hash change does not establish a defect.

## Italiano
Confronta hash e stati HTTP di snapshot di siti.
Nessun crawler o confronto visivo. Un hash cambiato non dimostra un difetto.

## Français
Comparez empreintes et codes HTTP de captures de sites.
Aucun robot ni comparaison visuelle. Une empreinte modifiée ne prouve pas un défaut.

## 简体中文
比较网站快照哈希和 HTTP 状态记录。
不抓取网站或比较视觉效果。哈希变化不能证明存在缺陷。

## Español
Compara hashes y estados HTTP de instantáneas web.
Sin rastreo ni comparación visual. Un cambio de hash no demuestra un fallo.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
