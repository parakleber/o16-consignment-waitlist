# O-16 demand test — consignment inventory reconciliation for Shopify

Pre-validation demand-test landing page for opportunity **O-16** in the [app-factory](https://github.com/parakleber/app-factory) pipeline (`company/opportunities/O-16-shopify-consignment-reconciliation.md`). Not a product yet — this only exists to check whether the problem is worth building for.

- Page: `index.html`, served via GitHub Pages from `main`.
- Signup capture: client-side `fetch()` POST to a [webhook.site](https://webhook.site) endpoint (zero-signup, provisioned via their public API). Requests are harvested periodically into `company/opportunities/O-16-shopify-consignment-reconciliation.md` in the factory repo — this repo is not the system of record.
- Pass threshold: 25 signups in 14 days from first real distribution, OR 3 explicit paid-pilot ($20+/mo) commitments. Fail -> O-16 folds back to rejected.

No code, no backend, no accounts, no secrets. Content only.
