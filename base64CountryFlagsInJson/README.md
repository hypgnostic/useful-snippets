## Base-64 Ecnoded Image Flags, in JSON

I took all 248 country flags (at the time of writing) in SVG and PNG format from https://github.com/madebybowtie/FlagKit, base64-encoded them and put them in a JSON object, keyed by the country-code.

This is good if you're trying to get country flag images uploaded to a Shopify theme using the [Shopify Asset API](https://help.shopify.com/en/api/reference/online-store/asset#update-2019-10), as part of building a Shopify app/theme.

If you'd like to re-generate the JSON yourself, use [`generate.sh`](./generate.sh).

**Note:** This is MIT-licensed! Reproduce license everywhere.
