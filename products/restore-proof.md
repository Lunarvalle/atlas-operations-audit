# Restore Proof
**Review backup age, restore-test evidence and recovery targets.**

Product ID: `restore-proof` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/restore-proof.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 3 findings. This is not evidence of customer savings.

## Input contract
- A: `system_id, rpo_hours, rto_minutes`.
- B: `system_id, backup_at, restore_test_at, restore_minutes, result, evidence_ref`.
- Options: `{"maxTestAgeDays":30}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Review backup age, restore-test evidence and recovery targets.
Checks supplied metadata only. Does not back up, restore or prove disaster readiness.

## Italiano
Rivedi età dei backup, prove di ripristino e obiettivi di recupero.
Solo metadati forniti. Non esegue backup o ripristini e non prova la resilienza ai disastri.

## Français
Examinez l’âge des sauvegardes, les tests de restauration et les objectifs.
Métadonnées fournies uniquement. Ne sauvegarde, ne restaure ni ne prouve la résilience.

## 简体中文
检查备份时效、恢复测试证据及恢复目标。
仅检查所提供的元数据。不执行备份或恢复，也不证明灾难恢复能力。

## Español
Revisa antigüedad de copias, pruebas de restauración y objetivos de recuperación.
Solo metadatos proporcionados. No realiza copias ni restauraciones ni prueba preparación ante desastres.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
