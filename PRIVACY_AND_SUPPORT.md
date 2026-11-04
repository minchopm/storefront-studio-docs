# StoreFront Studio — privacy, sources and support

## Data handling in the documented workflow

App screenshots can contain customer names, messages or account identifiers: use sample data. The public site describes App Store Connect API credentials held in the device Keychain. Keep those credentials out of exports and support reports. Uploading assets sends them to Apple; AI copy generation may involve additional provider processing.

## Public sources

[Official product website](https://storefront-studio.arte-soft.com/) · [App Store listing](https://apps.apple.com/app/id6757389314)

The public website and developer-provided product catalog were reviewed on 2026-11-04. Where their wording differs, these guides favor the current public site's explicit limitations. Follow the site's Privacy, Terms and Support links for current policies and contact information. This guide is not a legal policy or an independent audit.

## A useful support report

- Product and installed version/build.
- Device and operating-system version.
- Selected mode, relevant settings and permission state.
- The smallest sequence of actions that reproduces the problem.
- Expected result and observed result.
- Whether it happens every time and with a new sample input.
- A sanitized screenshot or short example only if needed.

Use invented names, sample media and dummy documents. Remove account identifiers, meeting links, personal messages, health/financial details and credentials. Do not post API keys or complete diagnostic dumps in public issues.

## Documentation boundaries

This repository intentionally describes public user-facing behavior. Application source, authentication details, private infrastructure, unpublished algorithms and internal benchmarks are outside its scope. Corrections should reference a public product page or a reproducible user-visible result.

[Back to documentation home](README.md)
