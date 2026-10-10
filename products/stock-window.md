# Stock Window
**Prioritize reorder quantities from stock, demand, pack sizes and budget.**

Product ID: `stock-window` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/stock-window.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 3 result rows and 2 findings. This is not evidence of customer savings.

## Input contract
- A: `sku, on_hand, reserved, on_order, units_sold, window_days, lead_days, safety_days, pack_size, moq, unit_cost, currency`.
- B: `not required`.
- Options: `{"budget":"200","budgetCurrency":"EUR"}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Prioritize reorder quantities from stock, demand, pack sizes and budget.
Historical-average scenario; confirm inbound delivery dates. No purchase order is placed.

## Italiano
Dai priorità ai riordini con scorte, domanda, confezioni e budget.
Scenario su media storica; conferma gli arrivi. Nessun ordine viene inviato.

## Français
Priorisez les réapprovisionnements avec stock, demande, lots et budget.
Scénario fondé sur une moyenne historique ; confirmez les livraisons. Aucune commande envoyée.

## 简体中文
根据库存、需求、包装数量和预算确定补货优先级。
基于历史平均值的情景计算；请确认到货日期。不会下单。

## Español
Prioriza reposiciones según existencias, demanda, lotes y presupuesto.
Escenario basado en medias históricas; confirma las entregas. No se envían pedidos.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
