# Payout Bridge
**Reconcile net transactions with exact payout IDs and currencies.**

Product ID: `payout-bridge` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/payout-bridge.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 1 findings. This is not evidence of customer savings.

## Input contract
- A: `transaction_id, payout_id, currency, gross, fee, net`.
- B: `payout_id, currency, amount`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Reconcile net transactions with exact payout IDs and currencies.
Matching arithmetic does not prove receipt in a bank account. No tax or revenue recognition.

## Italiano
Riconcilia transazioni nette con ID e valute esatti dei pagamenti.
La corrispondenza aritmetica non prova l’accredito in banca. Nessuna valutazione fiscale o contabile.

## Français
Rapprochez les transactions nettes avec les identifiants et devises des versements.
Une concordance arithmétique ne prouve pas un crédit bancaire. Aucune validation fiscale ou comptable.

## 简体中文
按准确的付款标识和币种核对净交易金额。
算术一致不等于银行已到账。不提供税务或收入确认判断。

## Español
Concilia transacciones netas con identificadores y monedas exactos de pagos.
La coincidencia aritmética no prueba el ingreso bancario. Sin validación fiscal o contable.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
