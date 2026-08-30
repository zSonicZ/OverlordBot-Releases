# OverLord Bot Releases

Binary-only distribution repository for managed OverLord Bot builds.

- Published release assets are immutable and signed with the offline Ed25519 release key.
- `channels/canary` and `channels/stable` contain byte-identical signed metadata that selects an immutable release.
- Public download access is not runtime authorization. The bot still requires a valid machine-bound license and the production API validates every operation.
- Source code, private keys, environment files, customer data, and fleet configuration do not belong in this repository.
