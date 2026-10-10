# CRM Cleanroom
**Review duplicate contact candidates and identity conflicts.**

Product ID: `crm-cleanroom` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/crm-cleanroom.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 3 result rows and 3 findings. This is not evidence of customer savings.

## Input contract
- A: `record_id, email, phone, name, company, do_not_contact`.
- B: `not required`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Review duplicate contact candidates and identity conflicts.
Exact normalized primary email/E.164 matches only. No automatic merge or consent inference.

## Italiano
Rivedi candidati duplicati e conflitti d’identità nei contatti.
Solo email primaria normalizzata e telefono E.164. Nessuna fusione automatica o consenso dedotto.

## Français
Examinez les doublons potentiels et conflits d’identité des contacts.
Correspondance exacte après normalisation du courriel principal/E.164. Aucune fusion ni déduction de consentement.

## 简体中文
检查重复联系人候选及身份冲突。
仅匹配规范化的主要邮箱和 E.164 电话。不自动合并，也不推断联系许可。

## Español
Revisa posibles contactos duplicados y conflictos de identidad.
Coincidencia exacta de correo principal normalizado/E.164. Sin fusiones automáticas ni consentimiento inferido.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
