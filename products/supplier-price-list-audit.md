# Supplier Price List Audit
**Compare supplier prices without confusing pack changes with discounts**

Product ID: `supplier-price-list-audit` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/supplier-price-list-audit.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 3 result rows and 1 findings. This is not evidence of customer savings.

## Input contract
- A: `sku, unit, pack_size, unit_price, currency`.
- B: `sku, unit, pack_size, unit_price, currency`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Compare normalized supplier prices without hiding unit or pack changes.
Exact SKU comparison only. No PDF extraction, currency conversion or negotiation. Local edition distinct from the existing cloud build.

## Italiano
Confronta listini normalizzati senza nascondere cambi di unità o confezione.
Solo SKU esatti. Nessuna estrazione PDF, cambio valuta o negoziazione. Edizione locale distinta dalla build cloud esistente.

## Français
Comparez les prix fournisseurs normalisés sans masquer changements d’unité ou lot.
SKU exacts seulement. Pas d’extraction PDF, conversion ou négociation. Édition locale distincte de la version cloud existante.

## 简体中文
比较规范化供应商价格，同时明确单位或包装变化。
仅按准确 SKU 比较。不提取 PDF、不换汇或谈判。本地版与现有云端构建不同。

## Español
Compara precios normalizados sin ocultar cambios de unidad o lote.
Solo SKU exactos. Sin extracción PDF, conversión ni negociación. Edición local distinta de la versión en la nube.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
