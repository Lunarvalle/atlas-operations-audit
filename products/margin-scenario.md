# Margin Scenario
**Calculate margin scenarios and break-even quantities.**

Product ID: `margin-scenario` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/margin-scenario.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 1 findings. This is not evidence of customer savings.

## Input contract
- A: `scenario_id, units, unit_price, unit_cost, fee_percent, fixed_cost, currency`.
- B: `not required`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Calculate margin scenarios and break-even quantities.
Demand and costs are assumptions; no forecast, tax or accounting advice. Aggregate fee rounding may differ from providers.

## Italiano
Calcola scenari di margine e quantità di pareggio.
Domanda e costi sono ipotesi; nessuna previsione o consulenza fiscale/contabile. Arrotondamento aggregato delle commissioni.

## Français
Calculez scénarios de marge et volumes d’équilibre.
Demande et coûts sont des hypothèses ; pas de prévision ni conseil fiscal/comptable. Frais arrondis globalement.

## 简体中文
计算利润情景和盈亏平衡数量。
需求及成本均为假设；不提供预测、税务或会计建议。手续费按总额取整，可能与平台不同。

## Español
Calcula escenarios de margen y cantidades de equilibrio.
Demanda y costes son supuestos; sin previsión ni asesoría fiscal/contable. Comisiones redondeadas sobre el total.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
