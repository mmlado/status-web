---
'@status-im/wallet': minor
'wallet': minor
---

feat(wallet): air-gapped QR signing for hardware wallets (personal_sign + signTypedData)

Adds `HardwareSignScreen` to `@status-im/wallet/components`. Wires `personal_sign` via the approval popup and `signMessage` / `signTypedData` via `signer-context` for `hardware-qr` wallets through the ERC-4527 two-QR round trip. Transaction signing for hardware wallets is tracked as a follow-up.
