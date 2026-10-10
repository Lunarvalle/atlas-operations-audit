# Supplier price changes: quantify the part you can actually compare

**AutoAtlasMarket | Supplier Price List Audit | Pilot enquiries**

Compare two supplier price lists before approving an update. The local tool matches exact SKUs, flags changes in unit, pack size or currency, and optionally applies your purchase volumes to comparable prices.

## A worked example, not a customer claim

| SKU | Previous price | New price | Supplied period quantity | Result |
|---|---:|---:|---:|---|
| A | EUR 10 | EUR 11 | 1,000 | EUR +1,000 |
| D | EUR 20 | EUR 18 | 50 | EUR -100 |
| B | EUR 20 per box of 10 | EUR 20 per box of 20 | 30 | Excluded: pack basis changed |

**Quantifiable expenditure change: EUR +900.** This is a partial scenario at the supplied quantities, not achieved savings, profit, a purchase order or a complete procurement assessment. Missing quantities are excluded rather than assumed to be zero; different currencies are never added together.

## What a bounded pilot would deliver

A readable HTML report, a CSV exception list, a JSON result, input-file hashes and a list of unresolved assumptions. The buyer supplies two structured price lists and, optionally, a quantity table for one stated period. The supplier confirms that quantities count the commercial units to which each price applies.

The initial pilot scope is one supplier, up to 500 rows per list and one correction/retest of the same supplied dataset. Larger scopes require a separate agreement. Turnaround and price are agreed only after reviewing a non-sensitive schema sample and confirming availability. No automatic or paid checkout is open in this repository.

The software supports at most 5,000 rows per table and 2 MB per input. It does not extract PDFs, connect to an ERP, execute purchases, negotiate with suppliers, convert currencies or certify business records. A language selector is not a native-speaker certification. Interfaces are available in English, Italian, French, Simplified Chinese and Spanish **inside the same product**; detailed diagnostics remain English.

## Enquiries

[View the existing Upwork profile to discuss an eligible pilot](https://www.upwork.com/freelancers/~01f0a4fe40bd04c611). This is a profile/contact route, not an active Project Catalog listing or a verified purchase link. Work and payment must follow the rules of the channel used.

**Do not upload price lists, personal data, credentials or client documents to public GitHub issues.** A private data-handling route, scope and commercial terms must be agreed before sending sensitive information or starting work.

## Other focused tools

[Redirect Guard](products/redirect-guard.md) reviews supplied redirect maps, not a complete live-site migration. [Locale Shield](products/locale-shield.md) reviews structural translation keys and placeholders, not linguistic fluency. [The complete catalogue](README.md) still contains 29 products, not one product per language.

## Evidence and availability

The local volume-impact enhancement passed 28 calculation/regression checks and 10 language/viewport browser-DOM paths, including six normal export checks. These are internal synthetic tests, not customer acceptance, a physical-phone test or independent certification. Local file navigation was blocked in the test environment; that target remains unqualified.

The original audit engine was reused unchanged. No full commercial engine or paid download is distributed in this public guide. Cloud builds and account-specific publication gates are separate from this local enhancement. No customer order or revenue is claimed here.
