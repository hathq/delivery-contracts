# @hathq/delivery-contracts

Describe the first view, trusted assets and readiness information that a display host delivers to a client.

## What you can do

- Validate bounded delivery envelopes.
- Tie the initial display to an exact projection identity.

## Current scope

The producer supplies readiness and source authority. Delivery data cannot introduce arbitrary executable UI.

Package distribution is not activated by this documentation. Use the checked-in source and the declared dependency versions; published availability must be verified separately.

## Getting started

The manifest currently requires locally supplied package archives: `@hathq/projection-contracts`, `@zixcel/interaction`. These archives are excluded from Git. Obtain the exact approved dependency artifacts before installing; a fresh clone alone is not sufficient. Registry distribution remains pending.

Use the package manager matching the checked-in lockfile and the Node.js version declared in `package.json` or the development configuration. Run from this repository:

```sh
pnpm install --frozen-lockfile
pnpm test
```

## Documentation and source

[Usage guide](docs/getting-started.md)

[Implementation and public interfaces](src) · [Verification cases](test) · [Contributing](CONTRIBUTING.md) · [Security reporting](SECURITY.md) · [License](LICENSE) · [Attribution notices](NOTICE)
