# Menu Board
**Create a portable five-language menu from reviewed item names and prices.**

Product ID: `menu-board` · Local revision: `2.0.1` · **One product; all five interface languages included.**

**Availability:** documentation preview. No public paid checkout has been verified. Do not send money or confidential files through this repository. Full local applications and their engines are not published here.

## Inspect the result
[Synthetic input and expected result](../examples/menu-board.json) · [All 29 products](../README.md#catalogue) · [Integration](../INTEGRATION.md) · [Support](../SUPPORT.md)

The synthetic example produces 2 result rows and 0 findings. This is not evidence of customer savings.

## Input contract
- A: `item_id, category, price, currency, available, en, it, fr, zh, es`.
- B: `not required`.
- Options: `{}`.
- Supply asOf as an ISO 8601 snapshot timestamp, including seconds and timezone. Replace synthetic sample dates with the reference date of your data.
- Local table interface: CSV or a JSON array of scalar-valued objects with identical columns; 1–5,000 rows and 2 MB per input file. Locale Shield instead accepts its two nested JSON documents.
- CSV supports comma, semicolon and tab. Numeric decimal separator is a point. Exact identifiers, currency and units matter. Technical keys and detailed diagnostics remain English.

## Two different deliveries
A local licence would deliver this one tool, all five interface languages, templates, browser interface, CLI, scoped MCP server and HTML/JSON/CSV reports. A cloud execution delivers one report, not a downloadable software licence. No language edition requires a separate product ID.

## English
Create a portable five-language menu from reviewed item names and prices.
You supply translations. No orders, hosting, allergen inference or regulatory certification. Review all content before publishing.

## Italiano
Crea un menu portabile in cinque lingue con nomi e prezzi revisionati.
Le traduzioni le fornisci tu. Nessun ordine, hosting, deduzione di allergeni o certificazione normativa. Rivedi tutto prima di pubblicare.

## Français
Créez un menu portable en cinq langues avec noms et prix vérifiés.
Vous fournissez les traductions. Ni commandes, hébergement, déduction d’allergènes ni certification. Relisez avant publication.

## 简体中文
使用审核过的菜品名称和价格生成便携的五语言菜单。
翻译由用户提供。不处理订单、托管、推断过敏原或认证法规要求。发布前请审核全部内容。

## Español
Crea un menú portátil en cinco idiomas con nombres y precios revisados.
Tú proporcionas traducciones. Sin pedidos, alojamiento, inferencia de alérgenos ni certificación. Revisa antes de publicar.

## Evidence and uncertainty
Local synthetic regression and browser tests do not establish demand, native-speaker translation review or compatibility with every device. These tools check supplied records; they do not operate the source systems or guarantee legal compliance, profit, realized savings or business outcomes.
