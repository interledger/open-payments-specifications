# Open Payments Specifications

<p align="center">
  <img src="https://raw.githubusercontent.com/interledger/open-payments/main/docs/public/img/logo.svg" width="700" alt="Open Payments">
</p>

## What is Open Payments?

Open Payments APIs are a collection of open API standards that can be implemented by account servicing entities (e.g. banks, digital wallet providers, and mobile money providers) to facilitate interoperability in the setup and completion of payments for different use cases including:

- [Web Monetization](https://webmonetization.org)
- Tipping/Donations (low value/low friction)
- eCommerce checkout
- P2P transfers
- Subscriptions
- Invoice Payments

The Open Payments APIs are a collection of three sub-systems:

- A **wallet address server** which exposes public information about Open Payments-enabled accounts called "wallet addresses"
- A **resource server** which exposes APIs for performing functions against the underlying accounts
- A **authorisation server** which exposes APIs compliant with the [GNAP](https://datatracker.ietf.org/doc/html/draft-ietf-gnap-core-protocol) standard for getting grants to access the resource server APIs

This repository hosts the Open API Specifications of the three APIs which are published along with additional documentation at
https://openpayments.dev.

## Contributing

1. Make the desired specification changes in the `openapi/` directory.
2. Update the `VERSION` file to reflect the new version, following [semantic versioning](https://semver.org/).
3. Update the `info.version` field in **each** specification to match the new version, even if only one specification was modified.
4. Open a pull request with your changes.
