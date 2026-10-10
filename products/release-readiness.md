# Release Readiness
**Check that required test receipts belong to the exact release artifact.**

Product ID: `release-readiness` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/release-readiness.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 2 findings. This is not evidence of customer savings.

## Input contract
- A: `check_id, required, max_age_hours`.
- B: `check_id, result, tested_at, artifact_hash, evidence_ref`.
- Options: `{"artifactHash":"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa"}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Check that required test receipts belong to the exact release artifact.
Receipt metadata only. Does not execute tests, verify signatures, certify security or deploy.

## Italiano
Controlla che le ricevute dei test richiesti riguardino l’esatto artefatto da rilasciare.
Solo metadati delle ricevute. Non esegue test, verifica firme, certifica sicurezza o distribuisce.

## Français
Vérifiez que les preuves de tests concernent l’artefact exact à livrer.
Métadonnées uniquement. Aucun test exécuté, signature vérifiée, sécurité certifiée ou déploiement.

## 简体中文
确认所需测试记录对应准确的发布构件。
仅检查测试记录元数据。不运行测试、验证签名、认证安全或部署。

## Español
Comprueba que las pruebas de test corresponden al artefacto exacto de la versión.
Solo metadatos. No ejecuta pruebas, verifica firmas, certifica seguridad ni despliega.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
