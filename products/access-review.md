# Access Review
**Review leaver, inactive and privileged accounts against a staff roster.**

Product ID: `access-review` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/access-review.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 2 findings. This is not evidence of customer savings.

## Input contract
- A: `account_id, person_id, role, last_seen, account_status`.
- B: `person_id, employment_status`.
- Options: `{"inactiveDays":90}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Review leaver, inactive and privileged accounts against a staff roster.
No live access scan, revocation or compliance certification. Confirm legitimate access needs.

## Italiano
Rivedi account di ex dipendenti, inattivi e privilegiati rispetto al personale.
Nessuna scansione live, revoca o certificazione. Conferma le esigenze legittime di accesso.

## Français
Examinez comptes de départs, inactifs et privilégiés selon le registre du personnel.
Aucun scan direct, retrait d’accès ou certification. Confirmez les besoins légitimes.

## 简体中文
根据员工名册检查离职、闲置及特权账户。
不实时扫描权限、不撤销访问，也不提供合规认证。请确认合理访问需求。

## Español
Revisa cuentas de bajas, inactivas y privilegiadas frente a la plantilla.
Sin análisis en directo, revocación ni certificación. Confirma las necesidades legítimas de acceso.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
