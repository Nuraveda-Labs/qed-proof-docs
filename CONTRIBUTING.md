# Contributing

Thank you for helping. Fixes and gaps are welcome, but a few things are different from most repositories because of
how this one is published.

Questions before you start? Ask on [Discord](https://discord.gg/9yhJs3EdCx).

## This repository is published from upstream

This repository is a one-way, gated export from the maintainers' private working repository — see
[README.md](README.md). **Pull requests opened here are never merged directly into this repository.** An accepted
change is instead imported into the upstream repository and published in the next export, so it may appear here as
part of a release commit rather than as your original commit. Your authorship is kept — accepted changes carry a
`Co-authored-by:` line crediting you when they land upstream.

## Sign-off (DCO)

Every commit must carry a `Signed-off-by:` line (`git commit -s`), certifying the
[Developer Certificate of Origin](https://developercertificate.org/) — the same requirement as the
[qed-proof-core](https://github.com/Nuraveda-Labs/qed-proof-core) repository.

## What we accept

- Factual fixes: a wrong command, a stale field name, a broken link, an out-of-date claim.
- Clarity: a confusing paragraph, a missing step, a better example.
- Missing coverage: something the product does that isn't documented anywhere yet.

## What we don't accept

- Pure style or wording preference with no factual or clarity gain.
- Anything that can't be verified against the product's current behavior.

## Before you open a pull request

Run a local preview and check links:

```bash
npx mint@4.2.939 dev
npx mint@4.2.939 broken-links
```

## Security issues

Please don't open an issue for a security problem here. Report it through the
[qed-proof-core repository](https://github.com/Nuraveda-Labs/qed-proof-core)'s private vulnerability reporting instead — see its
`SECURITY.md`.
