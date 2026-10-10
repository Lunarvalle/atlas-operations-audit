# A bigger pack is not automatically a price cut

Suppose SKU B changes from a box of 10 units at EUR 20 to a box of 20 at EUR 20. A direct amount comparison hides a change in what is being purchased. Treating this as a price reduction can incorrectly assume interchangeable contents and product identity.

[Supplier Price List Audit](../products/supplier-price-list-audit.md) marks changed units, pack sizes or currencies as incomparable and leaves the direct delta empty for review. See the [synthetic input and expected output](../examples/supplier-price-list-audit.json). A stable SKU A moving from EUR 10 to EUR 11 is a separate comparable 10% increase.

Confirm identity and conversion rules before buying. The tool does not fetch supplier prices, parse PDFs, convert currencies or place orders. This is an arithmetic illustration, not realized savings.
