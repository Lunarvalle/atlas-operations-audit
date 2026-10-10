# Supplier CSV import: a reproducible cost-impact example

AutoAtlasMarket, Supplier Price List Audit, local release 2.0.3. Technical example only; no customer savings or live paid checkout is claimed.

The new import route maps existing CSV columns and accepts an explicitly selected price decimal mark. It does not infer units, translate pack sizes or convert currencies. English, Italian, French, Spanish and Simplified Chinese interfaces remain inside one product.

## Why the price basis matters

| SKU | Old price | New price | Supplied quantity | Quantified change |
|---|---:|---:|---:|---|
| A | EUR 10 per piece | EUR 11 per piece | 1000 pieces | EUR+1000 |
| D | EUR 20 per piece | EUR 18 per piece | 50 pieces | EUR-100 |
| B | EUR 20 per box of 10 | EUR 20 per box of 20 | 30 old-basis boxes | Excluded: pack changed |

The comparable total is EUR+900, a partial expenditure scenario at the supplied volumes. It is not a saving achieved, a forecast, or a full procurement assessment. The new price and changed pack on B must be normalized and reviewed before comparing its cost.

## Try the arithmetic in your own workflow

An Italian-style source CSV may have headers `Codice;Unita;Confezione;Prezzo;Valuta` and values such as `A;piece;1;10,00;EUR`. Select semicolon as the CSV separator and comma as the price decimal mark. Map all five fields. The quantities file requires SKU, quantity, unit, pack size and currency. Review both column meaning and commercial basis; a suggestion is not a confirmation.

The new importer passed 53 internal Node tests and 28 recorded browser cases in Chromium memory at 390 and 1280 pixels. Tests cover ambiguous columns, quoted CSV, leading-zero SKUs, explicit decimals, invalid files, stale results, safe HTML, and exports. The separately formatted seller-source copy repeated the 53 Node cases. Counts are not independent certification or proof of market value.

## Bounds and availability

Up to 5000 data rows,50 columns and 2 MiB per UTF-8 CSV. Whole quantities only. No direct XLSX/PDF, ERP access, currency conversion, fuzzy SKU matching, tax/freight model or automated purchasing. The underlying comparator trims outer identifier whitespace. Detailed diagnostics remain English.

The browser route was tested in memory, not through direct file opening or on a physical phone. Those target checks remain pending. No full executable source is published in this example.

[Scope and existing enquiry route](BUYER_GUIDE.md). A contact is not a verified purchase link. Do not upload supplier files, client data, credentials or personal information to public issues; use only synthetic reproductions.
