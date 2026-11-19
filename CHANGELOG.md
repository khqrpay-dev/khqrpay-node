# Changelog

## 0.1.2 (2026-11-19)

- Package details only: the source moved to github.com/khqrpay-dev/khqrpay-node (the old address redirects). No code changes.

## 0.1.1 (2026-11-04)

- A connection that drops part-way through an answer now throws `KHQRPayError` with code `network_error`, like every other failure.
- README: how to load the SDK with `require`.

## 0.1.0 (2026-11-04)

- First release: payments (create, retrieve, list, simulate), usage, and webhook signature checks.
